# Shield-Gig: AI-Powered Micro-Insurance for Delivery Workers

> Instant protection for gig workers when real-world disruptions stop them from earning.

---

## Team Members
- Shivam Puri  
- Peehu Chand  
- Soumya Bhatia  
- Vivek Chandu  
- M Dharni  

---

## Problem Statement

Gig delivery workers depend entirely on daily earnings. If they cannot work for even a single day, their income drops to zero.

Situations like:
- Heavy rainfall  
- Floods  
- Extreme heat  
- High pollution  
- Curfews or city shutdowns  

directly prevent them from completing deliveries.

### Limitations of Existing Insurance
- Focus on accidents or health, not income loss  
- Slow and complex claim processes  
- Expensive premiums for gig workers  

**Core Issue:**  
If a worker cannot work today, they lose money today.

---

## User Persona

**Ramesh Gupta**  
- Age: 27  
- Occupation: Delivery Partner (Zomato / Swiggy / Zepto)  
- Daily Earnings: ₹700–₹900  

### Challenges:
- No fixed salary  
- No paid leave  
- No financial backup  

During extreme conditions, he is forced to stop working, leading to immediate income loss.

---

## Solution Overview

Shield-Gig is an AI-powered parametric micro-insurance platform designed for income protection.

### Key Features:
- No manual claim filing  
- Real-time disruption detection  
- Instant payout system  
- AI-based verification  

---

## How It Works

1. Worker registers and connects location  
2. System analyzes location-based risk  
3. Weekly premium is assigned  
4. Platform continuously monitors:
   - Weather data  
   - AQI levels  
   - City alerts  
   - Worker activity  
5. Disruption is detected  
6. System verifies inability to work  
7. Instant payout is triggered  

---

## Weekly Premium Model

| Risk Level      | Weekly Premium |
|----------------|--------------|
| Low Risk Area  | ₹29         |
| Medium Risk Area | ₹39       |
| High Risk Area | ₹49         |

---

## Parametric Triggers

Payouts are triggered automatically when thresholds are met:

- Rainfall > 50 mm  
- AQI > 300  
- Temperature > 45°C  
- Flood alerts or road closures  
- Government restrictions  

---

## AI Implementation

### Risk-Based Pricing
AI evaluates:
- Location risk  
- Environmental patterns  
- Worker behavior  

### Disruption Prediction
- Uses historical + real-time data  
- Predicts high-risk situations  

### Fraud Detection
- Detects suspicious claim patterns  
- Ensures genuine payouts  

---

## Tech Stack

### Frontend
- HTML  
- CSS  
- JavaScript  

### Backend
- Python (Flask / Django)  

### AI Models
- Scikit-learn  

### Database
- Firebase  

### APIs
- Weather API  
- AQI API  
- Maps API  
- UPI Payment Gateway  

---

# Adversarial Defense & Anti-Spoofing Strategy

Simple GPS-based verification is no longer reliable. Shield-Gig uses a multi-layer AI-driven system to ensure only genuine workers receive payouts.

---

## 1. Differentiation: Genuine Worker vs Spoofing Actor

The system analyzes behavioral patterns instead of relying only on GPS.

### Genuine Worker Pattern
- Gradual reduction in movement  
- Realistic delivery routes  
- Consistent app usage  
- Alignment with real-world conditions  

### Fraudulent Pattern
- Sudden location jumps  
- Impossible travel speeds  
- No match with real disruptions  
- Repeated suspicious claims  

### AI Approach
- Time-series analysis of movement  
- Anomaly detection (Isolation Forest)  
- Geo-spatial validation  

Each claim is assigned a **Fraud Risk Score**.

---

## 2. Data Beyond GPS (Multi-Signal Verification)

### Location Intelligence
- GPS data  
- Cell tower triangulation  
- IP-based location  

### Device & Sensor Data
- Accelerometer  
- Gyroscope  
- Device fingerprinting  

### Environmental Correlation
- Weather vs activity  
- AQI vs movement  
- Flood/road closure data  

### Behavioral Signals
- Delivery history  
- Activity patterns  
- Online/offline timing  

### Network-Level Analysis
- Multiple accounts per device  
- Synchronized fraud attempts  
- Pattern similarity detection  

---

## 3. UX Balance: Fairness for Genuine Workers

### Risk-Based Claim Handling

| Risk Score | Action |
|-----------|--------|
| Low Risk | Automatic approval |
| Medium Risk | Quick verification |
| High Risk | Manual review |

### Handling Real Issues
- Works in low network conditions  
- Uses alternative validation signals  
- Avoids false rejection  

### Worker Protection
- Transparent claim status  
- Explanation for flagged claims  
- Appeal option  
- No harsh penalties  

---

## Why This Matters

Gig workers lack financial safety nets.

Shield-Gig provides:
- Instant income protection  
- Fair and automated payouts  
- Real-world aware insurance system  

---

## Future Scope

- Integration with delivery platforms  
- Earnings-based payout models  
- Expansion to ride-sharing and freelancers  
- Advanced AI fraud detection  

---

## Conclusion

Shield-Gig combines:
- AI-driven risk prediction  
- Parametric insurance automation  
- Advanced fraud prevention  
- Worker-first design  

It ensures that when workers cannot work, they are still financially protected.um calculation, and claim system.
