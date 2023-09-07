
# Currency convertor

This repository is a demonstration project that showcases various aspects of mobile app development using Flutter. It provides examples of working with APIs, implementing state management using the Flutter_Bloc library (with a Cubit-based approach), and adhering to a clean architecture with a clear separation of layers: UI (pages and widgets), Business Logic (Cubits and Services), Repositories, and Data (models, API, local database).

## Features

- **API Integration**: The project demonstrates how to interact with external APIs, making network requests, and handling responses effectively.

- **State Management**: It showcases the use of the Flutter_Bloc library, emphasizing the Cubit pattern for managing app state.

- **Clean Architecture**: The codebase follows a clean architecture approach, ensuring a clear separation of concerns and making it easier to maintain and scale the project.

- **Local Database**: As an example, the project includes the implementation of a local database using sembast, a NoSQL database library for Flutter.

## Project Structure

The repository is organized into the following key directories:

- **UI**: Contains Flutter widgets and pages for the user interface.

- **Business Logic**: Includes Cubits and Services responsible for handling the app's business logic.

- **Repositories**: Manages data retrieval and storage operations, acting as an intermediary between the data sources and the application.

- **Data**: Houses data-related components, such as models, API communication, and local database management.

## Getting Started

To get started with this project, follow these steps:

1. Clone the repository to your local machine.
2. Ensure you have Flutter and Dart installed.
3. Navigate to the project directory.
4. Run `flutter pub get` to install dependencies.
5. Use your preferred IDE to run the app on an emulator or physical device.

## Contribution

Contributions are welcome! Feel free to fork this repository, create a branch, and submit a pull request with your improvements, bug fixes, or new features.

## License

This project is licensed under the [MIT License](LICENSE). Feel free to use it as a reference or a starting point for your own Flutter projects.

