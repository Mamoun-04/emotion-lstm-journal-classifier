# 🧠 Emotion Classifier with LSTM (Journal Entry Mood Detection)

This project uses an LSTM neural network (built with Keras) to detect the **emotional tone** of journal-style entries.  
It predicts one of the following emotions:

> `joy`, `sadness`, `anger`, `fear`, `surprise`, `love`

---

## ✅ Results

- 📊 **Test Accuracy**: `89.25%`
- 🧠 Model: Single-layer LSTM with Embedding layer
- 📈 Early stopping by validation curve analysis

---

## 📂 Project Files

| File | Description |
|------|-------------|
| `EmotionsClassification.ipynb` | Full notebook: training, evaluation, sample predictions |
| `README.md` | This file |

---

## 🧪 Sample Predictions

```python
predict_mood("I feel like everything is falling apart.")
# Expected: sadness

predict_mood("I can't wait for tomorrow! So excited.")
# Expected: joy

predict_mood("He hugged me and I felt so safe.")
# Expected: love
