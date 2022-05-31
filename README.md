# Physics-informed-Transformer-IDM
The implementation of the paper "A Physics-Informed Transformer Model for Vehicle Trajectory Prediction on Highways". The paper is now under review. Because of the confidentiality agreement and the commercial project application, the training part of the PIT-IDM has been deleted. Still, we upload the single trajectory visulization code, which contains the structures of the PIT-IDM and benchmark Transformer.

# Abstract of the paper
Autonomous Vehicles (AVs) have made remarkable developments and are anticipated to replace human drivers. In transitioning from human-driven vehicles to fully AVs, one crucial task is to predict the trajectories of the subject vehicle and its surrounding vehicles in real time. Most existing methods of vehicle trajectory prediction on highways are based on data-driven models that lack interpretability and physical constraints or physics-based models with low prediction accuracy. This paper proposes a Physics-Informed Deep Learning framework that fully leverages the advantages of data-driven and physics-based models to go beyond the existing models. We use the transformer neural network architecture with self-attention  as Physics-Uninformed Neural Network (PUNN) and Intelligent Driver Model (IDM) as Physics-Informed Neural Network (PINN), then complete the construction of Physics-Informed Transformer-Intelligent Driver Model (PIT-IDM). The experiments have been conducted in two datasets with different traffic environments, i.e., Next Generation SIMulation (NGSIM) data in the US, and the Ubiquitous Traffic Eyes (UTE) data in China. Compared with the three kinds of baselines, the best performing PIT-IDM reduces longitudinal trajectory prediction errors by 5%-50%, some of which are even reduced by more than 70%. Extensive empirical analyses have been carried out to verify its excellent spatio-temporal transferability and explore the physics-informed mechanism underlying this deep learning method. The results further validate the efficacy of this Physics-Informed Deep Learning framework in enhancing model accuracy, interpretability, and transferability.

# Getting started 
The Physics-Informed Transformer-IDM was constructed based on the open-source deep learning framework named pytorch. Please ensure you have already install it before using our code.

# Citation
If you find our work useful for your research, please consider citing the paper (the paper is now under review). 

# Reference 
The "multi_attention_forward.py" code base borrows from https://github.com/Majiker/STAR
