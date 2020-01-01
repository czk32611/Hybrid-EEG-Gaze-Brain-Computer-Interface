# Hybrid-EEG-Gaze-Brain-Computer-Interface  
We proposed a hybrid EEG/Gaze brain-computer interface.

There are two parts of this project:
## 1. Inferring the target from the past gaze trajectories.  
  ![Task Description](https://raw.githubusercontent.com/czk32611/Hybrid-EEG-Gaze-Brain-Computer-Interface/master/Task%20description.PNG)
The goal of the user is to use a joystick to control the cursor to reach the target (labelled as a number) while avoid hitting the obstacles (labelled as letters).  
  
To infer the target, we proposed a hidden-Markov-model-based algorithm to model the gaze trajectories. The input of this model it the current cursor position and gaze location.  
  
The demo of this work can be found in https://youtu.be/xyn6AthUFmc.  
  
Reference:  
  "A Two-Stage Model for Inference of Target Identity during 2D Cursor Control from Natural Gaze Trajectories", [EMBC 2015](https://ieeexplore.ieee.org/document/7318402)

## 2. Fuse the decision from EEG signal and eye gaze by Bayesian integration.
![Hybrid System](https://raw.githubusercontent.com/czk32611/Hybrid-EEG-Gaze-Brain-Computer-Interface/master/Hybrid%20system.png)

The subject is instructed to use his brain signal (motor imaginary) to control the robot arm in four directions in 2D.
  
The demo of this work can be found in https://www.youtube.com/watch?v=pIoZI_08u3I.  

References: 
    ```
    @inproceedings{dong2015hybrid,
     title={Hybrid brain computer interface via Bayesian integration of EEG and eye gaze},
     author={Dong, Xujiong and Wang, Haofei and Chen, Zhaokang and Shi, Bertram E},
     booktitle={International IEEE/EMBS Conference on Neural Engineering (NER)},
     pages={150--153},
     year={2015},
     organization={IEEE}
     } 
     ```
  "Hybrid gaze/EEG brain computer interface for robot arm control on a pick and place task", [EMBC 2015](https://ieeexplore.ieee.org/abstract/document/7318649)
