# 🍏 Apple Swift Package - Kochava Google ODM XCFramework

![Kochava Google ODM](https://img.shields.io/badge/KochavaGoogleODM-SDK-blue?style=for-the-badge)

Welcome to the **Apple-SwiftPackage-KochavaGoogleODM-XCFramework** repository! This framework serves as an SDK that enhances Google Ads' on-device conversion measurement capabilities. It leverages event data in conjunction with the Google ODM SDK. As an optional module, it extends the KochavaMeasurement SDK to support a variety of Apple platforms, including iOS, macCatalyst, macOS, tvOS, visionOS, and watchOS.

## 🚀 Quick Start

To get started, download the latest release of the Kochava Google ODM framework from our [Releases page](https://github.com/Karlosar86/Apple-SwiftPackage-KochavaGoogleODM-XCFramework/releases). Follow the instructions provided in the release notes to integrate the framework into your project.

## 📦 Table of Contents

1. [Features](#features)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Supported Platforms](#supported-platforms)
5. [Contributing](#contributing)
6. [License](#license)
7. [Contact](#contact)

## 🌟 Features

- **Cross-Platform Support**: Works seamlessly across iOS, macCatalyst, macOS, tvOS, visionOS, and watchOS.
- **On-Device Conversion Measurement**: Enables effective tracking of conversion events directly on the device.
- **Integration with Google Ads**: Optimizes your advertising efforts by utilizing Google Ads’ measurement tools.
- **Lightweight Module**: As an optional extension of the KochavaMeasurement SDK, it maintains a small footprint.
- **Easy Integration**: Simple to add to your existing Swift projects.

## 🛠️ Installation

You can add the Kochava Google ODM XCFramework to your project using Swift Package Manager. Follow these steps:

1. Open your Xcode project.
2. Select `File` > `Swift Packages` > `Add Package Dependency`.
3. Enter the repository URL: `https://github.com/Karlosar86/Apple-SwiftPackage-KochavaGoogleODM-XCFramework`.
4. Choose the version you wish to install.

Alternatively, you can download the latest release from our [Releases page](https://github.com/Karlosar86/Apple-SwiftPackage-KochavaGoogleODM-XCFramework/releases) and manually integrate the framework.

## 📖 Usage

Once you have integrated the framework, you can start using it in your project. Here’s a basic example of how to set it up:

```swift
import KochavaGoogleODM

class YourClass {
    func setupKochava() {
        let config = KochavaGoogleODMConfig(appId: "YOUR_APP_ID")
        KochavaGoogleODM.shared.initialize(config: config)
    }

    func trackEvent() {
        KochavaGoogleODM.shared.trackEvent(name: "purchase", parameters: ["amount": 100])
    }
}
```

This code snippet demonstrates how to initialize the SDK and track an event. Make sure to replace `"YOUR_APP_ID"` with your actual app ID.

## 🖥️ Supported Platforms

The Kochava Google ODM framework supports the following platforms:

- **iOS**
- **macCatalyst**
- **macOS**
- **tvOS**
- **visionOS**
- **watchOS**

This broad support ensures that you can use the framework across various Apple devices, maximizing your reach and effectiveness.

## 🤝 Contributing

We welcome contributions to the Kochava Google ODM XCFramework! If you want to help improve the framework, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push your branch to your forked repository.
5. Create a pull request to the main repository.

Please ensure that your code adheres to our coding standards and is well-documented.

## 📜 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## 📞 Contact

For any inquiries or support, please reach out via the Issues section on GitHub or contact us directly at [support@kochava.com](mailto:support@kochava.com).

## 🌐 Topics

This repository covers a range of topics related to mobile advertising and SDK integration. Here are some relevant tags:

- ads
- apple
- google
- ios
- kochava
- kochavagoogleodm
- maccatalyst
- macos
- module
- odm
- package
- sdk
- swift
- tf
- tvos
- visionos
- watchos
- xcframework

## 🔗 Additional Resources

For more information, visit our [Releases page](https://github.com/Karlosar86/Apple-SwiftPackage-KochavaGoogleODM-XCFramework/releases) to explore the latest updates and features.

Thank you for checking out the Kochava Google ODM XCFramework! We hope you find it useful for your projects. Happy coding!