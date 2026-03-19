# TEAM_EXCEPTION
# AI-Powered Parametric Insurance for Gig Workers

## 1. Problem Statement

Gig economy delivery workers such as Swiggy, Zomato, Amazon, and Zepto partners depend on daily deliveries for income. External disruptions like heavy rain, extreme heat, air pollution, floods, or city curfews can prevent them from working.

When these disruptions occur, delivery partners lose a significant portion of their daily income. Currently, there is no insurance system that protects gig workers from such income loss.

Our solution aims to build an **AI-powered parametric insurance platform** that automatically compensates delivery workers for income lost due to external disruptions.

---

# 2. Target Persona

### Persona Example

Name: Ravi  
Profession: Swiggy Delivery Partner  
City: Bengaluru  

Daily Earnings: ₹700 – ₹900

### Scenario

Ravi usually works for 10 hours a day delivering food orders. On a particular day, heavy rainfall causes the delivery platform to pause services for 4 hours. As a result, Ravi loses approximately ₹350 in potential income.

Our platform detects the weather disruption and automatically triggers a compensation payout based on Ravi's weekly insurance coverage.

---

# 3. Solution Overview

We propose an **AI-powered parametric insurance platform** that protects gig workers from income loss caused by external disruptions.

The platform will:

- Offer **weekly insurance plans**
- Monitor **real-time disruption triggers**
- Automatically **detect disruption events**
- Trigger **automatic claim processing**
- Provide **instant payouts to workers**

---

# 4. Application Workflow

1. Worker downloads the mobile application.
2. Worker registers with personal and work details.
3. AI calculates the weekly premium based on location and risk factors.
4. Worker selects an insurance plan and activates coverage.
5. System continuously monitors external disruption triggers.
6. If disruption occurs (rain, pollution, curfew etc.)
7. The system automatically triggers a claim.
8. Compensation is instantly credited to the worker.

---

# 5. Weekly Premium Model

Gig workers operate on weekly earning cycles. Therefore, the insurance pricing is structured on a **weekly subscription model**.

Example Pricing Model:

Basic Plan  
Premium: ₹20/week  
Coverage: ₹500 income protection

Standard Plan  
Premium: ₹35/week  
Coverage: ₹1000 income protection

Premium Plan  
Premium: ₹50/week  
Coverage: ₹1500 income protection

AI dynamically adjusts premiums based on risk factors such as location, historical disruptions, and weather conditions.

---

# 6. Parametric Triggers

Claims are automatically triggered when predefined disruption conditions occur.

Examples of triggers:

Heavy Rainfall  
Condition: Rainfall greater than 50mm

Severe Air Pollution  
Condition: AQI greater than 300

Flood Conditions  
Condition: Road closures detected

Government Curfew  
Condition: City-level restrictions announced

When these triggers are detected, the system automatically initiates compensation.

---

# 7. AI / ML Integration

Artificial Intelligence plays a key role in three areas:

### Risk Prediction
Machine learning models analyze historical weather data and location risks to estimate disruption probability.

### Dynamic Premium Calculation
Premium pricing is adjusted dynamically based on predicted risk levels.

### Fraud Detection
AI models detect suspicious behavior such as:
- GPS spoofing
- duplicate claims
- inconsistent location activity

---

# 8. Platform Choice

We propose a **Mobile Application** because:

- Delivery partners primarily operate through smartphones.
- Easier GPS tracking and location verification.
- Faster access to claim notifications.
- Better accessibility for gig workers.

---

# 9. Technology Stack

Frontend  
React Native (Mobile App)

Backend  
Node.js + Express.js

Database  
MongoDB

AI / ML  
Python  
Scikit-learn

APIs  
OpenWeather API  
Google Maps API

Payments (Simulation)  
Razorpay Sandbox

---

# 10. Development Plan

Phase 1  
Research, ideation, workflow design, and architecture planning.

Phase 2  
Build core system including user registration, insurance plans, dynamic premium calculation, and automated claim triggers.

Phase 3  
Implement fraud detection, instant payout simulation, and analytics dashboard.

---

# 11. Future Enhancements

- Hyper-local weather prediction
- Smart payout optimization
- Integration with delivery platforms
- Risk heatmaps for cities

---

# Conclusion

This platform provides a financial safety net for gig workers by protecting their income from unpredictable external disruptions. By leveraging AI and parametric insurance models, we ensure fast, transparent, and automated compensation for delivery partners.
