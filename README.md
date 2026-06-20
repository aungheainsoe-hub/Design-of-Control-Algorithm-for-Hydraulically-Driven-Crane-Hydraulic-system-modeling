# Control Algorithm for a Hydraulically Driven Crane

Design and high-fidelity simulation of a hydraulically actuated crane, built to
develop and test a motion control algorithm. Modelled in SolidWorks and simulated
in MATLAB Simulink with Simscape Multibody and Simscape Fluids.

## Overview
This project builds an end-to-end model of a hydraulic crane — from the mechanical
structure to the hydraulic power system — so that control strategies can be designed
and tested in simulation before any hardware is involved. The result is a coupled
hydraulic-mechanical model that captures realistic dynamics, ready for control
algorithm development.

## Tools & methods
- SolidWorks (crane assembly, joints, mass properties, constraints)
- MATLAB Simulink + Simscape Multibody (mechanical dynamics)
- Simscape Fluids (hydraulic actuator, valve, and pump modelling)
- Custom `.ssc` component files for the actuator and directional valve, including
  fluid compressibility and hose flexibility

## The system
- **Mechanical:** full crane assembly — pillar, boom, and cylinder-piston actuator
- **Hydraulic:** Parker PV016 pump, directional control valve, hoses, and reservoir
- CAD imported into Simscape Multibody, then coupled to the hydraulic model so the
  fluid system actually drives the mechanical motion

## What was done
- Designed the complete crane assembly in SolidWorks and defined the joints,
  mass properties, and constraints
- Wrote custom Simscape (`.ssc`) models for the actuator and directional valve,
  capturing fluid compressibility and hose flexibility
- Integrated the pump, hoses, and reservoir and connected them to the mechanical model
- Set up the model inputs and outputs as the platform for control algorithm development

## Results
- Validated CAD assembly and a verified, fully coupled hydraulic-mechanical model
- High-fidelity simulation ready for testing control strategies
- Demonstrates end-to-end capability: design, model, simulate, and analyse a complete
  electromechanical-hydraulic system


## Repository contents
- SolidWorks crane assembly and parts *(large files available on request / [link])*
- Simulink / Simscape model files
- Custom `.ssc` component files (actuator, directional valve)
- Project report (PDF)




*Project completed [year], [LUT coursework / self-directed].*
