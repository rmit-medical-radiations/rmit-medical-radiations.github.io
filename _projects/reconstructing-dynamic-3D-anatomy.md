---
title: Reconstructing dynamic 3D anatomy from sparse X-ray projections
areas: [medical-imaging, radiotherapy]   # one or more: medical-imaging, nuclear-medicine, radiotherapy, education
type:                     # phd (optional)
status: active             # active | completed
lead: Xin Zhang        # must match name field in _people/ exactly
collaborators:             # external collaborators (optional)
supervisors:               # must match name fields in _people/ exactly (PhD projects)
team:                      # must match name fields in _people/ exactly
funding: NHMRC             # funding body (optional)
start_year: 2023
end_year:                  # leave blank if ongoing
description: >-
  This project focuses on reconstructing dynamic 3D anatomy from sparse X-ray projections for applications in image-guided radiotherapy, CBCT, and orthopaedic imaging. Sparse radiographic views provide only incomplete observations of underlying anatomy, particularly when structures are moving, deforming, or articulated. To address this, I develop physics-aware learning frameworks that integrate continuous representations, anatomical priors, and differentiable X-ray rendering to recover patient-specific anatomy and motion directly from limited projection data.
---

## Background

Conventional CT and CBCT reconstruction requires many X-ray projections acquired over a full gantry rotation, imposing significant radiation dose and limiting temporal resolution. In image-guided radiotherapy and orthopaedic imaging, anatomy is often moving or deforming, and only sparse projection data may be available. Sparse radiographic views provide fundamentally incomplete observations of underlying structures, creating an ill-posed reconstruction problem that classical algorithms cannot reliably solve.

## Aims

- Reconstruct dynamic 3D anatomy from sparse X-ray projections in clinically relevant settings including image-guided radiotherapy, CBCT, and orthopaedic imaging.
- Recover patient-specific anatomy and motion directly from limited projection data without requiring full angular sampling.

## Methods

Physics-aware learning frameworks are developed that integrate continuous volumetric representations, patient-specific anatomical priors, and differentiable X-ray rendering. These components allow the model to reason about the underlying 3D anatomy consistent with the observed projections while respecting the physics of X-ray image formation.

## Outcomes
