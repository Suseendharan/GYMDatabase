# Gym Management System

## Description
The Gym Management System is a web application developed using Flask, SQLAlchemy, and MySQL. It provides an efficient way to manage gym operations, including user authentication, member and trainer management, payment processing, and more.

## Key Features
- **User Authentication and Role-Based Access**: Secure login and registration for admins, trainers, and members with different access levels.
- **CRUD Operations**: Manage members, trainers, and specialities efficiently.
- **Payment Processing**: Handle membership payments and track payment history.
- **Specialities Management**: Trainers can add and manage their specialities.

## Technologies Used
- **Backend**: Flask, SQLAlchemy
- **Database**: MySQL
- **Frontend**: HTML, CSS

## Setup and Installation

1. **Clone the repository:**
    ```bash
    git clone https://github.com/Suseendharan/GYMDatabase/edit/main/GymMS-DbmsMP-master.git
    ```

2. **Create and activate a virtual environment:**
    ```bash
    python -m venv venv
    source venv/bin/activate   # On Windows, use `venv\Scripts\activate`
    ```

3. **Setup the database:**
    - Ensure MySQL is installed and running.
    - Update the database connection settings in `main.py`.

4. **Run the application:**
    ```bash
    python main.py
    ```

5. **Access the application:**
    - Open your web browser and go to `http://localhost:5000`.

## Usage
- **Admin Login**: Admins can log in to manage trainers, members, and view payment details.
- **Trainer Login**: Trainers can log in to manage their specialities and assigned members.
- **Member Login**: Members can log in to view their details, make payments, and see assigned trainers.

## Contributing
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a new Pull Request.

## License
This project is licensed under the MIT License.
