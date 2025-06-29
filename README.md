# Reflect

Minimal daily journaling app with AI-powered weekly insights

## ✨ Overview

Reflect makes journaling effortless. Write just one sentence about your day, track your habits, and capture a photo. Every week, get personalized AI summaries of your progress and memories.

## 🎯 Features

- **One-sentence entries** - Capture your day without pressure
- **Habit tracking** - Simple visual indicators for daily habits
- **Photo memories** - Add images to bring entries to life
- **AI weekly insights** - Smart summaries of your progress and patterns
- **Beautiful timeline** - Organized by weeks and months
- **Privacy-first** - All data stored locally on your device

## 📱 Screenshots

*Coming soon*

## 🛠 Tech Stack

- **SwiftUI** - Modern iOS interface
- **Swift Observation** - Reactive data binding
- **PropertyList** - Local data persistence
- **FileManager** - Image storage management
- **AI Integration** - Weekly insight generation

## 🏗 Architecture

```
Reflect/
├── Models/
│   └── LocalEntry.swift          # Core data model
├── ViewModels/
│   ├── EntryViewModel.swift      # Data management
│   └── JournalPresentationViewModel.swift  # Display logic
├── Views/
│   ├── JournalView.swift         # Main timeline
│   ├── NewEntryView.swift        # Entry creation
│   ├── EntryListElement.swift    # List item component
│   └── WelcomeSheet.swift        # Onboarding
└── Utils/
    └── ImagePicker.swift         # Photo selection
```

## 🚀 Getting Started

### Prerequisites

- iOS 17.0+
- Xcode 15.0+
- Swift 5.9+

### Installation

1. Clone the repository
```bash
git clone https://github.com/yourusername/reflect.git
```

2. Open in Xcode
```bash
cd reflect
open Reflect.xcodeproj
```

3. Build and run on your device or simulator

## 💾 Data Storage

Reflect uses a privacy-first approach:

- **Entries**: Stored as PropertyList files in app's Documents directory
- **Images**: Saved locally in dedicated Images folder
- **No cloud sync**: Your data stays on your device

## ⚡ AI Features

Weekly AI insights analyze:
- Habit completion patterns
- Mood trends from your entries
- Photo memory highlights
- Progress celebrations
- Gentle suggestions for improvement

## 🎨 Design Philosophy

- **Minimal friction** - Write in seconds, not minutes
- **Beautiful simplicity** - Clean, focused interface
- **Consistent habits** - Small daily actions, big long-term impact
- **Mindful reflection** - Quality over quantity

## 🛣 Roadmap

- [ ] Export functionality
- [ ] Apple Watch companion
- [ ] Enhanced AI insights
- [ ] Mood tracking integration
- [ ] Search and filtering
- [ ] Custom habit creation
- [ ] Dark mode improvements

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👤 Authors

**Lovis Steinmayer**
**Carl Liesener**
**Jacob Sauter**
**Robin Thuorow**
