---
title: "iGENMap: Individualized Generative Mapping of Cortical Networks"
summary: Using individual functional eigenmodes as a compact representation of
  individual-specific network organization, cutting the fMRI data needed for
  reliable precision mapping by roughly a factor of four.
tags:
  - Precision Functional Mapping
  - fMRI
  - Generative Models
date: 2026-06-01
featured: true
draft: false
external_link: ''
image:
  caption: ''
  focal_point: Smart
  preview_only: false
links: []
---

Precision functional mapping has revealed that human brain network topography is
highly individual-specific — but reliable individual estimates typically demand
extensive fMRI data from every subject, which is impractical at scale and in the
clinic.

We observed that **functional eigenmodes closely follow each subject's fine-scale
network topography**, and that the correspondence between eigenmodes and networks
is similar across subjects. Building on this, we developed **iGENMap**
(Individualized GENerative Mapping using eigenmodes), which learns this common
eigenmode-to-network relationship across subjects and then uses it to map the
networks of an individual.

**Key results**

- Across three datasets including both healthy controls and patients with
  depression, iGENMap consistently achieved higher within-subject reliability than
  the Multi-Session Hierarchical Bayesian Model (MS-HBM).
- iGENMap estimates from **14 minutes** of data matched the reliability of MS-HBM
  estimates from roughly **1 hour** of data.
- With extensive data the two methods agreed closely overall; where local
  differences persisted, seed-region-based functional connectivity supported both
  network assignments.
- Using an MS-HBM map estimated from extensive held-out data as a reference,
  iGENMap estimates were *more* similar to that reference than MS-HBM's own
  estimates at scan durations of ≤28 minutes.

These findings suggest that individual functional eigenmodes provide a compact
representation of individual-specific cortical network organization. By reducing
the data required for reliable mapping, iGENMap may make precision mapping
feasible in large-scale datasets and more practical for clinical applications such
as individualized fMRI-based TMS targeting, where patient burden must be
minimized.

*Accepted as a Late-Breaking Abstract at SfN 2026.*
