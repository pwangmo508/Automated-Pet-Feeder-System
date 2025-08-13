# Automated Pet Feeder System  
*University of Canberra – Introduction to Information Technology (4478/8936)*



## Overview  
This project proposes a low-cost automated feeder for cats and dogs that dispenses food at scheduled times, monitors food consumption, and alerts staff if feeding issues occur. The design is based on clear flowchart logic, word-code implementation, and structured testing.

---

## Key Features  
- Scheduled feeding (up to 10 times per day)  
- Manual feeding option via user interface  
- Food level monitoring with alerts for low or empty bins  
- Bowl weight detection to confirm eating  
- LED status indicators (Green = normal, Yellow = feeding, Red = alert)  
- Alert notifications to staff for critical issues  

---

## Inputs  
- Current time (RTC/system clock)  
- Feeding schedule  
- Food level sensor  
- Bowl weight sensor  
- Manual feed command  

---

## Outputs  
- Motor control signal for dispenser  
- Alert notifications to staff  
- Status display via LED or UI  

---

## Limitations  
- Stores only last 100 events  
- Alerts are queued if network is down until connectivity returns  

---

## Testing Summary  
Test cases included for:  
- Pet does not eat  
- Food container empty  
- Normal operation  
- Manual feed request  

Each case was compared against expected outcomes and refined to improve reliability and usability.

---
