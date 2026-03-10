# Real-Time QR Code Scanner using Computer Vision

## 📌 Project Overview

This project is a **Real-Time QR Code Scanner** built using **Python and Computer Vision**.
It uses the computer's webcam to detect QR codes and automatically decode the information contained in them.

When a QR code containing a URL is detected, the program:

* Draws a **bounding box** around the QR code
* Displays the decoded data on the screen
* Prints the QR content in the terminal
* **Automatically opens the website in the default browser**

This project demonstrates the practical use of **Computer Vision for QR code detection and decoding**.

---

## 🚀 Features

* Real-time QR code detection using webcam
* Displays decoded QR data on the video frame
* Automatic browser opening for URL-based QR codes
* Prevents repeated scanning of the same QR code
* Lightweight and easy to run

---

## 🛠️ Technologies Used

* **Python**
* **OpenCV (cv2)** – for webcam capture and image processing
* **pyzbar** – for QR code decoding
* **webbrowser module** – to automatically open detected links

---

## 📂 Project Structure

```
QR-Code-Scanner
│
├── qr.py                # Main Python program
├── README.md            # Project documentation
├── requirements.txt     # Required libraries
└── screenshots          # Demo images of the project
```

---

## ⚙️ Installation

### 1️⃣ Clone the repository

```
git clone https://github.com/yourusername/qr-code-scanner.git
cd qr-code-scanner
```

### 2️⃣ Install required libraries

```
pip install opencv-python
pip install pyzbar
pip install numpy
```

Or install using:

```
pip install -r requirements.txt
```

---

## ▶️ Running the Project

Run the following command:

```
python qr.py
```

The webcam will open and start scanning QR codes in real-time.

Press **Q** on the keyboard to exit the scanner.

---

## 📸 Working Demo

1. The webcam captures the video feed.
2. The program detects QR codes in the frame.
3. A **green rectangle** appears around the detected QR code.
4. The decoded text or link is displayed.
5. If the QR contains a URL, it automatically opens in the browser.

---

## 🎯 Applications

* Contactless information sharing
* QR-based attendance systems
* Product scanning systems
* Payment verification systems
* Smart retail applications

---

## 🔮 Future Improvements

* Add sound notification when QR is detected
* Save scanned QR data to a database or CSV file
* Support for barcode detection
* Build a graphical user interface (GUI)

---

## 👨‍💻 Author

**Samyak Bansod**

---

## 📜 License

This project is open-source and available for educational purposes.
