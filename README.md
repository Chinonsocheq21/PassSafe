# PassSafeApp

A secure password manager built with Swift and SwiftUI.

## Objective
The goal of this project was to create a password management app that:
- Secures access with a PIN stored in the Keychain.
- Encrypts passwords using CryptoKit and stores them in a JSON file.
- Requires biometric authentication (Face ID/Touch ID) to view passwords.
- Simulates email notifications for saved passwords with email addresses.

## Procedure
1. Set up an Xcode project with SwiftUI views for PIN entry, home screen, adding passwords, and viewing details.
2. Implemented Keychain for PIN storage and CryptoKit for password encryption.
3. Added biometric authentication using LocalAuthentication.
4. Simulated email notifications with alerts.
5. Troubleshot errors like missing types and scope issues.

## Errors Encountered
- "Cannot find 'PasswordEntry' in scope" (fixed with proper imports).
- "Missing argument for parameter 'id'" (fixed with default UUID).
- "Cannot find 'EncryptionManager' in scope" (fixed with target membership).

## Technologies Used
- **Swift**: Programming language.
- **SwiftUI**: UI framework.
- **Foundation**: For UUID and file management.
- **CryptoKit**: For encryption.
- **Security**: For Keychain.
- **LocalAuthentication**: For biometric authentication.

## How to Run
1. Clone the repository: `git clone https://github.com/yourusername/PassSafe.git`.
2. Open in Xcode.
3. Build and run on the iOS Simulator or a device with biometric support.

## Learning Journey
This project was built as a learning exercise for a beginner in Swift. Resources used include:
- Apple's SwiftUI Tutorials.
- Hacking with Swift (100 Days of SwiftUI).
- Kodeco's Swift Apprentice.

## Future Improvements
- Add a "Copy to Clipboard" button.
- Integrate a real email notification service (e.g., Mailgun).
- Enhance UI with custom designs.# PassSafe

