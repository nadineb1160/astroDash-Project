# AstroDash

AstroDash is a daily morning dashboard that will allow the user to setup with birthday and location (city and state) so it can fetch horoscope, Chinese Zodiac, Daily Word, Sentiment, (both extracted from the daily horoscope), Local Weather, Air Quality Index, and Pollen Info through the use of several APIs.

## Features:

- Modal Dialogs using UIKit (Nadine)
- Paralax Amimation using UIKit (Nadine)
- Extensive Third Party API Data (Nadine - horoscope APIs, Kasey - Weather, Pollen)
- Sentiment Analysis (Kasey - retrieved data)
- Horoscope Calculator (Nadine)
- Chinese Zodiac Calculator (Kasey)
- Natal Chart App (Nadine)
- Form Input Value saved to localStorage for user's daily use (Nadine)
- Countdown for Birthday (Nadine)
- UI and frontend (Nadine)
- Integration (Kasey and Nadine)

## Why Astro?
#
This project came about after finding many horoscope and astrology APIS in our research phase. Kasey questioned whether we could compare multiple sources to see how the daily horoscopes aligned across signs. With lots of APIs to choose from, the AstroDash was born. We spent the first day researching and planning which is when we noticed that many of the APIs weren't free or were unexcessable. If we wanted to compare text and sentiment of horoscopes we would need enough data to make it interesting.

### Why Dash?
#
We then pivoted to a dashboard with an astrological theme so that more elements could be incorporated. Kasey grabbed more API data and we began creating the horoscope calculators. The backend seemed to be more managable so I stepped in to help manage the project since I was working on both the front and backend. Rand had responsibilty of designing the UI and we worked together to learn a new framework. The pivot caused setbacks for him and our team had very little communication about what he was doing on the frontend. The day before the project was due, he finally showed us the website and it took hours of hard work for kasey to integrate his back end. Unfortunely, the backend didn't look very polished which is why I created a new frontend and restructured the backend. This repository is my version of the data Kasey and I collected.

### Stretch Goals:
#
- Cleaner UI
- Sentiment and keywords both displaying (callbacks)
- Stats panel UI - not mobile responsive
- Validation of cities
- Modal closes after submit pressed
- More information about Horoscopes
- gphiy button, generated playlist (with keyword), moon-phase


## Website Snapshot
===================
### Desktop:
![Image](assets/img1.png)
### Mobile:
![Image](assets/img4.png)
### Horscope:
![Image](assets/img2.png)
### APIS:
![Image](assets/img3.png)

## Project Repo:
Note: All frontend changed were added to new-front-end of forked repo
https://github.com/nadineb1160/astrodash/tree/new-front-end

This is a copy of that branch:
https://github.com/nadineb1160/astroDash-Project

## Deployed Link:
https://nadineb1160.github.io/astroDash-Project/

## Technologies Used
- Javascript - to create functionality of page
- jQuery - simplified DOM manipulation
- JSON - data formatting for localStorage
- AJAX - to make calls to third party APIs
- UIKit - UI Framework
- OpenWeatherAPI - weather info
- Moment.js - library to work with date and time
- Moment-lunar - conversion to lunar calender
- Dandelion API - sentiment and keyword analysis
- Breezeometer API - air quality and pollen

### Author 
#
- Nadine Bundschuh

[LinkedIn](https://www.linkedin.com/in/nadine-bundschuh-731233b9)
|
[GitHub](https://github.com/nadineb1160)

- Kasey Chang (Backend)
- Rand Hunt (Minimal work on this iteration)

### License
#
This is licensed under the MIT License