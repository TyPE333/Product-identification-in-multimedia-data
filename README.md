# 🛍️ Product-in-Video Discovery

**Identify fashion products in videos and link them directly to purchase pages.**  
A computer vision + retrieval-based system built to bridge video content and e-commerce.

---

## 🚀 Project Overview

This project builds a system that detects fashion products appearing in videos, matches them to an e-commerce catalog, and returns purchase-ready links — like Shazam, but for fashion in video.

> 🔥 Imagine watching a YouTube vlog and instantly getting links to buy the outfit shown — that’s the future we’re building.

---

## 💡 Core Features

- **Visual Product Detection** in video frames using object detection
- **Product Feature Extraction** using pretrained deep vision models
- **Product Matching & Retrieval** using nearest neighbor search (FAISS)
- **Metadata Linking** to display names, categories, and purchase URLs
- **Lightweight UI** to simulate real-world usage (Streamlit/Gradio)

---

## 📁 Project Structure

```
product-in-video-discovery/
│
├── data/              # Raw and processed datasets
├── notebooks/         # EDA and experimental notebooks
├── src/               # Source code (data, models, utils)
├── configs/           # YAML/JSON configuration files
├── experiments/       # Logs, checkpoints, eval results
├── scripts/           # CLI tools to train/run models
├── ui/                # Front-end interface
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

## 🧠 Tech Stack

- **Python**, **PyTorch** / **TensorFlow**
- **YOLOv8 / Detectron2** for product detection
- **CLIP / ViT / ResNet** for feature extraction
- **FAISS** for product retrieval
- **Streamlit / Gradio** for UI prototyping

---

## 🛠️ Setup

```bash
git clone https://github.com/yourusername/product-in-video-discovery.git
cd product-in-video-discovery
pip install -r requirements.txt
```

---

## 📊 Datasets

- [DeepFashion2](https://github.com/switchablenorms/DeepFashion2)
- [Fashion Product Images (Hugging Face)](https://huggingface.co/datasets/ashraq/fashion-product-images-small)
- Custom dummy catalog with purchase URLs

---

## 🧪 Progress Checklist

- [x] Define problem and MVP
- [x] Select fashion as target domain
- [x] Set up metadata + image dataset
- [ ] Implement product detection on sampled frames
- [ ] Feature extraction + retrieval matching
- [ ] Prototype UI to simulate "product discovery"
- [ ] Evaluate precision of top-k matches
- [ ] Prepare for patent drafting

---

## 📄 License

MIT License. See [LICENSE](LICENSE) for details.

---

## 🤝 Contact

Built by Rohan Avireddy  
rohanavireddy2019@gmail.com

```