# 🚀 AI Career Mentor: Profile Module (MVP)

![Swift](https://img.shields.io/badge/Swift-5.0-orange.svg)
![UI](https://img.shields.io/badge/UI-SwiftUI-blue.svg)
![Platform](https://img.shields.io/badge/Platform-iOS-lightgrey.svg)

An interactive iOS application module designed to set up and manage user profiles for the upcoming **AI Career Mentor** platform. This foundational screen allows users to input their data, track their coding proficiency, and indicate their job market readiness.

## 📸 Interface Preview
<img width="361" height="746" alt="Снимок экрана 2026-04-09 в 09 40 17" src="https://github.com/user-attachments/assets/84d3ebaa-d979-4cf6-b6fc-d47d53fbf7a8" />

## ✨ Core Features (Current State)
* **Dynamic Profile Card:** A responsive UI card that instantly updates based on user input, utilizing SwiftUI's declarative syntax.
* **Skill Tracker:** Interactive stepper logic built with custom buttons to increment or decrement the user's Swift programming level.
* **Status Toggle:** A real-time toggle switch that changes the visual state of the profile (updating SF Symbols and colors) to reflect if the user is actively looking for a job.
* **Clean UI/UX:** Implemented a modern, card-based design with proper shadows, corner radius, and safe area management against a system-grouped background.

## 🛠 Technical Implementation
This view is built entirely with **SwiftUI**, demonstrating a solid understanding of modern iOS state management and layout structuring:
* **State Management:** Heavy use of `@State` property wrappers (`name`, `codingLevel`, `isReadyForWork`) to ensure the UI remains perfectly synced with the underlying data.
* **Declarative Layouts:** Deep nesting of `ZStack`, `VStack`, and `HStack` to achieve a clean, modular visual hierarchy.
* **Adaptive Styling:** Usage of dynamic colors (`UIColor.systemGroupedBackground`) and SF Symbols that adapt to user interaction.

## 🚀 Future Roadmap
* Integrate CoreData / UserDefaults for persistent data storage.
* Connect to an external API (OpenAI) to generate personalized career advice based on the `codingLevel` and `isReadyForWork` status.
* Implement NavigationStack for transitioning to the AI Chat interface.
