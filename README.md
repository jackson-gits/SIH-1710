

# **Smart India Hackathon (SIH) – Workshop Submission**

**Problem Title:**
**SIH 1710: Enhancing Navigation for Railway Station Facilities and Locations**

**Problem Creator’s Organization:**
**Ministry of Railways, Government of India**



## 1. Idea 

Railway stations are chaotic by design. People, luggage, announcements, time pressure, and zero clarity. The idea is to build a **Smart Indoor Navigation & Assistance System** for railway stations that works even when GPS doesn’t, because concrete and metal hate satellites.

Our solution, **RailNav+**, provides **real-time, indoor-aware navigation** for passengers using a combination of **station-mapped zones, QR/NFC checkpoints, computer vision, and AI-based assistance**.

Unlike traditional map apps, RailNav+ understands:

* Indoor station layouts
* Crowd density
* Accessibility needs
* Temporary changes like platform shifts or blocked routes

The system works across **mobile apps, station kiosks, and voice-based interfaces**, ensuring every passenger can find what they need without playing hide-and-seek with platforms.



## 2. Proposed Solution / Architecture (Explained)**

<img width="1192" height="664" alt="image" src="https://github.com/user-attachments/assets/4cd6d2c0-3497-41af-a6a9-8c0caf0a493f" />


### High-Level Flow

1. **User Entry Point**

   * Mobile App
   * Digital Kiosk
   * Voice Assistant Mode

2. **Authentication (Optional)**

   * Guest Mode for quick navigation
   * Logged-in mode for saved preferences and journeys

3. **Indoor Localization**

   * QR/NFC markers placed at key locations
   * Wi-Fi/Bluetooth signal triangulation
   * Camera-based landmark recognition

4. **Navigation Engine**

   * AI path optimizer (shortest, least crowded, accessible)
   * Real-time updates from station control systems

5. **Information Layer**

   * Facilities data (toilets, food, exits, lifts)
   * Train/platform updates
   * Emergency routing

6. **Analytics & Management Dashboard**

   * Crowd heatmaps
   * Bottleneck detection
   * Facility usage trends



## **3. Use Cases**
<img width="391" height="637" alt="image" src="https://github.com/user-attachments/assets/252e1fae-90b6-4544-aff1-aa7003561d72" />


### **Passenger Use Cases**

* Find the nearest platform with step-by-step directions
* Locate facilities like restrooms, food courts, waiting halls
* Get wheelchair-friendly routes
* Receive voice navigation in regional languages
* Emergency evacuation guidance

### **Railway Management Use Cases**

* Monitor crowd density in real time
* Identify congestion-prone areas
* Push instant route changes to users
* Optimize facility placement using analytics

### **Special Assistance Use Cases**

* Visually impaired users get voice-only guidance
* Elderly users receive simplified navigation paths
* Tourists access multilingual support


## **4. Technology Stack **

### **Frontend**

* **React.js** (Mobile Web & Kiosk UI)
* **React Native** (Android App)
* **Three.js** (Lightweight 3D station visualization)

### **Backend**

* **Node.js (Express.js)**
* **PostgreSQL** (Structured station & route data)
* **Redis** (Real-time navigation caching)

### **AI & Intelligence**

* **Python (FastAPI)** for AI services
* **Computer Vision** for landmark recognition
* **Pathfinding Algorithms (A*, Dijkstra hybrid)**

### **Mapping & Localization**

* Custom **Indoor Mapping Engine**
* QR/NFC based checkpoints
* Wi-Fi signal fingerprinting

### **Authentication & Security**

* **Firebase Authentication**
* Role-based access for management dashboard

### **Dev & Collaboration Tools**

* GitHub
* Postman
* Docker (for deployment)
* Figma (UI/UX)



## **5. Dependencies & Timeline**

### **Dependencies**

| Task                           | Duration |
| ------------------------------ | -------- |
| Station layout data collection | 8 days   |
| Indoor mapping & zoning        | 10 days  |
| QR/NFC placement planning      | 5 days   |
| AI navigation logic            | 7 days   |
| UI/UX design & testing         | 6 days   |
| Integration & testing          | 4 days   |

**Total Estimated Time:** ~40 days


## **6. Budget Estimation**

| Item                      | Cost (INR) |
| ------------------------- | ---------- |
| QR/NFC tags & testing     | ₹12,000    |
| Cloud services & APIs     | ₹15,000    |
| Development & prototyping | ₹18,000    |
| Contingency               | ₹5,000     |

**Total Budget:** **₹50,000**



## **7. Why This Solution Is Different**

* Works **indoors** where GPS fails
* Supports **accessibility-first design**
* Real-time crowd-aware routing
* Scalable across small and large stations
* Reduces passenger confusion without human dependency

In short, fewer lost passengers, fewer missed trains, and fewer angry announcements over the PA system.


