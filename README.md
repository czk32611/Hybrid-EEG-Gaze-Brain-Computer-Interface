# Hybrid-EEG-Gaze-Brain-Computer-Interface  
We proposed a hybrid EEG/Gaze brain-computer interface.

There are two parts of this project:
## 1. Inferring the target from the past gaze trajectories.  
  ![Task Description](https://raw.githubusercontent.com/czk32611/Hybrid-EEG-Gaze-Brain-Computer-Interface/master/Task%20description.PNG)
The goal of the user is to use a joystick to control the cursor to reach the target (labelled as a number) while avoid hitting the obstacles (labelled as letters).  
  
To infer the target, we proposed a hidden-Markov-model-based algorithm to model the gaze trajectories. The input of this model it the current cursor position and gaze location.  
  
The demo of this work can be found in https://youtu.be/xyn6AthUFmc.  
  
### Bibtex 

    @inproceedings{chen2015two,
     title={A two-stage model for inference of target identity during 2D cursor control from natural gaze trajectories},
     author={Chen, Zhaokang and Shi, Bertram E},
     booktitle={Annual International Conference of the IEEE Engineering in Medicine and Biology Society (EMBC)},
     pages={474--477},
     year={2015},
     organization={IEEE}
     }

## 2. Fuse the decision from EEG signal and eye gaze by Bayesian integration.
![Hybrid System](https://raw.githubusercontent.com/czk32611/Hybrid-EEG-Gaze-Brain-Computer-Interface/master/Hybrid%20system.png)

The subject is instructed to use his brain signal (motor imaginary) to control the robot arm in four directions in 2D.
  
The demo of this work can be found in https://www.youtube.com/watch?v=pIoZI_08u3I.  

### Bibtex 
    
    @inproceedings{dong2015hybrid,
     title={Hybrid brain computer interface via Bayesian integration of EEG and eye gaze},
     author={Dong, Xujiong and Wang, Haofei and Chen, Zhaokang and Shi, Bertram E},
     booktitle={International IEEE/EMBS Conference on Neural Engineering (NER)},
     pages={150--153},
     year={2015},
     organization={IEEE}
     } 
     
    @inproceedings{wang2015hybrid,
     title={Hybrid gaze/EEG brain computer interface for robot arm control on a pick and place task},
     author={Wang, Haofei and Dong, Xujiong and Chen, Zhaokang and Shi, Bertram E},
     booktitle={Annual International Conference of the IEEE Engineering in Medicine and Biology Society (EMBC)},
     pages={1476--1479},
     year={2015},
     organization={IEEE}
     }
