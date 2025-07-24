# 🌍 Satellite Water Segmentation with U-Net

This project performs **semantic segmentation of water bodies** from satellite images using a **custom-built U-Net** model in PyTorch.

The goal is to accurately classify water regions (lakes, rivers, streams, etc.) from **12-band remote sensing images**. This work is ideal for environmental monitoring, flood detection, and mapping water resources.

---

## 📈 Project Results

After training for **19 epochs** using Dice Loss with early stopping, the model achieved:

| Metric         | Value   |
|----------------|---------|
| **Dice Score** | 0.54    |
| **IoU**        | 0.44    |
| **F1 Score**   | 0.54    |




