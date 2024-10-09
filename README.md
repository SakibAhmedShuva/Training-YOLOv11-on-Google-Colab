# Training YOLOv11 on Google Colab

This repository contains code for training YOLOv11 models on Google Colab for image segmentation/classification tasks. You will also see how you can save the trained weights directly on your google drive. In case the train fails, you can easily recover the weights and continue training exactly from where it stopped.

## Directory Structure

```
/content/gdrive/MyDrive/training/
├── weights/
│   └── best.pt
├── data_modified.yaml
└── [training outputs]
```

## Notes

- Make sure you have sufficient Google Drive space for saving model checkpoints
- Adjust batch size based on available GPU memory

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
