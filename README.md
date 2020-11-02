## Multi-task Learning for Predicting Alzheimer's Disease (AD) Progression

The main objective is to investigate multi task learning approaches into predicting Alzheimer's disease progression measured by the cognitive scores and selecting biomarkers predictive of the progression with good accuracy.
In order to achieve good accuracy, we investigate four different objective funcytions namely ridge regression, lasso regression, multi task lasso regression and temporal group lasso regression to optimize the learning models.
We use the Magnetic Resonance Imaging (MRI) and cognitive scores data sets from the Alzheimer's Disease and Neuroimaging Initiative (ADNI) site. The data is split into seven different time periods for each patient.

Some of the observations and analysis made are:
- We see that the temporal group lasso model has the least root mean square error values compared to the other three learning models.
- The data is more sparse int he later stages, hence sparsity including models like temporal group lasso perform better in the later time points.
- Using the weights calculated by the learning models, we select the most relevant biomarkers that predict the disease progression.
