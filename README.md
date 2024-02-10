# GitHub Profile Viewer

This project is a simple web application built using AngularJS (version 1.x) to fetch and display information about a GitHub user's profile and repositories. Users can input a GitHub username, click on the "Get Profile" button, and view details such as the user's avatar, GitHub ID, name, bio, followers, public repositories, and a list of repositories with their names, descriptions, and star counts.

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/github-profile-viewer.git
   ```

2. Open the `index.html` file in your web browser.

3. Enter a GitHub username in the input field and click the "Get Profile" button.

4. View the user's profile information and a list of repositories.

## Project Structure

- `index.html`: The main HTML file that contains the structure of the web page.
- `styles.css`: The CSS file that provides styling for the web page.
- `angular.min.js`: AngularJS library for handling dynamic content and making HTTP requests.
- `README.md`: Documentation providing information about the project.

## File Descriptions

- `index.html`: Defines the structure of the web page, including input fields, buttons, and areas to display profile and repository information. Uses AngularJS for dynamic content.
- `styles.css`: Contains styles for various elements on the web page, enhancing the visual appeal and readability.
- `angular.min.js`: The AngularJS library for enabling dynamic behavior and making HTTP requests to the GitHub API.
- `README.md`: This documentation file providing information about the project, its usage, and file descriptions.

## How it Works

1. Users input a GitHub username in the designated field.

2. Upon clicking the "Get Profile" button, the application makes an HTTP request to the GitHub API to fetch the user's profile information.

3. If the profile is found, the user's avatar, GitHub ID, name, bio, followers, and public repositories are displayed.

4. The application then fetches and displays a list of the user's repositories, including repository names, descriptions, and star counts.

5. In case of errors, such as a non-existent profile (404 status), appropriate error messages are displayed.

## Images 
#### Succesful Output
![Successful](https://github.com/Surajrs812/Github-profile-viewer/assets/118114735/eb2bf078-96c0-4820-8aff-4e67994a9b9a)

#### Error Message
![Error](https://github.com/Surajrs812/Github-profile-viewer/assets/118114735/1a19a76e-ffd7-408b-b603-913a8f7c21e2)

