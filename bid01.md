# Project Bid for P2025-17  Robotic Mobile Fulfillment System Simulator

## <center>Team.20205.24


<center>Yiqi CHENG</center>
<center>Xuanchen QIAN</center>
<center>Yijun SUN</center>
<center>Xiaoyan GONG</center>
<center>Ding SHAO</center>


## Project Motivation and Team Suitability

Our team is motivated to participate in this simulation project, as most of our team members are either interested in how digital simulation can migrate to real-world scenarios or has some previous experience on robotics and digital-twin project. We consider that this project offers a decent opportunity to explore the knowledge of simulation, optimization algorithms, data management and so on. 

## Team Member Profile

- Ding Shao: Have solid experience in Python programming, was awarded the First Prize and Excellence Award in the Lanqiao Cup Python Creative Programming Competition.
- Xiaoyan Gong: Captain and Leader of the Algorithm Group of the FOSE Robotics Team AIM, experienced in using NVIDIA Isaac simulator to configure and validate robots' algorithms.
- Xuanchen Qian: Has taken part in a monocular depth estimation project before. Familiar with python and Java, could help build the backend of this system.
- Yijun Sun: Awarded third prize in the Dimension Cup National Mathematical Modeling Competition, capable for forming mathematical model for AMR control in the simulation environment.
- Yiqi Cheng: Has hands-on experience with Python and AI model implementation through participation in the FURP project. Demonstrates strong analytical thinking, adaptability, and an ability to apply algorithm strategies to practical applications.

## Initial Project Ideas

To build the Robotic Mobile Fulfillment System (RMFS) Simulator, our initial concept focuses on developing a modular, extensible simulation framework that integrates warehouse environment modeling, autonomous robot control, and visualization. The key ideas and early technical considerations include:

1. Simulation Environment (Isaac Lab Integration)

   - Utilize NVIDIA Isaac Lab Simulator as the foundation for 3D warehouse and robot modeling.

   - Implement customizable layouts (aisles, pods, workstations) using predefined assets and parametric configuration files.

   - Incorporate multiple AMRs operating simultaneously with basic kinematic and task behaviors.

2. AMR Dispatch and Control Layer

   - Develop a dispatch management module capable of assigning tasks, defining routes, and handling traffic control.

   - Implement a pluggable architecture that allows integration of different control algorithms, which may need to support multiple control paradigm for AMR.

   - Enable data logging of performance metrics.

3. Data and Configuration Management

   - Design a configuration system (YAML or JSON) to define warehouse layouts, robot parameters.

   - Store simulation logs and metrics for analysis.

4. Frontend Visualization and Interaction

   - Create a lightweight web-based dashboard to visualize warehouse layouts, and task progress in real time.

   - Provide user controls for spawning robots, setting tasks, and modifying warehouse parameters during runtime.

---

## Estimated Timeline and Deliverables Schedule

| **Estimated Duration** | **Main Objectives and Deliverables**  |
| ---- | -- |
| **Oct 13 – Oct 20**    | Learn the fundamentals of Isaac Lab Simulator; determine system requirements and overall architecture.           |
| **Oct 20 – Nov 1**     | Set up the development environment, establish version control (Git repository), and define workflow conventions. |
| **Nov 1 – Dec 1**      | Develop the integration backbone for the Isaac Lab API and implement basic simulation components.                |
| **Dec 1 – Dec 15**     | Implement backend interfaces to connect the simulator with frontend modules and management logic.                |
| **Dec 16 – Dec 31**    | Develop a user-friendly frontend interface for visualization, monitoring, and task configuration.                |
| **Jan 1 – Jan 31**     | Conduct backend system testing, ensuring stability and performance of core simulation modules.                   |
| **Feb 1 – Feb 15**     | Test frontend functionalities, ensuring smooth user interaction and data synchronization.                        |
| **Feb 15 – Mar 1**     | Integrate and validate system components; refine documentation and improve usability.                            |
| **Mar 1 – Mar 25**     | Final evaluation and presentation; prepare final project report and future improvement recommendations.          |

By following this development roadmap, the project aims to deliver:

- A modular AMR simulation platform leveraging Isaac Lab Simulator.
- Support for customizable warehouse environments and task modeling.
- Integration with existing AMR control strategies.
- A responsive frontend interface for visualization and system management.
- Documentation and test results validating system stability and scalability.

Ultimately, this project will provide a flexible and extensible simulation framework for robotic warehouse automation.


## Key Milestones and Demonstrable Deliverables

| **Milestone**                                 | **Expected Date** | **Deliverable Description**                                                                    |
| --------------------------------------------- | ----------------- | ---------------------------------------------------------------------------------------------- |
| **Project Setup and Architecture Definition** | Oct 20            | Project repository initialized; architecture and requirement documentation completed.          |
| **Isaac Lab Integration Prototype**           | Dec 1             | Core simulation modules operational within Isaac Lab; basic AMR behavior verified.             |
| **Interim Report Submission**                 | **Dec 4**         | Interim report submitted, summarizing background, design, and development progress.            |
| **Backend–Frontend Integration**              | Dec 31            | Established communication between simulation backend and control frontend. <br> (It is expected that we could provide a early-access version at this moment)|
| **Usable Frontend Interface**                 | Jan 31            | GUI/visualization panel implemented for task configuration and monitoring.                     |
| **System Testing Phase**                      | Feb 15            | Backend and frontend modules fully tested; performance and stability validated.                |
| **Final Submission and Demonstration**        | Mar 25            | Fully functional AMR simulation system demonstrated; final report and documentation submitted. |
