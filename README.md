# NebulaMind: A StarCraft II Bot Powered by AI

## Overview

**NebulaMind** is an AI-powered StarCraft II bot developed using the **Python-SC2** library. It demonstrates the potential of **Artificial Intelligence** (AI) in real-time strategy games, focusing on the **Rush strategy** to defeat opponents. The bot leverages **macro-management** techniques for efficient resource allocation and rapid army production.

### Key Features:
1. **Rush Strategy**: Builds a small but powerful army quickly to attack the opponent before their defenses are fully established.
2. **Resource Management**: Efficient gathering of **minerals** and **vespene gas** using optimized worker tasking.
3. **Map Expansion**: Proactive expansion to gather resources and gain a strategic edge.
4. **Offensive Force Management**:
   - Deploys **Gateways**, **Cybernetics Core**, and **Stargates** to build offensive units.
   - Focuses on **Stalker** (ground units) and **Void Ray** (air units) compositions for early and effective attacks.

---

# How to run the code

1. How To Get Started
- Install Starcraft 2
-- https://us.battle.net/account/download/

- Install pyhton-sc2
-- pip install sc2

- Download Maps
-- https://github.com/Blizzard/s2client-proto#map-packs
-- Extract zip into the StarCraftII Directroy under Maps directory
-- May need to create the Map directory if the game has not been played

2. Common Issues
- Protobuf version
-- pip install protobuf==3.2

--- 
## Methodology

NebulaMind follows a three-phase approach:
1. **Resource Gathering**:
   - Distributes worker units (Probes) efficiently.
   - Builds Pylons and Assimilators to optimize Psi and vespene gas production.
2. **Map Expansion**:
   - Deploys additional Nexuses to secure resources based on gameplay progress.
3. **Building and Managing Offensive Forces**:
   - Constructs buildings for unit production.
   - Produces **Stalkers** and **Void Rays** based on resource availability and game progression.
   - Executes intelligent attack strategies to overwhelm opponents.

---

## Evaluation

The bot was rigorously tested against **StarCraft II AI opponents** at varying difficulty levels (Medium and Harder) and maps:
- **AbyssalReefLE** and **BelShirVestigeLE** maps.
- Performance was evaluated against the **Terran**, **Zerg**, and **Protoss** races.

### Key Results:
- Achieved up to **60% win rate** against "Harder" AI opponents.
- Performed better on larger maps due to strategic advantages.
- Faced challenges against **Rush** and **Timing** strategies due to resource perks in AI opponents.

---

## Future Work

To further enhance NebulaMind:
- Implement **Reinforcement Learning** for flexible and adaptive decision-making.
- Compete against higher AI levels, including **Insane Cheat** difficulty.
- Explore new strategies beyond Rush for more dynamic gameplay.

---

## Technologies Used
- **Python-SC2** Library
- **StarCraft II AI** for testing
- AI decision-making for resource optimization and offensive force control.

---

## Contributors
- **Carlos Guzman** (University of Central Florida)  
- **Zaheen E Muktadi Syed** (University of Central Florida)

---

## References
- Ontañón et al., *A Survey of Real-Time Strategy Game AI Research*.
- Čertický et al., *StarCraft AI Competitions*.

---
