# 🌍 HALOROUTE: Sentinel Safety Grid

## 🛡️ Project Overview

**HaloRoute** is a comprehensive, client-side web application designed to enhance tourist safety through real-time geospatial intelligence, decentralized identity, and integrated Generative AI. Built as a proof-of-concept for a secure, modern safety system, the application uses a high-contrast **Command Console** aesthetic to provide crucial information instantly.

This project was developed as a final-year submission focusing on combining front-end development (SPA architecture) with advanced third-party API integration (Mapping, AI, and Blockchain simulation).

---

## ✨ Key Features & Functionality

HaloRoute is a Single Page Application (SPA) with three main views: Dashboard, Tracker, and Settings.

* **Real-Time Geofencing:** Utilizes the Geolocation API and a **Ray-Casting Algorithm** to continuously check the user's location against predefined "Danger Zones" (Red Polygon). Triggers instant visual and score alerts.
* **Panic Protocol:** A one-click SOS system featuring a custom **Radar Animation Modal** and a contact list manager, simulating an emergency broadcast to a mesh network.
* **Blockchain Identity (Web3):** Implements **Ethers.js** integration (with a fallback simulation) to use anonymous wallet addresses as the user's primary ID, promoting privacy and data security.
* **Context-Aware AI Assistant:** Integrated with the **Google Gemini 2.5 Flash API**. The AI is fed the user's *live* dashboard context (Safety Score, Zone Status) via a system prompt to provide highly relevant, location-specific advice.
* **ID Tracker Module:** A dedicated secondary map instance (separate from the main dashboard map) for authorities to input a cryptographic ID and locate a target's last known position.

---

## 🛠️ Tech Stack & Libraries

| Category | Technology | Purpose |
| :--- | :--- | :--- |
| **Frontend** | HTML5, Vanilla JavaScript | Core SPA architecture and logic. |
| **Styling** | **Tailwind CSS** | Used for the modern, scannable, high-contrast UI and responsive design. |
| **Mapping** | Leaflet.js | Lightweight and open-source library for interactive maps. |
| **AI** | Google Generative Language API | Powers the context-aware Gemini 2.5 Flash chatbot. |
| **Blockchain** | Ethers.js | Library for interacting with the Ethereum network (identity simulation). |

---

## 🚀 Getting Started

This project is a client-side SPA and requires no backend server setup.

### Prerequisites

You need a web browser (Chrome, Firefox, Edge, etc.) to run the application.

### Installation

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/](https://github.com/)[Your-GitHub-Username]/HaloRoute.git
    cd HaloRoute
    ```
2.  **Get Your API Key:**
    * The project uses a placeholder API key. To enable the live AI features, you must obtain a key from the **Google AI Studio**.
    * *Note: In the provided code, the key is hardcoded as a placeholder for demonstration purposes. Replace this in the final deployment.*
3.  **Run Locally:**
    * Simply open the `index.html` file in your preferred web browser.

    ```bash
    open index.html 
    ```
    *(The login screen will appear first. Use placeholder credentials: `admin` / `1234`)*

---

## 📹 Demo & Presentation

Watch the video presentation for a full walkthrough of all features, including the Geofencing logic and the AI contextual awareness:

[![HaloRoute Video Presentation Thumbnail]]([LINK TO YOUR YOUTUBE VIDEO])

---

## 👤 Team & Contact

* **[Your Name]** (Role: [Lead Developer / UI/UX / etc.]) - [Your LinkedIn or Portfolio Link]
* **[Teammate Name]**
* **[Teammate Name]**

## ⚖️ License

This project is open-source and available under the **MIT License**.

```markdown
