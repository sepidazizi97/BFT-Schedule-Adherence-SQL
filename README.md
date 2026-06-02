# BFT Schedule Adherence SQL Reports

This repository contains SQL queries developed for Ben Franklin Transit schedule adherence analysis.

## Reports

### 1. Stop-Level Schedule Adherence
Calculates average and maximum arrival/departure delta by:
- Month
- Day of Week
- Route Short Name
- Direction
- Trip
- Stop Code
- Stop Name
- Scheduled Arrival Time
- Scheduled Departure Time

### 2. Trip-Level Schedule Adherence
Calculates average and maximum arrival/departure delta by:
- Month
- Day of Week
- Route Short Name
- Direction
- Trip

## Metrics

- Average Arrive Delta Seconds
- Maximum Arrive Delta Seconds
- Average Depart Delta Seconds
- Maximum Depart Delta Seconds
- Observation Count

The deltas are calculated directly as:

Actual Time - Scheduled Time
