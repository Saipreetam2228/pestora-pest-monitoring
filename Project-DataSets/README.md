---

## 📂 Dataset Creation

To ensure crop-specific and reliable pest detection, Pestora uses custom-built datasets created specifically for this project.

### 🌾 Target Crops

The dataset is organized separately for:

- Vegetables
- Rice
- Maize

Each crop has its own trained model to improve accuracy and avoid a one-size-fits-all approach.

---

## 🖼️ Data Collection Method

Images are collected through:

- Field photographs of crop leaves
- Public agricultural image sources
- Research datasets (where permitted)
- Manual verification and labeling

All images focus primarily on **leaf-level pest damage**, since farmers typically observe pest symptoms on leaves first.

---

## 🏷️ Data Labeling

Each image is labeled with:

- Crop type
- Pest type (or healthy)
- Severity level (if applicable)

Example label structure:

Crop_Name/
    Pest_Type/
        image1.jpg
        image2.jpg

This structured format allows efficient training of crop-specific AI models.

---

## 🧹 Data Preprocessing

Before training, images undergo:

- Resizing and normalization
- Noise removal
- Data augmentation (rotation, flipping, brightness adjustment)
- Train-test split

This ensures better model generalization and improved performance.

---

## 🧠 Dataset Purpose

The custom dataset enables:

- Crop-specific pest identification
- Confidence-aware prediction generation
- Reduced false positives
- Improved reliability in real-field conditions

---

## 🔄 Future Dataset Improvements

- Increase dataset size for better robustness
- Include more pest categories
- Add multi-stage pest severity levels
- Collect real-time field data from farmers
- Expand to additional crops

---
