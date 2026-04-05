# social_helper_app

### Project Structure

Here is how our project is organized. You will find the main source code in the `lib` folder, while platform-specific files are neatly tucked away in their own folders.

```text
social_helper_app/
├── android/            # Android-specific code and configuration
├── ios/                # iOS-specific code and configuration
├── lib/                # The heart of the app (Dart source code)
│   ├── core/           # Shared helpers, routing, and theme settings
│   └── features/       # Individual app features (like on-boarding)
├── web/                # Web app assets and entry point
├── windows/            # Windows desktop support
├── macos/              # macOS desktop support
├── linux/              # Linux desktop support
├── test/               # Folder for your widget and unit tests
├── pubspec.yaml        # Project dependencies and settings
└── README.md           # You are reading this right now!
```

#### Key Directories:
- **`lib/`**: This is where you will spend most of your time. 
    - `core/`: Contains reusable logic like theme styles, navigation routes, and helper extensions.
    - `features/`: Keeps your app organized by grouping code based on specific features, making it easier to scale as the app grows.
- **`android/` & `ios/`**: These folders contain the native setup for mobile devices. You generally don't need to touch these unless you are configuring native permissions or icons.
