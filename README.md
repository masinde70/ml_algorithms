# ml_algorithms
## Types of 2D Imaging Algorithms 
1. Classification
   The classification algorithm assesses a whole image and returns an output stating whether or not a disease or abnormality is present in an image. These types of algorithms can be used for binary or multi-class classification, where a single algorithm can classify for the presence or absence of multiple types of findings or diseases

2. Localization
Localization algorithms are intended to aid radiologists in determining where in an image a particular finding is. These types of algorithms output a set of coordinates that create a bounding box around a section of the image where a particular type of finding is. These types of algorithms can be very useful for drawing radiologists' attention to certain types of findings that are difficult to see on imaging.

3. Segmentation 
   Segmentation algorithms return a set of pixels that contain the presence of a particular finding in an image, creating a border around a particular finding that allows for the calculation of its exact area. Segmentation algorithms are typically used to measures the size of particular findings or count the number of findings in an image. They are often used to count cells in microscopy data as well, where each cell in an image is segmented individually   

## Applications 
- Mammography screening
- Assesing tumour growth over time
- Patients are given chemotherapy to kill lung tumours 
- Efficacy of chemo is assessed by tumour shrinking (segmentation algorithm is good for this)
