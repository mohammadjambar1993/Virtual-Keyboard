# Virtual Keyboard with Computer Vision

A computer vision-powered virtual keyboard that allows you to type using hand gestures.

## Requirements

- Python 3.10, 3.11, or 3.12
- Webcam
- Windows/Mac/Linux


## Installation & Running
1. Install Python
Make sure Python 3.10, 3.11, or 3.12 is installed.
Download from python.org
.
Important: During installation, check “Add Python to PATH”.

2. Clone the repository
```
git clone <https://github.com/mohammadjambar1993/Virtual-Keyboard>
cd Virtual-Keyboard
```
3. Create a virtual environment
```
py -3.11 -m venv venv
```
4. Activate the virtual environment

Windows (PowerShell):
```
.\venv\Scripts\Activate.ps1
```

If you get a permission error:
```
Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass
```
5. Upgrade pip (optional but recommended)
```
pip install --upgrade pip setuptools wheel
```
## Installation

Install the required packages:
```bash
pip install -r requirements.txt
```

## Running the Application

Start the virtual keyboard:
```bash
python main.py
```

## Usage

- Make sure your webcam is working and you have good lighting.
- Hold your hand in front of the camera with your palm facing the camera.
- Point your index finger at the keys you want to press.
- Make a clicking gesture by bending your index finger down towards your palm.
- Press **'q'** to quit the application.

## Troubleshooting

- If you encounter import errors, run `pip install -r requirements.txt` to install dependencies.
- Ensure your webcam is not being used by another application.
- Check lighting and hand visibility for best results.


Author:
```
Mohamamd Jambar
```