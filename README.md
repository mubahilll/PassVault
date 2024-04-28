# PassVault = Password Management System

PassVault is a simple web application built using Django, a high-level Python web framework. It provides user authentication functionality along with account activation via email.

## Features

- **User Signup:** Users can create an account by providing a username, first name, last name, email address, and password. Password **strength validation** is implemented to ensure a secure password.
- **User Signin:** Registered users can sign in using their credentials.
- **Account Activation:** Upon signup, users receive an activation email with a unique link. Clicking the link activates their account.
- **User Signout:** Users can securely sign out of their accounts.
- **User Interface:** The application provides a clean and intuitive user interface for a seamless user experience.

## Installation

1. Clone the repository:

```bash
git clone https://github.com/your_username/my-app.git
```
2. Install the required dependencies:
```bash
pip install -r requirements.txt
```
3. Set up the database by running migrations:
```bash
python manage.py migrate
```
4. Create a superuser for administrative tasks:
```bash
python manage.py createsuperuser
```
5. Start the development server:
```bash
python manage.py runserver
```
6. Access the application in your web browser at http://localhost:8000/
## Configuration
* Email Settings: Configure the email settings in the **info.py** file to enable account activation emails. Update the `EMAIL_HOST`, `EMAIL_HOST_USER`, and `EMAIL_HOST_PASSWORD` variables with your **SMTP** server details.
## Usage
* Visit http://localhost:8000/signup to create a new account.
* After signup, check your email for the activation link.
* Sign in with your credentials at http://localhost:8000/signin.
* Enjoy using PassVault!

## Contributing
Contributions are welcome! If you have any ideas for improvement or find any issues, feel free to open an issue or submit a pull request.

```
Feel free to customize it according to your project's specific details and requirements!
```

## License
This project is licensed under the MIT License. See the LICENSE file for details.





