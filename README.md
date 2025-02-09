# Airwise

**AirWise: Real-Time Vehicle Emissions Monitoring**

An innovative project aimed at providing real-time monitoring of vehicle emissions. Our objective is to offer a user-friendly solution for tracking harmful gas levels emitted by vehicles, ensuring they remain within safe and acceptable limits to protect both the environment and public health.


**Project Overview**
AirWise is designed to tackle the growing concern of vehicle emissions and their detrimental effects. By leveraging advanced sensors and real-time data processing, we can monitor and visualize the emission levels of Carbon Monoxide (CO), Nitrogen Oxides (NOx), and Hydrocarbons (HC). The system utilizes an ESP32 microcontroller to collect data from gas sensors, which is then transmitted to Firebase. The collected data is displayed on a web-based dashboard with interactive gauges, providing an intuitive and informative user experience.

Features
Real-Time Monitoring: Continuously tracks vehicle emissions and updates the dashboard in real-time.

Interactive Gauges: Visual representation of emission levels using dynamic gauges with color-coded indicators.

Threshold-Based Alerts: Emission levels are categorized into three levels based on predefined thresholds:

Good: Emissions are within safe and acceptable limits.

Warning: Emissions are elevated and vehicle needs to be serviced.

Danger: Emissions are high and require immediate attention.

**** exceeding danger will be marked to authorities and their pollution certificate needs to be reviewed****

Firebase Integration: Utilizes Firebase Realtime Database for data storage and retrieval.

User-Friendly Dashboard: Web-based interface for easy access and monitoring.

**Components**
ESP32 Microcontroller: Central unit for reading sensor data and communicating with Firebase.

MQ3, MQ7, MQ135 Sensors: Gas sensors for detecting CO, NOx, and HC levels respectively.

Firebase Realtime Database: Cloud-based database for storing sensor data.

Web Dashboard: HTML, CSS, and JavaScript-based interface for data visualization.



**Usefulness and Impact
Environmental Protection**
One of the primary benefits of AirWise is its contribution to environmental protection. Vehicle emissions are a significant source of air pollution, contributing to global warming and climate change. By monitoring and controlling these emissions, AirWise helps reduce the environmental impact of vehicles, promoting cleaner air and a healthier planet.

**Public Health**
Emissions from vehicles contain harmful pollutants that can have serious health effects, including respiratory diseases, heart conditions, and even cancer. By providing real-time data on vehicle emissions, AirWise enables individuals and authorities to take proactive measures to reduce exposure to these pollutants, thereby protecting public health.

**Regulatory Compliance**
AirWise can assist vehicle owners and fleet managers in ensuring compliance with environmental regulations. By continuously monitoring emission levels and providing alerts when they exceed acceptable limits, AirWise helps avoid potential fines and penalties associated with non-compliance.

**Education and Awareness**
AirWise serves as an educational tool by raising awareness about the importance of monitoring vehicle emissions. It encourages individuals to be more conscious of their environmental impact and to adopt practices that reduce emissions, such as regular vehicle maintenance and the use of cleaner fuels.

**Innovation and Research**
AirWise provides a platform for further research and innovation in the field of environmental monitoring. The data collected by the system can be used to study trends in vehicle emissions, identify areas for improvement, and develop new technologies to reduce emissions.

**Future Enhancements**
Mobile App: Develop a mobile application for on-the-go monitoring.

Advanced Analytics: **Integrate machine learning algorithms to predict future emission trends and give weekly reports of the vehicle.**

Expanded Sensor Array: Add more sensors for comprehensive environmental monitoring.

