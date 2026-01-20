# 🔐 Image Steganography Using Python

This project demonstrates **image steganography**, a technique used to hide secret messages inside images so that the presence of the message is not easily detectable.

The project uses the **LSB (Least Significant Bit)** method with the `stegano` library to embed and extract text from image files.

---

## 🚀 Features

- Hide secret text messages inside images
- Reveal hidden messages from stego-images
- Uses LSB-based steganography
- Simple and beginner-friendly Python script
- Works with PNG images

---

## 🧠 Tech Stack

- Python 3.10+
- stegano
- Pillow
- OpenCV
- NumPy
- colorama / crayons (dependencies)

---

## 📦 Installation

### 1️⃣ Clone the Repository
bash
git clone https://github.com/your-username/image-steganography-python.git
cd image-steganography-python

## 2️⃣ Install Dependencies
pip install -r requirements.txt

## ▶️ Usage
🔒 Hide a Message

Place an image named test.png in the project directory
Edit the secret message inside main.py
Run the script:
python main.py
A new image steg.png will be created containing the hidden message.
🔓 Reveal the Message
The script automatically extracts and displays the hidden message from steg.png.

## 📂 Project Structure
image-steganography-python/
│
├── main.py
├── requirements.txt
├── runtime.txt
├── test.png
└── steg.png

## 🎯 Learning Outcomes

Understanding steganography concepts

LSB (Least Significant Bit) technique

Image processing with Python

Secure data hiding basics

## ⚠️ Disclaimer

This project is intended for educational purposes only.
Do not use it for illegal or unethical activities.

## 👨‍💻 Author

Atul Anand
BCA (Hons)
Amity University, Noida

## ⭐ Support

If you find this project useful, don’t forget to star ⭐ the repository!