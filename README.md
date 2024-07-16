# Attendance Management System

This project is an Attendance Management System developed using Python. It provides a way to manage and track attendance for students or employees using a user-friendly interface.

## Features

- **User Authentication**: Admin and student login functionality.
- **Attendance Tracking**: Mark and manage attendance records.
- **Subject Management**: Handle attendance for different subjects like Maths and Python.
- **Reports**: Generate attendance reports.
- **Graphical Interface**: User-friendly interface for interaction.

## Installation

1. **Clone the repository**:

    ```bash
    git clone https://github.com/yourusername/Attendance-Management-System.git
    cd Attendance-Management-System
    ```

2. **Install the required dependencies**:

    ```bash
    pip install -r requirements.txt
    ```

3. **Run the application**:

    ```bash
    python main.py
    ```

## Project Structure

```
Attendance-Management-System/
├── .idea/                          # IDE configuration files
│   ├── .gitignore
│   ├── .name
│   ├── Attendance management system.iml
│   ├── misc.xml
│   ├── modules.xml
│   ├── sample_!.iml
│   └── inspectionProfiles/
│       └── Project_Default.xml
├── ImageAttendance/                # Sample images for attendance tracking
│   ├── bill.jpg
│   ├── chinmay.jpg
│   ├── elon musk.jpg
│   ├── jack.jpg
│   ├── kshitija.jpg
│   └── sakshi.jpg
├── image basic/                    # Basic images
│   ├── bill.jpg
│   ├── elon musk.jpg
│   └── elon test.jpg
├── __pycache__/                    # Compiled Python files
│   ├── admin_login.cpython-38.pyc
│   ├── at.cpython-38.pyc
│   ├── att_p.cpython-310.pyc
│   ├── att_p.cpython-38.pyc
│   ├── attendance_project.cpython-38.pyc
│   ├── face_track_page.cpython-38.pyc
│   ├── maths.cpython-310.pyc
│   ├── maths.cpython-38.pyc
│   ├── python.cpython-38.pyc
│   └── student_login.cpython-38.pyc
├── at.csv                          # CSV file for attendance data
├── at.py                           # Attendance tracking script
├── att_p.py                        # Attendance processing script
├── att_p.ui                        # UI file for attendance processing
├── attendance_project.py           # Main attendance project script
├── home_p.py                       # Home page script
├── home_p.ui                       # UI file for home page
├── main.py                         # Main entry point of the application
├── maths.csv                       # CSV file for Maths subject attendance data
├── maths.py                        # Maths subject script
├── python.csv                      # CSV file for Python subject attendance data
├── python.py                       # Python subject script
└── workspace.xml                   # Workspace configuration file


- `main.py`: The main entry point of the application.
- `at.py`, `att_p.py`, `attendance_project.py`, etc.: Core functionality scripts.
- `home_p.ui`, `att_p.ui`: UI design files.
- `*.csv`: CSV files storing attendance data.
- `ImageAttendance/`: Folder containing sample images for attendance tracking.

```
## Dependencies

- Python 3.x
- PyQt5 (for GUI)
- pandas (for handling CSV data)
- OpenCV (for image processing)

## Usage

1. **Run the application**:

    ```bash
    python main.py
    ```

2. **Login**: Use the admin or student credentials to log in.

3. **Mark Attendance**: Navigate through the UI to mark and manage attendance.

4. **Generate Reports**: Use the reporting features to generate attendance reports.

## Contributing

Contributions are welcome! Please create a pull request with detailed information about the changes.

Feel free to modify the content to better suit your needs. Let me know if you need any additional information or changes.
