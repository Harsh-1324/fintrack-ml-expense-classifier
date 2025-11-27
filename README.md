Project Overview
The Student Expense Analyzer (EAS) is a mobile and ML-enabled application designed to help students track, categorize, and visualize their expenses from multiple sources such as SMS, UPI notifications, and wallet alerts. The system converts unstructured financial data into meaningful insights, enabling students to manage their finances effectively.

Team Details
Name	Role	Year
Harsh Rakeshkumar Gupta	-Leader	
Janhvi Vijay Ahire -Member	
Nakul Dighavkar	-Member	
Prajakta Deepak Ghodke	-Member	

Problem Statement
Students often struggle to manually track expenses across multiple platforms. EAS automates this process by:
Parsing unstructured financial data from SMS and digital notifications.
Categorizing expenses into segments such as Food, Travel, Bills, and Entertainment.
Providing actionable visualizations and insights for better financial planning.

Proposed Approach
The project follows a modular approach:
Data Input Layer: Collect financial data with user consent.
Data Extraction & Preprocessing: Use regex and keyword parsing to extract transaction fields (amount, merchant, date, payment mode).
ML Categorization: Train a classifier (Naive Bayes / Logistic Regression) for expense categorization.
Feedback Loop: User corrections improve model accuracy over time.
Analytics & Visualization: Generate monthly summaries and charts using Flutter Charts or Matplotlib/Seaborn.
Smart Suggestions Engine: Provide saving reminders, budget alerts, and personalized insights.
App Layer: Flutter-based mobile app with offline capability, local SQLite storage, and cloud sync via Firebase.

Tech Stack

Frontend: Flutter
Backend: Python (Flask / FastAPI)
ML: scikit-learn (expandable to TensorFlow/PyTorch)
Database: SQLite (offline), Firebase (cloud sync)
Libraries: Pandas, Regex, Matplotlib, Flutter Charts
