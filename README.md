# Vehicle Performance Analysis

## Assignment Description

### Parameters:
1. **RPM**: 0 to 5000, divided into buckets of 500.
2. **AC Motor Controller Current**: Proportional to Torque at a given RPM.
3. **Throttle Command**: 0 to 9, mapped to min to max speed requested.
4. **Motor Temperature**: Partly linked to current at the RPM, partly linked to ambient temperature.
5. **Battery Temperature**: Proportional to current and ambient temperature.

### Objectives:
- Build models to identify issues at Fleet level and Vehicle level.
- Identify average vehicle performance.
- Divide vehicles into 10 buckets of performance.
- Rank vehicles which are under-performing across different parameters.

### Machine Learning Goals:
1. Build models for fleet average and cluster vehicles into 5 groups of similar performance.
2. Classify any new vehicles into the identified performance categories.

### Data Analysis Focus:
1. Detect overload, normal load, and underload conditions.
2. Identify motors degrading faster and heating more in a shorter span.
3. Identify batteries heating faster in a shorter span.

## Note:
- The current notebook provides the approach and methodology for solving the assignment. Sample Random data and implementation code can be added into it.
