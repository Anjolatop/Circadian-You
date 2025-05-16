💤 Circadia: Smart Sleep Companion
Track your sleep. Understand your rhythm. Wake up smarter.

🌟 Overview
Circadia is a mobile app designed for students, shift workers, and anyone with an irregular sleep schedule. By learning your unique sleep/wake patterns, Circadia suggests personalized bedtimes and sets smart alarms that align with your circadian rhythm and natural 90-minute sleep cycles — helping you feel more refreshed and in control of your sleep health.

📱 Features
⏰ Smart Alarm: Wake up during light sleep within your preferred time window.

🌙 Personalized Sleep Suggestions: Learn your ideal bedtime and wake-up time based on your recent habits and circadian trends.

📊 Sleep Pattern Learning: Adaptive machine learning that grows more accurate the more you use it.

📆 Schedule-Aware: Tell us when you need to wake up — we’ll handle the rest.

📓 Sleep Logging (Manual/Automatic): Log when you sleep and wake, or integrate with wearables (coming soon!).

🧠 How It Works
You log your sleep and wake-up times.

Circadia trains a lightweight ML model (on your device!) to track your internal clock and preferred patterns.

You set a wake-up window (e.g. “before 8:30 AM”).

Circadia picks an optimal alarm time based on:

Your predicted circadian rhythm

Your latest sleep onset

90-minute sleep cycle heuristics

The app sets a smart alarm and learns from your feedback over time.

🔧 Tech Stack
Layer	Tech/Tools
Frontend	Flutter (cross-platform mobile UI)
ML Models	Python, Scikit-learn, TensorFlow/Keras
ML Deployment	TensorFlow Lite (Android/iOS), Core ML (iOS)
Backend (Optional)	Firebase (auth, sync), Firestore
Data Storage	Local DB (SQLite) or Cloud Firestore
Alarm Logic	Native alarm managers + 90-min cycle model

🚀 Roadmap
 Manual sleep/wake logging

 Personalized sleep/wake time prediction

 Smart alarm logic based on 90-min cycles

 Sleep quality feedback integration

 Chronotype detection (morning/night person)

 Wearable data integration (Fitbit, Apple HealthKit