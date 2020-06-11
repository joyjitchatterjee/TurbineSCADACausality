# TurbineSCADACausality
Supplementary material for our TORQUE 2020 Submission "Temporal Causal Inference in Wind Turbine SCADA Data Using Deep Learning for Explainable AI"

# Contents 
This repository contains:-
1. Flowchart of preprocessing process towards labelling of faults in SCADA data and cleaning, for temporal causal inference.
2. Multiple temporal causal graphs for different types of anomalies, constructed using SCADA data.

*Note: The causal relationships Y->X should be interpreted as: change in Y occurs due to variation in X, where X and Y are SCADA features (time-series) of observations. The identified causal relationships may include relations which can otherwise be disregarded as noise/irrelevant by a human, but are significant to how the AI model makes its predictions.*

# Acknowledgments
We would like to acknowledge the Offshore Renewable Energy (ORE) Catapult for providing us access to operational data from the turbine through Platform for Operational Data (POD) (http://pod.ore.catapult.org.uk). We are also grateful to Aura Innovation Centre and the University of Hull for their support.

We are also thankful to Nauta et al. for their paper on "Causal Discovery with Attention-Based Convolutional Neural Networks" https://www.mdpi.com/2504-4990/1/1/19 which proposes the Temporal Causal Discovery Framework used as the basis to construct temporal causal graphs, and their learning model for financial & neuroscientfic domains was modified and utlised to construct the temporal causal graphs for our study using SCADA data under different types of anomalies. 

# Disclaimer
It should be noted that the causality graphs obtained above are an interpretation on how the AI model performs its predictions, and what are the key features the model looks at while predicting (derived during causal validation as per the attention scores of the dilated CNN for temporal causal discovery). Thereby, there may be many causal relationships which do no make sense to a human, and we do not claim the accuracy of all the relationships. Rather, these are machine-utilised during prediction, and temporal causal inference can help engineers & technicians investigate why the anomaly is caused as a consequence of such features. 

# License

This repo is based on the MIT License, which allows free use of the provided resources, subject to the original sources being credit/acknowledged appropriately. The software/resources under MIT license is provided as is, without any liability or warranty at the end of the authors.
