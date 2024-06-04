# Hospital Management System

This project is a simple hospital management system developed in Java. It allows users to perform various tasks such as adding patients, viewing patients, viewing doctors, and booking appointments.

## Features

- Add new patients to the system with their name, age, and gender.
- View the list of patients currently registered in the system.
- View the list of doctors along with their specialization.
- Book appointments between patients and doctors on specified dates.

## Requirements

- Java Development Kit (JDK)
- MySQL Database Server
- JDBC Driver for MySQL (included)
- IDE or text editor for Java development (optional)

## Usage

1. Clone or download this repository to your local machine.
2. Ensure that you have Java and MySQL installed on your system.
3. Set up the MySQL database by importing the provided `hospital.sql` file.
4. Update the database connection settings in the `HospitalManagementSystem.java` file if necessary (username, password, database URL).
5. Compile the Java files using your preferred Java compiler or IDE.
6. Run the `HospitalManagementSystem` class to start the application.
7. Follow the on-screen prompts to perform various tasks within the hospital management system.

## Database Schema

The project uses a simple database schema with two tables:

1. `patients`: Stores information about patients, including their ID, name, age, and gender.
2. `doctors`: Stores information about doctors, including their ID, name, and specialization.
3. `appointments`: Stores information about appointments booked between patients and doctors, including the patient ID, doctor ID, and appointment date.

## Contributing

Contributions are welcome! If you find any bugs or have suggestions for improvements, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
