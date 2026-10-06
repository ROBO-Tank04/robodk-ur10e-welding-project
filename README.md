# UR10e Robotic Arc Welding Cell Simulation

##  Project Overview
This project demonstrates the design, setup, and simulation of an automated robotic arc welding cell[cite: 1]. Using a collaborative robot arm, the simulation models a complete industrial welding operation, focusing on precise torch trajectory planning, fixture placement, and collision-free path execution.

##  Objectives
* **Cell Setup:** Configure a realistic industrial workspace incorporating a robotic manipulator, a welding torch tool, a fixture table, and a target component[cite: 1].
* **Trajectory Programming:** Program accurate end-effector paths to follow complex welding seams continuously.
* **Reach & Collision Analysis:** Validate joint limits, workspace reachability, and collision avoidance within the simulation environment[cite: 1].

##  Software Used
* **RoboDK:** Primary offline programming and simulation environment for industrial robots.
* **UR10e Robot Kinematics:** Collaborative robot model utilized for the welding operations[cite: 1].

##  Results
* Successfully simulated a continuous automated welding cycle[cite: 1].
* Generated optimized robot paths with smooth transitions, avoiding singularity zones and joint limits.
* Verified that the welding torch maintains a consistent standoff distance and orientation relative to the workpiece.

##  Learning Outcomes
* Gained hands-on experience in industrial cell layout design and offline robot programming (OLP).
* Enhanced understanding of collaborative robot integration, particularly trajectory planning for welding processes.
* Improved proficiency in using simulation tools like RoboDK to validate automation workflows prior to physical deployment[cite: 1].

##  Project Files
```text
├── CAD_Models/         # 3D models of the fixture, workspace, and components
├── Station_Files/      # RoboDK station and project files (.rdk)
├── Programs/           # Generated robot controller programs / script files
├── Media/              # Renders, screenshots, and screen recordings of the simulation
└── README.md           # Project documentation
