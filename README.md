# Color-Detection-Data-Science-Project
COLOR DETECTION USING PYTHON

INTRODUCTION:

Color plays a important role in human daily life for recognition. Color plays
crucial role on how we perceive and analyze things around us. Based on
primary colors (Red, Green, Blue), a lot of color models were established to
quantitatively measure color. Quantitative color measurement is one of the key
component in color science, scene analysis, detection and tracking. RGB and
HSV color model are one of the simple color models that are widely used today
in detection and tracking. There are many important real-world applications in
which color detection can be applied, such as skin color detection, traffic light
detection, vehicle color recognition, image segmentation, biometric
identification, video surveillance, and etc.

ABSTRACT:

Color Recognition plays very important role in image processing techniques, for
applications based on color, like Object recognition, Face recognition, Skin color
recognition etc. The accuracy of color recognition plays very important role in many
applications. This paper is based on color classification by K-Nearest Neighbor
classification algorithm and R, G, B Color Histogram is used to train KNN algorithm.
It can recognize eight different colors namely Yellow, Voilet, Orange, White, Green,
Red, Blue, and Black.
Color detection is necessary to recognize objects, it is also used as a tool in various
image editing and drawing apps. It is the process of detecting the name of any color.
Well, for humans this is an extremely easy task but for computers, it is not
straightforward. Human eyes and brains work together to translate light into color.
Light receptors that are present in our eyes transmit the signal to the brain. Our brain
then recognizes the color. Hence the problem that arises in front of us is how to make
a computer understand or recognize colors , so we are going to solve this problem.
So basically in this project using python we need 3 different parts to be used. Python
code which will be recognizing color, Image that will be used for
testing the color recognition, a .csv file that will be containing the colors as dataset.

ARCHITECHTURE AND DESIGN:

![image](https://user-images.githubusercontent.com/104318300/203710969-760d34a7-96e9-4779-9c24-cac1be4d1c7c.png)

SYSTEM FRAMEWORK:

Color classification is done by using K-NN classifier algorithm. The K-NN
classifier is trained by image R, G, B Color Histogram value. The work-flow for the
procedure is given below. The general procedure Color Recognition system
includes feature extraction, training KNN classifier, classifcation by trained KNN.

![image](https://user-images.githubusercontent.com/104318300/203711174-f1b17fdb-a1c5-4cb8-9c8c-611e0a4eae4d.png)
![image](https://user-images.githubusercontent.com/104318300/203711200-36aa5612-2853-476e-b5c8-1fec29915b07.png)

RGB Model preferred over Lab Color Model:

The specific reason why the lab color model is not preferred over the RGB model
of the proposed method, because cameras have dynamic ranges that are largely
outside of the circumstances under which Lab is accurate, which makes this space
more evident in its defects. Any modern camera that uses HDR by default at a
Hundred ISO of dynamic ranges between 9 -13 EV Lab isn't meant to accommodate
far more dynamic range. It is quite difficult to force pixel values in lab space,
particularly while solving compositing and image blending in video editors with
smooth & featheredge. The lab is not suited to practical physical corrections, such
as pixelation, denoising, etc. Whereas the proposed method with the RGB model
doesn't get affected by blurring or any other effects on the image. Without showing
unwanted side effect faster algorithms can handle more drastic changes, functioning
in RGB is better. A lab can also not allow higher dynamic ranges, so after HDR
tone mapping, care must be taken while using the Lab components.

![image](https://user-images.githubusercontent.com/104318300/203711517-575912a0-8c2a-4124-a0bc-60b8e4c4321c.png)

IMPLEMENTATION:

K-NN is the commonly used algorithm and it is the simplest algorithm for
identifying different patterns in regression and classification problem. It is an
unsupervised and this algorithm is called lazy learning algorithm. Working of
K-NN starts by first calculating the distance of one test observation from all the
available observations of training dataset and later followed by finding ‘K’
nearest neighbors of it. The above step is carried out for each test observation
and this is how the similarities present in the data is found. In order to make the
algorithm work best on the dataset we need to choose the most suitable distance
metric. There are a lot of different methods to calculate the distance available,
Euclidean distance has been chosen in this implementation. Euclidean distance
function is set default in the SK-learn KNN classifier in python. It is the
measurement of straight-line distance between 2 points present in the Euclidean
space.

Classification by trained KNN:

![image](https://user-images.githubusercontent.com/104318300/203711620-96f65b8a-647b-4379-b314-a6c453ca4780.png)

![image](https://user-images.githubusercontent.com/104318300/203711651-8626b7d8-8369-4639-8dd9-cd73c427d086.png)

Algorithm that is used to implement classification, is called as Classifier. The
term "classifier" is referred as the mathematical function, which is implemented
by classification algorithm, which plots the given data into a category. K-NN is
a algorithm that stores all the available cases and also classifies new cases based
on the similarity measures (For Example., distance functions).

![image](https://user-images.githubusercontent.com/104318300/203711724-2595378a-001b-4695-a9d8-3469eb8f0aaf.png)

EXPERIMENT RESULTS & ANALYSIS:

![image](https://user-images.githubusercontent.com/104318300/203711900-a9a33fe3-20a3-40ff-aae0-8c9ac0da3727.png)

![image](https://user-images.githubusercontent.com/104318300/203711964-a5990eae-78e2-4f15-86d9-0c386ea38a25.png)

CONCLUSION AND FUTURE ENHANCEMENT:

Color recognition is an important step in most of the image processing applications.
Color detection has received significant interest in most of the computer visions due
to the wide range of applications including video surveillance, face indexing and so
on. In this project, we present color recognition method using KNN classifier which
is trained by RGB color histogram. The training data has a huge importance in
accuracy. This model can classify Green, Orange, Red, Blue, Yellow White, Black,
and Violet. For classifying more colors and improving the accuracy we should
consider large training dataset.
In Future Color identification in real-time comprises
limited colors but we wish to expand the data on which our KNN classifiers are
trained to give more accurate results. In our project only 8 basic colors can be
detected, we can improve the model to classify more colors and to improve the
accuracy and to detect various colors desired by the user. It can be improved to
detect Different shades of colors and not just the basic colors. In the existing project
only single color is being detected from the given input image, it can me improved
to detect multi-colors in single input image. color detection from an image can be
developed further and used as a feature in software for photo editing, video editing
or it may be used in color selecting and mixing software or in face detection. And
real-time color identification can be used in self-driving cars, robotics and can be
applied to many more technical applications.

REFERENCES:

[1] Rabia Bayraktar, Batur Alp Akgul and Kadir Sercan Bayram, "Colour
recognition using colour histogram feature extraction and Knearest neighbor
classifier", 2020.
[2] Shima Ramesh maniyath,Akshatha K N, Dr. S Rama Subramoniam,
Architha L and S,Ramachandra hebbar "Soil Color Detection Using Knn
Classifier", 2018.
[3] P.Sudharshan duth and M. Mary Deepa, "Color detection in RGB modeled
images using MAT LAB", 2018.




