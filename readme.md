

# Avalanche Rescue using Image Processing

🚑 **Avalanche Rescue System** built with **YOLOv8**, **DeepSORT**, and **OpenCV** to detect and track victims in avalanche scenarios.  
This project leverages **deep learning (PyTorch)** and **computer vision** to assist in **search and rescue operations** using real-time or static image/video inputs.

---
## 🖼️ UI

### YOLOv12

![User Interface 1](testimage\test1.jpg)  
![User Interface 2](testimage\test2.jpg)

## 📌 Features
- 🎯 **Object Detection** using YOLOv8 (`ultralytics`).
- 🧭 **Tracking** with DeepSORT for continuous monitoring.
- 🖼️ Works with both **images and videos**.
- 🎨 Beautiful bounding boxes with solid colors & transparency overlays.
- ⚡ Fast and optimized with **PyTorch + OpenCV**.

---

## 🛠️ Tech Stack
- [Python 3.9+](https://www.python.org/)
- [PyTorch](https://pytorch.org/)  
- [OpenCV](https://opencv.org/)  
- [Ultralytics YOLOv8](https://github.com/ultralytics/ultralytics)  
- [DeepSORT](https://github.com/ZQPei/deep_sort_pytorch)  

---

## 📂 Project Structure
```

AVALANCHE\_RESCUE\_USING\_IMAGE\_PROCESSING/
│── rescue\_model/          # YOLOv8 trained model weights
│── search-and-rescue/     # Validation images/videos
│── testimage/             # Output results
│── main.py                # Main detection + tracking script
│── README.md              # Project documentation

````

---

## 🚀 How to Run

### 1️⃣ Clone the repository
```bash
git clone https://github.com/CodewithAvijit/AVALANCHE_RESCUE_USING_IMAGE_PROCESSING_AND_VIDEO_PROCESSING.git
cd avalanche-rescue
````

### 2️⃣ Install dependencies

```bash
pip install torch torchvision torchaudio
pip install opencv-python ultralytics
pip install deep-sort-realtime
```

### 3️⃣ Run detection on an image

```bash
python main.py --source "search-and-rescue\test\images\xxx.jpg"
```

### 4️⃣ Run detection on a video / webcam

```bash
python main.py --source "TEST\testvideo\xxx.mp4"
# OR webcam
python main.py --source 0
```

---

## 📊 Example Output

* **Bounding boxes** drawn with unique colors for each class.
* **Tracked IDs** displayed over detected victims.
* **Processed frames** saved in `testimage/`.

---
---
## IMPORTANT
* Adjust confidence as your need in model
* Dataset: https://universe.roboflow.com/datasets-pdabr/sard-8xjhy/dataset/17
---
## 📖 Future Improvements

* Integrate **thermal imaging fusion** for night rescue.
* Deploy on **edge devices (Jetson Nano, Raspberry Pi)** for field use.
* Add **GPS integration** for real rescue mapping.

---

## 🤝 Contributing

Pull requests are welcome! If you’d like to add improvements, feel free to fork and submit a PR.

---

## 📜 License

This project is licensed under the MIT License.


