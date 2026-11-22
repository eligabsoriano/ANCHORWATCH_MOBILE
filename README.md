# AnchorWatch Mobile

## Overview

AnchorWatch Mobile is a cross-platform Flutter client for monitoring stablecoin and macro-financial data. It provides account authentication, a financial dashboard, charts and market insights, alert and notification management, maintenance status monitoring, support/contact tools, and real-time communication with the AnchorWatch backend.

The app follows a layered architecture with separate domain, data, presentation, routing, service, and utility layers. State is managed with BLoC, while dependency injection and repository implementations keep UI components separated from backend integrations.

## Tech Stack

- Flutter and Dart
- BLoC / Cubit with `flutter_bloc`
- Dio for REST API communication
- WebSocket channel support
- GetIt and Injectable for dependency injection
- Shared Preferences for local state
- Syncfusion Flutter Charts
- Image Picker and AWS S3 upload support
- Android, iOS, web, Windows, macOS, and Linux targets

## Key Features

- Secure registration, login, logout, password recovery, profile, and session management
- Stablecoin dashboard with supply, market, chart, and data-quality information
- Macro trends and financial chart summaries
- Price, volume, sentiment, anomaly, and system-health alerts
- Real-time alert updates through WebSockets
- Local email notifications and device notification support
- Maintenance-mode detection and monitoring
- Onboarding flow and responsive bottom navigation
- AnchorWise chat and conversation history
- FAQ, contact support, and feedback workflows
- Profile image selection and upload