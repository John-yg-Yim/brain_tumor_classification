# 🧠 Brain Tumor Classification using Transfer Learning

This project presents a deep learning-based approach to classify brain tumors from MRI images,  
focusing on both presence detection and tumor type classification.

We achieved high accuracy by applying fine-tuning to a ResNet50V2-based transfer learning model,  
while minimizing misclassifications of tumor cases as non-tumor.

---

## 📁 Key Files

- **Dataset Source**: [Kaggle – Brain Tumor MRI Dataset](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset/data)

| Filename                         | Description                               |
|----------------------------------|-------------------------------------------|
| `brain_tumor_classification.ipynb` | Full experiment pipeline with visualizations |
| `brain_tumor_classification.html` | Static version of the notebook (for viewing) |

> 📝 Trained model file (`.h5`) is not included,  
> but running the notebook will reproduce the same results and architecture.

---

## 🧪 Experiment Summary

- **Preprocessing**: 512×512 grayscale image conversion and normalization
- **Baseline Accuracy** (simple CNN): 93–95%
- **Transfer Learning Comparison**: 13 pre-trained models tested → ResNet50V2 selected
- **Fine-Tuning Applied**: Final model performance significantly improved

---

## 📊 Final Results

- **Validation Accuracy**: 99%  
- **F1-score**: 99%  
- **No false negatives** (i.e., no tumors misclassified as normal)

---

## 🔗 Dataset Info

- Classes: `no_tumor`, `glioma`, `meningioma`, `pituitary`  
- The provided test set was used for validation purposes.

---

## 🚀 Demo

> *[Try the demo on Hugging Face →](https://huggingface.co/spaces/JohnYim0213/project-note)*  
> *(Note: unrelated placeholder, may not reflect this exact project.)*