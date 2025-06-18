# AI Image Processor

## Project Description
A Streamlit-based AI image processing application that combines TensorFlow and PyTorch models to perform image colorization, super-resolution enhancement, and Daltonization (color blindness simulation). The app provides an intuitive web interface for users to upload images and view processed results side-by-side.

## Features
- 🎨 **Image Colorization**: Convert grayscale images to color using a TensorFlow model
- 🔍 **Super-Resolution Enhancement**: 4x image resolution upscaling with PyTorch-based RRDBNet architecture
- 👁️ **Daltonization**: Simulate color blindness correction effects
- 🖼️ Responsive UI with three-column comparison view
- ⬇️ Direct image download capability

## Installation
1. Clone the repository
2. Install dependencies:
```bash
pip install -r requirements.txt
```
3. Ensure both model files are present in the root directory:
- `color_image_checkpoint.keras` (TensorFlow colorization model)
- `RRDB_ESRGAN_x4.pth` (PyTorch super-resolution model)

## Usage
1. Run the Streamlit app:
```bash
streamlit run streamlit6.py
```
2. Upload an image (JPG/PNG format)
3. Click "Process Image" to generate:
   - Original image
   - AI-enhanced colorized image
   - Daltonized color correction
4. Download the processed image using the provided button

## Contribution Guidelines
Contributions welcome! Please follow these guidelines:
1. Fork the repository
2. Create a new feature branch
3. Submit a pull request with detailed description
4. Follow PEP8 style guide
5. Include test cases for new features

## License
This project is licensed under the MIT License - see [LICENSE](LICENSE) file for details
