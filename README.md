# 📸 IMAGE_CAPTIONING: Combining NLP with CV

**Image Captioning** means looking at a picture and writing a sentence that describes what is in the picture. It combines **Computer Vision (CV)** to understand the image and **Natural Language Processing (NLP)** to write the sentence. This project tests different models (like BLIP, GPT-2, and CLIP) to see how well they can do this job. The results are measured using a score called **Fréchet Distance (FGD)**.

---

## 📊 Model Trainings and Results

| Model | Description | FGD Score |
|-------|-------------|-----------|
| **Model v1** | Simple **BLIP-2** | 0.4732 |
| **Model v2** | Advanced **BLIP-2** | 0.4603 |
| **Model v3** | **BLIP-2 Advanced (No Fine-Tune)**: 0.46958<br>**GPT-2 Advanced (No Fine-Tune)**: 0.52361<br>**Ensemble (BLIP-2 + GPT-2 + CLIP)**: 0.51733 | Various |
| **Model v4** | **BLIP-1 (Fine-Tuned)** (Best Model) | **0.44041** |
| **Model v5** | **BLIP-1 Large (New Fine-Tuned)** | 0.44075 |
| **Model v6** | **BLIP-2 (Torch Optimized)** | 0.44469 |

---

### 📌 Key Highlights
- 🖼️ Combines **BLIP**, **GPT-2**, and **CLIP** models for **image captioning**.
- 📈 Uses **FGD (Fréchet Distance)** metric to evaluate how similar generated captions are to true captions.
- 🏆 **Model v4 (BLIP-1 Fine-Tuned)** achieved the best performance with an FGD score of **0.44041**.
- 🔥 Includes fine-tuning and optimization with **Torch** for improved results.

---

### 🛠️ Setup and Usage
1. Clone this repository:
```bash
git clone https://github.com/giraydorukyurt7/IMAGE_CAPTIONING_Combining_NLP_With_CV.git
cd IMAGE_CAPTIONING_Combining_NLP_With_CV