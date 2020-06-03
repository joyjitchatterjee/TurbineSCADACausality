# TurbineSCADACausality
Supplementary material for our TORQUE 2020 Submission "Temporal Causal Inference in Wind Turbine SCADA Data Using Deep Learning for Explainable AI"

# Contents 
This repository contains:-
1. Flowchart of preprocessing process towards labelling of faults in SCADA data and cleaning, for temporal causal inference.

Note: The causal relationships X->Y should be interpreted as X is caused by Y, where X and Y are SCADA features (time-series) of observations. 

# Acknowledgments
We would like to acknowledge the Offshore Renewable Energy (ORE) Catapult for providing us access to operational data from the turbine through Platform for Operational Data (POD) (http://pod.ore.catapult.org.uk). We are also grateful to Aura Innovation Centre and the University of Hull for their support.
# Disclaimer
It should be noted that the causality graphs obtained above are an interpretation on how the AI model performs its predictions, and what are the key features the model looks at while predicting. Thereby, there may be many causal relationships which do no make sense to a human, and we do not claim the accuracy of all the relationships. Rather, these are machine-utilised during prediction, and temporal causal inference can help engineers & technicians investigate why the anomaly is caused as a consequence of such features. 
