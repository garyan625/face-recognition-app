Project Overview
A real-time attendance management solution that automates the check-in process using advanced Computer Vision. This system identifies individuals via a live webcam feed and automatically logs their presence, significantly reducing the manual effort required in traditional classroom or office attendance taking.

Key Features
Automated Recognition: Real-time face detection and matching using high-performance CNN models.


Scalable Database: Easily manage a database of authorized personnel by simply adding images to the known_faces directory.

Visual Feedback: Real-time GUI overlay showing detected faces and identity verification labels.

Architecture
Tech Stack
Core Language: Python 3.12

Face Detection & Recognition: face-recognition, dlib

Image Processing: opencv-python

Data Handling: numpy, pandas (for CSV logging)

Build System: cmake, Visual Studio Build Tools

Project Structure
Plaintext
/face-recognition-attendance
│── /known_faces          # Store images of authorized personnel here
│── main.py               # Main script to run the webcam feed
│── .venv                 # Project dependencies
└── README.md             # Project documentation
Setup Instructions
Prerequisites
Install Visual Studio Build Tools (with "Desktop development with C++" workload).

Install CMake.

Installation
Clone the repository:

Bash
git clone [your-repo-link]
cd face-recognition-attendance
Create and activate a virtual environment:

Bash
python -m venv .venv
source .venv/bin/activate  # On Windows: .venv\Scripts\activate
Install dependencies:

Bash
pip install -r requirements.txt

Usage
-> Add photos of people you wish to track into the /known_faces folder.

-> Run the application:
Bash
python main.py
Attendance logs will be generated in the /attendance_logs directory.

Professional Experience Gained
-> System Integration: Navigated complex environment builds by linking high-level Python libraries with low-level C++ compilers.

-> Computer Vision Optimization: Implemented real-time frame processing to balance detection accuracy with system performance.

-> Data Lifecycle Management: Architected a pipeline from raw visual input to structured timestamped data.
