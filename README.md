-----

# Student Affairs Automation System

This project is a simple automation system designed to facilitate school-related operations for students and faculty members. Students can select courses, view their grades, and message their advisors, while faculty members can approve courses, enter grades, and communicate with students.

## Features

### Student Module

  * **Personal Information:** Displays student details (name, surname, ID, advisor, number of courses taken, overall GPA) and time spent in the system.
  * **Course Selection:** Allows students to choose from available courses and send their selections for advisor approval.
  * **Grade Viewing:** Students can view their grades for enrolled courses.
  * **Messaging:** Enables communication with other students and faculty members within the system.
  * **Settings:** Provides options to change password and user ID.

### Faculty Member Module

  * **Personal Information:** Displays faculty member details (name, surname, ID, number of advised students) and time spent in the system.
  * **Course Operations:** Faculty can approve or reject student course selection requests.
  * **Grade Entry:** Allows faculty to enter and update grades for their advised students' courses.
  * **Messaging:** Enables communication with students and other faculty members within the system.
  * **Settings:** Provides options to change password and user ID.

## Technologies

  * **Java**: The primary programming language for the project.
  * **Swing**: Used for building the graphical user interface (GUI).

## Installation

To run the project on your local machine, follow these steps:

1.  Clone the repository:
    ```bash
    git clone https://github.com/YOUR_USERNAME/OgrenciIsleriOtomasyonu.git
    ```
2.  Navigate to the project directory:
    ```bash
    cd OgrenciIsleriOtomasyonu
    ```
3.  Open the project in a Java IDE (e.g., Eclipse, IntelliJ IDEA).
4.  Run the `OgrenciIsleriOtomasyonu.java` file.

## Usage

When the application starts, you will see a login screen.

### Default Login Credentials

The application includes default test users upon initial launch:

  * **Faculty Member:**
      * **ID:** `1`
      * **Password:** `1`
      * **Name:** Zeynep Tuğçe
  * **Student:**
      * **ID:** `1306230027`
      * **Password:** `1`
      * **Name:** Mustafa Burak
  * **Student:**
      * **ID:** `1306220076`
      * **Password:** `2`
      * **Name:** Zeynep Pınarlı

Select your user type and enter your ID and password to log in.

## Contributing

Contributions are welcome\! For any bug reports, feature requests, or improvement suggestions, please open an issue or submit a pull request.

1.  Fork the project.
2.  Create your feature branch (`git checkout -b feature/AmazingFeature`).
3.  Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4.  Push to the branch (`git push origin feature/AmazingFeature`).
5.  Open a Pull Request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.
