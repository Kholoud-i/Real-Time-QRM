# Real-Time-QRM
## Overview
This project implements a quantitative risk management system in Python designed to support pharmacovigilance operations.
It continuously evaluates patient safety signals by estimating, scoring, and prioritizing potential adverse drug risks using statistical and probabilistic models.

The system supports:

**Early detection** of safety risks  
**Quantitative prioritization** of adverse events  
**Data-driven regulatory decision-making**  
**Scalable integration** into healthcare pipelines

## Key Concepts
**Risk Scoring**:	Assigns numeric risk levels to adverse events  
**Signal Detection**:	Identifies abnormal event patterns  
**Uncertainty Modeling**:	Quantifies confidence and variability  
**Temporal Analysis**:	Tracks risk trends over time  
**Decision Support**:	Converts metrics into actionable outputs

## Methods

The system applies:  
**Bayesian updating** for dynamic risk estimation  
**Poisson & Binomial models** for adverse event frequency  
**Z-score anomaly detection**  flags whether safety signals is abnormal compared to baseline
**Exponential weighting** for recency effects  
**Composite risk functions** combining severity, frequency, and uncertainty
