# BrainSeg

### University of Minnesota 

**BrainSeg: Automated Brain CT Image Segmentation with MONAI**  

BrainSeg is a research-driven project aimed at developing and experimenting with deep learning models for automatic segmentation of brain CT images. Built with the MONAI framework, BrainSeg supports multiple neural network architectures (e.g., UNet, Swin UNETR) and offers customizable data pipelines, loss functions, and training workflows tailored for brain trauma analysis.  

### Key Features:
- Flexible model experimentation framework for brain CT segmentation  
- Preprocessing pipelines optimized with MONAI transforms  
- Support for multiple segmentation models  
- Easily configurable YAML-based experiment management  
- Comprehensive visualization and evaluation tools  

### Getting Started:
1. Clone the repository:
   ```bash
   git clone git@github.com:SakshiRa/BrainSeg.git
   cd brainseg
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Train a model:
   ```bash
   python src/main.py --config configs/unet_config.yaml
   ```

---
