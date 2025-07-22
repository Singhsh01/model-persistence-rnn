# 🧠 model-persistence-rnn

A hands-on implementation of a character-level Recurrent Neural Network (RNN) for text generation, trained to approximate the structure of Limerick poetry. This repository demonstrates model persistence (saving and loading), efficient training using Google Colab, and performance comparison across model variations.

---

## 📌 Overview

The project consists of two tasks:

### **Task A – Model Training and Persistence**
- Set up for execution in **Google Colab** with GPU acceleration  
- Dataset loading and preprocessing for character-level modeling  
- RNN architecture implemented using **PyTorch**  
- Model training loop  
- **Model saving and loading** logic using `torch.save` and `torch.load`  

### **Task B – Text Generation with Trained RNNs**
- Functions to **generate limerick-style text** from trained models  
- Use of **temperature scaling** to control output diversity  
- Comparison of outputs from two versions:  
  - `model_v1`: shorter generation  
  - `model_v2`: longer generation with increased temperature  
- Critical reflection on model performance:  
  - Structure partially learned (line breaks, poetic form)  
  - Limitations in rhyme and semantics  

---

## 🗃️ Directory Structure

model-persistence-rnn/
├── A_RNN.ipynb # Model training, Colab setup, and persistence
├── B_RNN.ipynb # Limerick generation with trained models
├── Data/ # (To store input data files)
│ └── .gitkeep
├── Model/ # (To store saved model checkpoints)
│ └── .gitkeep



---

## 🚀 Google Colab Support

Both notebooks are optimized for use in [Google Colab](https://colab.research.google.com/), enabling faster training through GPU acceleration.

> ⚠️ A Google account is required to run Colab notebooks.  
> See the notebooks for setup instructions and privacy considerations.

---

## 🧪 Sample Generation Output

From the trained model:

> Deep Thought, after millions of years,  
> With the ultimate answer appears,  
> &nbsp;&nbsp;&nbsp;&nbsp;Which is just 42.  
> &nbsp;&nbsp;&nbsp;&nbsp;This is certainly true,  
> Though it sounds a bit strange to the ears.

> **Note**: The generated text structure resembles limericks but lacks semantic consistency and rhyme — highlighting the potential of LLMs over traditional RNNs for such tasks.

---

## 🛠️ Technologies Used

- Python 3.x  
- PyTorch  
- Google Colab  
- Character-level RNNs  
- Text sampling with temperature control


