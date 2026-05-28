# FLQ_Mod2_Cardiotoxicity_Workflow
AI-guided computational workflow for cardiotoxicity-aware fluoroquinolone redesign using docking, MD, MM/GBSA, and AI target prediction.
FLQ_Mod2_Cardiotoxicity_Workflow/
│
├── README.md
│
├── Docking/
│   ├── glide_xp_scores.csv
│   ├── gnina_rescoring.csv
│   ├── docking_replicate_summary.csv
│
├── MD/
│   ├── rmsd.csv
│   ├── rmsf.csv
│   ├── hbond_occupancy.csv
│   ├── sasa.csv
│   ├── md_rep1.xtc
│   ├── md_rep2.xtc
│   ├── md_rep3.xtc
│
├── MMGBSA/
│   ├── mmgbsa_per_frame.csv
│   ├── mmgbsa_replicate_summary.csv
│   ├── convergence_curve.csv
│
├── ADMET/
│   ├── swissadme_output.csv
│   ├── pkcsm_output.csv
│   ├── protox_output.csv
│   ├── deepherg_output.csv
│
├── AI_TargetPrediction/
│   ├── deepchem_predictions.csv
│   ├── swiss_target_prediction.csv
│   ├── combined_targets_ranked.csv
│
└── Structures/
    ├── moxifloxacin_ligand.sdf
    ├── FLQ_Mod_2.sdf
    ├── docking_pose_herg.pdb
    ├── docking_pose_gyrase.pdb

    MD_Trajectories/
│   ├── hERG_FLQ_Mod2_200ns_rep1.xtc
│   ├── hERG_Moxifloxacin_200ns_rep1.xtc
│   ├── DNAgyrase_FLQ_Mod2_200ns_rep1.xtc
│
├── MD_Representative_Frames/
│   ├── hERG_FLQ_Mod2_MD_RepresentativeFrame.png
│   ├── hERG_Moxifloxacin_MD_RepresentativeFrame.png
│   ├── DNAgyrase_FLQ_Mod2_MD_RepresentativeFrame.png
│
├── README.md
All supplementary computational reproducibility materials, representative structures, MM/PBSA datasets, and molecular dynamics representative snapshots are publicly available at Zenodo: DOI: 10.5281/zenodo.20434649 


