# NotePoint Suite

[![License](https://img.shields.io/badge/license-GPL--3.0-blue.svg)](https://opensource.org/licenses/GPL-3.0)
[![GitHub Release](https://img.shields.io/github/v/release/noahchaney214/notepoint)](https://github.com/noahchaney214/notepoint/releases)

NotePoint Suite is a free, cross-platform, open-source, all-in-one information management suite made with Flutter, designed for a variety of tasks including note-taking, password management, PDF annotation, script programming, and more!

## Features

- **Note Taking:** Efficient and organized note-taking with Markdown support.
- **Password Management:** Securely store and manage your accounts and passwords.
- **PDF Annotation:** Annotate and mark up PDF documents seamlessly.
- **Script Programming:** Write and run script programs within the application (not available on iOS or Android).
- **Cross-Platform:** Works on Windows, macOS, Linux, iOS, and Android.

## Download the App

- [Google Play Store](https://play.google.com/store/apps/details?id=com.yourusername.notepoint) (not available yet)
- [iOS App Store](https://apps.apple.com/us/app/notepoint/idyourappid) (not available yet)

## Getting Started

### Prerequisites

- [Flutter](https://flutter.dev/) installed
- [Dart](https://dart.dev/) (Flutter's programming language)
- [Git](https://git-scm.com/) installed

### Installation

1. Clone the repository: `git clone https://github.com/yourusername/notepoint.git`
2. Navigate to the project directory: `cd notepoint`
3. Install dependencies: `flutter pub get`
4. Run the application: `flutter run`

For more detailed instructions, refer to the [Installation Guide](docs/installation.md).

## Usage

1. Launch NotePoint on your platform.
2. Explore the intuitive interface and start using the features.

For detailed usage instructions, please refer to the [User Documentation](docs/user-guide.md).

## Contributing

We welcome contributions! If you want to contribute to NotePoint, please follow our [Contribution Guidelines](CONTRIBUTING.md).

### Creating a Module

You can extend NotePoint's functionality by creating custom modules. Follow these steps to create and integrate a module into the app:

1. **Module Structure:**
   - Create a new Flutter project for your module, ensuring it follows a clear and organized structure.

2. **Dependency Integration:**
   - Add your module as a dependency in NotePoint's `pubspec.yaml` file.

   ```yaml
   dependencies:
     yourmodule:
       path: path/to/your/module

## License

This project is licensed under the GNU General Public License v3.0 - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Thanks to [Name] for their inspiring library/framework/tool that made this project possible.
- Special thanks to our contributors for their valuable efforts.

## Contact

For support, suggestions, or feedback, please email us at [email@example.com].

