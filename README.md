# 🏋️ IronCore Gym – AI Powered Fitness Website

<p align="center">
<img src="https://readme-typing-svg.herokuapp.com?font=Orbitron&size=28&duration=3000&pause=1000&color=F59E0B&center=true&vCenter=true&width=700&lines=IronCore+Gym+Website;AI+Workout+Generator;React+%2B+Tailwind+Project;Powered+by+Gemini+AI" />
</p>

<p align="center">
<img src="https://img.shields.io/badge/React-18-blue?style=for-the-badge&logo=react"/>
<img src="https://img.shields.io/badge/TailwindCSS-Modern-38B2AC?style=for-the-badge&logo=tailwind-css"/>
<img src="https://img.shields.io/badge/Gemini-AI-orange?style=for-the-badge&logo=google"/>
<img src="https://img.shields.io/badge/Status-Active-success?style=for-the-badge"/>
</p>

---

# 🚀 Project Overview

IronCore Gym is a modern **AI-powered gym website** designed to showcase a professional fitness center with an engaging user interface and smooth animations.

The website includes an **AI Trainer** that generates **personalized workout plans** using **Google Gemini AI**. Users can input their fitness goal, experience level, and workout frequency to receive a customized training routine.

This project demonstrates modern frontend development using **React, TailwindCSS, and AI API integration**.

---

# ✨ Key Features

### 🧠 AI Workout Planner
Generate personalized workout routines powered by Google Gemini AI.

### 🎨 Modern Animated UI
Includes smooth hover effects, glassmorphism cards, gradient text effects, and animated hero backgrounds.

### 📱 Fully Responsive
The website works seamlessly across:

- Desktop
- Tablets
- Mobile devices

### 🏋️ Complete Gym Website
Includes multiple sections such as:

- Hero section with animated backgrounds
- Gym features and amenities
- Membership pricing plans
- Operating hours
- Google Maps location
- AI workout planner

---

# 🖥 Website Sections

| Section | Description |
|------|-------------|
| Hero | Animated gym background slider |
| Features | Equipment, trainers, cardio, sauna |
| Packages | Membership plans |
| Timings | Gym opening hours |
| Location | Embedded Google Maps |
| AI Trainer | Personalized workout generator |

---

# 🛠 Tech Stack

## Frontend

- React 18
- TailwindCSS
- Lucide Icons
- Babel (JSX Support)

## AI Integration

- Google Gemini API

---

# 📂 Project Structure

IronCore-Gym

- index.html  
- apikey.js  
- README.md  

---

# 🔑 Gemini API Setup

Follow these steps to enable the **AI Workout Planner** in the IronCore Gym project.

---

## 1️⃣ Create a Google AI Studio Account

1. Go to:

https://aistudio.google.com

2. Sign in using your **Google account**.

---

## 2️⃣ Generate an API Key

1. Open the API key page:

https://aistudio.google.com/app/apikey

2. Click **Create API Key**

3. Copy the generated API key.

Example:

```javascript
AIzaSyDxxxxxxxxxxxxxxxxxxxxxxxx
```

---

## 3️⃣ Create `apikey.js`

Inside your project folder create a new file:

```
apikey.js
```

Add the following code:

```javascript
const API_KEY = "YOUR_GEMINI_API_KEY";
```

Example:

```javascript
const API_KEY = "AIzaSyDxxxxxxxxxxxxxxxxxxxxx";
```

---

## 4️⃣ Connect the API Key to the Website

Make sure this line exists in your **index.html**:

```html
<script src="apikey.js"></script>
```

This loads the API key into the project.

---

## 5️⃣ Use the API Key in JavaScript

The application connects to Gemini using:

```javascript
const apiKey = API_KEY;
```

This allows the AI Trainer feature to generate workout plans.

---

## 6️⃣ Run the Project

Simply open:

```
index.html
```

in your browser.

Then:

1. Click **✨ AI Custom Plan**
2. Select your
   - Fitness goal
   - Experience level
   - Workout days
3. Click **Generate Plan**

The AI will generate a personalized workout routine.

---

## ⚠️ Security Note

In this demo project the API key is stored in the frontend for simplicity.

For production applications it is recommended to:

- Use a **backend server**
- Store API keys using **environment variables**
- Avoid exposing API keys in client-side code
