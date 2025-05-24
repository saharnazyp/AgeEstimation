## 🧠 Age Estimation with UTKFace Dataset

This project uses the [UTKFace dataset](https://susanqq.github.io/UTKFace/) to build a machine learning pipeline that estimates a person’s age based on facial images. The dataset contains over 20,000 facial images with labels for age, gender, and ethnicity.

### 📌 Project Goals

* Build a robust image processing pipeline.
* Train and evaluate an age prediction model using deep learning (e.g., CNN).
* Explore and visualize the dataset.
* Provide reusable and scalable code for facial age estimation tasks.

---

### 📂 Project Structure

```text
UTKFace-AgeEstimation/
├── 📁 Data
│   ├── UTKFace/                # Raw image dataset
│   ├── valid_set.csv           # Validation image labels
│   └── ...
├── 📓 AgeEstimation.ipynb      # Main Jupyter notebook for training and evaluation
├── 📜 README.md                # Project documentation (you're here)
├── 📊 Outputs/                 # Plots and results
└── 📁 Models/                  # Saved trained models (if any)
```

---

### 🛠️ Features

* Data preprocessing including resizing and normalizing images.
* Custom PyTorch Dataset class for handling UTKFace images and CSV labels.
* CNN-based model for age regression.
* GPU support for accelerated training.
* Clear metrics and loss tracking.

---

### 📈 Sample Results

> Include plots like training loss curves, sample predictions, or model architecture here.

---

### 📦 Requirements

```bash
pip install -r requirements.txt
```

Or manually install the major packages:

```bash
pip install torch torchvision pandas numpy matplotlib scikit-learn
```

---

### 🚀 Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/UTKFace-AgeEstimation.git
   cd UTKFace-AgeEstimation
   ```

2. Download the [UTKFace dataset](https://susanqq.github.io/UTKFace/) and place it inside the `Data/UTKFace/` directory.

3. Run the notebook:

   ```bash
   jupyter notebook AgeEstimation.ipynb
   ```

---

### 📌 To-Do

* [ ] Improve model accuracy with data augmentation.
* [ ] Implement cross-validation.
* [ ] Deploy with Gradio or Streamlit.
* [ ] Add gender and ethnicity classification.

---

### 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

### 👩‍💻 Author

Developed with ❤️ by [Saharnaz Yaghoobpour](https://github.com/saharnazyp)

