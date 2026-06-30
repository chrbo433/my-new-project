# CaveRescueAI – AI-Assisted Cave Rescue System

Final project for the Building AI course

## Summary

CaveRescueAI is an AI-assisted decision support system designed to improve rescue operations in caves. By combining environmental sensor data, digital cave maps, and machine learning, the system helps rescue teams identify safer routes and estimate the probable location of trapped people.

---

## Background

Cave rescue operations are among the most challenging emergency situations because rescuers often work in dark, narrow, flooded, and complex underground environments. Every minute is critical, and poor visibility or limited information can delay rescue efforts.

My motivation for this project comes from the increasing use of artificial intelligence in emergency management and disaster response. AI has the potential to support rescue teams by analyzing multiple sources of information much faster than humans alone.

Problems addressed:

* Difficult navigation inside cave systems.
* Limited communication with trapped people.
* Slow decision-making during rescue operations.
* High risk for rescue personnel.
* Limited visibility and environmental hazards.

---

## How is it used?

The system would be used by cave rescue teams before and during rescue missions.

The process would be:

1. Collect environmental data from IoT sensors placed inside the cave.
2. Import cave maps and previous exploration data.
3. Analyze sensor measurements such as temperature, humidity, oxygen concentration, CO₂ levels, and water level.
4. Use AI models to estimate the safest rescue path and the most probable location of missing persons.
5. Display recommendations on a GIS-based map for rescuers.

Potential users include:

* Fire and Rescue Services
* Cave Rescue Organizations
* Civil Protection Agencies
* Emergency Management Authorities

Example system architecture:

```
Sensors → AI Model → Risk Assessment → GIS Map → Rescue Team
```

---

## Data sources and AI methods

Possible data sources:

* Cave maps from national speleological organizations
* Environmental IoT sensors
* Historical cave rescue reports
* Weather information
* Digital Elevation Models (DEM)
* Indoor positioning data (where available)

Possible AI methods:

* Classification (safe / unsafe routes)
* Pathfinding algorithms (A*)
* Decision Trees
* Random Forest
* Neural Networks
* Anomaly Detection
* Geographic Information Systems (GIS)

Example dataset:

| Feature | Description |
|----------|-------------|
| Temperature | Cave temperature (°C) |
| Humidity | Relative humidity (%) |
| Oxygen | Oxygen concentration (%) |
| CO₂ | Carbon dioxide level |
| Water level | Flooding risk |
| Distance | Distance from entrance |
| Passage width | Width of cave passage |

---

## Challenges

The system cannot replace professional rescue teams.

Limitations include:

* Lack of real-time data.
* GPS does not work underground.
* Sensor failures.
* Complex cave geometries.
* Ethical responsibility remains with human rescuers.

The AI should only provide recommendations rather than making autonomous decisions.

---

## What next?

Future improvements could include:

* Integration with drones and robotic explorers.
* Thermal cameras for victim detection.
* 3D cave mapping using LiDAR.
* Digital twins of cave systems.
* Real-time communication networks underground.
* Reinforcement learning for optimal rescue planning.

Additional expertise would be required in:

* Artificial Intelligence
* GIS
* Robotics
* Speleology
* Emergency Management
* IoT Systems

---

## Acknowledgments

* University of Helsinki – Building AI Course
* European Cave Rescue Association (ECRA)
* National Speleological Organizations
* OpenStreetMap
* Scientific publications on cave rescue and emergency management
