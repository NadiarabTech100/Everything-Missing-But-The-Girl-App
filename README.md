# Everything Missing But The Girl App 

An app designed to empower solo female travellers and enhance saftey and security to ensure that you can reach your destination. 

<div align="center">
  <img src="./assets/Logo.png" alt="App Logo" width="300" height="300">
</div>


---

## Highlights

- **Emergency Alarm**: An alarm set of to deter threats, the app will contact the local emergency services and then notifies your emergency contact via sms sending your exact location. 
- **Danger Zone Mapping**: Displays on a map the locations of all the high crime areas. The app also maps out more isolated areas with fewer pedestians therefore making them unsafe. As an added bonus the app also includes areas with poor reception and Wi-Fi. 
- **Go Home Feature**: The app literally takes you home it plans a route using the fastest mode of transport to take you home. The app will lay out all the options bus, train or taxi and comment on any adverse weather and delays in the area that may prevent you reaching your destination. The app will also re-route if required to ensure the users saftey is the first priority. 
- **Nav-Pal**: The app includes a Location Tracker that updates the user's live location every 30 minutes, ensuring real-time updates are sent to their pre-selected emergency contacts. This feature enhances safety by keeping trusted individuals informed about the user's whereabouts during their journey.

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

4. **Bus and Train Finder** (Upgrade)  
   Helps users locate the nearest public transportation options in cases where travellers are compeletley lost. 

5. **Pre-travel advice** (Upgrade)  
   Provides tailored safety tips such as devices to have and general tips:
   - Packing essentials (e.g., power bank, mobile data).
   - Avoiding isolated areas like industrial estates or alleys.
   - Wearing practical footwear like trainers for ease of travel.
   - Situational Awareness such as retracing your steps if required remebering landmarks
   - Reporting crimes - Offering a list if non-emergency phone numbers for the police and transport services. This will encourage teaveller to report crimes increasing safety for all travellers.

6. **Real-Time travel distruption to public transport services & Adverse weather conditons** (Upgrade) Informs users of immediate travel delays on trains and buses.
  This also includes weather conditons preventing travellers from reaching their destinations and any road closures. 

7. **Reduced WiFi Notification**  
   Alerts users to areas with limited WiFi connectivity to enable better journey planning for the travller.

8. **Language Support**: Offer multi-language support for international travellers. 



---
## **Benefits for Female Solo Travellers**

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
- Medical conditions- This feature will allow your mobile to display all your medical conditions.
- Travel Buddy System: A community based approach to connect fellow travellers (requires passport or identification document upload to  ensure safety of travellers.
- Multiple device compatibility: Compatible with smartwatches or fitness trackers to provide discrete SOS alerts


## Target Audience:
- Women and other vulnerable individuals prioritizing personal safety.
- Solo travelers navigating unfamiliar areas.
- Individuals seeking enhanced awareness of their surroundings during travel.






