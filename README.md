# User Registration

A sample project demonstrating database connectivity with phpMyAdmin from the XAMPP server, capable of performing CRUD operations.

## Table of Contents

- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Requirements

- XAMPP or any other web server with PHP and MySQL support
- phpMyAdmin
- Basic knowledge of PHP and SQL

## Installation

1. **Clone the repository:**
   ```sh
   git clone https://github.com/tagging-danger/user-registration.git
   

2. **Start XAMPP:**
   - Ensure Apache and MySQL are running.

3. **Database Setup:**
   - Open phpMyAdmin.
   - Create a new database called `user_registration`.
   - Import the `user_registration.sql` file from the `sql` directory into the database.

4. **Configure the project:**
   - Navigate to the project directory:
     ```sh
     cd user-registration
     
   - Open `phpcrud/config.php` and update the database configuration details if necessary.

## Usage

1. **Access the Project:**
   - Open a web browser and go to `http://localhost/user-registration`.

2. **Register a New User:**
   - Fill in the registration form and submit to add a new user to the database.

3. **Login:**
   - Use the credentials of a registered user to log in.

4. **Perform CRUD Operations:**
   - After logging in, you can create, read, update, and delete user records.

## Contributing

Contributions are welcome! Follow these steps to contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a pull request.

## License

Distributed under the MIT License. See `LICENSE` for more information.

Project Link: [https://github.com/tagging-danger/user-registration](https://github.com/tagging-danger/user-registration)
