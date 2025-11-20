This project is my Final Year Engineering Project (PFA), developed to secure physical spaces using a robust facial recognition system capable of real-time detection, classification, and decision making.

---

# 🎯 Project Objectives
- Build a **secure access control system** using facial recognition  
- Train and optimize a **VGG16-based deep learning classifier**  
- Detect and preprocess faces using **OpenCV**  
- Improve robustness using **data augmentation**  
- Evaluate system performance (precision, recall, confusion matrix)

---

# 🧠 **System Architecture**

User → Camera → Face Detection → Preprocessing → Feature Extraction → Classification → Access Granted/Denied


# 🏗️ **Technical Components**

### 📌 1. **Face Detection**
- Haar cascades  
- OpenCV image preprocessing  
- Gaussian blur, thresholding  
- ROI extraction  

### 📌 2. **Feature Extraction (Deep Learning)**
- VGG16 pretrained model  
- Feature vectors extracted from last convolutional block  
- Transfer learning for improved accuracy  

### 📌 3. **Classifier**
- Dense neural network  
- Softmax activation  
- Adam optimizer  
- Early stopping + dropout  

### 📌 4. **Evaluation**
- Training accuracy / validation accuracy  
- Confusion matrix  
- Precision, recall, F1-score  

---

# 📊 **Dataset**
- Custom dataset captured in controlled environment  
- Includes multiple angles, lighting variations, and expressions  
⚠️ *No real faces are uploaded to GitHub for privacy reasons.*

---

# 🧪 **How to Run**
```bash
pip install -r requirements.txt
python train_model.py
python test_model.py
📈 Results
High classification accuracy after fine-tuning

Excellent generalization after augmentation

Stable performance under different lighting conditions

🚀 Future Improvements
Implementing face tracking

Integration with RFID or smart lock hardware

Real-time deployment using TensorFlow Lite

Adding anti-spoofing mechanisms

🏁 Conclusion
This project demonstrates expertise in:

Deep learning

Computer vision

Image processing

System design

AI engineering

It represents a complete and functional access control solution built for real-world environments.
