## Recipe App — Reactive Flutter Mobile Application
A high-performance, cross-platform mobile application built with Flutter, focused on delivering a seamless culinary discovery experience with reactive state management.

[Live Demo](https://github.com/kenneth183721/recipe-project)
- This is a Flutter mobile app project.
- Please reduce the width of the browser to simulate viewing at a phone scale.

## 🚀 Project Overview
This project showcases the implementation of a modern mobile UI using Flutter and Dart. The goal was to build a highly responsive recipe explorer that handles complex user preferences (Favorites & Filtering) without compromising performance. By utilizing Riverpod, the app achieves a clean separation of concerns between business logic and the UI layer.

## 🛠 Tech Stack
- Framework: Flutter (Dart).
- State Management: flutter_riverpod (Scalable, reactive state handling).
- UI Philosophy: Material Design 3 / Adaptive Layouts.

## 💡 Key Engineering Highlights
- Reactive State Management with Riverpod: Implemented a robust state architecture using Riverpod. This allows for efficient data flow across the app, ensuring that "Favorite" status updates are instantly reflected across different screens (e.g., Category View and Favorites Tab) without unnecessary rebuilds.
- Dynamic Multi-Criteria Filtering: Developed a sophisticated filtering engine that allows users to narrow down recipes based on dietary requirements (e.g., Gluten-free, Vegan). The logic is encapsulated within Riverpod Providers, ensuring the UI reactively updates as users toggle filter settings.
- Performance-Driven UI: Leveraged Flutter’s efficient rendering engine to implement smooth transitions and list animations. 
- Clean Architecture: Structured the code into distinct layers (Models, Providers, Widgets) to ensure scalability. This modular approach makes the codebase easy to test and maintain, reflecting professional software engineering practices.
