Both the files FinalRL.m and LoacationOfBoltAndWaypointGen.m  Is to be runed befor running simulinkFinal program.  The solver much be set to auto.  If there is no agent.mat file present.  The agent need to be trained using the RobotsimTrainReinforcment_Way_60.slxc.  together with both the to matlab script. 
There is inmportant the the line 24:  env = rlSimulinkEnv('RobotsimFinal2','RobotsimFinal2/EnabledReinforcment1/RL Agent',obsInfo,actInfo);   refers to the corect sublock name.  Runing the training script. The training filename must be entered at line24, and changed again when running the simulinkfinal program. Thus the matlab script containing the agent configuration, much be changed when switching between training and runing final simulation

Link to agent.mat.: 

http://www.fileconvoy.com/dfl.php?id=g7aea3d0a14145bf710003522252a573fcdbbb22a15
