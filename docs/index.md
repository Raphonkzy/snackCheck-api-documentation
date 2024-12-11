# snackCheck API Documentation

The SnackCheck API is a web service that enables interaction with various features of the SnackCheck project. It employs bearer token authentication to ensure secure access to its endpoints. To use the API, you must first obtain a bearer token by logging in with valid credentials. This token must then be included in the Authorization header of each API request.

The SnackCheck API provides the following key functionalities:

- **User Management**: Facilitates user registration, login, and profile management.
- **Snack Management**: Allows users to create prediction, view histories, and search history by id.

To interact with the API, send HTTP requests to the relevant endpoints, including the necessary parameters and the bearer token in the header. Responses are provided in JSON format, containing either the requested data or error messages.

Ensure the bearer token is included in the header of all requests requiring authentication to securely access the available features. For detailed information about endpoints, request parameters, and response structures, refer to the API documentation. Note that unauthorized usage or misuse of the SnackCheck API will be addressed accordingly.

---

#Base URL

1. Base URL for all API endpoints: ```https://backend-dot-capstone-snackcheck.et.r.appspot.com```
2. Base URL for snack: ```https://backend-dot-capstone-snackcheck.et.r.appspot.com/snack```
3. Base URL for accounts: ```https://backend-dot-capstone-snackcheck.et.r.appspot.com/auth```
4. Base URL for profile: ```https://backend-dot-capstone-snackcheck.et.r.appspot.com/profile```
5. Base URL for machine learning: ```https://ml-api-711542614177.asia-southeast2.run.app```

---

# List of Contents

1. Related to user account
    - [/register](Account/register.md)
    - [/accounts](Account/accounts.md)
    - [/login](Account/login.md)
    - [/password](Account/password.md)
    - [/token](Account/token.md)
    - [/logout](Account/logout.md)

2. Related to user profile
    - [/photo](Profile/photo.md)
    - [/fullname](Profile/fullname.md)
    - [/profile](Profile/profile.md)
    
3. Related to app features
    - [/predicts](Snack/predicts.md)
    - [/histories](Snack/histories.md)



