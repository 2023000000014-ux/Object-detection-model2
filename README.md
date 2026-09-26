# YO-DETR: Hybrid Ensemble Object Detection Architecture

YO-DETR is a high-performance hybrid traffic detection framework developed for challenging low-light and adverse weather conditions (fog, headlight glare at dawn).

## 🚀 Key Highlights
- **Architecture:** Dual Ensemble of YOLOv8s (CNN) + RT-DETR-L (Vision Transformer)
- **mAP@50:** **0.996**
- **mAP@50-95:** **0.885**
- **Recall:** **0.995**
- **Inference Speed:** ~22.1 ms (~45 FPS)

## 📁 Repository Structure
- `fixed_data.yaml` - Dataset pathing & class mappings.
- `YO-DETR Inference Scripts` - Pipeline logic combining local spatial features and transformer global attention via Non-Maximum Suppression (NMS).
