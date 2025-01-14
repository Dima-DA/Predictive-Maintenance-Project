# Predictive-Maintenance-Project
Analysis of machine performance data to optimize maintenance schedules.

# Predictive Maintenance Analysis

## Overview
This project focuses on analyzing machine performance data to develop predictive maintenance strategies, minimizing downtime and optimizing reliability.

## Files and Resources
- [Final Report (PDF)](https://drive.google.com/file/d/1kjvkzUoCOybdfmGCoGlV3LIn7HLNusd_/view?usp=drive_link)
- [Detailed Dataset (Google Sheets)](https://docs.google.com/spreadsheets/d/1J_ew1u7rp21EHTr7Ly7mhmAxWmGODX7V6k_Q-f684eU/edit?usp=drive_link)

## Key Insights
- Machines 3 and 4 are high-risk due to frequent anomalies.
- RPM was identified as the strongest contributor to vibration levels.

## How to Use
1. Download the final report to explore the project findings.
2. Access the dataset for detailed analysis and reproducibility.


## 🎯 Project Objectives
- Analyze sensor data from five machines to identify failure patterns
- Develop predictive maintenance strategies using historical sensor data
- Optimize maintenance schedules and reduce downtime
- Create actionable recommendations for machine reliability enhancement

## 📊 Dataset Features
- 15,000 rows of machine sensor data including:
  - Timestamp
  - Machine_ID
  - Sensor_ID
  - Temperature (°C)
  - Vibration (amplitude)
  - Pressure (PSI)
  - RPM (revolutions per minute)
  - Load (percentage)
  - Anomaly_Flag (0: normal, 1: anomaly)
  - Failure_Type

## 🛠️ Methodology
1. **Data Preprocessing**
   - Outlier detection using IQR method
   - Data standardization using Z-score
   - Time-based categorization
   - Completeness verification (no missing values)

2. **Statistical Analysis**
   - Mean and standard deviation calculations
   - Anomaly detection
   - Trend analysis
   - Time-period analysis (Early Morning, Morning, Afternoon)

3. **Predictive Modeling**
   - Linear regression model development
   - Formula: `Predicted Vibration = 0.4933126545 + (0.000003812543248 × RPM) + (0.00004684496958 × Load)`
   - Model accuracy: Mean absolute error of 0.07625032222

## 📈 Key Findings
1. **Machine Performance**
   - Machines 3 and 4 identified as high-risk
   - Frequent pressure and load anomalies detected
   - Overheating and leakage most common failure types
   - Normal operations maintained over 96% of the time

2. **Operational Insights**
   - Higher RPM values correlate with increased vibration
   - Maximum vibration (0.5738) at 20,000 RPM
   - Load fluctuations show moderate impact
   - Critical time periods identified for maintenance

## 🎯 Recommendations
1. Prioritize Machines 3 and 4 maintenance
2. Implement load balancing systems
3. Enhance temperature and vibration monitoring
4. Deploy predictive analytics
5. Strengthen anomaly detection systems

## 🔧 Tools Used
- Google Sheets for:
  - Data analysis and preprocessing
  - Statistical calculations
  - Linear regression modeling
  - Pivot table analysis
  - Data visualization
  - Scenario modeling

## 📊 Visualizations Created

1. Distribution of Anomaly Flags



![Anamoly Flag For Temp , Vibration,Pressure, RPM, Load](https://github.com/user-attachments/assets/7037b05a-bbcc-435c-a63b-a6f630beaf4a)




![Anomaly occurrence in Machines and Sensors (1)](https://github.com/user-attachments/assets/9d4f04b4-e1fc-45fa-aac7-ee8cbac170b2)

2. Machine Failure Types Analysis


![Machine Failure Type](https://github.com/user-attachments/assets/c4e4f0cd-e410-4e9a-87eb-7422927c949f)


3. Pressure Anomaly Trends


   ![Time of Pressure Anomaly](https://github.com/user-attachments/assets/057298be-35a0-4d50-844f-2a373d2637b2)

4. Temperature and Load Trends


  ![Machine Temperature and Load](https://github.com/user-attachments/assets/ac28c754-2c70-45f9-af45-0b63448a5945)

5. Time-based Pressure Anomalies



   ![Time of Pressure Anomaly](https://github.com/user-attachments/assets/4f06e974-2472-4e07-911e-7c0de51a08c9)

6. Predicted Machine Performance



Scenario 	RDM	Load	Predicted Vibration
Scenario A	2000	80	0.5046853386
Scenario B	1500	60	0.5018421675
Scenario C	1500	0.56	0.4990548919
Scenario D	500	100	0.4999034231
Scenario E	2500	40	0.5047178114
Scenario F	500	0.56	0.4952451593
Scenario G	5000	90	0.516591418
Scenario H	10000	20	0.5323749864
Scenario I	15000	25	0.5516719275
Scenario J	20000	30	0.5709688685
Scenario K	20000	90	0.5737795667




    ![image](https://github.com/user-attachments/assets/b0a7f4de-5bdc-4ce0-9fc6-b2d44996ddab)

    


## 💡 Skills Demonstrated
- Data Analysis & Preprocessing
- Statistical Analysis
- Predictive Modeling
- Data Visualization
- Technical Report Writing
- Problem-Solving
- Industrial Analytics
- Google Sheets Advanced Functions

## 📚 References
- Jupyter & Sylvester (2020)
- Li & Yang (2019)
- Kumar & Panneerselvam (2011)
- Ding & Zhang (2015)

## 🤝 Contact
- gloriaidemoh@gmail.com
- Open to Data Analysis opportunities!
- Proficient in spreadsheet analysis and data visualization
- Experienced in industrial data analysis

## 🔄 Future Improvements
1. Real-time monitoring integration
2. Advanced machine learning model implementation
3. Automated alert system development
4. Enhanced visualization dashboard creation



