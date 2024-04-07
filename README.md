
## Enviroment Details

This environment is called the Reacher Environment. It consists of a double-jointed arm can move to target locations. When the agent's hand is on the target location, it receives a reward of +0.1. The state-space consists of 33 variables corresponding to the arm's position, rotation, velocity, and angular velocities. The action space is a 4 number vector representing torque applicable to two joints, and every entry in the action vector should be a number between -1 and 1. The environment is solved once the agent receives an average score of 30 over 100 consecutive episodes. Currently, robotic arms in factories require a very tightly controlled environment. This technology can serve as a solution to more versatile machinery.

## Getting Started

#### Download the Unity enviroment:
    Linux: https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Linux.zip    
    Mac OSX: https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher.app.zip    
    Windows (32-bit): https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Windows_x86.zip    
    Windows (64-bit): https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Windows_x86_64.zip    
            
#### Requirements:    
    tensorflow==1.7.1    
    Pillow>=4.2.1    
    matplotlib    
    numpy>=1.11.0    
    jupyter    
    pytest>=3.2.2    
    docopt    
    pyyaml    
    protobuf==3.5.2    
    grpcio==1.11.0    
    torch>=1.0.0    
    pandas    
    scipy    
    ipykernel    
    

## Instructions

In order to run the project, go to Continuous_Contol.ipynb. From there, run all of the code cells.

## Acknowledgements

The code was written making a references to:
GitHub. 2022. ContinousControl/Continuous_Control.ipynb at master · gkowalik/ContinousControl. [online] Available at: <https://github.com/gkowalik/ContinousControl/blob/master/Continuous_Control.ipynb> [Accessed 10 May 2022].
