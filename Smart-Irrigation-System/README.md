Smart Irrigation Decision System

Project Overview

The Smart Irrigation Decision System is a rule-based expert system developed using Prolog.

It helps farmers decide whether irrigation is required based on crop type, soil moisture, temperature, humidity, and expected rainfall.

Objectives

- Analyse soil and weather conditions.
- Support different crops with different moisture requirements.
- Recommend suitable irrigation levels.
- Avoid unnecessary irrigation.
- Provide a reason for every recommendation.

Technology Used

- Programming Language: Prolog
- Tool: SWI-Prolog
- Editor: Visual Studio Code

Input Parameters

1. Crop Type
2. Soil Moisture
3. Temperature
4. Humidity
5. Expected Rainfall

Irrigation Recommendations

- High Irrigation
- Medium Irrigation
- Low Irrigation
- No Irrigation

How to Run

1. Install SWI-Prolog.

2. Open the project folder.

3. Start SWI-Prolog.

4. Load the program:
   
   "consult('smart_irrigation.pl')."

5. Run the system:
   
   "start."

6. Enter the requested inputs.

Sample Input

- Crop: Tomato
- Soil Moisture: 20
- Temperature: 38
- Humidity: 30
- Rainfall Expected: No

Expected Result

- Soil Condition: Dry
- Temperature: High
- Humidity: Low
- Recommendation: Irrigation Required
- Suggested Level: High

