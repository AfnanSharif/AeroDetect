<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=00c6ff,0072ff&height=200&section=header&text=AeroDetect&fontSize=70&fontColor=ffffff&animation=twinkling" width="100%" />

<img src="https://img.icons8.com/?id=43604&format=png&size=100" width="90" />

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=2500&pause=1000&color=00c6ff&center=true&vCenter=true&width=700&height=50&lines=Aerial%20Object%20Detection;Custom%20YOLOv3" alt="Typing SVG" />

[![Python](https://img.shields.io/badge/Python-3.10%2B-3776AB?style=for-the-badge&logo=python&logoColor=white)](#)
[![YOLOv3](https://img.shields.io/badge/YOLOv3-00FFFF?style=for-the-badge)](#)

</div>

---

## 📖 Overview

**AeroDetect** trains and runs a from-scratch YOLOv3 object detector
(`yolo3_one_file_to_detect_them_all.py`) for aerial/drone imagery, configured via
`config.json` and anchor boxes generated with `gen_anchors.py`.

## 🏗️ Project Layout

```
AeroDetect/
├── train.py                                  # Train the detector
├── predict.py                                  # Run inference on an image
├── evaluate.py                                    # Evaluate mAP
├── gen_anchors.py                                    # Generate YOLO anchor boxes
├── yolo3_one_file_to_detect_them_all.py                 # Core YOLOv3 implementation
└── config.json                                            # Model/training configuration
```


## ⚡ Setup & Run

### 🪟 Windows / 🍎 macOS / 🐧 Linux
```bash
git clone https://github.com/AfnanSharif/AeroDetect.git
cd AeroDetect

python -m venv venv
# Windows: venv\Scripts\activate | macOS/Linux: source venv/bin/activate
pip install -r requirements.txt

python train.py -c config.json      # train
python predict.py -c config.json -i /path/to/image.jpg   # run detection
```

---

<div align="center">

**Created by [AfnanSharif](https://github.com/AfnanSharif)** · ⭐ star this repo if it helped you

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=00c6ff,0072ff&height=80&section=footer" width="100%" />

</div>
