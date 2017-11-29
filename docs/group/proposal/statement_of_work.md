# Statement of Work

Meganalytics of fMRI and DWI Connectomes 
Eric Bridgeford, 2017

| Sprint   | Date Due | Requirements |
|---|---|---|
| Sprint 1: NDMG Preliminary Meganalysis | 11/6 | <ul><li>Tie NDMG-f and NDMG-d together into m3r-release: deliverable is a github branch/docker container with both modalities, and a demo for each modality</li><li>Identify differences in connectivity ipsi-laterally vs. contra-laterally in fMRI and DWI: deliverable is a RMarkdown containing algorithms.md for the investigation</li><li>Identify differences in connectivity bulaterally vs. non-bilaterally in fMRI and DWI: deliverable is a RMarkdown containing algorithms.md for the investigation</li></ul>  |
| Sprint 2: Parametric Investigations of Batch Effects | 12/20  | <ul><li>Use GTheory to investigate Batch Effects of connectome Data: Deliverable is an RMarkdown containing algorithms.md for GTheory on connectome data</li><li>Use Mixed-Effects Modelling to investigate Batch Effects of connectome Data: Deliverable is an RMarkdown containing algorithms.md for mixed-effects modelling on connectome data</li><li>MGC package updated: nature checklist, vignettes for each function, and travis-ci tests for MGC package</li></ul>  |
| Spring 3: Non-parametric Investigations of Batch Effects | 3/15   | <ul><li>Update MGC statistic to perform with fixed and random effects</li><li>Use of updated MGC statistic on fMRI and DWI data to investigate sources of error in connectomes: deliverable is a notebook investigating this on the full graphs</li></ul> |
| Sprint 4: Refinement of Connectome Estimation with Non-Parametric Methods | 5/15 | <ul><li>Use of updated MGC statistic to guide development of optimal normalization technique: deliverable is a notebook investigating the impact of normalization techniques on MGC statistic</li><li>Use of updated MGC statistic to guide development of optimal dimensionality reduction  technique: deliverable is a notebook investigating the impact of dimensionality reduction techniques on MGC statistic</li></ul> |
