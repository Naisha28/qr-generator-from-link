# 🔗 QR Code Generator with Embedded Logo  

Generate custom QR codes that instantly redirect to any website with own brand logo at the center.  
This Python-based project runs smoothly in **Jupyter Notebook** and produces clean, high-quality QR codes ready for digital or print use.  

---

## ✨ Features  
✅ Generate QR codes for any website link  
✅ Embed a custom logo at the center (maintains full scannability)  
✅ Automatically adjusts logo size for perfect balance  
✅ Clean white background and professional finish  
✅ Simple setup — runs in just a few lines of code  

---

## 🧠 How It Works  
1. Enter your target website link.  
2. The script generates a QR code with a white background.  
3. Your logo (from `Logo.jpg`) is added automatically to the center.  
4. The final QR (`qr_with_logo.png`) is saved and displayed right inside your notebook.  

---

## ▶️ Getting Started  

### 1. Clone this repository  
```bash
git clone https://github.com/Naisha28/qr-generator-from-link.git
cd qr-generator-from-link
```

### 2. Install dependencies
```bash
!pip install qrcode pillow
```

### 3. Add your logo
Place your logo file in the same folder as the notebook and rename it to: Logo.jpg

### 4. Run the notebook
jupyter notebook generate_qr_with_logo.ipynb

### 5. Input your website
Type any URL (e.g., https://www.example.com) when prompted, and your QR code will appear instantly.

---
## 📂 Project Structure

```text
qr-generator-from-link/
│
├── generate_qr_with_logo.ipynb     # Main notebook
├── Logo.jpg                        # Logo saved in JPG format
├── qr_with_logo.png                # Generated QR code (output)
└── README.md                       # Project documentation
```
## 🛠 Tech Stack
Python 3.x
qrcode – for QR code generation
Pillow (PIL) – for image processing
Jupyter Notebook – for execution and visualization

## 📜 License
This project is open-source and available under the MIT License
Feel free to modify and use it for personal or commercial purposes.
