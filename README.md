Flutter Retrofit Example

This project demonstrates how to create a simple Flutter application with REST API integration using the Retrofit package.


Description

This project is a basic implementation of a Retrofit client in Flutter. It simplifies API integration and reduces boilerplate code by using dependency injection. The app fetches data from a REST API and displays it in the UI.



Features

Fetches data using Retrofit and Dio.

Generates data model and API service files using build_runner.

Simplifies data handling with dependency injection.


Dependencies

The following packages are used in the project:

retrofit: ^5.1.1

dio: ^5.1.0

json_annotation: ^4.8.1

build_runner: ^2.4.6 (dev dependency for code generation)


Steps to Run

1. Clone the Repository

git clone <repository-url>
cd retrofit_example


2. Install Dependencies
Run the following command to install the required dependencies:

flutter pub get


3. Generate Files
Use the build_runner to generate necessary files:

flutter pub run build_runner build


4. Run the App
Launch the application:

flutter run


File Structure

lib/

main.dart - Entry point of the application.

api_service.dart - Contains Retrofit interface for API calls.

post.dart - Defines the data model for posts.

home_page.dart - Displays the fetched data in a simple UI.





API Used

The app uses the JSONPlaceholder fake online REST API to fetch sample data.


Conclusion

This project demonstrates how to use Retrofit in Flutter to simplify REST API integration. It's a great starting point for more complex applications that require robust API handling with minimal boilerplate code.

