 # Parametric Pedestrian Bridge

This repository contains the project files and documentation for the "Parametric Pedestrian Bridge," a project developed for the Advanced Building Information Modelling course during the Summer-Term 2025 at Bauhaus-Universität Weimar, Faculty of Civil and Environmental Engineering. The primary goal of this project was to design a bridge with modular segments that can dynamically adapt to user inputs, utilizing parametric families and visual programming to reduce modeling time. 

## Team Members
* Kuntal Pawan Dive (Digital Engineering)
* Abhishek Dilip Patil (Digital Engineering)
* Swaraj Sudhakar Sonawane (Digital Engineering)

## Software & Technologies
* **Autodesk Revit:** Base BIM modeling software used to create standard and custom parametric families.
* **Dynamo:** Visual programming extension for Revit used to automate the bridge placement.
* **DesiteMD:** Interfacing software used to create a 4D simulation of the construction schedule.
* **IFC (Industry Foundation Classes):** The open file format used to export the model from Revit for 4D simulation.
* **BPMN:** Process mapping methodology used to outline team workflows.

## Key Project Features

### 1. Revit Parametric Families
* The team utilized a Generic model Adaptive family to create the core bridge element, which consists of the deck and the pillar.
* Adaptive points were used so that the model geometry responds to the overall spline path, allowing the bridge to incorporate a curve.
* Parametric dimensions include the bridge element's width and thickness, as well as the pillar's depth.
* Custom standalone families were also modeled for the bridge's railings and streetlamps.

### 2. Dynamo Automation Script
* A custom Dynamo script automates the application of the bridge elements along a designated spline.
* Users simply select the spline path and input the desired number of elements to populate the bridge.
* The script automatically calculates and adjusts the height of the pillars from level 0 to the specific elevation of the bridge deck at each point, allowing the bridge to accommodate ramps and elevation changes.

### 3. 4D Construction Simulation
* The finalized Revit model was successfully exported into IFC format and imported into DesiteMD.
* Custom selection sets were built in DesiteMD to logically group the model components.
* A time schedule was created in the "Activities" tab and linked to the selection sets to generate a 4D animation demonstrating the sequential construction of the bridge.

## Documentation
For full project details, workflow diagrams, and methodology, please reference the official project report: AdvacedBIM_Group_22_ProjectReport.pdf.
