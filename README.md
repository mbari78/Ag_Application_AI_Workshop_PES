# Ag_Application_AI_Workshop_PES_NMSU

## AI Predictive Analytics in Agriculture
This repository contains materials for a hands-on workshop on Artificial Intelligence (AI) driven predictive analytics in agriculture, with on deep learning application on UAV imagery, lab-derived phenotyping data to extract features, and predict yield, genomic selection for yield prediction, path optimization for robotic spot spraying.

The workshop includes:

1. Deep learning applications to predict crop yield using UAV and lab-derived imagery (Bari et al. 2026).
2. Genomic selection using a published dataset from Medina et al. (2025) to predict forage biomass yield in complex polyploid species.
3. Reinforcement Learning (RL) concepts showing how fleets of robots can collaborate to optimize chemical application, identify efficient spraying paths, and reduce environmental impact.

By the end of the workshop, participants will gain a practical understanding of tools and workflows needed to build end-to-end agricultural prediction pipelines.

## Setup
Download and install python https://www.python.org/downloads/ and VS code https://code.visualstudio.com/ in your machine. You can create an environment or use the base python environment. Please follow [this](https://www.youtube.com/watch?v=cUAK4x_7thA) tutorial if you need. Use the following command to install the necessary python packages:
```bash
pip install -r requirements.txt
```
Additionally, follow the below steps for the hands-on session:

1. Download the weight files from [here](https://eltnmsu-my.sharepoint.com/:f:/g/personal/mabari_nmsu_edu/IgBCUc_ebmWqQbAb513KFaVUAXYb5EEQbrd8nuFKG9Y8m_4?e=qsbc6L) and put them under `dl_yield_prediction\weights`.
2. Download and install CoppeliaSim from here: [https://www.coppeliarobotics.com/](https://www.coppeliarobotics.com/). Select the "Edu" version (registration is optional).


For more please explore
```bash
@article{BARI2026_DL_Phenomics,
title = {Deep learning for sorghum yield forecasting using uncrewed aerial systems and lab-derived imagery},
journal = {Plant Phenomics},
volume = {8},
number = {1},
pages = {100133},
year = {2026},
issn = {2643-6515},
doi = {https://doi.org/10.1016/j.plaphe.2025.100133},
url = {https://www.sciencedirect.com/science/article/pii/S2643651525001396},
author = {Md. Abdullah Al Bari and Aliva Bakshi and Jahid Chowdhury Choton and Swaraj Pramanik and Trevor D. Witt and Doina Caragea and Scott Bean and S.V. {Krishna Jagadish} and Terry Felderhoff},
keywords = {Deep Learning, Computer Vision, YOLO, Faster-RCNN, Unmanned Aerial Systems (UAS) Imagery, Extracting Yield Features, Sorghum Yield Prediction using Machine Learning}
}
```
## References
Bari et al. (2026). Deep learning for sorghum yield forecasting using uncrewed aerial systems and lab-derived imagery. Plant Phenomics. https://doi.org/10.1016/j.plaphe.2025.100133.

Medina et al. (2025). Genome-Wide Association and Genomic Prediction of Alfalfa (Medicago sativa L.) Biomass Yield Under Drought Stress. Int J Mol Sci. http://doi: 10.3390/ijms26020608.

Choton and Hsu (2025). Coverage Path Planning in Precision Agriculture: Algorithms, Applications, and Key Benefits. https://doi.org/10.48550/arXiv.2412.19813
