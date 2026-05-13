---
title: Automated Longitudinal Segmentation of Glioblastoma on the MR-Linac
areas: [medical-imaging, radiotherapy]   # one or more: medical-imaging, nuclear-medicine, radiotherapy, education
status: active             # active | completed
lead: Daryl Wilding-McBride        # must match name field in _people/ exactly
collaborators:             # external collaborators (optional)
  - name: A/Prof Sweet Ping Ng
    institution: Department of Radiation Oncology, Austin Health
team:                      # must match name fields in _people/ exactly
funding: NHMRC             # funding body (optional)
start_year: 2024
end_year:                  # leave blank if ongoing
description: >-
  Glioblastoma is the most aggressive primary brain tumour in adults, with a median survival of around 15 months despite surgery, radiotherapy, and chemotherapy. Tumours are diffuse, morphologically heterogeneous, and can shift substantially during the treatment course, yet standard radiotherapy planning treats them as static. The MR-Linac addresses this by acquiring MRI at every treatment fraction, creating a longitudinal imaging record unique among radiotherapy modalities. In current clinical practice this data is largely underused, because manual tumour delineation is too time-consuming to perform daily. This project addresses that gap with an automated segmentation model based on the nnU-Net framework, trained on the UPENN-GBM dataset (630 de novo GBM patients) using T2 and FLAIR sequences, and evaluated against expert manual delineations on MR-Linac patient data. Results across two patients show Dice similarity coefficients of 0.84–0.89 maintained across fractions, with mean surface distances of 1.6–4.5 mm. A key finding is tumour migration of up to 19 mm between fractions — a shift large enough to compromise dose coverage — which automated tracking makes routinely detectable where manual delineation cannot. The longer-term aim is a clinical alert system that flags volumetric or positional changes exceeding predefined thresholds, supporting the clinical team in deciding whether plan adaptation is warranted.
---

## Background

Glioblastoma is the most aggressive primary brain tumour in adults, with a median survival of around 15 months despite surgery, radiotherapy, and chemotherapy. Tumours are diffuse, morphologically heterogeneous, and can shift substantially during the treatment course, yet standard radiotherapy planning treats them as static. The MR-Linac acquires MRI at every treatment fraction, creating a longitudinal imaging record unique among radiotherapy modalities — but in current clinical practice this data is largely underused, because manual tumour delineation is too time-consuming to perform daily.

## Aims

- Develop an automated segmentation model capable of tracking glioblastoma across the MR-Linac treatment course.
- Quantify tumour volumetric and positional changes fraction by fraction.
- Build a clinical alert system that flags changes exceeding predefined thresholds, supporting adaptive planning decisions.

## Methods

The segmentation model is based on the nnU-Net framework, trained on the UPENN-GBM dataset (630 de novo GBM patients) using T2 and FLAIR sequences. The model is evaluated against expert manual delineations on MR-Linac patient data.

## Outcomes

Results across two patients show Dice similarity coefficients of 0.84–0.89 maintained across fractions, with mean surface distances of 1.6–4.5 mm. A key finding is tumour migration of up to 19 mm between fractions — a shift large enough to compromise dose coverage — which automated tracking makes routinely detectable where manual delineation cannot.
