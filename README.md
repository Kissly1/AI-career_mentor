# 🚀 AI Career Mentor: Profile & Chat Module (MVP)

<div align="center">
  <img src="https://img.shields.io/badge/Platform-iOS-000000?style=for-the-badge&logo=apple&logoColor=white" alt="Platform" />
  <img src="https://img.shields.io/badge/Swift-FA7343?style=for-the-badge&logo=swift&logoColor=white" alt="Swift" />
  <img src="https://img.shields.io/badge/UI-SwiftUI-31A8FF?style=for-the-badge" alt="SwiftUI" />
  <img src="https://img.shields.io/badge/AI-Integration_Ready-8A2BE2?style=for-the-badge" alt="AI Integration" />
</div>

<br>

An interactive, native iOS application module designed to set up and manage user profiles for an upcoming AI-driven career mentoring platform. This foundational MVP allows users to input their educational background, track their coding proficiency, define specific career goals, and seamlessly transition into an AI advisory chat.

## 📸 Interface Preview

> **Note:** The UI features a clean, modern, card-based design tailored for a native iOS experience.

<div align="center">
  
<!-- ======================================================== -->
<img width="291" height="572" alt="Снимок экрана — 2026-06-02 в 17 50 04" src="https://github.com/user-attachments/assets/d32dc942-79a4-4999-9bde-dcaf40d971a8" />

<img width="286" height="570" alt="Снимок экрана — 2026-06-02 в 17 50 33" src="https://github.com/user-attachments/assets/ed880b44-447c-4ab2-87e7-a7db43e27a5e" />

<!-- ======================================================== -->

</div>

## ✨ Core Features (Current State)

* **Dynamic Profile Builder:** A responsive UI card that captures user data (Name, University) to contextualize AI advice for the local IT market and networking opportunities.
* **Skill & Goal Tracking:** Interactive elements allowing users to add specific technical skills and set long-term career goals (e.g., targeting specific local companies).
* **AI Mentor Chat Interface:** A dedicated, scrollable chat view ready to handle interactive dialogues, step-by-step roadmaps, and career Q&A.
* **Clean UI/UX:** Implemented a modern design with proper shadows, corner radius, and safe area management against a system-grouped background `UIColor.systemGroupedBackground`.
* **Custom Navigation:** Smooth transition capabilities between the Profile tab and the AI Mentor tab.

## 🛠 Technical Implementation

This view is built entirely with **SwiftUI**, demonstrating a solid understanding of modern iOS state management and layout structuring:

* **State Management:** Heavy use of `@State` property wrappers to ensure the UI remains perfectly synced with the underlying data (user inputs, skills array, text fields).
* **Declarative Layouts:** Deep, optimized nesting of `ZStack`, `VStack`, and `HStack` to achieve a clean, modular visual hierarchy.
* **Adaptive Styling:** Usage of dynamic system colors and SF Symbols that adapt fluidly to user interactions and states.

## 🚀 Future Roadmap

* **[ ]** Integrate `CoreData` or `UserDefaults` for persistent local data storage.
* **[ ]** Connect to an external LLM API (e.g., OpenAI or Anthropic) to generate personalized, context-aware career advice based on the user's university, skills, and target job.
* **[ ]** Implement `NavigationStack` for deeper routing within the AI Chat interface and settings.

## 💻 Installation & Setup

**1. Clone the repository:**
```bash
git clone [https://github.com/Kissly1/AI-career_mentor.git](https://github.com/Kissly1/AI-career_mentor.git)
```

2. Open the project in Xcode:

```
cd AI-career_mentor
open AICareerMentor.xcodeproj
```

3. Build & Run:

Select an iPhone simulator (iOS 16.0+ recommended) and press Cmd + R.
