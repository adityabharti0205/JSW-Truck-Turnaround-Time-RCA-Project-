# Truck Turnaround Time Optimization | Root Cause Analysis

## Project Overview

This project analyzes 1,500 synthetic truck operations records from a simulated cement manufacturing logistics environment to identify factors associated with excessive truck turnaround time (TAT).

**Business Objective:** Investigate why trucks exceed the four-hour turnaround target and evaluate potential operational improvements.

## Tools & Technologies

- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Jupyter Notebook
- Excel

## Key Findings

- **60.47%** of truck trips exceeded the four-hour target.
- Pre-loading waiting accounted for **47.40%** of the average stage-time gap between delayed and on-time trucks.
- Unscheduled trucks had the highest average turnaround time at **5.32 hours**.
- Morning unscheduled arrivals had a **93.75% delay rate**.
- Transporters 01 and 02 had the highest average TAT, approximately **4.98 hours**.

## Business Impact Simulation

A hypothetical 20% reduction in pre-loading waiting time produced the following results:

| Metric | Current | Simulated |
|---|---:|---:|
| Average TAT | 4.64 hrs | 4.27 hrs |
| Delay Rate | 60.47% | 49.47% |

**Potential operational benefit:**
- 558.32 truck-hours saved across 1,500 trips
- Approximately 22.33 minutes saved per truck
- Estimated financial value of ₹2,79,158, assuming ₹500 per truck-hour

These estimates represent a hypothetical scenario, not verified operational or financial savings.

## Recommendations

1. Improve truck appointment scheduling and adherence.
2. Investigate pre-loading queue congestion.
3. Review loading capacity during morning and evening shifts.
4. Investigate transporter-specific turnaround patterns.
5. Monitor loading-bay utilization and operational delays.

## Dataset

The dataset contains 1,500 synthetic truck trips with operational timestamps, loading durations, appointment statuses, transporters, shifts, and turnaround metrics.

**Disclaimer:** This is a portfolio project using synthetic data. Findings and savings estimates should not be interpreted as actual JSW Cement operational results as they dataset is inspired by the JSW's operational dataset.
