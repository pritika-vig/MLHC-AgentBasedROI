# MLHC-AgentBasedROI
Interpretable Agent-Based ROI Selection for Tumor Classification in Digital Pathology

Exploration code of the dataset can be found in the notebooks/ directory. 

ML4H_Patch_predictor.ipynb contains the code that trained the patch predictor.
ML4H_Camelyon16_Unet_SegFormer_training.ipynb contains the code that traiend the segmentation model. 
few_shot_cancer_agent.ipynb contains a version of the agent using few shot learning. 
gen_output_cancer_agent_SegTransformer_Integration.ipynb contains a version of the agent using the segmentation model. 

Running these books requires access to the dataset, which can be downloaded at: https://camelyon17.grand-challenge.org/Data/
It also requires an anthropic api key with money attached. 
