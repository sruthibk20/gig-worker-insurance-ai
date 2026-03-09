# gig-worker-insurance-ai
AI-Powered Parametric Insurance for Gig Delivery Workers
Problem Statement
Food delivery partners working for platforms like Zomato and Swiggy often face income loss due to external disruptions such as heavy rain, extreme heat, pollution, or local restrictions. Since these workers earn daily wages, even a few hours of disruption can reduce their weekly income significantly.

Currently, gig workers have no income protection system against such uncontrollable events. This project aims to create an AI-powered parametric insurance platform that protects delivery workers from income loss caused by environmental or social disruptions.

Solution Overview
We propose an AI-driven parametric insurance platform designed specifically for food delivery partners. The platform automatically detects external disruptions that prevent workers from completing deliveries and provides instant compensation for lost income.

Instead of manual claim filing, the system uses real-time data from external APIs and predefined trigger conditions to initiate payouts automatically.

This ensures:

Fast claim processing

Reduced fraud

Reliable income protection for gig workers

Target Persona
Food Delivery Partner

Examples:

Swiggy delivery partners

Zomato delivery partners

Typical characteristics:

Earn daily/weekly income

Depend on outdoor mobility

Highly affected by weather conditions and environmental disruptions

System Workflow
1. Worker Registration
Delivery partners register on the platform and provide:

Name

Location

Delivery platform (Zomato / Swiggy)

Average weekly income

2. AI Risk Assessment
The system analyzes location-based risk factors such as:

Weather patterns

Flood-prone zones

Pollution levels

Using this information, the AI model calculates the weekly premium.

Example:

Low risk area → ₹20/week
Medium risk area → ₹40/week
High risk area → ₹70/week

3. Policy Creation
Workers can activate a weekly insurance policy that protects their earnings for that week.

Example policy:

Weekly Premium: ₹40
Coverage: Compensation for income loss caused by external disruptions.

4. Real-Time Monitoring
The system continuously monitors external data sources using APIs such as:

Weather API

Air Quality Index API

Traffic disruption alerts

These data sources help detect conditions that may stop deliveries.

5. Parametric Trigger Detection
When a disruption exceeds a predefined threshold, the system triggers an automated claim.

Example triggers:

Heavy Rain → Rainfall above threshold
Extreme Heat → Temperature above safe working limit
Severe Pollution → AQI above safe level

6. Automatic Claim Processing
Once a trigger is detected:

The system validates worker location

Checks activity records

Initiates the claim automatically

No manual claim submission is required.

7. Instant Payout
The worker receives compensation for lost working hours through a payment gateway (mock/sandbox integration).

Possible payout channels:

UPI

Razorpay test mode

Stripe sandbox

8. Dashboard & Analytics
Worker Dashboard

Active insurance coverage

Weekly premium details

Claims history

Payout status

Admin Dashboard

Number of insured workers

Claims triggered

Fraud alerts

Risk analytics

AI / ML Components
Dynamic Premium Calculation
Machine learning models estimate risk based on:

historical weather data

location risk level

disruption frequency

This helps calculate fair weekly premiums.

Fraud Detection
AI-based anomaly detection prevents fraudulent claims by checking:

GPS location validation

duplicate claims

abnormal activity patterns

Parametric Triggers
Example disruption triggers:

Heavy Rain

Extreme Heat

Severe Air Pollution

Flood Warning

These triggers automatically initiate claim processing.

Technology Stack
Frontend
React / Web Application

Backend
Node.js with Express

Database
MongoDB / Firebase

AI / ML
Python with Scikit-learn

APIs
Weather API
AQI API

Payments
Razorpay Sandbox / Mock Payment Gateway

Future Enhancements
Predictive weather risk modeling

Personalized premium recommendations

Integration with delivery platforms

Real-time disruption alerts for workers

Project Goal
To build a simple, automated insurance system that protects gig delivery workers from sudden income loss, improving financial stability and resilience for the gig economy.
