# Keyboard Event Tracker (Python)

## Overview
This project is a Python-based keyboard event tracker developed as part of an internship. It captures and logs real-time keyboard input events and stores them in a structured JSON format.

The project is designed for educational purposes to understand event-driven programming and basic cybersecurity concepts.

---

## Features
- Real-time keyboard event tracking  
- Differentiates between **Pressed, Held, and Released** keys  
- Stores data in structured **JSON format**  
- Runs continuously until stopped using the **Esc key**  
- Lightweight and easy to use  

---

## Technologies Used
- Python 3.x  
- pynput library  
- JSON  
- File handling (Python I/O)  

---

## How It Works
- The program listens to keyboard events using the pynput library  
- Each key action is captured and categorized  
- Data is stored in a file named `logs.json`  
- Press **Esc** to stop the program safely  

---

## Installation & Setup

### 1. Clone the repository
```bash
git clone https://github.com/TheRedart/keylogger-python.git
cd keylogger-python.git
