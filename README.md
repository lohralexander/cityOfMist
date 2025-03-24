# 🕵️‍♂️ City of Mist Tracking Cards

A web-based tool to create, manage, and save **Tracking Cards** for the **City of Mist** tabletop roleplaying game. Built with Firebase for cloud sync and Google login support.

## 📖 What is *City of Mist*?

*City of Mist* is a cinematic tabletop RPG where modern-day characters wield legendary powers. Players take on the roles of **Rifts**—individuals who have been awakened to mythical archetypes like gods, fairy tale figures, or folklore legends. The game is narrative-driven, focused on character development, mysteries, and dramatic storytelling rather than crunch-heavy mechanics.

## 🎴 What are Tracking Cards?

Tracking Cards help visualize and track **Tags** and **Statuses** that affect characters, locations, or scenes during gameplay. Each card:

* Holds a tag or condition relevant to the story
* Allows for visual markers to be toggled on specific positions
* Helps players and GMs quickly reference evolving game states
* Is saved in real-time to the cloud and persists between sessions

This tool aims to enhance immersion and streamline bookkeeping during a session.

## 🚀 Features

* 📌 **Add and Remove Tracking Cards** with tag names
* 🎯 **Click to mark pre-defined positions** on each card (e.g., damage, effects)
* 🔐 **Google Sign-In** for personalized storage
* ☁️ **Cloud Sync with Firebase** – cards are saved and loaded per user
* 📱 **Responsive layout** with side menu navigation

## 🧰 Technologies Used

* **HTML/CSS/Vanilla JavaScript**
* **Firebase 9 (Modular SDK)**
  * Authentication (Google Sign-In)
  * Firestore (NoSQL Realtime DB)
* 🧪 Optional integration with custom tracker images

## 📦 Setup Instructions

1. Clone or download the repository
2. Replace the default tracker image (`tracker.png`) with your own if desired
3. Link a Firebase project or reuse the default (for personal or demo use)
4. Open the `index.html` file in a browser

⚠️ Do **not** expose real API keys in public deployments. The Firebase credentials here are for example/demo purposes.

## 📝 Customization Tips

* 🎨 To change the marker locations or add symbols, edit the `allowedMarkerPositions` array
* 🧩 To modify styling, tweak the CSS in `css/styles.css`
* 🃏 Want custom cards for different themes or mechanics? Swap the background image or update marker logic

## 🧙‍♀️ Made for City of Mist Players and GMs

A utility born out of love for myth, mystery, and modern storytelling.