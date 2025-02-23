# Situational-Aware Motion Planning for Mobile Robots in Intralogistics

## Project Overview
This project aims to develop a situational-aware motion planning system for mobile robots operating in intralogistics environments. The system will be built using **URDF, Gazebo, and ROS** and will focus on obstacle avoidance, path planning, and real-time navigation in dynamic warehouse settings.

## Documentation

You can find the project documentation online at: 

[Situational Awareness Robot Documentation](https://rubin-embedded.github.io/situational_aware_robot/)

For more details on the implementation and usage, please refer to the documentation linked above.

## Project Timeline

### **Phase 1: Project Planning and Setup (Week 1-2)**
#### Goals:
- Define project scope and objectives.
- Set up the development environment.
- Learn necessary tools (ROS, Gazebo, URDF).

#### Tasks:
- Research and finalize project requirements.
- Install ROS (Noetic or Humble), Gazebo, and other dependencies.
- Set up a GitHub repository for version control.
- Create a basic URDF model of the mobile robot.
- Learn ROS fundamentals (topics, nodes, services, actions).

#### Deliverables:
- Project plan document.
- Development environment setup.
- Basic URDF model of the robot.

---

### **Phase 2: Robot Modeling and Simulation (Week 3-4)**
#### Goals:
- Complete the robot model in URDF.
- Simulate the robot in Gazebo.

#### Tasks:
- Add sensors (LiDAR, camera) to the URDF model.
- Create a Gazebo world for the intralogistics environment (e.g., shelves, conveyor belts, obstacles).
- Test the robot's basic movement in Gazebo.
- Integrate ROS controllers for the robot's wheels.

#### Deliverables:
- Complete URDF model with sensors.
- Gazebo world file.
- Basic robot movement in simulation.

---

### **Phase 3: Sensor Integration and Mapping (Week 5-6)**
#### Goals:
- Integrate sensors (LiDAR, camera) into the simulation.
- Generate a map of the environment.

#### Tasks:
- Configure LiDAR and camera plugins in Gazebo.
- Use ROS gmapping or cartographer to create a map of the environment.
- Test sensor data in RViz.

#### Deliverables:
- Sensor data visualization in RViz.
- Map of the intralogistics environment.

---

### **Phase 4: Navigation Stack Setup (Week 7-8)**
#### Goals:
- Set up the ROS navigation stack (move_base).
- Implement global and local planners.

#### Tasks:
- Configure move_base for the robot.
- Set up a global planner (A* or Dijkstra) and a local planner (DWA or TEB).
- Test navigation in a static environment.

#### Deliverables:
- Functional navigation stack.
- Robot navigating in a static environment.

---

### **Phase 5: Situational Awareness and Dynamic Planning (Week 9-10)**
#### Goals:
- Implement situational awareness using sensor data.
- Add dynamic obstacle avoidance.

#### Tasks:
- Use LiDAR/camera data to detect obstacles.
- Integrate dynamic obstacle avoidance into the local planner.
- Test navigation in a dynamic environment (e.g., moving obstacles).

#### Deliverables:
- Dynamic obstacle avoidance functionality.
- Robot navigating in a dynamic environment.

---

### **Phase 6: Optimization and Testing (Week 11-12)**
#### Goals:
- Optimize the motion planner for efficiency and smoothness.
- Test the robot in various scenarios.

#### Tasks:
- Tune planner parameters (e.g., velocity, acceleration, obstacle thresholds).
- Test the robot in complex environments (e.g., narrow passages, crowded areas).
- Fix bugs and improve performance.

#### Deliverables:
- Optimized motion planner.
- Test results and performance metrics.

---

### **Phase 7: Documentation and Final Presentation (Week 13)**
#### Goals:
- Document the project.
- Prepare a final presentation.

#### Tasks:
- Write a detailed project report (including design, implementation, and results).
- Create a presentation (slides or video demonstration).
- Prepare a demo for the final presentation.

#### Deliverables:
- Project report.
- Final presentation.
- Demo video or live demonstration.

---

## **Development Tools & Technologies**
- **ROS** - Robot Operating System for robot control.
- **Gazebo** - Simulation environment.
- **URDF/Xacro** - Robot modeling.
- **Rviz** - Visualization tool.
- **Move_base** - ROS navigation stack.
- **LiDAR/Camera Plugins** - Sensor simulation.
- **A* / Dijkstra / DWA / TEB** - Motion planning algorithms.
- **GitHub** - Version control.

## **Contributors**
- Rubin Khadka

