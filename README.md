
# Attendance Management System

This is a Python-based **Attendance Management System** that uses **Face Recognition** for recording attendance. 
It leverages `tkinter` for the GUI interface, `OpenCV` for face detection, and a local database for storing attendance details.

## Features
- **Face Recognition**:
  - Detects and recognizes faces using Haar cascades.
  - Automates the attendance marking process.
- **Student Management**:
  - Add, update, and manage student details.
- **Training Module**:
  - Trains the system to recognize faces from images.
- **Attendance Logs**:
  - Saves attendance records with timestamps.
  - View and manage attendance data.
- **User-Friendly GUI**:
  - Built with `tkinter` for an easy-to-use interface.

## Project Structure
```
Attendance-Management/
├── Attendance/                     # Stores attendance logs
├── StudentDetails/                 # Stores student information
├── TrainingImage/                  # Stores training images for recognition
├── TrainingImageLabel/             # Stores label data for training
├── haarcascade_frontalface_alt.xml # Haar cascade for face detection (alternative)
├── haarcascade_frontalface_default.xml # Haar cascade for face detection (default)
├── main_Run.py                     # Main file to run the application
├── training.py                     # Training module for face recognition
├── testing.py                      # Script for testing the system
├── requirements.txt                # Python dependencies
├── training code.txt               # Training-related notes
├── Presentation shraddha.pptx      # Project presentation (optional)
```

## Requirements
To run this project, you need:
- Python 3.x
- Required libraries listed in `requirements.txt`.

## Installation and Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/Satkar1/Attendance-Management.git
   cd Attendance-Management
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the application:
   ```bash
   python main_Run.py
   ```

4. Add student details and train the model for face recognition.

## Usage
1. **Add Students**:
   - Upload student details and images.
   - Train the system using the **Training Module**.
2. **Mark Attendance**:
   - Launch the application.
   - Recognize faces and record attendance automatically.
3. **View Attendance Logs**:
   - Access the `Attendance` folder for attendance records.

## Files and Folders
- **Attendance/**: Contains CSV files of attendance logs.
- **StudentDetails/**: Stores student profile information.
- **TrainingImage/**: Contains images used for training.
- **TrainingImageLabel/**: Stores encoded training data.

## Technologies Used
- **Python**:
  - `tkinter`: For GUI design.
  - `OpenCV`: For face detection and recognition.
  - `sqlite3`: For database management.
- **Haar Cascades**: For face detection.

## Future Enhancements
- Integrate real-time attendance tracking.
- Export attendance data in multiple formats (e.g., Excel, PDF).
- Deploy as a web application.

## Credits
Developed by **Satkar Garje** as part of a project for attendance automation.

## License
This project is open-source and available under the [MIT License](LICENSE).
