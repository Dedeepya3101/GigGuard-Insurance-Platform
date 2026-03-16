# GigGuard AI
AI-Powered Parametric Insurance for India's Gig Economy
->1. Selected Persona

*Target Segment:* Food Delivery Partners (Zomato / Swiggy)

**Persona Description**

Food delivery partners work long hours to complete deliveries and earn income. Their earnings depend directly on the number of deliveries they complete each day.

However, their work is highly vulnerable to external disruptions such as heavy rain, extreme heat, floods, pollution, or sudden curfews. During such events, delivery partners cannot work and lose their daily income even though the situation is beyond their control.

GigGuard AI aims to protect delivery partners from **loss of income caused by such external disruptions**.
-> 2. Problem Statement

In India, delivery partners frequently face income loss due to uncontrollable external events such as heavy rainfall, extreme heat waves, floods, and local curfews.

These disruptions prevent them from completing deliveries, leading to **20–30% loss in their monthly earnings**.

Currently, there is **no automated financial protection system** that compensates gig workers specifically for lost working hours.

GigGuard AI provides a **parametric insurance solution that protects only the worker's lost income**, without covering health, life, or vehicle damages.


->3. Requirement & Workflow

The system provides a simple workflow from registration to automatic payout.

1. Onboarding
Delivery partners register on the platform by entering their basic details, working location, and delivery platform (Zomato or Swiggy).

2.Subscription
Users subscribe to a **weekly premium plan** that provides protection against income loss caused by disruptions.

3. Monitoring
The system continuously monitors external data sources such as weather APIs, traffic alerts, and news feeds.

4. Trigger
If a disruption event occurs (for example heavy rain exceeding a threshold), the system automatically triggers a claim.

5.Validation
AI verifies whether the worker was active in the affected area during the disruption.

6.Payout
Once validated, the system initiates an **instant payout to compensate for lost income**.

->4. Financial & Insurance Model

* Weekly Pricing Model

GigGuard AI follows a "weekly premium model", which aligns with gig workers' weekly earning cycles.

The premium is dynamically calculated based on hyper-local risk factors such as:

- Rain frequency
- Flood-prone areas
- Extreme heat zones
- Traffic congestion
- Historical disruption data

Example pricing model:

Low-risk zones → ₹20 per week  
Medium-risk zones → ₹40 per week  
High-risk zones → ₹60 per week  



* Parametric Triggers

Claims are triggered automatically based on predefined external conditions.

"Environmental Triggers"

- Rainfall greater than 15mm per hour
- Temperature above 45°C
- Severe flood alerts
- Extreme pollution levels

"Social Triggers"

- Local strikes
- Government curfews
- Emergency city lockdowns

When these events occur in the worker's location, the system automatically activates compensation.
->5. AI / ML Integration Strategy

*Dynamic Premium Calculation

AI models analyze historical disruption data and hyper-local environmental conditions to adjust weekly premium pricing.

For example, workers operating in flood-prone areas may have slightly higher premiums due to increased risk.
* Intelligent Fraud Detection

AI helps detect fraudulent claims using multiple validation techniques.

*Location Validation*

Worker GPS location is verified against the disruption area.

**Activity Validation**

The system checks whether the worker was active on the delivery platform during the disruption period.

**Anomaly Detection**

Machine learning models identify suspicious patterns such as repeated claims or abnormal activity.

---

-> 6. Platform Choice & Tech Stack

**Platform:** Web Application

A web platform is chosen because it is easier to deploy quickly and accessible from both mobile and desktop devices without requiring installation.
*Frontend

HTML  
CSS  
JavaScript  



*Backend

Node.js / Python

->APIs

OpenWeather API – for real-time weather monitoring  
News APIs – for curfew and strike detection  
Google Maps API – for location validation  

(Mock APIs will be used for delivery platform activity data)


->Database

MongoDB / Firebase

-> 7. Development Roadmap (6-Week Plan)

-> Phase 1
Ideation, research, and prototype design.

Create GitHub repository, README documentation, and a basic prototype interface.

**Deadline: March 20**

--------------------------

-> Phase 2

Develop automation features such as:

- AI risk pricing engine
- Parametric trigger detection
- Real-time monitoring of disruption events

Weeks 3–4
->Phase 3

Add advanced features including:

- Fraud detection system
- Automated payout simulation
- Admin analytics dashboard

Weeks 5–6
-> Prototype Demo

Prototype Link: (Add your prototype link here)


## Video Demonstration

2-minute project explanation video:

(Add your video link here)

*System Workflow*

1. Delivery partner registers on the platform
2. System collects location and platform activity data
3. AI risk engine calculates weekly premium
4. User subscribes to weekly coverage
5. System monitors weather and disruption APIs
6. If disruption detected → parametric trigger activated
7. AI validates worker location and activity
8. Automatic claim approval
9. Instant payout sent to worker
