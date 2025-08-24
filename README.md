# Rice Grain Counting using OpenCV

This project is an **exploratory computer vision application** where I leveraged **OpenCV** to detect and count rice grains from images with high accuracy. The challenge was not just in detecting individual grains but also in handling **complex real-world cases** such as **overlapping or joined grains** that often lead to miscounts.  

Through **iterative experimentation** and **refined image preprocessing techniques**, I was able to build a pipeline that significantly improves grain detection accuracy.

---

## 🔍 Project Overview

- Implemented a **computer vision pipeline** using **OpenCV** in a Jupyter Notebook.  
- Tackled the problem of **accurately counting rice grains** in images, which involved challenges like:
  - Handling **joined/overlapping grains**.  
  - Eliminating background noise and unwanted reflections.  
- Designed and tested multiple approaches before refining the method for **robust detection and counting**.  

This project demonstrates skills in **image preprocessing, contour analysis, morphological operations, and object segmentation**.

---

## 🛠️ Tools & Technologies

- **Python**
- **Jupyter Notebook**
- **OpenCV** (for computer vision & image processing)
- **NumPy** (for efficient computation)
- **Matplotlib** (for visualization of intermediate steps)

---

## ⚙️ Workflow

1. **Preprocessing** – Applied grayscale conversion, thresholding, and filtering to clean the background.  
2. **Segmentation** – Used contour detection and morphological operations to isolate grains.  
3. **Dealing with Joined Grains** – Experimented with distance transforms, watershed segmentation, and custom logic to **separate touching grains**.  
4. **Counting & Validation** – Counted grains and validated results visually with bounding boxes/contours.  
5. **Iterative Refinement** – Fine-tuned parameters to improve **accuracy and consistency**.

---

## Sample Workflow & Results

Below are the key steps and outputs from the rice grain counting process:

### 1. Original Image
<img src="images/original_image.jpg" alt="Original Rice Image" width="500"/>

### 2. Processed / Thresholded Image
<img src="images/thresholded_image.jpg" alt="Thresholded Rice Image" width="500"/>

### 3. Final Output with Count
<img src="images/output_count.jpg" alt="Final Grain Count Output" width="500"/>

---

## 🚀 Key Highlights

- Demonstrated **end-to-end problem-solving skills** in a real-world image processing task.  
- Built **robust methods** to separate and count **seemingly joined grains**.  
- Showcased **exploratory data science mindset**: experimenting, failing, and refining until achieving optimal results.  
- Learned to balance **accuracy vs computational efficiency** in CV pipelines.  
- Project can be extended for **quality control in agriculture/food processing industries**.  

---

## 📂 Project Structure

