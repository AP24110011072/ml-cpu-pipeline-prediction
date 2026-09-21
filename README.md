# ml-cpu-pipeline-prediction
# ML-Based CPU Pipeline Prediction

## Project Overview

This project combines Computer Organization and Architecture (COA)
with Machine Learning to analyze and predict CPU pipeline performance.

The project focuses on a 5-stage CPU pipeline:

1. Instruction Fetch (IF)
2. Instruction Decode (ID)
3. Execute (EX)
4. Memory Access (MEM)
5. Write Back (WB)

The system analyzes instruction sequences, identifies pipeline
hazards and stalls, and uses Machine Learning to predict pipeline
performance.

## Problem Statement

CPU pipeline performance is affected by instruction dependencies,
hazards and stalls. Calculating pipeline performance for different
instruction sequences manually can become time-consuming.

Our project aims to use Machine Learning to learn the relationship
between instruction characteristics and pipeline performance.

## Project Workflow

Instruction Sequence
        ↓
CPU Pipeline Simulator
        ↓
Hazard & Dependency Analysis
        ↓
Dataset Generation
        ↓
ML Model Training
        ↓
Performance Prediction
        ↓
Actual vs Predicted Comparison

## Dataset

We are initially using a custom-generated dataset.

Each row represents an instruction sequence and contains features
related to pipeline behavior such as:

- Instruction count
- Data dependencies
- Data hazards
- Control hazards
- Structural hazards
- Stall cycles
- Total cycles
- CPI

The dataset is generated based on our pipeline simulation rather
than using a generic external ML dataset.

## Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook
- Git & GitHub

