# Meeting Scheduling App

## Overview
The Meeting Scheduling App is a Laravel-based application designed to facilitate the scheduling of meetings. It provides a user-friendly interface for users to create, manage, and organize meetings efficiently.

## Features
- User authentication and authorization
- Create, update, and delete meetings
- View scheduled meetings in a calendar format
- Notifications and reminders for upcoming meetings
- Integration with email services for sending invites

## Project Structure
The project follows the standard Laravel directory structure:

- **app/**: Contains the core application logic, including models, controllers, and middleware.
- **bootstrap/**: Contains files for bootstrapping the application.
- **config/**: Contains configuration files for various services and settings.
- **database/**: Contains migration, factory, and seeder files for database management.
- **public/**: Contains publicly accessible files such as CSS, JavaScript, and images.
- **resources/**: Contains views, language files, and assets for the application.
- **routes/**: Contains route definitions for the application.
- **storage/**: Contains files generated by the application, such as logs and cached files.
- **tests/**: Contains feature and unit tests for the application.

## Installation
1. Clone the repository:
   ```
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```
   cd meeting-scheduling-app
   ```
3. Install dependencies:
   ```
   composer install
   npm install
   ```
4. Copy the `.env.example` file to `.env` and configure your environment settings:
   ```
   cp .env.example .env
   ```
5. Generate the application key:
   ```
   php artisan key:generate
   ```
6. Run migrations to set up the database:
   ```
   php artisan migrate
   ```
7. Start the development server:
   ```
   php artisan serve
   ```

## Usage
Once the application is running, you can access it at `http://localhost:8000`. Users can register, log in, and start scheduling meetings.

## Contributing
Contributions are welcome! Please submit a pull request or open an issue for any suggestions or improvements.

## License
This project is licensed under the MIT License. See the LICENSE file for details.