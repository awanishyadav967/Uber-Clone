# Uber Clone (Java + Firebase)

## Overview

This Uber Clone app replicates key functionalities of the Uber ride-hailing service, developed using **Java** and **Firebase** for backend services. The app allows users to book rides, track drivers, and handle payments seamlessly. In addition to the core Uber features, this clone includes two additional unique features for enhancing the passenger experience during long journeys, as well as a smart fare calculation system based on real-time traffic data.

## Features

### Core Features
- **Ride Booking**: Users can book a ride by selecting pickup and drop locations.
- **Real-Time Location Tracking**: Track the driver's location using Google Maps integration.
- **Driver and Customer Authentication**: Firebase Authentication for both drivers and riders, including phone number and email login.
- **In-App Payment Integration**: Multiple payment options available within the app.
- **Ride History**: Both riders and drivers can view their ride history.

### Additional Features

#### 1. In-App Games and Movies (Extra Feature)
- **Entertainment on Long Journeys**: Passengers can enjoy a selection of in-app games and movies during long trips, keeping them entertained throughout the journey.
  - **Movies**: A curated list of popular movies available for passengers to watch.
  - **Games**: Simple yet engaging games that passengers can play to pass the time.

#### 2. Smart Fare Calculation System (My Suggested Feature)
- **Real-Time Fare Adjustment Based on Traffic**: This feature leverages live traffic data to estimate and adjust the fare during a trip. In high-traffic conditions, the fare will be dynamically updated, helping users get a more accurate trip cost based on the current traffic scenario.

#### 3. Emergency Alert System (Extra Feature)
- **SOS and Emergency Contacts**: An emergency alert button is integrated into the app for both riders and drivers. Users can press this button in any critical situation, which will immediately notify emergency services and the user’s predefined emergency contacts, along with the current location.

---

## Tech Stack

- **Frontend**: Java (Android)
- **Backend**: Firebase (Authentication, Realtime Database, Cloud Firestore)
- **Map Integration**: Google Maps API
- **Payment Gateway**: Integrated with payment services such as Stripe or PayPal
- **Real-Time Fare Calculation**: Google Directions API for traffic and route analysis

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/uberclone.git
