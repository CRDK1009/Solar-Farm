# Solar-Farm
https://github.com/user-attachments/assets/77ba209f-f18a-4a85-b72f-dd629661bbcc
### Overview
This project presents a cost-efficient smart solar farm system powered by machine learning to dynamically optimize solar panel orientation for maximum power generation across seasons. By simulating solar trajectories and deploying predictive models, it reduces the need for complex hardware while boosting energy output.
### Key Features
Sun Simulation Environment: Built using Tkinter to realistically model solar paths across spring, summer, autumn, and winter.

Dynamic Panel Alignment: Red lines visualize real-time orientation adjustments to keep panels perpendicular to the sun.

Data Generation: Synthetic dataset generated simulating 360 days with sun positions (Sun_x, Sun_y) based on time and season.

Machine Learning Models:

Bagging: Random Forest (Best performer)

Boosting: XGBoost, LightGBM

Baseline: Multilayer Perceptron (for comparison)

Visualization: Real-time color-based feedback system where red intensity correlates with power generation.
### Results
Random Forest achieved the best MSE (~0.62) and MAE (~8.74), significantly outperforming deep learning models on tabular data.

Power prediction performance is seasonally consistent, with Random Forest leading in all conditions.
### Deployment
The trained model is integrated into the simulation to autonomously predict sun movement and guide solar panel behavior. The system features self-correcting behavior by enabling nightly model retraining using new data for daily redeployment.
### Conclusion
The Smart Solar Farm system provides an affordable and scalable solution for maximizing solar energy efficiency. It combines intuitive visualization, solid ML performance, and environmental adaptability—ideal for real-world solar farm integration.
### References
Grinsztajn, L., Oyallon, E., Varoquaux, G. (2022). Why do tree-based models still outperform deep learning on typical tabular data?, NeurIPS.

Géron, A. (2019). Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow (2nd Ed.), O’Reilly Media.
