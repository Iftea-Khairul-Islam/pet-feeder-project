# pet-feeder-project

## Project Overview
This project aims to develop a cost-effective automated pet feeder for animal shelters. The system dispenses food at scheduled times, monitors consumption using weight sensors, and sends alerts if food is uneaten or the supply is low. It ensures consistent feeding while minimizing human intervention.

## Features
- Scheduled feeding via real-time clock
- Servo-controlled food dispensing
- Food-level and bowl-weight monitoring
- Alerts via LEDs, buzzers, or notifications
- Manual feed request option
- Modular and well-documented code

## System Components
- **Inputs:** Feeding times, food-level sensor (binary), bowl weight sensor
- **Outputs:** Servo motor, LED/Buzzer alerts, LCD display
- **Hardware:** Arduino for basic control; Raspberry Pi for advanced features (camera, email alerts)

## Project Structure
- `Step1_Analysis` – System sketches and overview
- `Step2_Datatable` – Inputs, outputs, sample values, and constraints
- `Step3_Flowchart` – Flowchart of the algorithm
- `Step4_WordCode` – Step-by-step operational algorithm
- `Step5_Testing_Refinement` – Sample test cases, discussion, and refinements

## Operational Logic
1. Initialize system (clock, servo, sensors)  
2. Check feeding schedule or manual feed request  
3. Check food availability  
4. Dispense food and record bowl weight  
5. Wait and monitor consumption  
6. Check bowl weight change and send alerts if necessary  
7. Return to waiting state

## Test Cases & Results
- **Scheduled Feeding, Pet Eats:** Pass  
- **Scheduled Feeding, Pet Does Not Eat:** Pass  
- **Servo Malfunction:** Fail (requires refinement)  
- **Manual Feeding Request:** Pass  
- **Food Bin Empty:** Pass  

## Suggested Refinements
- Dynamic feeding thresholds for small pets  
- Multiple weight checks over time  
- Camera or motion sensor integration  
- Cloud-based logging and notifications  
- Battery backup for power outages  
- Adaptive feeding schedules using ML  

## AI Assistance
Microsoft Copilot helped refine step-by-step logic, suggested improvements for error handling, alerts, and hardware integration, and improved documentation and code modularity.

## Author
Iftea Khairul Islam Shanto
Student_Id- u3312802
Email- u3312802@uni.canberra.edu.au
