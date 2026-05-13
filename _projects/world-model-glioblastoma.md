---
title: A World Model for Adaptive Radiotherapy of Glioblastoma on the MR-Linac 
areas: [medical-imaging, radiotherapy]   # one or more: medical-imaging, nuclear-medicine, radiotherapy, education
status: active             # active | completed
lead: Daryl Wilding-McBride        # must match name field in _people/ exactly
collaborators:             # external collaborators (optional)
  - name: A/Prof Sweet Ping Ng
    institution: Department of Radiation Oncology, Austin Health
team:                      # must match name fields in _people/ exactly
funding: NHMRC             # funding body (optional)
start_year: 2025
end_year:                  # leave blank if ongoing
description: >-
  Glioblastoma's poor prognosis reflects in part the limitations of fixed treatment plans applied to a tumour that evolves throughout the radiotherapy course. The MR-Linac makes visible what was previously hidden — fraction-by-fraction changes in tumour volume, morphology, and position — but current planning tools remain reactive, working only from today's anatomy with no capacity to anticipate how the tumour will respond to alternative treatment decisions. This project develops a world model — a learned simulator trained on longitudinal GBM MRI data — that takes the current tumour state observed on the MR-Linac and a proposed treatment action (dose, fractionation) as input, and predicts tumour appearance at the next fraction without delivering the treatment. This enables counterfactual reasoning over competing adaptive plans and, eventually, training of a reinforcement learning agent to discover optimal fraction-by-fraction strategies. The model is trained on the LUMIERE dataset (91 GBM patients, 638 longitudinal studies), with tumour state represented by volume, segmentation mask, diffusion signal, and MGMT methylation status. A first prototype demonstrates plausible prediction of the contrast-enhancing tumour region at the next timepoint. Key open questions include data volume requirements for generalisation, validation standards for clinical utility, and how to formalise treatment outcome as an optimisation objective.
---
