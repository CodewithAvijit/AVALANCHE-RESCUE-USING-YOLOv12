# Avalanche Rescue using Image Processing

🚑 **Avalanche Rescue System** built with **YOLOv12**, **DeepSORT**, and **OpenCV** to detect and track victims in avalanche scenarios.
This project leverages **deep learning (PyTorch)** and **computer vision** to assist in **search and rescue operations** using real-time or static image/video inputs.

---
## 🖼️ IMAGE PROCESSING

### YOLOv12
![User Interface 1](TEST/testimage/test1.jpg)
![User Interface 2](TEST/testimage/test2.jpg)

---

## 📌 Features

* 🎯 **Object Detection** using YOLOv12.

* 🧭 **Tracking** with DeepSORT for continuous monitoring.

* 🖼️ Works with both **images and videos**.

* 🎨 Beautiful bounding boxes with solid colors & transparency overlays.

* ⚡ Fast and optimized with **PyTorch + OpenCV**.

---

## 🛠️ Tech Stack

* [Python 3.9+](https://www.python.org/)

* [PyTorch](https://pytorch.org/)

* [OpenCV](https://opencv.org/)

* [Ultralytics YOLOv12](https://github.com/ultralytics/ultralytics)

* [DeepSORT](https://github.com/ZQPei/deep_sort_pytorch)

---

## 📂 Project Structure

```

AVALANCHE\_RESCUE
├── MODEL/
│   ├── rescue\_model1.pt
│   └── rescue\_model2.pt
├── TEST/
│   ├── testimage/
│   └── testvideo/
├── model.ipynb
└── README.md

````

---

## 🚀 How to Run

### 1️⃣ Clone the repository

```bash
git clone [https://github.com/CodewithAvijit/AVALANCHE_RESCUE_USING_IMAGE_PROCESSING_AND_VIDEO_PROCESSING.git](https://github.com/CodewithAvijit/AVALANCHE_RESCUE_USING_IMAGE_PROCESSING_AND_VIDEO_PROCESSING.git)
cd AVALANCHE_RESCUE_USING_IMAGE_PROCESSING_AND_VIDEO_PROCESSING
````

### 2️⃣ Install dependencies

```bash
pip install torch torchvision torchaudio
pip install opencv-python ultralytics
pip install deep-sort-realtime
```

### 3️⃣ Run detection on an image

```bash
python main.py --source "TEST/testimage/test1.jpg"
```

### 4️⃣ Run detection on a video / webcam

```bash
python main.py --source "TEST/testvideo/video.mp4"
# OR for webcam
python main.py --source 0
```

-----

## 📊 Example Output

  * **Bounding boxes** drawn with unique colors for each class.

  * **Tracked IDs** displayed over detected victims.

  * **Processed frames** saved in `testimage/`.

-----

## 📖 Future Improvements

  * Integrate **thermal imaging fusion** for night rescue.

  * Deploy on **edge devices (Jetson Nano, Raspberry Pi)** for field use.

  * Add **GPS integration** for real rescue mapping.

-----

## 🤝 Contributing

Pull requests are welcome\! If you’d like to add improvements, feel free to fork and submit a PR.

-----

## 📜 License

This project is licensed under the MIT License.

```
```