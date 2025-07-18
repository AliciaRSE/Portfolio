# Portfolio
# 🤖 LIMO Autonomous Navigation

This project focuses on developing and demonstrating an autonomous navigation system for the AgileX LIMO robot using ROS 1 (Melodic). The robot is equipped with depth sensing and must safely navigate a simulated arena, avoiding obstacles and environmental hazards (like drop-offs) using the ROS navigation stack.

> 🎯 **Objective**:  
> To design, implement, and verify a depth-aware autonomous navigation system using ROS 1 and the `move_base` stack, while applying a SEBoK-aligned systems engineering approach throughout the lifecycle.

---

## 🧩 Project Overview

- 📍 **Platform**: AgileX LIMO
- 🧠 **Framework**: ROS 1 (Melodic)
- 🔎 **Focus**: Obstacle avoidance, depth sensing, costmap tuning
- 🧪 **Environment**: Simulated arena in Gazebo
- ⚙️ **Approach**: Full Systems Engineering lifecycle (SEBoK-aligned)

---

## 📘 My Role and Contributions

This was a collaborative team project. My individual responsibilities included:

- 🧠 Designed the system context and defined operational constraints
- ⚙️ Implemented and tuned ROS navigation stack (`move_base`, `costmap_common_params.yaml`)
- 🧪 Conducted simulation-based testing in Gazebo and analyzed logs
- 📝 Acted as second-in-charge for documentation and meeting minutes  
  (tracked discussions, design decisions, and action items)
- ✍️ Authored the reflection report and contributed to final presentation
- 🧭 Applied the SEBoK Systems Approach to guide decision-making

---

## 🧠 Systems Engineering Approach (SEBoK-Aligned)

1. **Engineered System Context**  
   Defined stakeholders, robot environment, safety constraints, and performance metrics.

2. **Identifying and Understanding Problems**  
   Clarified key risks: ledge detection, narrow space navigation, and obstacle density.

3. **Synthesizing Possible Solutions**  
   Proposed costmap configurations, depth sensor strategies, and control loop parameters.

4. **Analysis and Selection of Alternatives**  
   Compared performance tradeoffs of different `local_planner` and `controller_frequency` setups.

5. **Implementing and Proving the Solution**  
   Developed the solution using ROS, ran multiple test iterations, and validated outputs via RViz and simulation logs.

6. **Deploying, Using, and Sustaining the System**  
   Successfully demonstrated the robot in a simulated challenge with minimal collision and high goal reachability.

7. **Applying the Systems Approach**  
   Maintained documentation, design traceability, and project lifecycle governance with Git and team coordination tools.

---

## 📘 Learning Outcomes Demonstrated

✔️ Configured and operated a robotics Technology Stack under performance constraints  
✔️ Applied SE Toolchain to plan, monitor, and evaluate autonomous system performance  
✔️ Produced artefacts and documented system decisions in a professional portfolio

---

## 🧪 Key Skills & Tools

| Category | Skills |
|---------|--------|
| Programming | Python (ROS nodes), Bash |
| Robotics | ROS 1 (Melodic), TurtleBot3, AgileX LIMO, URDF |
| Navigation | `move_base`, costmap tuning, recovery behaviors |
| Simulation | Gazebo, RViz |
| Lifecycle | SEBoK Systems Approach |
| Collaboration | Git, Markdown, structured meeting records |
| Documentation | System context diagrams, tradeoff logs, PDF reflections |

---

## 📂 Project Structure

```text
limo-autonomous-navigation/
├── launch/             # ROS launch files
├── scripts/            # Python ROS nodes
├── config/             # Costmap, planner configs
├── urdf/               # Robot description (if modified)
├── docs/
│   ├── system-context.png
│   ├── design-tradeoffs.md
│   └── reflection.pdf
├── media/
│   └── demo.gif
├── CMakeLists.txt
├── package.xml
└── README.md

<!-- Tags: ROS1, AgileX LIMO, Autonomous Navigation, move_base, costmap, URDF, Gazebo, RViz, Python, Systems Engineering, SEBoK, system context, synthesizing solutions, stakeholder requirements, obstacle avoidance, path planning, robot simulation, ROS navigation stack, meeting minutes, teamwork, documentation -->
