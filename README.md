# ME_Recognition
Recognizing subtle facial micro-expressions using EfficientNet, PSR, attention modules, Transformers, and GCNs only from the apex frame of the subjects video sequence.
It is based for real time application.
The base framework:

✅ Landmark Extraction using MediaPipe to localize facial keypoints.

📦 Data Preprocessing with image augmentation and landmark alignment.

🔁 Pseudo-Sequence Reconstruction (PSR) to simulate temporal dynamics from static apex frames.

🎯 Multi-scale Attention using Triplet and Spatial attention modules for robust feature refinement.

🧠 Transformer Blocks to model long-range dependencies across facial regions.

🕸️ Graph Convolution Network (GCN) with Attention Pooling over facial landmarks for spatial reasoning.

🖼️ ROI Extraction around key landmarks to focus on micro-expression-relevant areas.

📊 Classification of micro-expressions into emotion classes.

<img width="2076" height="1592" alt="Flowchart" src="https://github.com/user-attachments/assets/9e8162f4-bec1-4580-a6bc-2c24561a6ed5" />
