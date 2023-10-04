# Melanoma

## Data Collection
image source: https://wiki.cancerimagingarchive.net/pages/viewpage.action?pageId=37225348 

We selected male patient PET-CT scan images and collected their subcutaneous fat (sub-q fat) area and sub-q fat thickness using slices at the L3-L4 vertebral level. All the measurement are done by using ImageJ.

**Sub-q fat**: For each patient's slice, the subcutaneous fat area was measured 3 times and then we took the mean value for later analysis. As for subcutaneous fat thickness, we measured the thickness 3 times for both left and right body sides and then we took the mean value for the analysis.

In this figure, the left one shows how we measure the subcutaneous fat area for one patient. The right one shows how we measure subcutaneous fat thickness.

<img width="708" alt="image" src="https://github.com/YuanGao00/Melanoma/assets/111895795/ff7dd858-3399-4479-82bd-a8e3a06ea675">

**Tumor size**: We also collected the pre-treatment and post-treatment tumor sizes for each patient. We selected the axial CT slice with the largest axial area of tumor to represent the tumor size.

For patients without a tumor (e.g., Hydrothorax and pneumonia) or who only had one series of CT scans so that could not be determined whether they were from pre-treatment or post-treatment, we labeled them ‘None’. After filtering 42 patients, we have 20 patients left, which were the subjects of our study.

<img width="585" alt="image" src="https://github.com/YuanGao00/Melanoma/assets/111895795/ba9ecaa0-888c-4a2c-a392-68354e865893">

**treatment responsiveness**: we calculated the treatment responsiveness by using the pre-treatment tumor size to minus the post-treatment tumor size.

We define the obesity by using either the sub-q fat area or the sub-q fat thickness. We defined a patient as obese if the thickness was greater than 20 mm and vice versa. In addition, we defined a patient as obese if the sub-q fat area was greater than 25000 mm^2 and vice versa.
