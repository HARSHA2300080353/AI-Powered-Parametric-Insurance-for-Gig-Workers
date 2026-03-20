# 🚀 AI-Powered Parametric Insurance for Gig Workers

## 👥 Team Details
- Team Name: Bug Busters
- Members:
  - A. Sri Harsha
  - L. Prasanna Kumar
  - K. Viswanadh

---

## 📌 Problem Statement
Gig delivery workers face significant income loss due to external disruptions such as weather conditions, pollution, and unexpected events. These disruptions reduce their working hours and directly impact their earnings, with no existing financial protection system.

---

## 🎯 Selected Persona
**Food Delivery Worker (Zomato)**

### 👤 Persona Description
- Daily working hours: 8–12 hours (flexible based on demand)
- Average earnings: ₹500–₹1000/day
- Works in harsh outdoor conditions (rain, heat, pollution)
- No fixed salary (earnings depend on orders)

### ⚠️ Challenges
- Income loss due to weather disruptions
- Traffic delays and long working hours
- No insurance for income protection
- Platform dependency and instability

---

## 💡 Problem Scenario
A delivery partner is unable to work due to heavy rain or extreme heat. As a result, deliveries stop and the worker loses income. Currently, there is no mechanism to compensate for this loss.

---

## 🚀 Proposed Solution
We propose an **AI-powered parametric insurance platform** that:

- Monitors real-time environmental conditions  
- Detects disruptions automatically  
- Triggers claims without manual intervention  
- Provides instant payouts to workers  

---

## 🔄 System Workflow

1. User registers on platform  
2. System tracks location, activity, and device signals  
3. APIs monitor weather/AQI conditions  
4. If disruption crosses threshold → trigger event  
5. Claim is automatically generated  
6. AI-based fraud detection evaluates claim  
7. Verified claims are processed for instant payout  

---

## 💰 Weekly Premium Model

- Premium calculated **weekly**
- Based on:
  - Location risk  
  - Weather history  
  - Work frequency  
  - Claim history  
  - Behavioral risk score (AI)

### Example:
- Low-risk → ₹20/week  
- High-risk → ₹50/week  

---

## ⚙️ Parametric Triggers

- Rainfall > X mm  
- AQI > 300  
- Temperature > 45°C  
- Flood alerts  

---

## 🤖 AI/ML Integration

### 1️⃣ Risk Prediction
- Predict disruption probability using historical weather + location data  
- Generate **risk score per worker/location**

### 2️⃣ Dynamic Premium Calculation
- Adjust premium using:
  - Risk score  
  - Past claims  
  - Real-time environmental data  

### 3️⃣ Intelligent Fraud Detection
- AI anomaly detection identifies suspicious claims using:
  - Behavior deviation  
  - Location inconsistencies  
  - Pattern mismatch  

---

## 🚨 Adversarial Defense & Anti-Spoofing Strategy

To protect the system from GPS spoofing and coordinated fraud attacks:

### 🔍 Differentiation (Real vs Fake Users)
We differentiate genuine workers from attackers using:

- Movement consistency (continuous vs sudden jumps)  
- Speed patterns (real travel vs unrealistic teleportation)  
- Delivery activity (active vs idle spoofing users)  
- Route validation using map-based path tracking  

👉 Fake users show:
- Static location with no movement  
- Sudden unrealistic jumps  
- No delivery activity  

---

### 📊 Data Used (Beyond GPS)
Our system uses **multi-layer data validation**:

- GPS coordinates + movement history  
- Accelerometer & motion patterns (real movement detection)  
- Delivery logs (orders, timings, frequency)  
- Network signals (IP consistency, device fingerprint)  
- Time-based behavior patterns  

👉 This prevents **coordinated fraud rings** from exploiting the system.

---

### ⚖️ UX Balance (Fairness + Security)

We ensure fraud prevention **without harming genuine users**:

- Suspicious claims are **flagged, not instantly rejected**  
- Claims are categorized:
  - Low risk → instant payout  
  - Medium risk → delayed verification  
  - High risk → manual review  

- Additional validation includes:
  - Delivery history check  
  - Device consistency check  

- **Partial payouts** may be given for uncertain cases  
- Genuine users always have **fallback verification options**  

👉 This ensures:
✔ Fair treatment of honest workers  
✔ Strong fraud prevention  

---

## 🛠️ Tech Stack

### Frontend:
React / HTML-CSS

### Backend:
Node.js / Express

### Database:
MongoDB

### AI/ML:
Python, Scikit-learn

### APIs:
- Weather API  
- AQI API  
- Google Maps API  

### Payment:
Razorpay (Test Mode)

---

## 📊 Future Scope (Phase 2 & 3)

- Real-time API integration  
- Full AI model implementation  
- Payment gateway integration  
- Worker & Admin dashboards  
- Advanced fraud detection with deep learning  

---

## 🎥 Demo Video
https://drive.google.com/file/d/10MiGVhaXnXMfWK7zu5kHUjvIi-8sj0ei/view?usp=sharing

---

## 🔗 GitHub Repository
https://github.com/HARSHA2300080353/AI-Powered-Parametric-Insurance-for-Gig-Workers
