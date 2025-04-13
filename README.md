              🦿 Knee X-Ray Classification

You will find the dataset in Kaggle at:
📂 /kaggle/input/digital-knee-xray

This dataset contains digital knee X-ray images categorized by severity levels ranging from 0Normal to 4Severe.

🔁 Image Augmentation & DataLoader

Images are augmented using torchvision.transforms (resize, normalize, etc.).

Augmented images are then fed into a PyTorch DataLoader for efficient batching during training and evaluation.

🧠 Transfer Learning

This project uses transfer learning with the Vision Transformer (ViT) model from 🤗 Hugging Face Transformers.

The ViT model is fine-tuned on the knee X-ray dataset to classify severity levels.

