# Hospital Management System

## Overview
The Hospital Management System is a comprehensive application designed to manage various operations in a hospital. It includes functionalities for managing patients, doctors, departments, appointments, and medical records. The system is built using Python with a Tkinter GUI and MySQL as the database.

## Features
- **Patient Management:** Add, update, view, search, and delete patient records.
- **Doctor Management:** Add, update, view, search, and delete doctor records.
- **Department Management:** Manage different departments within the hospital.
- **Appointment Scheduling:** Schedule, view, and manage patient appointments with doctors.
- **Medical Records:** Maintain detailed medical records for each patient.
- **User Authentication:** Secure login system for hospital staff.

## Installation

### Prerequisites
- Python 3.x
- MySQL

### Steps
1. **Clone the repository:**
    ```sh
    git clone https://github.com/yourusername/hospital-management-system.git
    cd hospital-management-system
    ```

2. **Install required Python packages:**
    ```sh
    pip install -r requirements.txt
    ```

3. **Setup MySQL database:**
    - Create a new MySQL database.
    - Run the provided SQL script to create necessary tables:
      ```sh
      mysql -u yourusername -p yourpassword yourdatabase < database_setup.sql
      ```

4. **Configure database connection:**
    - Update the database configuration in `config.py`:
    ```python
    db_config = {
        'user': 'yourusername',
        'password': 'yourpassword',
        'host': 'localhost',
        'database': 'yourdatabase'
    }
    ```

5. **Run the application:**
    ```sh
    python main.py
    ```

## Usage
1. **Login:**
    - Use your staff credentials to log in.
2. **Navigate:**
    - Use the menu to navigate through different sections like Patients, Doctors, Departments, Appointments, and Medical Records.
3. **Perform Operations:**
    - Add, update, search, and delete records as needed.

## Screenshots
![Login Screen](screenshots/login_screen.png)
![Dashboard](screenshots/dashboard.png)
![Patient Management](screenshots/patient_management.png)

## Contributing
1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/YourFeature`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Open a pull request.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact
For any questions or inquiries, please contact [your email address].

