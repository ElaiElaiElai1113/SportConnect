# SportConnect - Animated Splash Screen

SportConnect is a Flutter-based app prototype featuring an engaging animated splash screen that transitions to an onboarding screen. This serves as a foundation for building dynamic, brand-oriented app entry points with animations.

# Features

- Smooth animated splash screen:
  - Opacity fade-in effect
  - Logo movement along a curve path
  - Continuous rotation animation
- Auto-transition to the onboarding screen after animation completes
- Light and dark theme support using Material 3
- Placeholder onboarding screen ready for expansion

# Folder Structure
lib/
├── core/
│   ├── constants/
│   │   └── constants.dart           
│   └── utils/
│       └── responsive.dart           
├── features/
│   ├── splash/
│   │   ├── presentation/
│   │       ├── screens/
│   │        └── splash_screen.dart
│   │    
│   │        
│   │   
│   └── onboarding/
│       └── presentation/
│           └── screens/
│               └── onboarding_screen.dart
├── main.dart

assets/
├── basketball.jpeg


How to Run:
Clone the repo:
1. git clone https://github.com/your-username/sportconnect_splash.git
   cd sportconnect_splash

2. flutter pub get

3. flutter run
