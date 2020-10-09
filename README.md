# Pro-documentation
Mini - Technical Specification Report for the project where detailed explanation is given is included here

![image](https://user-images.githubusercontent.com/57037068/86809032-75a62a80-c08c-11ea-92af-31d78f28a1f8.png)

## Solar-powered Smart Water Cleanliness Analyzer

Proposed system: Real-time Solar energy powered IoT Smart Drinking Water Cleanliness Analyzer with Mobile and Web application

A complex system of sensors is designed to acquire data from those sensors which is to be processed to be sent to the cloud where it is saved for further analysis. Data is now in the stage of the main Data Analysis and Machine Learning part. After the process is done to judge the cleanliness of the water, the result is sent to be displayed in terms of all 3 parts of the products; LCD on hardware, display of both web application, and mobile device. 

### Hardware System:
It is a big and complex network of boards and sensors creating a tool for water quality management. Far sited Arduino centered node is located in different locations of the water source for getting a more precise value about the whole. While on the coast, the Raspberry pi centered server operates for collecting all this data coming from different sources. Collected bank of data is sent to cloud for later analysis and display on mobile and web applications.

### Mobile App:
Speech recognition powered mobile app enables the user to let all the system run by a single voice command where system automatically shots the picture of the water, sends it to the cloud for further analysis besides sending all data coming from sensors, and eventually, the result about the classification model is displayed on the screen of mobile device with the related accuracy about the water whether it is drinkable or not.

### Web Application:
Map oriented web application lets the user be able to access to the data acquired from sensors visually where all the BI tools are applied. The proposed main page illustrates a world map to show the clean and dirty water sources, while graphs and charts visualize the real-time change in the values of conductivity, pH, etc.


#### Essential features to be used for deciding upon the cleanliness of water:

Turbidity, Conductivity(saltiness), Water level, pH (acid), water level, temperature.

#### Essential boards and hardware parts to be used:

Sensors: turbidity sensor, conductivity sensor, water level sensor, pH sensor(acid), temperature sensor, camera
Boards: Arduino kit, Raspberry Pi (+ SD card)
Radio modules: LoRa (LoRaWAN) Module, Xbee 


Imaginery and realistic requirements for now:

Tural A – Connect Arduino with raspberry & connect raspberry to cloud data & Android 

Tural S – research about making 4 main sensors & connecting with Arduino & write to csv

Elvin -  ML collect data and analyze & train & Android App Design

Javid -  Web Application Back-Front & API 
	Map and Chart, Graphs in Website

Eshan -  ML collect data and analyze & train


Common physico-chemical water quality parameters
i.	pH - This is a measure of the degree of acidity or alkalinity of a solution. A pH of 7 is neutral, while that below and above neutral is considered acidic and alkaline, respectively. For distribution systems, a pH that is between 6.0 and 9.0 is normally recommended.
ii.	Electrical conductivity - This is a measure of a solution’s capability to pass electrical current. Conductivity is used as an indication of the concentration conductive ions that normally come from dissolved salts and other inorganic material. The more the dissolved salts present, the higher the conductivity. Drinking water should have a conductivity that ranges between 0 and 2500 μS/cm.
iii.	Oxidation reduction potential (ORP) - ORP measures how strongly electrons are transferred between component species in a solution. This indicates the ability of water to rid itself of contaminants. Healthy water normally has very high ORP readings.
iv.	Turbidity - This indicates the concentration of suspended and colloidal material in water and it is measured in nephelometric turbidity units (NTU). Drinking water should have turbidity that is less than 1 NTU.
v.	Redox
vi.	Dissolved oxygen
ALl - temperature, pH, conductivity, depth, turbidity, phosphate and dissolved oxygen

Water Hygiene - Awareness and Education
With water constituting over 60% of the human body, it is of utmost importance to ensure that the water we use is clean, safe, and pure. Community efforts, thus, play a vital role in not just creating awareness around water purity but also taking appropriate steps to ensure safety.
Leverage technology to bring communities closer, build support groups, and increase community awareness about water safety, its importance, and the steps required to ensure it.

Around 5 million people die due to waterborne diseases around the world (Water Resource Information System of India, 2017).

According to WHO report 21% of the total diseases are caused by unsafe water and 77 Million people are suffering due to not having access to safe drinking water. This data clearly raises an alarm on this issue.

Water borne disease continues to occur and is one of the key concerns in developing countries. • In India 3.4 million people, mostly children, die annually from water-related diseases. • About 2.2 million people die from diarrhoea. • 90% of these deaths are among children, mostly in developing countries. • More than 1 billion people draw their water from unsafe sources. • The UN has included “Safe Drinking Water” for everyone in Sustainability Development Goals 2030

Water pollution leads to roughly 9 million premature deaths a year and 16% of all deaths worldwide.


