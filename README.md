# 🚘 Devanagari Vehicle & License Plate Detection System  

An AI-powered system that detects **two-wheelers, four-wheelers, and license plates in Devanagari script** (Nepali number plates) in real time.  
This project leverages **YOLOv8, OpenCV, and OCR** to build a robust traffic automation solution tailored for Nepal’s transportation ecosystem.  

---

## 🔑 Features  
- ✅ Detects **two-wheelers** and **four-wheelers** from images and videos  
- ✅ Identifies and localizes **Nepali license plates**  
- ✅ Performs OCR on **Devanagari script** for accurate text recognition  
- ✅ Works in real time with **CCTV feeds or video streams**  
- ✅ Handles low-light conditions, motion blur, and diverse weather  

---

## ⚙️ Tech Stack  
- **Object Detection:** YOLOv8 (PyTorch)  
- **Computer Vision:** OpenCV  
- **OCR:** Tesseract / Custom Devanagari OCR  /Yolov8
- **Backend/Deployment:** Flask / FastAPI  

---
## 📊 Sample Results

**Sample Output:**

| Input Frame   | Detection Output                                         | OCR Result                               |
|---------------|----------------------------------------------------------|-----------------------------------------|
| Image/Video   | Vehicle classification (2-wheeler / 4-wheeler), License plate detection | Recognized Devanagari text (e.g., बा.२ च १२३४) |

- ✅ Vehicle classification (2-wheeler vs 4-wheeler)  
- ✅ License plate detection  
- ✅ OCR recognition of Devanagari plate

---

## 📌 Applications
- 🚦 **Traffic Management** – Automated vehicle classification and congestion analysis  
- 👮 **Law Enforcement** – Tracking vehicles violating traffic rules  
- 🅿️ **Parking & Toll Systems** – Automated entry/exit with plate logging  
- 🏙️ **Smart Cities** – AI-powered surveillance for safer transportation

---

## 📧 Contact

**Saishna Budhathoki**  
Email: saishna.mlengineer@nicrfnepal.org.np | saishna.budhathoki@gmail.com  
LinkedIn: [Saishna Budhathoki](https://www.linkedin.com/in/saishna-budhathoki)  





## 🚀 Installation & Running

**Install the required packages:**
```bash
pip install -r requirements.txt

# Run the application
python app.py