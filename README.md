### Introduction

Welcome to the Strange-Land GitHub organization, an ecosystem built to advance the state of the art in Autonomous Vehicle and Human-Robot Interaction (HRI) studies. Based on the original StrangeLand simulator published by David Goedicke et al., the platform aims to provide a modular and extensible environment for multiuser shared virtual simulations.

#### Key Features
- **Modular Approach**: Components like Embodiments and Clients can be freely combined, catering to a range of simulation setups.
- **Configurability**: Customizable through a Configuration "Engine" that handles roles, experiment conditions, etc.
- **Scenario Preparation**: Ease of creating new scenarios via Unity Editor.
- **Data Recording**: Built-in mechanisms for both quantitative and qualitative data collection.

### Planned Repositories

The organization will host various repositories, each serving distinct functionalities. A proposed naming scheme is also provided.

#### Core Components
1. `core_Server`: Houses the Core Server Architecture.

#### Clients -  Contains all client-controlled objects like cameras, hands, and interactions
1. `cli_VR`: Specific to VR interfaces using OpenXR.
2. `cli_Display`: For display-based interactions.
3. `cli_ThreeSimulatorScreens`: Specific ``Host`` client.
4. `cli_ExperimentController`: Interface for the experimenter.
5. `cli_InstrumentCluster`: Vehicle-related displays.

#### Embodiments - Contains all server-side physically simulated elements
1. `emb_Driver`: Contains the vehicle simulation based on GENIVI.
2. `emb_AVPassenger`: AV simulation using the GENIVI vehicle dynamics with waypoints.
3. `emb_NPCs`: Example of a server-controlled Non-Playable Characters (NPCs).

#### Scenarios Management
1. `scen_StrangeTown`: An example town built with unity assets.(not Public
2. `scen_NPCsLoader`: Manages NPCs within the scene.
3. `scen_NPC_TrafficLights`: Manages NPCs within the scene.
#### Recording
1. `rec_ReRun`: For recording and playing back the scenarios inside Unity. (uses the UltimateReplay 2.0 Unity package)
2. `rec_CSV`: Houses data recording elements to CSV (Farlab_logger).
