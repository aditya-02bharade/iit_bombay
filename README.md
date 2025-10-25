# 🧠 Mental Rotation Project

## 📘 Overview
The **Mental Rotation Project** focuses on analyzing and simulating human spatial reasoning by testing the ability to mentally rotate 2D or 3D shapes.  
This project demonstrates how computational models can mimic cognitive processes involved in spatial visualization, with potential applications in **psychology, neuroscience, and AI-based perception systems**.

---

## ⚙️ Installation

1. **Clone or extract** the project files:
   ```bash
   unzip mental_rotation_project-1.zip
   cd mental_rotation_project-1
   ```

2. **Create a virtual environment (optional but recommended):**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use: venv\Scripts\activate
   ```

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

---

## 🚀 Usage

1. **Run the main script**:
   ```bash
   python main.py
   ```

2. **Provide inputs** (e.g., rotation angle, shape type, or dataset path) as prompted.

3. **View results/output**, which may include:
   - Visualizations of rotated shapes  
   - Model accuracy and response time  
   - Comparison between human and model performance

---

## 📦 Requirements

- Python 3.8+
- NumPy
- Matplotlib
- OpenCV (if image processing is used)
- TensorFlow / PyTorch (if using deep learning models)

If `requirements.txt` is available in the project, simply run:
```bash
pip install -r requirements.txt
```

---

## 🧩 Notes

- Ensure all dataset files (if required) are placed in the `/data` folder.  
- Logs and generated visual outputs will be stored in the `/output` directory.  
- You can modify configuration settings in `config.py` for custom experiments.
