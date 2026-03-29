# Student Performance Predictor

## Problem Statement

The goal of this project is to build a **Student Performance Prediction System** using pure Python (without external ML libraries). The system estimates a student's final marks based on key academic and lifestyle factors.

## Objectives

- Generate synthetic student data
- Train prediction models
- Evaluate model performance
- Make predictions for new student inputs
- Save and load trained models

## Input Features

Each student is represented using the following parameters:

1. **Study Hours** (0–12 hours)
2. **Attendance Percentage** (40–100%)
3. **Sleep Hours** (4–10 hours)
4. **Previous Marks** (0–100)

## Output

- **Predicted Final Marks** (0–100)

## Models Implemented

### 1. Rule-Based Predictor
- Uses a fixed weighted formula:
  
