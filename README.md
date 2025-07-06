# 🧥 Python Invisibility Cloak

This is a fun and simple **Computer Vision project** using Python and OpenCV that creates an **invisibility cloak effect** — anything red (like a cloak, hoodie, or object) disappears on camera, just like magic! 🔴✨

## 🛠️ How It Works

1. The webcam captures the **static background** (without you) in the first 5 seconds.
2. Then it continuously checks for **red-colored objects** in the video.
3. Wherever red is detected, it is replaced by the background — creating an illusion of invisibility.

You can change the target color in the code (e.g., pink, blue, green).

## ▶️ How to Run

```bash
git clone https://github.com/tia0016/python-invisibility-cloak.git
cd python-invisibility-cloak
pip install opencv-python numpy
python invisibilityred.py
```

📌 Make sure:
- You **move out of the frame** for the first 5 seconds (so background is captured).
- You're wearing something **red**.
- Your webcam is accessible by your editor/terminal.

## 📦 Requirements

- Python 3.x
- OpenCV (`opencv-python`)
- NumPy

You can install them using:

```bash
pip install opencv-python numpy
```

## 💡 Customization

Want to make other colors invisible?  
Just change the HSV range in the script — for example, to make pink or green objects invisible.

---

## 📁 File

- `invisibilityred.py`: Main Python script that runs the invisibility cloak effect.

---

## 🌟 Credits

Made with using Python, NumPy & OpenCV  
Project by [Tia Panwar]([https://www.linkedin.com/in/tia0016](https://www.linkedin.com/in/tia-panwar-5a6aa0293/))

---
