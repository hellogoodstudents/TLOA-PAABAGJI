# TLOA-Power-Adaptive-Algorithm-Based-on-Air-Ground-Joint-Interference
The data and code for the paper "TLOA Power Adaptive Algorithm Based on Air-Ground Joint Interference  " can be found here.
The TLOA algorithm designed in this paper
Running Python Integrated Development Environment (IDE) version:PyCharm 2023.2.1 (Professional Edition)Runtime version: 17.0.8+7-b1000.8 amd64
Equipped third-party libraries: anaconda_depends_2023.09 and PyTorch version: 1.13.1
For the drawing programs of Scenario 1, Scenario 2, Scenario 3, and Scenario 4 in the "Scenario Plotting" folder, they can generate images directly after running.
In each scenario file:
Open the main function and click "Run" to execute the algorithm once with default settings. Modify the number of runs at the end of the program to enable repeated execution.
generate_nodes.py is the simulation program for the initial power of communication nodes.
modify_communication_nodes.py is the simulation program for the dynamic power adjustment of communication nodes.
jammer_first_run.py is the jamming program for the jammer's first decision based on the strategy.
jammer_run.py is the jamming program for the jammer's non-first decisions based on the strategy.
test.py is the detection program for jamming effectiveness in the simulation scenario.
Click to run the "Data Statistics" program to calculate the comparative data presented in the paper.
