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

## Performance Metrics
### Sensitivity
Sensitivity is a metric that tells us among ALL the positive cases in the dataset, how many of them are successfully identified by the algorithm, i.e. the true positive. In other words, it measures the proportion of accurately-identified positive cases.

You can think of highly sensitive tests as being good for ruling out disease. If someone has a negative result on a highly sensitive algorithm, it is extremely likely that they don’t have the disease since a high sensitive algorithm has low false negative.

### Specificity
Specificity measures ALL the negative cases in the dataset, how many of them are successfully identified by the algorithm, i.e. the true negatives. In other words, it measures the proportion of accurately-identified negative cases.

You can think of highly specific tests as being good for ruling in disease. If someone has a positive result on a highly specific test, it is extremely likely that they have the disease since a high specific algorithm has low false positive.

### Dice coefficient
The dice coefficient measures the overlap of algorithm output and true labels. It is used to assess the performance of segmentation and localization.
