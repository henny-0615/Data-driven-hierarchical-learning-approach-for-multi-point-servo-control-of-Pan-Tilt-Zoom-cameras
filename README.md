# Data-driven-hierarchical-learning-approach-for-multi-point-servo-control-of-Pan-Tilt-Zoom-cameras

This repository consists of two main parts: the virtual simulator and the training code for the control agent.
## Evaluate in the virtual simulator.
1. Install the necessary dependencies。Note that we conducted our experiments using python 3.8.10.

`<div style="background-color: #f0f0f0; padding: 10px;">
pip install -r requirements\requirements_sim.txt</div>`

2. The virtual environment is built using Unity 3D, and includes swamp and mountain scenes located in Simulator\Assets\scenes.

3. Note that the paths for agent.py and featureMatching.py in Simulator\Assets\Scripts\Unity_Python need to be updated.
