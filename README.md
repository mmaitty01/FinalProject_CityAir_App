# Development of Mobile Application For Daily Air Quality Assessment In Bangkok ---App Part
City Air แอปพลิเคชันประเมินคุณภาพอากาศรายวันในกรุงเทพมหานคร โดยใช้แบบจำลอง LSTM ในการทำนาย PM2.5 ล่วงหน้า 7 วัน และใช้เทคโนโลยี GIS ในการแสดงผลเชิงแผนที่บน Application
<p align="center"><img src = "https://github.com/user-attachments/assets/b6b53864-b855-4bd4-af88-ad857b7846a2"></p>

<p align="center" >
  <a href="#Overview">Overview</a> •
  <a href="#Features">Features</a> •
  <a href="#Use-Case-Diagram">Use Case Diagram </a> •
  <a href="#Results">Results</a> •
  <a href="#Operation">Operation</a> •
  <a href="#getting-started">Getting Started</a> •
  <a href="#Screenshots">Screenshots</a> •
</p>


## Overview
Air is essential for all living beings, but PM2.5 pollution has become a major issue, especially in Bangkok, due to urban expansion, population growth, and changing weather conditions. This project aims to develop an app that provides air quality and forecast 7-Day PM2.5 in Bangkok, to help residents plan their travels and raise awareness about air pollution prevention.

## Features
1. Display air quality and PM2.5 levels in Bangkok using data from the Pollution Control Department, presented via ArcGIS software in an Android application.
2. Show daily PM2.5 levels for the user's current location and surrounding areas in Bangkok.
3. Provide detailed health information on how different air pollution levels impact public health.
4. Display PM2.5 trend forecasts for the next 7 days.
5. Allow users to report garbage burning sites or other pollution sources to be displayed on the application's map.

## Use Case Diagram 
<p align="center"><img width="600" src = "https://github.com/user-attachments/assets/776a74fe-adb5-46e3-93e9-c1a970523044"></p>


## Results
In the application part. We have developed a mobile application that connects to the postgresql database to show details of the pm2.5 forecast. The application will start when users selects "allow" or
"don't allow" location and displays it on the menu list. After selecting menu, users can view the details of the menu. The server-side consists of a PM2.5 Forecast database. the model that runs on the webserver
to predict PM2.5 and return predictions to the application of the client.

## Operation
- STEP 1 : **Select Data** (PM2.5, PM10, Wind speed, Pressure, Humidity,Temperature, and traffic )
- STEP 2 : **Manage Data** (Clean Data/Interpolation)
- STEP 3 : **Select Modes** (Compare and Select models GRU and LSTM)
- STEP 4 : **Create App** (Desige and Develop on Android studio)
- STEP 5 : **Connect server** (Database with Android studio and ArcGis Server with Android)
> [!NOTE]
> Steps 1-3 will be included in the content of the GitHub repository: <a href="https://github.com/mmaitty01/FinalProject_CityAir_Model">Model Part</a>

## Getting Started

To run this app on your local machine or Android device, follow these steps:
1. Clone this repository to your local machine using `git clone https://github.com/mmaitty01/FinalProject_CityAir_App.git`
2. Open the project in Android Studio or your preferred Android development environment.
3. Build and run the application on an Android emulator or a physical Android device.


## Screenshots
<p align="center"><img width="200" height = "350" src = "https://github.com/user-attachments/assets/6b32c00c-1ea6-4396-b361-b642e8505d4e">   <img width="200" height = "350" src = "https://github.com/user-attachments/assets/80b6495a-5e4d-4a7b-a236-f9ad3dc9f45e">   <img width="200" height = "350"  src = "https://github.com/user-attachments/assets/97674ef9-7f5b-4d80-ac11-20d8bb8af18f"> <img width="200" height = "350" src = "https://github.com/user-attachments/assets/92f1dc0a-5c52-476b-ad7c-6fb3ab5b0406"> </p>








