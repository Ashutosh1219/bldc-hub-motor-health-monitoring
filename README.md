# Multi-Domain Health Monitoring of Hub-Mounted BLDC Motor Using Physics-Based Fault Modeling

## Overview

This project presents a simulation-driven framework for health monitoring of hub-mounted Brushless DC (BLDC) motors through multi-domain fault modeling and structured feature extraction.

A physics-based BLDC motor model is developed in MATLAB/Simulink, and electrical, mechanical, and sensor faults are systematically injected to analyze fault signature evolution. The objective is to enhance early-stage fault detectability and improve reliability assessment in electric mobility systems.

---

## Research Motivation

Hub-mounted BLDC motors are critical components in electric mobility platforms. Undetected degradation in electrical windings, mechanical structures, or sensing mechanisms can result in:

- Efficiency loss
- Performance degradation
- System instability
- Reduced operational reliability

While existing literature primarily focuses on isolated fault categories, limited work investigates integrated multi-domain fault modeling in hub motor configurations.

This work addresses that gap through a structured reliability-oriented evaluation approach.

---

## Key Contributions

- Development of a physics-based multi-domain BLDC fault model
- Integrated electrical, mechanical, and sensor fault injection framework
- Comparative evaluation of statistical and transient-based features
- Sensitivity assessment for early-stage fault detectability
- Reliability-focused system-level analysis

---

## System Architecture

The modeled system consists of:

- Three-phase BLDC motor dynamic model
- Electronic commutation logic
- Hall sensor feedback system
- Closed-loop speed control loop
- Mechanical load representation (hub-motor configuration)

Faults are injected independently and in controlled combinations to observe system response.

---

## Fault Modeling Framework

### 1. Electrical Faults
- Phase imbalance
- Partial winding degradation
- Supply irregularities

### 2. Mechanical Faults
- Load disturbances
- Rotor imbalance
- Increased frictional effects

### 3. Sensor Faults
- Hall sensor offset
- Signal dropout
- Timing mismatch

Each fault is modeled using parameter perturbation techniques within the physics-based framework.

---

## Methodology

1. Develop detailed BLDC motor model using motor dynamic equations.
2. Implement closed-loop speed control architecture.
3. Inject structured faults in electrical, mechanical, and sensing domains.
4. Capture system response signals.
5. Perform feature extraction on time-domain and transient responses.
6. Evaluate feature sensitivity across fault severities.

---

## Feature Extraction Strategy

The diagnostic framework includes:

### Statistical Features
- Mean
- RMS
- Variance
- Skewness
- Kurtosis

### Transient Metrics
- Rise time
- Settling time
- Overshoot magnitude

### Signal Transition Characteristics
- Zero-crossing deviations
- Switching irregularities

Feature sensitivity is analyzed to determine separability between fault conditions.

---

## Reliability-Oriented Analysis

The framework evaluates:

- Early-stage fault detectability
- Fault severity correlation
- Feature robustness under varying operating conditions
- Diagnostic separability across fault classes

The approach emphasizes reliability enhancement rather than control optimization.

---

## Tools & Environment

- MATLAB
- Simulink
- Signal processing techniques
- Statistical feature analysis

---

## Current Status

- ✔ Physics-based BLDC model implemented
- ✔ Multi-domain fault injection completed
- ✔ Feature extraction pipeline established
- ✔ Comparative analysis of fault signatures completed
- ✔ Journal ready manuscript is done and applied for publication

---

## Engineering Relevance

This work is relevant to:

- Electric mobility reliability engineering
- Condition monitoring systems
- Simulation-driven validation
- Predictive maintenance frameworks
- Embedded diagnostic algorithm development

The methodology can be extended to hardware validation environments and real-time diagnostic systems.

---

## Publication Status

Journal manuscript under preparation.  
This repository contains technical documentation and modeling overview only.  
The formatted manuscript will be referenced upon official publication.

---

## Disclaimer

This repository presents a structured overview of the modeling and diagnostic framework.  
Publication-formatted manuscripts and copyrighted material are not included to comply with journal policies.
