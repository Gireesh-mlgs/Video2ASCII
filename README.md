# 🎥 Video2ASCII

Convert any video into an ASCII art animation directly in your terminal using Python and OpenCV.

Video2ASCII reads a video frame-by-frame, converts each frame into ASCII characters based on pixel brightness, and displays the animation in real time inside the console.

---

## ✨ Features

* 🎬 Convert videos into ASCII art
* ⚡ Real-time terminal playback
* 📺 Preserves the original video frame rate
* 🖥 Lightweight and fast
* 📏 Adjustable output width
* 🐍 Built with pure Python and OpenCV
* 📂 No temporary image or text files required

---

## 📸 Preview

```text
@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
@@@@@@%%%%%%%######*****+++++++
@@@@%%%#####****+++====------::
@@%%%###***+++===----::::......
@@@%%##***++===---:::..........
```

---

## 🛠 Technologies Used

* Python 3
* OpenCV
* NumPy (optional for future optimization)

---

## 📁 Project Structure

```text
Video2ASCII/
│── main.py
└── README.md
```

---

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/Gireesh-mlgs/Video2ASCII.git

cd Video2ASCII
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

Or install OpenCV manually:

```bash
pip install opencv-python
```

---

## ▶️ Usage

Place a video in the project directory or provide the full path to your video.

Run:

```bash
python main.py sample.mp4
```

Or:

```bash
python main.py "C:\Users\YourName\Videos\movie.mp4"
```

---

## ⚙️ How It Works

1. Opens the input video using OpenCV.
2. Reads frames one by one.
3. Converts each frame to grayscale.
4. Maps pixel brightness to ASCII characters.
5. Prints the ASCII frame to the terminal.
6. Repeats until the video finishes.

---

## 📦 Requirements

* Python 3.8 or later
* OpenCV

Install dependencies:

```bash
pip install opencv-python
```

---

## 🎯 Future Improvements

* Colored ASCII output
* Live webcam support
* GIF support
* Terminal resizing
* Adjustable character sets
* Playback controls (pause, seek, speed)
* Export ASCII animations as text or video
* NumPy vectorization for even faster rendering

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome. Feel free to fork the repository and submit a pull request.

---


---

## ⭐ Support

If you found this project useful, consider giving it a **⭐ Star** on GitHub. It helps others discover the project and motivates future improvements.
