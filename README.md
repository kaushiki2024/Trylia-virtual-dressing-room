# Trylia – Virtual Dressing Room

Trylia is an AI-powered **Virtual Dressing Room Web Application** that enables users to try clothing virtually using real-time computer vision. The system detects the user's body pose through a webcam and overlays clothing items dynamically using pose detection algorithms.

The project demonstrates the integration of **computer vision technologies with a modern full-stack web application architecture** using a **React frontend and Flask backend**.

---

## Overview

Traditional online shopping does not allow customers to visualize how clothing will appear when worn. Trylia addresses this limitation by providing a virtual try-on experience powered by computer vision.

Using pose detection and image overlay techniques, the system aligns clothing images with the user's body in real time, enabling an interactive and immersive experience.

---

## Key Features

* Real-time **virtual clothing try-on**
* **Pose detection** using MediaPipe
* Webcam-based interaction
* Full-stack architecture with **React + Flask**
* Clothing catalogs for **male and female**
* Contact form with validation and backend API integration
* Modular and scalable project structure

---

## Technology Stack

### Frontend

* React.js
* JavaScript
* HTML5
* CSS3

### Backend

* Python
* Flask
* Flask-CORS
* Flask-Mail

### Computer Vision

* OpenCV
* MediaPipe
* CVZone
* NumPy

---

## System Architecture

```id="qhojsd"
User Webcam
     │
     ▼
Frontend (React)
     │
     ▼
Backend API (Flask)
     │
     ▼
Computer Vision Engine
(OpenCV + MediaPipe + CVZone)
     │
     ▼
Clothing Overlay Rendering
```

---

## Project Structure

```id="2f5m8c"
Trylia-virtual-dressing-room
│
├── backend
│   ├── api_server.py
│   ├── tryon_service.py
│   ├── email_service.py
│   ├── validation_utils.py
│   ├── requirements.txt
│   └── static
│       ├── male
│       └── female
│
├── frontend
│   ├── public
│   ├── src
│   └── package.json
│
└── README.md
```

---

## Installation

### Clone the repository

```id="60b3mp"
git clone https://github.com/kaushiki2024/Trylia-virtual-dressing-room.git
cd Trylia-virtual-dressing-room
```

---

## Backend Setup

Navigate to the backend directory:

```id="dz6fgb"
cd backend
```

Create a virtual environment:

```id="3h3hbo"
python -m venv venv
```

Activate the environment:

Windows

```id="1pqjv4"
venv\Scripts\activate
```

Install dependencies:

```id="s9f6x2"
pip install -r requirements.txt
```

Run the backend service:

```id="3h5b8y"
python api_server.py
```

Backend server runs at:

```id="d8b7gt"
http://localhost:5000
```

---

## Frontend Setup

Navigate to frontend directory:

```id="lqfpb4"
cd frontend
```

Install dependencies:

```id="c6er0q"
npm install
```

Start development server:

```id="y2eog2"
npm start
```

Frontend runs at:

```id="v95lhb"
http://localhost:3000
```

---

## How It Works

1. The user accesses the application through a web interface.
2. The webcam captures the user's body in real time.
3. MediaPipe detects body landmarks.
4. OpenCV processes the video stream and aligns clothing images with the detected pose.
5. The processed frame is displayed to the user as a virtual try-on.

---

## Future Enhancements

* AI-based size recommendation
* Improved garment alignment and scaling
* Mobile device support
* Cloud deployment
* Integration with e-commerce platforms
* 3D garment simulation

---

## Contributing

Contributions are welcome. If you would like to improve the project, please fork the repository and submit a pull request.

---

## License

This project is intended for **educational and research purposes**.

---

## Author

Developed as a **Computer Vision and Full Stack Development Project**.
