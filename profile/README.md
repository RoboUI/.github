<p align="center">
  <a href="https://roboui.dev">
    <img src="https://roboui.dev/icons/icon-256.png" width="100" height="100" alt="RoboUI">
  </a>
</p>

<h2 align="center">Build robot apps. Not robot UI.</h2>

<p align="center">
  Open-source SDK for building native robot control apps.<br>
  Joystick, LiDAR, video, telemetry — drop in and ship. iOS + Android.
</p>

<p align="center">
  <a href="https://roboui.dev"><strong>roboui.dev</strong></a> · 
  <a href="https://github.com/RoboUI/roboui-ios">iOS SDK</a> · 
  <a href="https://github.com/RoboUI/roboui-android">Android SDK</a> · 
  <a href="mailto:hello@roboui.dev">Contact</a>
</p>

---

### 📦 Repositories

| Repo | Description | Status |
|------|-------------|--------|
| **[roboui-ios](https://github.com/RoboUI/roboui-ios)** | Swift SDK — SwiftUI components for ROS2 | ✅ Alpha |
| **[roboui-android](https://github.com/RoboUI/roboui-android)** | Kotlin SDK — Compose components for ROS2 | 🗓️ Coming soon |
| **[roboui.dev](https://github.com/RoboUI/roboui.dev)** | Landing page | 🌐 Live |

### 🚀 Quick Start (iOS)

```swift
import RoboUI

let connection = RosbridgeConnection(url: URL(string: "ws://robot.local:9090")!)
connection.connect()

// That's it. Now use JoystickView, LaserScanView, TwistPublisher...
```

### 🤝 Get Involved

- ⭐ Star the repo if this is useful
- 🐛 [Open an issue](https://github.com/RoboUI/roboui-ios/issues) for bugs or feature requests
- 📧 [hello@roboui.dev](mailto:hello@roboui.dev) for partnerships
- 📝 [Join the waitlist](https://roboui.dev) for early access to RoboUI App
