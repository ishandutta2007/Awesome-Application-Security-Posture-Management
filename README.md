# Awesome-Autonomous-Vehicle-Development

## Top Autonomous Vehicle Development Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Simulation, Validation & Autonomous Driving Software Stacks*  

**Last updated: March 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Autonomous Vehicle Development**. These tools support simulation, scenario testing, sensor modeling, and full-stack autonomous driving software for automotive OEMs, Tier 1 suppliers, robotics companies, and research institutions.



**Examples** include Applied Intuition, Cognata, Foretellix, Parallel Domain, dSPACE, IPG CarMaker, CARLA Cloud, BeamNG.tech, Hexagon Autonomy, and VI-grade (the category leaders).



**Open-source emphasis**: This section is expanded with active projects for self-hosting, custom simulation environments, and transparent autonomous driving stacks — ideal for researchers, startups, and developers building vendor-independent AV solutions. The open-source ecosystem for AV development is notably strong, with production-grade frameworks and simulators available under permissive licenses.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Applied Intuition](https://www.appliedintuition.com/)**  

  End-to-end toolchain for autonomous vehicle development covering simulation, validation, and data management with high-fidelity sensor models and scenario generation.



- **[Cognata](https://www.cognata.com/)**  

  AI-driven simulation platform for ADAS and autonomous vehicle validation with realistic 3D environments and sensor simulation.



- **[Foretellix](https://www.fortellix.com/)**  

  Coverage-driven verification platform for autonomous systems with formal scenario description language (M-SDL) and measurable safety metrics.



- **[Parallel Domain](https://paralleldomain.com/)**  

  Synthetic data generation and simulation platform for autonomous vehicle perception training and validation.



- **[dSPACE](https://www.dspace.com/)**  

  Simulation and validation solutions for autonomous driving with hardware-in-the-loop (HIL) testing and sensor simulation.



- **[IPG CarMaker](https://ipg-automotive.com/)**  

  Virtual vehicle development platform for testing autonomous driving functions, ADAS, and powertrain systems.



- **[CARLA Cloud](https://carla.org/)**  

  Cloud-hosted version of the open-source CARLA simulator with managed infrastructure and scalable scenario execution.



- **[BeamNG.tech](https://www.beamng.tech/)**  

  Soft-body physics-based simulation platform for autonomous vehicle development with realistic vehicle dynamics and sensor simulation.



- **[Hexagon Autonomy](https://hexagon.com/)**  

  Autonomous systems development platform combining sensor simulation, positioning, and validation tools.



- **[VI-grade](https://www.vi-grade.com/)**  

  Driving simulator and simulation software solutions for vehicle dynamics, ADAS, and autonomous driving validation.



## Open-Source GitHub Projects



- **[CARLA Simulator](https://github.com/carla-simulator/carla)**  

  The leading open-source simulator for autonomous driving research with 14,369+ stars and MIT license. Built on Unreal Engine, providing realistic urban environments, configurable sensor suites (LiDAR, cameras, radar, GNSS, IMU), and flexible Python/C++ APIs. Supports scenario_runner, ROS bridge, and reinforcement learning baselines .



- **[Autoware](https://github.com/autowarefoundation/autoware)**  

  The world's leading open-source autonomous driving software stack with 12,050+ stars under Apache-2.0 license. Production-ready framework used by 100+ companies across 30+ vehicles in 20+ countries. Provides comprehensive perception, planning, control, and localization modules with Level 4 autonomous driving capabilities .



- **[Apollo](https://github.com/ApolloAuto/apollo)**  

  Baidu's open autonomous driving platform with 27,000+ stars under Apache-2.0 license. Full-stack solution covering localization, perception, planning, control, and cloud services. Includes Cyber RT framework for high-performance runtime .



- **[CARLA Scenario Runner](https://github.com/carla-simulator/scenario_runner)**  

  Traffic scenario definition and execution engine for CARLA with 569+ stars. Enables reproducible testing of autonomous driving scenarios including cut-ins, pedestrian crossings, and complex intersections .



- **[CARLA ROS Bridge](https://github.com/carla-simulator/ros-bridge)**  

  ROS/ROS2 bridge for CARLA Simulator with 528+ stars, enabling seamless integration with ROS-based autonomous driving stacks including Autoware .



- **[LGSVL Simulator](https://github.com/lgsvl/simulator)**  

  Unity-based autonomous vehicle simulator from Microsoft AI & Research with 16,251+ stars. Provides seamless ROS and CyberRT integration with high-fidelity sensor models .



- **[Pylot](https://github.com/erdos-project/pylot)**  

  Modular autonomous driving platform that runs on both CARLA simulator and real-world vehicles. Designed for research with clean abstraction between perception, planning, and control modules .



- **[CARMA Platform](https://github.com/usdot-fhwa-stol/carma-platform)**  

  USDOT FHWA's Cooperative Driving Automation (CDA) platform built on ROS. Enables vehicle-to-infrastructure and vehicle-to-vehicle cooperation for enhanced safety and efficiency .



- **[AWSIM](https://github.com/tier4/AWSIM)**  

  TIER IV's open-source autonomous driving simulator built with Unity, designed as a reference environment for Autoware. Features ROS2-compatible communication, GPU-accelerated LiDAR, and pre-integrated demo simulations .



- **[Self-Driving Vehicle (Habrador)](https://github.com/Habrador/Self-driving-vehicle)**  

  Unity-based simulation of path planning for self-driving vehicles implementing Hybrid A* pathfinding algorithm .



- **[CARLA Autonomous Driving Leaderboard](https://github.com/carla-simulator/leaderboard)**  

  Official CARLA leaderboard for benchmarking autonomous driving agents with 182+ stars. Provides standardized evaluation protocols for perception, planning, and control .



### Additional Strong Open-Source Options



- **SUMO (Simulation of Urban MObility)** — Eclipse SUMO is an open-source, highly portable, microscopic traffic simulation package designed for large networks, often integrated with CARLA .

- **Scenic** — A compiler and scenario generator for the Scenic scenario description language, for probabilistic scenario specification .

- **RobotecGPULidar** — GPU-accelerated LiDAR simulation for CARLA, enabling real-time ray tracing for sensor modeling .

- **carla-autoware** — Integration of Autoware AV software with CARLA simulator with 252+ stars .

- **carla-map-editor** — Standalone GUI application to enhance RoadRunner maps with traffic lights and traffic signs information .

- **DReyeVR** — VR driving and eye tracking simulator based on CARLA for driving interaction research .

- **TeleCARLA** — Open source extension of CARLA for teleoperated driving research using off-the-shelf components .



**Frameworks for building custom AV development solutions**: Combine **CARLA** for high-fidelity simulation, **Autoware** or **Apollo** for production-grade autonomous driving stacks, **AWSIM** for Autoware-native simulation, and **Scenario Runner** for reproducible testing. For cooperative driving research, **CARMA Platform** provides V2X capabilities. For pure research, **Pylot** offers clean modular abstractions.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Autonomous vehicle development tools must comply with applicable safety standards (ISO 26262, SOTIF) and regional regulations.

- Self-hosted open-source solutions require proper infrastructure, sensor calibration, and validation before on-road testing.



---



**Made for automotive engineers, AV researchers, robotics developers, and mobility innovators.**  

Let's make autonomous vehicle development more open, transparent, and collaborative.
