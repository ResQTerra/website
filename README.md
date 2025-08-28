# Cerberus - Drone-Based Landslide Search and Rescue System

## **Project Overview**
This project aims to develop a drone-based system equipped with LiDAR, Ground Penetrating Radar (GPR), and other sensors to assist in locating individuals trapped in landslides. The system processes data from the sensors, performs real-time analysis, and provides actionable insights for rescue operations.

The system is modular, comprising a drone, onboard Raspberry Pi, an Arduino controller, and a laptop for advanced data processing.

---

## High-Level Architecture Diagram

```mermaid
graph TD
    subgraph Cerberus_v0.3_Architecture["Cerberus v0.3 Architecture"]
        A["Application Layer (Drone Swarm Control, Mission Planning)"]
        B["Communication Manager & Decision Engine"]
        C["BitChat Mesh Communication Module"]
        D["5G Communication Module"]
        E["Satellite Communication Module"]
        F["Emergency Radio Beacon Module"]
        G["Enhanced Security & Threat Detection Framework"]
        H["Emergency Failsafe & Autonomous Recovery Systems"]
        I["Performance Optimization Modules"]
        J["Hardware Abstraction Layer (5G Modem, Satellite Modem, Radios)"]
    end

    A --> B
    B --> C
    B --> D
    B --> E
    B --> F
    C --> G
    D --> G
    E --> G
    F --> G
    B --> H
    B --> I
    C --> J
    D --> J
    E --> J
    F --> J

    style B fill:#ADD8E6,stroke:#333,stroke-width:2px,color:#000
    style C fill:#90EE90,stroke:#333,stroke-width:2px,color:#000
    style D fill:#FFD700,stroke:#333,stroke-width:2px,color:#000
    style E fill:#FFD700,stroke:#333,stroke-width:2px,color:#000
    style F fill:#FFD700,stroke:#333,stroke-width:2px,color:#000
    style G fill:#FFB6C1,stroke:#333,stroke-width:2px,color:#000
    style H fill:#FFB6C1,stroke:#333,stroke-width:2px,color:#000
    style I fill:#FFB6C1,stroke:#333,stroke-width:2px,color:#000
    style J fill:#D3D3D3,stroke:#333,stroke-width:2px,color:#000
```
