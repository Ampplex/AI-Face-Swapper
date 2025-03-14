# **Face Swapper – AI-Powered Face Swapping** 🎭🔄

🚀 **Face Swapper** is an AI-powered face swapping tool that seamlessly replaces faces in images using **deep learning models**. It leverages **InsightFace** for face detection and feature extraction, along with **INSWAPPER** for high-quality face swapping.

---

## **✨ Features**
✅ **AI-Based Face Detection** – Uses **RetinaFace** to detect faces with high accuracy.  
✅ **Seamless Face Swapping** – Powered by **INSWAPPER (ONNX)** for realistic swaps.  
✅ **Automatic Landmark Alignment** – Ensures natural blending of facial features.  
✅ **High-Resolution Outputs** – Generates sharp and visually accurate swapped faces.  
✅ **Supports CPU & GPU** – Runs on **CUDA** (GPU) for fast performance or **CPU** for universal compatibility.  

---

## **📌 Installation**
```bash
git clone https://github.com/yourusername/face-swapper.git
cd face-swapper
pip install -r requirements.txt
```

---

## **🖼️ Usage**
```bash
python face_swap.py --source elon.jpg --target zuck.jpg --output swapped.jpg
```

- `--source` → Path to the source face image.
- `--target` → Path to the target image where the face will be swapped.
- `--output` → Path to save the swapped image.

---

## **🛠️ Dependencies**
- **Python 3.8+**
- **OpenCV**
- **InsightFace**
- **INSWAPPER (ONNX)**
- **Matplotlib**
- **NumPy**

---

## **📥 Download INSwapper Model**
To use the face swapper, download the **inswapper_128.onnx** model from **Hugging Face**:
[Download INSwapper Model](https://huggingface.co/ezioruan/inswapper_128.onnx/tree/main)

---

## **🚀 Example Output**
| Original Image | Swapped Image |
|---------------|--------------|
| ![Elon](elon.jpg) | ![Swapped](swapped.jpg) |

---

## **📜 License**
This project is licensed under the **MIT License**.

---

🚀 **Happy Swapping!** 🔄😊
