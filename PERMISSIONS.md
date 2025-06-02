# iOS Permission Usage Descriptions

Sample user-facing strings for all common iOS permissions.  
Pick one and adapt for your app, or use as inspiration!

---

## Camera

**Key:** `NSCameraUsageDescription`

- The app needs camera access to let you take photos for [specific feature].
- We need camera access so you can capture images for instant identification.
- Camera access is required to scan QR codes and add pictures to your notes.
- To take and share photos within the app, camera access is necessary.

---

## Photo Library

**Key:** `NSPhotoLibraryUsageDescription`

- The app needs access to your photo library so you can select pictures for upload or analysis.
- We need permission to access your photos so you can save images or share them with friends.
- Access is needed to allow you to pick images for your profile or posts.
- To select and upload images, photo library permission is required.

---

## Media Library (Apple Music)

**Key:** `NSAppleMusicUsageDescription`

- The app needs access to your media library so you can play your own music.
- We need permission to let you listen to your playlists while using the app.
- To add background music from your library, we require media access.

---

## Location

**Key:** `NSLocationWhenInUseUsageDescription` / `NSLocationAlwaysUsageDescription`

- The app needs your location to show nearby places and provide local recommendations.
- We need location access to map your walks and display saved locations.
- To deliver location-based features, access is used while the app is active.

**Temporary/Precise Location:**

- The app requires temporary access to your precise location to show relevant points of interest.
- We only use your location when necessary for [feature].

---

## Microphone

**Key:** `NSMicrophoneUsageDescription`

- The app needs microphone access to let you record audio messages.
- We need permission to capture audio for voice notes or chatting with friends.
- To use voice features, microphone access is required.

---

## Health & Fitness

**Keys:** `NSHealthShareUsageDescription`, `NSHealthUpdateUsageDescription`, `NSMotionUsageDescription`

- The app needs access to your health data to track workouts and provide insights.
- We need permission to read your activity to personalize your daily goals.
- Motion access is required to count your steps and log movement.

---

## Contacts

**Key:** `NSContactsUsageDescription`

- The app needs contact access to help you find friends already using the service.
- We need permission to suggest connections from your contacts.
- To invite friends and enhance your social experience, contact permission is required.

---

## Calendar

**Key:** `NSCalendarsUsageDescription`

- The app needs calendar access so you can create and view events within the app.
- We need permission to add reminders for your scheduled activities.
- Calendar permission is required to sync and notify you about upcoming events.

---

## Reminders

**Key:** `NSRemindersUsageDescription`

- The app needs your reminders to help you keep track of important tasks.
- We need permission to read and write reminders for personalized notifications.
- To integrate with your to-do list, reminder access is necessary.

---

## Bluetooth

**Key:** `NSBluetoothAlwaysUsageDescription`

- The app needs Bluetooth access to connect with nearby devices and accessories.
- We need permission to pair and sync with your wearable or smart device.
- Bluetooth permission is required to discover and use compatible hardware.

---

## Local Network

**Key:** `NSLocalNetworkUsageDescription`

- The app needs access to your local network to find and connect with devices nearby.
- We need permission to communicate with devices on your home network.
- Local network permission is required for device discovery and smart home integration.

---

## Speech Recognition

**Key:** `NSSpeechRecognitionUsageDescription`

- The app needs speech recognition so you can control features with your voice.
- We need permission to transcribe your spoken words into text for hands-free use.
- To provide voice commands and dictation, speech recognition access is required.

---

## Siri

**Key:** `NSSiriUsageDescription`

- The app needs Siri access so you can use voice commands and shortcuts.
- We need permission for Siri to complete tasks and retrieve information.
- Siri permission is required for hands-free and voice assistant features.

---

## Face ID

**Key:** `NSFaceIDUsageDescription`

- The app needs Face ID access to securely authenticate your identity and protect your information.
- We need permission to use Face ID for faster sign-in and enhanced security.
- Face ID permission is required for quick and secure login.

---

## Motion

**Key:** `NSMotionUsageDescription`

- The app needs motion access to count your steps and track activity levels.
- We need permission to log your daily movement and fitness activities.
- Motion data is required to provide accurate health and fitness tracking.

---

## Example Formatting

For each permission, add this key and your chosen description to your app’s Info.plist.

    <key>NSCameraUsageDescription</key>
    <string>The app needs camera access to let you take photos for [specific feature].</string>

---

PRs with improvements or new permissions are welcome!
