# Hi, I'm Jiarui Hua 👋

I am a graduate student at **Beihang University (BUAA)**, focusing on autonomous UAV systems.

My research interests include **Reinforcement Learning, UAV Trajectory Planning, Planning & Control, and End-to-End Autonomous Flight**.

---

## 🎓 Education

### Beihang University (BUAA)

**Institute of Unmanned Systems**
M.Eng. in **Multi-Domain Autonomous Unmanned System Design**
*Sep. 2025 – Jun. 2028 (Expected)*

### Beihang University (BUAA)

**School of Aeronautic Science and Engineering**
B.Eng. in **Aircraft Control and Information Engineering**
*Sep. 2021 – Jun. 2025*

---

## 💼 Experience

### Differential Robotics

**Agile Flight Algorithm Intern · Frontier Innovation Team**
*Sep. 2026 – Jun. 2027 (Expected)*

---

## 🔬 Research & Projects

### Reinforcement Learning-based UAV Waypoint Planner

Developing a LiDAR-based local waypoint planning framework for autonomous UAV navigation and collision avoidance in unknown environments.

* Process **Livox MID-360** 3D point clouds through horizontal and vertical angular discretization and extract the nearest obstacle distance within each angular bin to construct fixed-dimensional LiDAR observations.

* Fuse **LiDAR observations, relative goal information, and UAV motion states** as policy inputs. The reinforcement learning policy generates desired linear velocities and yaw-rate commands, which are executed through downstream tracking and control modules.

* Implement and evaluate reinforcement learning policies using **SAC with Stable-Baselines3** and **PPO with SKRL**.

* Investigate multi-frame observations and temporal feature extraction using **LSTM, GRU, and Transformer** architectures for improved perception and avoidance of dynamic obstacles.

* Apply LiDAR-oriented **domain randomization**, including random measurement dropout, distance perturbation, and perception latency, to reduce the gap between simulated LiDAR observations and the real-world **Fast-LIO** perception pipeline.

* Conduct training and evaluation in **AirSim** and **Isaac Sim / Isaac Lab**, perform Sim-to-Sim validation in **Gazebo**, and evaluate the policy on a real UAV platform.

* Compare the learning-based planner against representative approaches including **Fast-Planner, EGO-Planner, NAVRL, and YOPO**.

### Related Work

* *End-to-End Mapless UAV Target Tracking via Transformer-based Reinforcement Learning*

---

## 🧠 Research Interests

* Reinforcement Learning
* UAV Motion Planning
* UAV Trajectory Optimization
* Planning & Control
* End-to-End Autonomous Flight
* Learning-based Navigation
* Sim-to-Real

---

## 🛠️ Technical Stack

### Reinforcement Learning

* **Algorithms:** SAC, PPO
* **Training Techniques:** Reward Design, Curriculum Learning, Domain Randomization
* **Libraries:** Stable-Baselines3, SKRL

### Deep Learning

* **Framework:** PyTorch
* **Architectures:** MLP, CNN, LSTM, GRU, Transformer

### UAV Planning & Control

* **Trajectory Optimization:** Fast-Planner, EGO-Planner, MINCO
* **Learning-based Planning:** YOPO, NAVRL
* **Fundamentals:** Path Planning, Trajectory Generation, Trajectory Optimization

### Perception & State Estimation

* Extended Kalman Filter (EKF)
* Fast-LIO Series
* LiDAR-Inertial Odometry

### Simulation & Robotics

* Isaac Sim
* Isaac Lab
* AirSim
* Gazebo
* ROS / ROS 2

### Development

* Python
* C++
* Linux
* Git
* Docker

---

## 📚 Selected Research Topics

`Reinforcement Learning` · `UAV` · `Trajectory Optimization` · `Motion Planning` · `Planning & Control` · `End-to-End Learning` · `Sim-to-Real`

---

## 📫 Links

* **GitHub:** [VicHxuan](https://github.com/VicHxuan)
* **Personal Website:** [vichxuan.github.io](https://vichxuan.github.io/)
* **Knowledge Tree & Open Tutorials:** [vichxuan.github.io/knowledge-tree](https://vichxuan.github.io/knowledge-tree/)

---

> Learning-based planning and control for autonomous aerial robots.
