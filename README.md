# SafetyNow — Android Emergency SOS Application

*(Note: The original source code for this project was lost due to a hardware failure. The fully functional application has been extracted from hardware, verified, and preserved as a downloadable release below.)*

## 🛡️ Overview
SafetyNow is a native Android emergency utility built to streamline communications during critical, high-stress situations. The application operates entirely client-side, allowing users to store a medical profile locally, manage a dedicated list of emergency contacts, and dispatch location-verified distress signals instantly with a single tap.

## 📱 Application Demo
*(Drag and drop your screen recording or a converted .gif file right here in the GitHub browser editor to display it automatically)*

## ✨ Key Features Shown in Video

*   **Local Medical Profile Registry:** Houses essential personal data directly on the device—including Full Name, Age, Blood Group, Allergies, and underlying Medical Conditions—ensuring critical reference data is securely stored.
*   **Dynamic Contact Dashboard:** Integrates a custom modal dialog interface allowing users to dynamically populate, store, and manage custom emergency phone entries (e.g., family, medical services).
*   **Intuitive Lifecycle Gestures:** Implements clear user flow utilities, including single-tap triggers, instant notification state updates, and long-press event handlers to safely remove contacts via confirmation prompts.
*   **One-Tap SOS Emergency Broadcast:** A high-visibility, single-action button optimized for emergency conditions. Pressing it immediately loops through all verified contacts and dispatches a multi-channel alert.
*   **Google Maps Location Link Integration:** Automatically parses precise hardware GPS coordinates into the broadcast string, packaging a live, clickable Google Maps tracking URL (`https://maps.google.com/?q=latitude,longitude`) straight into the automated SMS array.
*   **Dedicated Sandbox Verification:** Features an explicit "Test SMS" routine allowing users to safely validate network delivery constraints and background messaging syntax without triggering a real-world emergency event.

## 🛠️ Technical Stack & Architecture
*   **Core Development Language:** Java
*   **Interface Layout Engine:** Native Android XML (utilizing responsive material design fields, toast alerts, and modal dialog fragments)
*   **Framework System:** Android SDK
*   **Hardware Integration Layer:**
    *   `SmsManager` API (Handles programmatic background text payload execution)
    *   `LocationServices` API / GPS Module (Fetches real-time geographical coordinates)

## 📥 Download & Deployment
The pre-compiled standalone app binary is ready for testing.
1. Head over to the **[Releases](../../releases)** sidebar menu of this repository.
2. Download the `SafetyNow.apk` package directly to your computer or Android device.
3. Open the file on your device to execute installation. *(Note: Ensure "Install Unknown Apps" or sideloading configurations are temporarily permitted inside your Android system settings).*
