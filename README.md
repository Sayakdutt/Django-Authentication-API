
# Authentication API with Django Rest Framework and Simple JWT

This project is an Authentication API built with Django Rest Framework and Simple JWT. It includes features such as user registration, custom user model login, password change, and password reset through email. The API uses Simple JWT for token authentication.
## Features

- Custom User registration
- Custom user model login
- Password change for authenticated users
- Password reset through email
- Simple JWT token authentication


## API Reference


| URL | Method    | Description                |
| :-------- | :------- | :------------------------- |
| `api/user/register/` | `POST` | **Register a new user** 
| `api/user/login/`      | `POST` | **User login with a proper credentials and authentication token** |
| `api/user/profile/`      | `GET` | **Displays profile page** |
| `api/user/changepassword/`      | `POST` | **Changes User password** |
| `api/user/send-reset-password-email/`      | `POST` | **Sends the reset password email** |
| `api/user/reset-password/<uidb64>/<token>/`      | `POST` | **url for the changing the password** |








## Contributing

Contributions are welcome. Please fork the repository and create a new branch for your feature or bug fix. Once you have made your changes, submit a pull request and your changes will be reviewed.

