# MOMDP
Solver for discrete Mixed Observable Markov Decision Processes (MOMDPs).  MOMDPs are decision-making formalism for high-level planning under mixed full and partial observations. In this repo, we leverage MOMDP to solve a planning problem, where the agent (blue) has to explore the uncertain regions (light drown), which may be traversable, and the goal regions (green), which may containt the a science sample that the agent is looking for. The figure below shows a closed-loop trajectory for the blue agent. In this simulation the location of the agent is fully observable, but the state of the uncertain regions (light brown) and goal regions (green) is partially observable.

<p align="center">
<img src="https://github.com/urosolia/MOMDP/blob/main/trajectory.gif" width="500" />
</p>



# Prerequisite 

Please create pyMOMDP conda environment running the following commands

```
conda env create --file pyMOMDP.yml
```