# 🖼️ Image to Pencil Sketch  

This project converts any colored RGB image into a **realistic pencil sketch** using **OpenCV in Python**.  
It was developed as part of the **LGM Data Science Virtual Internship Assignment**.  

---

## ✨ Features  
- Convert any **RGB image** into a **pencil sketch effect**.  
- Uses **grayscale conversion, image inversion, Gaussian blur, and blending techniques**.  
- Fully customizable — you can experiment with OpenCV filters for improved results.  

---

## 📖 How It Works  
1. Convert the RGB image to **grayscale**.  
2. **Invert** the grayscale image (negative effect).  
3. Apply **Gaussian Blur** to the inverted image.  
4. **Blend** the grayscale image with the inverted blurred image using division.  
5. Output → Pencil sketch version of the original image.  

---

## 📂 Dataset / Input  
- A sample image (`dog.jpg`) is provided.  
- You can replace it with any image of your choice.  

---

## 🛠️ Tech Stack  
- **Python**  
- **OpenCV (cv2)**  
- **Jupyter Notebook**  

---

## 🚀 Getting Started  

### 1. Clone the Repository  
```bash
git clone https://github.com/Sanika1524/Image-to-Pencil-Sketch.git
cd Image-to-Pencil-Sketch
