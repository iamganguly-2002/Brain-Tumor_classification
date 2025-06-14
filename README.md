# Brain-Tumor_classification

Classifies MRI scans into **Glioma**, **Meningioma**, **Pituitary**, or **No tumor** using a custom CNN. Dataset includes pre-split `train/` and `test/` folders. Achieves **94%+ accuracy** with TensorFlow/Keras. Includes training scripts, evaluation metrics, and single-image prediction.  

**Quick Start**:  
```bash
python train.py --data_path dataset/train
python predict.py --image_path sample.jpg
