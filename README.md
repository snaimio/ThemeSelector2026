<div align="center">

# 🎨 ThemeSelector
### SwiftUI Dynamic Theming & AppStorage Persistence Engine

[![iOS](https://img.shields.io/badge/iOS-17.0%2B-000000?style=for-the-badge&logo=apple&logoColor=white)](https://developer.apple.com/ios/)
[![Swift](https://img.shields.io/badge/Swift-5.9%2B-F05138?style=for-the-badge&logo=swift&logoColor=white)](https://swift.org/)
[![SwiftUI](https://img.shields.io/badge/UI-SwiftUI-0071E3?style=for-the-badge&logo=swift&logoColor=white)](https://developer.apple.com/xcode/swiftui/)
[![Persistence](https://img.shields.io/badge/State-@AppStorage-FF2D55?style=for-the-badge)](https://developer.apple.com/)
[![License](https://img.shields.io/badge/License-MIT-CEFF00?style=for-the-badge&logoColor=black)](LICENSE)

<br/>

**A lightweight iOS theme and design system engine built with SwiftUI and `@AppStorage` for real-time dynamic color scheme switching and persistent user preferences.**

</div>

<br/>

---

## 📌 Technical Overview
**ThemeSelector** provides a clean architecture for managing application-wide themes, accent colors, and dark/light modes. It demonstrates type-safe settings persistence with `@AppStorage` and unit-tested preference stores.

### 💼 Technical Highlights
- **Type-Safe Settings Architecture**: Centralized key definitions (`SettingsKeys.swift`) and observable stores (`Settings.swift`).
- **Dynamic SwiftUI Environment Injection**: Propagates active color tokens seamlessly across the entire view hierarchy.
- **Unit & UI Test Suites**: Comprehensive test coverage verifying persistence across app restarts.

---

## 🚀 Setup & Run
1. Clone the repository:
   ```bash
   git clone https://github.com/snaimio/ThemeSelector2026.git
   cd ThemeSelector2026
   open ThemeSelector2026.xcodeproj
   ```
2. Build and run via Xcode (`⌘ + R`).

---

## 📄 License
This project is licensed under the [MIT License](LICENSE).

---

## 👨‍💻 Author
**Sheikh Naim**  
*Mobile & Full-Stack Web Developer*  
- **LinkedIn**: [linkedin.com/in/snaimio](https://www.linkedin.com/in/snaimio)  
- **GitHub**: [@snaimio](https://github.com/snaimio)  
- **Portfolio**: [snaimio.github.io](https://snaimio.github.io)
