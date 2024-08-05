
# Carb-pool ([Presentation Link](https://www.canva.com/design/DAFupxuxsvc/0C2iO5jECyUlllmukw0u3Q/edit?utm_content=DAFupxuxsvc&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton))
An efficient carpooling solution that connects people to reduce the overall carbon footprint.

## Authors
- [@Kashish-G](https://github.com/Kashish-G)
- [@krishij03](https://github.com/krishij03)
- [@jasleengill2003](https://github.com/jasleengill2003)
- [@FreshAv0cad0](https://github.com/FreshAv0cad0)

![image](https://github.com/Kashish-G/technovate_noname.csv/blob/main/Application%20screenshot.png)

## Problem Statement
The increasing traffic congestion and environmental concerns in urban areas necessitate an innovative carpooling solution. Our goal is to develop a data-driven carpooling platform that uses AI/ML algorithms to efficiently connect commuters, optimize routes, and reduce traffic congestion. This platform addresses challenges such as matching compatible users, calculating fares, predicting peak demand, ensuring safety, enabling transparent cost-sharing, and incentivizing carpooling during high-demand times.

## Features
- **End-to-End Recommendation Algorithm**: Matches users based on preferences and prioritizes safety.
- **Demand Prediction**: Uses ARIMA to forecast demand during peak hours.
- **Fare Calculation**: Employs Linear Regression for effective fare distribution and calculation.
- **Route Optimization**: Utilizes the Traveling Salesman Problem algorithm to find the most efficient routes.
- **Safety Measures**: Incorporates Human-in-the-Loop Reinforcement Learning for safety ratings, carbon credits for each ride, and automatic notifications for underage users.
- **Chat Functionality**: Enables users to chat with co-passengers before the ride.

## User Flow
- **Introduction**: Carb-pool connects like-minded commuters to optimize routes, reduce carbon footprints, and enhance the travel experience.
- **Preference-Based Matching**: Uses cosine similarity to match users based on preferences like gender and age, ensuring a comfortable journey.
- **Safety Features**: Includes minor travel alerts, a rating system, and legal document verification to enhance user safety and accountability.
- **Fare and Route Optimization**: Calculates precise fares using Linear Regression and determines efficient routes with the Traveling Salesman Problem algorithm.
- **Carpool Chat**: Facilitates communication between users before the ride to build trust and comfort.
- **Carbon Credits**: Rewards users with carbon credits for each ride, incentivizing eco-friendly behavior and providing an opportunity to earn money.

## Installation

First, Git clone.

Next, install requirements.txt.

```bash
  pip install -r requirements.txt
```
Run project
```bash
  python manage.py runserver
```


