# Code For "Guard2Vul: Effective Vulnerability Detection via Augmented Data and Sensitive Semantic"

<img width="647" alt="fw" src="https://github.com/shenhtrick/Guard2Vul/assets/43394667/79d7fec4-ec1d-4828-a3f6-d696f7425c08">


# Dataset
The dataset was not stored here due to its size. You can find it at the following website: https://drive.google.com/drive/folders/1SlOx2J2xfeW7BSyABbaARxE0rGnvTPhi?usp=sharing
# models
This module contains the definitions of classifiers and models, where you can choose the type of aggregator.
# resnet
This module contains the definition of the residual connection network, where you can make changes to the details of the residual connection network.
# utils
This module includes the definition of evaluation indicators, the definition of evaluation functions, the functions of the adversarial training methods we have constructed, and the details of how to train the model.
# main
This is the main function, which includes the parameter definition of the model and the saved results after training.
# Comparison results (with the experimental results of different dataset split)
Comparison result with the dl-based baselines (recorded in the paper):

<img width="334" alt="rq1" src="https://github.com/shenhtrick/Guard2Vul/assets/43394667/d916bede-7bd5-496d-9571-38238fbdc86c">

# Dataset
token number:
<img width="334" alt="rq1" src="https://github.com/shenhtrick/Guard2Vul/assets/43394667/b6b9b0ab-ba93-4d57-bc8f-d5873dff7df1">
train token number:
<img width="334" alt="rq1" src="https://github.com/shenhtrick/Guard2Vul/assets/43394667/39272384-e292-4a99-b408-08918b0101bc">
token number after GraphSMOTE:
<img width="334" alt="rq1" src="https://github.com/shenhtrick/Guard2Vul/assets/43394667/6376461e-425f-49a9-8af5-084183c91dc7">
