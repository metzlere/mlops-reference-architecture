# mlops-reference-architecture

This is a reference architecture that I've built for classical ML in production. It was designed for an organization with a low level of data maturity and is not fully automated, requiring manual triggers of the model development component and manual selection of a champion model. It uses all open-source tools. A custom class was made for experiment tracking because MLFlow was not available as an option. 

It draws inspiration from the Azure Architecture Center and was modified to fit my org's specific tools, needs, and skill levels.
https://learn.microsoft.com/en-us/azure/architecture/ai-ml/guide/machine-learning-operations-v2

![Alt text](MLOps_ref_architecture_v1.png)
