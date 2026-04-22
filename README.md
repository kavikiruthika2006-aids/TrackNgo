# TrackNgo – Real-Time Bus Tracking System

## Overview

TrackNgo is a full-stack real-time bus tracking application designed to improve public transportation efficiency. It allows passengers to track live bus locations, view estimated arrival times (ETA), and access route information through an interactive map interface.
The system connects drivers, passengers, and administrators on a single platform, reducing waiting time and enhancing travel planning.

## Objectives
-Provide real-time bus location tracking

-Reduce passenger uncertainty and waiting time

-Enable efficient communication between users

-Monitor bus activity and detect inactive vehicles

##🚀 Key Features

##👤 Passenger

-View buses for selected routes

-Live tracking using map interface

-ETA for upcoming stops

-Bus details (bus number, driver info)

##🧑‍✈️ Driver

-Secure login and route selection

-Real-time location sharing

-Start/Stop tracking functionality

##🛠️ Admin

-Monitor all buses in real time

-Identify active and inactive buses

-Access driver and bus details

##🧠 Tech Stack

##Frontend:

-React.js

-TypeScript

-Tailwind CSS

-Leaflet.js (Map Integration using OpenStreetMap)

##Backend:

-Node.js

-Express.js

-Socket.IO (Real-time communication)

##Database:

Firebase Realtime Database

##⚙️ System Workflow

-Driver logs in and starts location tracking

-GPS coordinates are sent to the backend server

-Backend updates data in Firebase and broadcasts via Socket.IO

-Passenger interface displays live bus locations on the map

-Admin monitors system activity and bus status

##📍 Core Functionalities

-Real-time GPS tracking

-ETA calculation based on distance and speed

-Multi-user role management

-Active/Inactive bus detection

-Route and stop visualization

##Future Enhancements

-AI-based traffic prediction

-Route optimization

-Push notifications for arrivals

-Multi-language support

-Voice-based interaction

##👩‍💻 Authors

Kiruthika R

Dharani R

Divyabharathi S
