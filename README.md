# Everything Missing But The Girl App 

An app designed to empower women and solo travelers to travel safely a user-focused, scalable app  

<div align="center">
  <img src="./assets/Logo.png" alt="App Logo" width="300" height="300">
</div>


---

## Key Features

- **Emergency Alarm**: A loud alarm to deter threats,that contacts emergnecy services and notifies your emergency contact of your exact location and that you require assistance 
- **Danger Zone Mapping**: Displays on your map the locations of high-crime areas and less busy areas with low WiFi areas such as countryside or industrial estates where there is a higher chance of possiblity of crime taking place. 
- **Transport Locations **: Locates buses and train stations in your vicinity.

---

## Tech Stack

- **Frontend**: React Native  
- **Backend**: Node.js, Express.js  
- **Database**: MongoDB Atlas  
- **APIs**:
  - Google Maps API (for Danger Zones and Safe Zones Finder)
  - Google Places API

---

## Setup Instructions

### **Install Dependencies**

- **For the frontend**:  
  - Run the following commands:
    ```bash
    cd frontend
    npm install
    ```

- **For the backend**:  
  - Run the following commands:
    ```bash
    cd backend
    npm install
    ```

---

### **Start the App**

- **Start the backend server**:  
  - Run the following commands:
    ```bash
    cd backend
    npm start
    ```

- **Start the frontend**:  
  - Run the following commands:
    ```bash
    cd frontend
    npm start
    ```

---

## Deployment

- **Backend**: Hosted on **Heroku/Render/AWS**.  
- **Frontend**: [Google Play Store link (if applicable)].

---

## Features Comparison

| Feature                        | Everything Missing But The Girl | Other Apps  |
|--------------------------------|---------------------------------|-------------|
| **Crime Hotspot Mapping**       | ✅                              | ❌           |
| **Safe Zone Finder**            | ✅                              | ❌           |
| **Emergency Alarm**             | ✅                              | ✅           |
| **Police Station Locator**      | ✅ (Upgrade)                    | ❌           |
| **Bus and Train Finder**        | ✅ (Upgrade)                    | ❌           |
| **Advice & Guidance for Solo Travelers** | ✅ (Upgrade)            | ❌           |
| **Go Home Navigation**          | ✅                              | ❌           |
| **Real-Time Alerts**            | ✅ (Upgrade)                    | ❌           |
| **Reduced WiFi Notification**   | ✅                              | ❌           |

---

### **Feature Descriptions**

1. **Crime Hotspot Mapping**  
   Alerts users to high-crime areas and helps avoid unsafe neighborhoods and areas.

2. **Safe Zone Finder**  
   Identifies well-lit and busy public areas like cafes, malls, or train stations for safe waiting spots in case the traveller requires time to find their location. 

3. **Emergency Alarm**  
   A loud, accessible alarm to deter threats and notify emergency contacts through sms immediately of a possible threat to person or property. 

4. **Police Station Locator** (Upgrade)  
   Shows nearby police stations for immediate help during emergencies.

5. **Bus and Train Finder** (Upgrade)  
   Helps users locate the nearest public transportation options in cases where travellers are compeletley lost. 

6. **Advice & Guidance for Solo Travelers** (Upgrade)  
   Provides tailored safety tips such as devices to have and general tips:
   - Packing essentials (e.g., power bank, mobile data).
   - Avoiding isolated areas like industrial estates or alleys.
   - Wearing practical footwear like trainers for ease of travel.

7. **Real-Time travel distruption to public transport services & Adverse weather conditons** (Upgrade)  
   Informs users of immediate travel delays on trains and buses.
  This also includes weather conditons preventing travellers from reaching their destinations and any road closures. 

8. **Reduced WiFi Notification**  
   Alerts users to areas with limited WiFi connectivity to enable better journey planning for the travller. 



---
## **Safety First Women Travelling Alone**

### **Risk Reduction**
Hotspot Crime Locator: Alerts users about high-crime areas, helping them avoid potentially unsafe neighborhoods.  
Emergency Alarm: A quick and accessible feature to deter threats and notify emergency contacts.  
Safe Zones Finder: Guides users to busy, well-lit areas, reducing exposure to isolated locations.  
Reduced Wifi notifications: App allows user to become aware of locations with reduced WiFi reception such as industrial estates or countryside locations.  

### **Freedom and Security Wrapped**
Encourages independence by providing practical tools for navigation, route planning, and safe decision-making.  
The "Go Home" feature ensures users always have a quick way to navigate back to a trusted location that includes real time updates informing you of any delays on Trains any crashes on the motorways ect.  

### **Checklist**
A pre-journey checklist equips users with essentials like a power bank and mobile data, preparing them for unexpected situations.  

### **Empowerment**
Designed to be lightweight and easy to use, making it perfect for travelers unfamiliar with their surroundings.  
Supports single women in navigating unfamiliar areas confidently without relying on others.

## Future Enhancements
- Real-time alerts for high-crime areas.
- Offline Mode
Feature: Allow users to download routes and schedules for offline use.
How It Adds Depth: Makes the app usable even without internet access, which is crucial for rural areas or while traveling.
Implementation: Cache data locally using SQLite or AsyncStorage in React Native.
- Transport Accessibility Checker
Feature:
Highlight routes and transport options that are wheelchair accessible or suitable for people with disabilities.
Include live updates on lifts and escalator outages.
How It Adds Depth: Addresses a specific and often overlooked user group.
Implementation: Use transport APIs that provide accessibility information and crowdsource updates.
- Predictive Analytics
Feature: Predict delays, traffic, or crowd levels based on historical data and current conditions.
How It Adds Depth: Prepares users for potential issues before they arise, adding value through foresight.
Implementation: Use machine learning models to analyze historical data and predict future trends.
- Cost Comparison
Feature: Display the cost of each transport option (e.g., bus fare, train ticket, fuel costs) and suggest the cheapest or fastest option.
How It Adds Depth: Helps users make informed decisions based on their budget or time constraints.
Implementation: Fetch pricing data through APIs and integrate fare calculators for taxis or ride-sharing.

## Target Audience:
- Solo female travellers from across the world.
- Vulnerable and disabled female travellers
- Environmentally conscious travelers.
- People requiring accessibility-focused travel options.






