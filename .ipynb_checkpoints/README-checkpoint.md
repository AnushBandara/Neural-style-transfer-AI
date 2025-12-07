# 🎨 Neural Style Transfer

### What this project does
This program takes two images—a regular photo and a piece of art—and blends them together. It uses a technique called **Neural Style Transfer** to redraw your photo using the artistic style (colors, textures, and brushstrokes) of the artwork, creating a unique new image.

![Project Banner](BannerImages/Img2_2.png)

---

## ✨ Features
* **Style Transfer:** Merges content from one image with the style of another using Deep Learning.
* **Loss Visualization:** Real-time plotting of the training loss to track how the model improves over time.
* **Image Processing:** Uses PIL and custom functions to load, resize, and de-process images.
* **Visual Output:** Displays the Content, Style, and Final Generated image side-by-side using Matplotlib.

## 🛠️ Tech Stack
* **Python 3.x**
* **PyTorch** (Deep Learning framework)
* **NumPy** (Data manipulation)
* **PIL (Pillow)** (Image loading and processing)
* **Matplotlib** (Visualization)

## 🚀 How to Run
1.  **Clone the repository**
    ```bash
    git clone [https://github.com/AnushBandara/Neural-style-transfer-AI.git](https://github.com/AnushBandara/Neural-style-transfer-AI.git)
    cd Neural-style-transfer-AI
    ```

2.  **Install dependencies**
    ```bash
    pip install torch torchvision numpy matplotlib pillow
    ```

3.  **Run the Notebook**
    ```bash
    jupyter notebook style_transfer.ipynb
    ```

4.  **Customization**
    * Change the image paths in the notebook to use your own content and style images.

## 📊 Sample Results

| Content Image | Style Image | Generated Result |
|:---:|:---:|:---:|
| ![Content](ContentImages/Resized/NightCity.png) | ![Style](StyleImages/StaryNight_resized.jpg) | ![Result](GeneratedImages/StaryNight_NightCity/generated_1500.png) |

## 🤝 Contributing
Feel free to fork this project and submit a pull request if you have ideas for improvements!