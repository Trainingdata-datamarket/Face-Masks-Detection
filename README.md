# Face Masks Detection Dataset
1. [ About the dataset ](#about)
2. [ Distributions ](#dist)
3. [ Content ](#cont)
4. [ Get the Dataset ](#getdat)
5. [ Links ](#link)

<a name="about"></a>
# About the dataset
We introduce a large image dataset called Selfie and ID Dataset for training a neural network to solve reidentification tasks. The dataset consists of selfie photos and personal document photos of people. The list of documents, from which photos are taken: passports, foreign passports, driving licenses, medical certificates, membership/bank/transport cards, certificates, diplomas, etc. 

"Selfie and ID Dataset" can be utilized in several applications, including facial recognition algorithms, identity verification systems, forensic analysis, and deep learning research. By providing both personal and official photographs, this dataset offers a comprehensive resource for evaluating and improving the performance of algorithms in various real-world scenarios.

The dataset consists of **5,591** sets of images (**83,865** images in total) from **4,200+** unique people from **55** countries. The data for the dataset is still gathering, so the number of photos is getting bigger!

### The dataset includes 4 different types of images:
- **Type 1** - no mask on the face.
- **Type 2** - mask is on, but does not cover the nose or mouth.
- **Type 3** - mask covers the mouth, but does not cover the nose.
- **Type 4** - mask is worn correctly, covers the nose and mouth.

![MacBook Air - 1 (2)](https://github.com/Trainingdata-datamarket/Face-Masks-Detection/assets/113421352/bac36c6e-ad9c-428f-b2e1-19e4d25173af)

### Data in the dataset
- People from 18 to 81 years old are presented in the dataset.
- For each person in the dataset age, country and gender is presented.
- The data was mostly collected indoor, however there are also selfies made outdoors.
- The lighting is artificial, natural daily lightning, evening outdoor lighting and dark indoor lighting.
- People provided selfies where the head takes up at least 1/2 of the frame.
- Distance from the camera is approximately 20-30 centimeters.

### People in the dataset
![MacBook Pro 14_ - 1](https://github.com/Trainingdata-datamarket/Face-Masks-Detection/assets/113421352/5bfbc0f6-d51b-4170-9de8-557b2c8821a5)


<a name="dist"></a>
# Distributions

### Gender of people in the dataset

![image](https://github.com/Trainingdata-datamarket/Face-Masks-Detection/assets/113421352/797b91f0-13e4-485b-9802-beb622feab55)

### Age of people in the dataset

![image](https://github.com/Trainingdata-datamarket/Face-Masks-Detection/assets/113421352/6e66e508-68b1-4c15-9f96-5cd682442614)

### Ethnicity of people in the dataset

![image](https://github.com/Trainingdata-datamarket/Face-Masks-Detection/assets/113421352/46027dae-ef5f-4a37-b5c2-69e5c84869d9)

### Regions of people in the dataset

![image](https://github.com/Trainingdata-datamarket/Face-Masks-Detection/assets/113421352/11ba3114-2ae7-485e-8568-5312991b209d)

<a name="cont"></a>

# Content
### The folder **"images"** includes 10 folders:
- corresponding to each person in the sample
- containing of 4 selfies of the individual (*no mask, mask does not cover the nose or mouth, mask covers the mouth, mask covers the nose and mouth*)

### File with the extension .csv
includes the following information for each media file:
- **WorkerId**: identifier of the person who provided the media file,
- **Country**: country of origin of the person,
- **Age**: age of the person,
- **Sex**: gender of the person,
- **Type**: type of media file,
- **Link**: URL to access the media file

<a name="getdat"></a>
# Get the Dataset
This is just an example of the data. If you need access to the entire dataset, contact us via [sales@trainingdata.pro](mailto:sales@trainingdata.pro) or leave a request on **[trainingdata.pro/data-market](https://trainingdata.pro/data-market?utm_source=github)**

<a name="link"></a>
# Links
| Resource | Link |
| --- | --- |
| TrainingData.pro | [trainingdata.pro/data-market](https://trainingdata.pro/data-market?utm_source=github) |
| TrainingData.solutions | [trainingdata.solutions/data-market](https://trainingdata.solutions/data-market?utm_source=github) |
| Kaggle | https://www.kaggle.com/trainingdatapro |
| HuggingFace | https://huggingface.co/TrainingDataPro |


