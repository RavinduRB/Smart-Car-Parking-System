## **Smart Car Parking System with Python and QR Code Integration 🚀**  

I’m excited to share my personal project I’ve been working on a **Smart Car Parking System** developed using **Python** with a user friendly **Tkinter** interface. This system streamlines parking operations with real time monitoring, QR code based entry/exit, and automated receipt generation. 🅿️💳 



https://github.com/user-attachments/assets/e2647bff-0b12-49b7-8fe7-fccabb382e2d



### ❄️ **Key Features:**  
✅ **Interactive GUI:** Built with Tkinter for easy parking management.  
✅ **Real Time Parking Spot Display:** Visual representation of available and occupied spots.  
✅ **QR Code Generation:** Generates QR codes for parked cars for quick check in/out.  
✅ **QR Code Scanning:** Integrated camera support for reading QR codes.  
✅ **Parking Fee Calculation:** Automatically calculates charges based on parking duration.  
✅ **Digital Receipts:** Generates PDF receipts using ReportLab.  
✅ **Parking History:** Maintains a log of all parked vehicles with timestamps.  
✅ **Tooltip Hover:** Displays detailed info (car number and time) on parked spots.  

### 🌍 **Technologies Used:**  
🔹 **Python** – Core programming language.  
🔹 **Tkinter** – For building the graphical user interface (GUI).  
🔹 **OpenCV** & **Pyzbar** – For real time QR code scanning via webcam.  
🔹 **Pillow (PIL)** – For image handling in the GUI.  
🔹 **qrcode Library** – For generating QR codes.  
🔹 **ReportLab** – For creating PDF receipts.  
🔹 **JSON** – For storing parking history.  
🔹 **Datetime** – For managing timestamps and calculating parking duration.  

### 📌 **Use Cases:**  
✔️ Smart parking solutions for **malls, hospitals, offices, and gated communities**.  
✔️ Enhancing security and reducing manual errors.  
✔️ Providing a **seamless digital experience** for users.  

This project is a blend of **technology and convenience**, showcasing how automation can improve daily operations. 📊  

---

## **Smart Car Parking System - User Manual**

### Introduction
Welcome to the Smart Car Parking System! This user manual will guide you through the steps to efficiently manage parking using this software.

### 1. System Requirements
- **Operating System:** Windows 10 or higher
- **Python Version:** 3.10 or higher
- **Dependencies Installed:** Tkinter, OpenCV, Pyzbar, Pillow, qrcode, ReportLab, JSON
- **Webcam:** Required for QR code scanning

### 2. Launching the Application
- Run the script by executing `python parking_system.py` in your terminal.
- The main window will appear displaying the parking spots and available actions.

### 3. User Interface Overview
- **Title:** Displays 'Smart Car Parking System'.
- **Parking Spots Frame:** Visual representation of available and occupied spots.
- **Car Number Entry:** Input field for car license numbers.
- **Control Buttons:** Includes 'Park Car', 'Remove Car', and 'Scan QR Code'.
- **Parking History:** List showing past parking activity.
- **Status Label:** Displays real-time messages and updates.

### 4. Parking a Car
1. Enter the car number in the input field.
2. Click on the 'Park Car' button.
3. A QR code will be generated and saved as an image.
4. The parking spot will change color to red (Occupied).
5. The system will log the activity in the parking history.

### 5. Removing a Car
1. Enter the car number in the input field.
2. Click on the 'Remove Car' button.
3. A PDF receipt with parking details and fees will be generated.
4. The parking spot will change back to green (Empty).
5. The system will log the removal activity in the parking history.

### 6. Scanning QR Code
1. Click the 'Scan QR Code' button.
2. The webcam will open.
3. Point the QR code to the camera.
4. The system will display the scanned car details and check status.

### 7. Viewing Parking History
- The parking history section lists all parked and removed cars with timestamps.

### 8. Safety and Security
- Data is stored locally in `parking_history.json`.
- QR codes are unique for each car and session.
- Receipts are automatically saved in PDF format for record-keeping.

### 9. Troubleshooting
- **No webcam detected:** Ensure your webcam is connected and functional.
- **Car already parked:** Verify the car number entered.
- **No available spots:** Wait until a spot is freed or check the parking status.

**Thank you for using Smart Car Parking System!**

**This project is a blend of technology and convenience, showcasing how automation can improve daily operations. 📊**
