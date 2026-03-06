# 🛡️ SafeCampus – Disaster Preparedness System

SafeCampus is an interactive web application designed to help students and staff quickly learn how to respond during emergencies such as earthquakes, fires, floods, and cyclones.

The system provides scenario-based guidance, safety checklists, and emergency contacts to improve disaster awareness and preparedness in educational institutions.

---

# 🚨 Problem Statement

Educational institutions often lack accessible digital tools to train students and staff on emergency response procedures.

During disasters such as:

* Earthquakes
* Fires
* Floods
* Cyclones

people may panic due to a lack of knowledge about what actions to take.

**SafeCampus solves this problem by providing a simple web-based platform that guides users through correct emergency responses.**

---

# 🎯 Key Features

### 📚 Disaster Learning Modules

Users can learn safety instructions for major disaster scenarios:

* Earthquake
* Fire
* Flood
* Cyclone

Each module explains immediate actions and evacuation procedures.

---

### ⚡ Scenario-Based Guidance

Users select a disaster type from a dropdown menu and instantly receive **step-by-step emergency response instructions**.

---

### ✅ Preparedness Checklist

A simple checklist allows users to evaluate their disaster readiness.

The system calculates a **Preparedness Score** based on completed safety measures.

---

### ☎️ Emergency Resources

Quick-access emergency contacts are displayed, including:

* Police
* Fire Department
* Ambulance

This ensures users can quickly reach help during an emergency.

---

### 📱 Clean & Accessible UI

* Simple and easy to use
* Mobile-friendly interface
* Designed for fast access during emergencies

---

# 🧠 Response Logic

The application follows a structured emergency response flow:

1. User selects a disaster type.
2. System displays immediate safety actions.
3. Evacuation or safety instructions are provided.
4. Emergency contacts are shown for quick help.

---

# 🌪️ Supported Disaster Types

| Disaster   | Description                                                   |
| ---------- | ------------------------------------------------------------- |
| Earthquake | Guidance for shaking events and building evacuation           |
| Fire       | Steps to safely exit buildings and avoid smoke                |
| Flood      | Instructions to move to higher ground and avoid water hazards |
| Cyclone    | Safety procedures during strong winds and storms              |

---

# 📥 Input Requirements

The application requires:

* **Disaster Selection** via dropdown menu
  Options:

  * EARTHQUAKE
  * FIRE
  * FLOOD
  * CYCLONE

* **User Interaction**

  * Viewing safety steps
  * Completing preparedness checklist

---

# 📤 Output Structure (JSON Schema)

The application generates the following structured response:

```json
{
  "disaster_type": "EARTHQUAKE | FIRE | FLOOD | CYCLONE",
  "preparedness_score": 0,
  "safety_actions": ["Step 1", "Step 2", "Step 3"],
  "emergency_contacts": ["Police", "Fire Department", "Ambulance"],
  "status": "Prepared | Needs Improvement"
}
```

---

# 🛠️ Technologies Used

* HTML5
* CSS3
* JavaScript
* JSON Data Structures

---

# 📂 Project Structure

```
SafeCampus/
│
├── index.html
├── style.css
├── script.js
├── safecampus.html
└── README.md
```

---

# 🚀 How to Run the Project

1. Clone the repository

```
git clone https://github.com/your-username/safecampus.git
```

2. Open the project folder

3. Run the application by opening:

```
index.html
```

in your browser.

---

# 💡 Future Improvements

* Campus-specific evacuation maps
* Real-time disaster alerts
* AI-based emergency guidance
* Integration with official emergency APIs
* Multi-language support

---

# 👨‍💻 Hackathon Project

This project was built as part of **HACKARENA – Civic Tech / Disaster Management Track**.

Goal:
Create a digital solution that improves **disaster awareness and emergency preparedness in educational institutions**.

---

# 📜 License

This project is open-source and available under the **MIT License**.

---

⭐ If you found this project useful, consider giving the repository a star!
