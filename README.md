# ICS321 Horse Racing Database - Front-End Interface

This repository contains the front-end client for the Horse Racing Database System project. It provides a simple, clean user interface for both **Admin** and **Guest** users to interact with the live database.

This project consists of three static pages (HTML, CSS, and vanilla JavaScript) that communicate with a separate back-end API.

* **Front-End (This Repo):** Contains the `index.html` (Login), `admin.html`, and `guest.html` pages.
* **Back-End (Separate Repo):** The .NET API is located at: [https://github.com/ZiyadAlsufyani/backend](https://github.com/ZiyadAlsufyani/backend)

## 🚀 Live Demo

This project is deployed using GitHub Pages.

**You can access the live website here:**
**https://o5mu.github.io/horse-racing-project/**

> **Note:** For the website to be fully functional, the back-end API must be running and deployed.

## 🌟 Features

The interface is split into two distinct roles, matching the project requirements.

### 👤 Guest Portal (`guest.html`)

A read-only portal for browsing public information.

* **Get Horses by Owner:** Browse the names and ages of horses owned by a person, given their last name.
* **View Winning Trainers:** See a list of all trainers who have trained horses that won first place.
* **View Trainer Winnings:** Get a list of trainers sorted by their total prize money winnings.
* **View Track Statistics:** See a table of all race tracks, the count of races held there, and the total number of horses that have participated.

### 🔐 Admin Portal (`admin.html`)

A portal for managing and modifying database records.

* **Add New Race:** A user-friendly form to add a new race, including its date, time, and a dynamic list of horse results (position and prize).
* **Delete Owner:** Delete an owner and all their related information from the database.
* **Move Horse:** Move a horse from its current stable to a new one.
* **Approve Trainer:** Approve a new trainer to join a specific stable.

## 💻 Technology Used

This is a lightweight front-end built with web fundamentals.

* **HTML5:** For the structure of all three pages.
* **CSS3:** For all custom styling, layout (Flexbox/Grid), and responsiveness. No external frameworks were used.
* **JavaScript (ES6+):** For all client-side logic:
    * Handling form submissions.
    * Making API calls using the `fetch()` API.
    * Dynamically building HTML tables to display data from the API.

## 🔌 API Connection

This front-end is configured to connect to the live production API deployed on Azure.

* **API Base URL:** `https://ics321-racing-api-gdd6g6hvdcbch7bu.uaenorth-01.azurewebsites.net/` 
