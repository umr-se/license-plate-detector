# License Plate Detector

## Overview
This project is a **License Plate Detector** developed using **YOLOv11** and **PaddleOCR**. The model was fine-tuned on a dataset of over **500 images of cars**, annotated and trained on **Roboflow**. The script runs on **Google Colab** for easy deployment and training.

## Features
- Utilizes **YOLOv11** (pretrained and fine-tuned) for **license plate detection**.
- Extracts license plate text using **PaddleOCR**.
- Dataset curated and trained using **Roboflow**.
- Runs efficiently on **Google Colab**.

## Requirements
To run this script, install the following dependencies:

```sh
pip install paddleocr ultralytics opencv-python roboflow
```

## Usage
Run the script on **Google Colab**:

1. Clone the repository:
   ```sh
   git clone https://github.com/umr-se/license-plate-detector.git
   cd license-plate-detector
   ```
2. Open `colab_script.ipynb` in Google Colab.
3. Train or test the model as per the notebook instructions.

## Model Training
- The model is trained on a dataset of **500+ images**.
- Uses **Roboflow** for dataset preprocessing and augmentation.
- Fine-tuned **YOLOv11** for optimized detection performance.

## License Plate Recognition
- Detected plates are processed using **PaddleOCR**.
- Extracted text is displayed for further processing.

## Input Image

![img1](https://github.com/user-attachments/assets/4c655986-9388-47cb-8ce6-3ac3cba1405b)

## Example Output

![trained](https://github.com/user-attachments/assets/f1bdd4d1-4587-441c-a618-7669b3929894)

![ocrlist](https://github.com/user-attachments/assets/7602bf83-9feb-4b00-bbe5-c115cc5e0566)

## Future Improvements
- Improve accuracy with a larger dataset.
- Optimize inference speed for real-time detection.
- Deploy as a web application or API.

## Contributing
Feel free to fork and contribute to this project! Open an issue or submit a pull request.

