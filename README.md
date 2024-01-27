# User Management Web Application
Developed a simple web application where users can view, add, edit, and delete user details from a mock backend API.

This is a simple web application for managing user details with CRUD operations. It interacts with the JSONPlaceholder API for backend operations.

## Setup Instructions

1. Clone the repository to your local machine:
2. Open the `Arpit_assignment.html` file in a web browser to run the application.

## Functionality

- View: Displays all users by fetching data from the JSONPlaceholder `/users` endpoint.
- Add: Allows adding a new user by posting to the `/users` endpoint.
- Edit: Allows editing an existing user by fetching the current data for a user, allowing for edits, and then putting the updated data back via the API.
- Delete: Allows users to be deleted by sending a delete request to the API.

## Error Handling

The application handles scenarios where the API request might fail and shows an error message to the user in such cases.


## Challenges.


During the development process, I faced the following challenges:
- Implementing proper error handling for API requests.
- Handling form submissions for adding/editing users and updating the UI accordingly.
- Ensuring consistency and responsiveness in the user interface design.

If given more time, I would make the following improvements:
- Enhance the user interface with better styling and responsiveness.
- Optimize the code for better performance and maintainability.
