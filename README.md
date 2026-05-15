# Grayscale-and-Color-Histogram-Using-OpenCV


---

## Aim

To write a Python program using OpenCV to compute:

- The histogram of a grayscale image
- The histogram of one channel (Blue, Green, or Red) from a color image

The program reads an image, calculates the intensity distribution of pixels, and displays the histogram using Matplotlib.

---

## Software Used

- Anaconda – Python 3.7 or above
- Jupyter Notebook / VS Code
- OpenCV (`cv2`)
- Matplotlib (`matplotlib.pyplot`)

---


## Applications

- Image enhancement
- Contrast analysis
- Thresholding
- Histogram equalization
- Object detection
- Image segmentation

---
## Algorithm

### Step 1:
Import the required libraries: OpenCV and Matplotlib.

### Step 2:
Read the input image in grayscale mode.

### Step 3:
Calculate the histogram of the grayscale image using `cv2.calcHist()`.

### Step 4:
Display the grayscale image and plot its histogram.

### Step 5:
Read the same image in color mode.

### Step 6:
Select one color channel:
- 0 → Blue
- 1 → Green
- 2 → Red

### Step 7:
Calculate the histogram of the selected channel.

### Step 8:
Display the color image and plot the histogram of the selected channel.

---


### Developed By:
**Name:** Aaron I

**Register No:** 212223230002

---

## Output

### Grayscale Histogram

<img width="817" height="537" alt="image" src="https://github.com/user-attachments/assets/2ff1c341-032b-4c76-9074-3119ea1aa05f" />


### Color Channel Histogram

<img width="777" height="540" alt="image" src="https://github.com/user-attachments/assets/478611a4-286a-4256-ab7d-3f6a48d9b769" />

---

## Result

Thus, the histogram of a grayscale image and the histogram of one color channel from a color image were successfully computed and displayed using OpenCV and Matplotlib. This helps analyze the brightness and contrast distribution of the image.

---
