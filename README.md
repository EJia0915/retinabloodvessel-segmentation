# retinabloodvessel-segmentation
Filter-Based Retina Blood Vessel Segmentation  

## 📌 Project Overview  
This project focuses on **retinal blood vessel segmentation** using **filter-based image processing techniques**. The approach enhances and extracts blood vessels from retinal images to aid in medical diagnoses such as **diabetic retinopathy** and **glaucoma detection**.  

## ⚙️ Methods Used  
1. **Preprocessing**  
   - **Green Channel Extraction**: Enhances contrast for better vessel detection.  
   - **CLAHE (Contrast Limited Adaptive Histogram Equalization)**: Improves image contrast.  

2. **Vessel Segmentation**  
   - **Frangi Filter**: Enhances tubular structures like blood vessels.  
   - **Mean Filter**: Reduces noise and smooths the image.  
   - **Bottom-Hat Transformation**: Enhances dark vessel structures.  
   - **Image Blending**: Combines filtered images for better segmentation.  

3. **Post-processing**  
   - **Masking**: Defines the region of interest (ROI).  
   - **Adaptive Thresholding**: Dynamically segments vessels from the background.  
   - **Connected Component Analysis**: Removes noise and improves accuracy.  

## 📈 Results  
- Achieved **94.84% average accuracy** in blood vessel segmentation.  
- Improved sensitivity (**72.93%**) and specificity (**98.07%**).  
- Outperforms several existing segmentation techniques.  

## 🚀 How to Run the Program  
1. Open `IIP.ipynb` in **Jupyter Notebook**.  
2. Run the first cell to import libraries and set the image path.  
3. Execute all cells to process and segment the retinal blood vessels.  
4. Change the `i` variable in the second cell to test different images.  

