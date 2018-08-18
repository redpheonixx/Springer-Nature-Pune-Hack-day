<h1>Springer-Nature-Pune-Hack-day</h1><br>.<br>
-------------------------------------------------------------------------------------------------------------------

This repo is for the Springer Nature Pune hack day competition
<h3>Problem</h3>
<br>
Every publisher aspires to automate the identification, classification, enhancing, etc. of images using computer vision, which has a large variety of practical applications. Since this task of recognizing a visual concept is relatively trivial for a human to perform and is worth considering the challenges involved are from the perspective of a computer vision model. This problem statement talks about the need to automate the identification of the images as color or grey, which would help the publisher in decision making.
<br>
Background Information
<br>
The manuscripts submitted by authors have many images inside it. These images can be either colour or grey or both. As part of the business services, the author submitted images will be processed by the publisher before publication. The processing of images differs for color and grey scale images. The identification of this helps to further automate their processing.
<br>
Use Case
<br>
Verify whether the image is grey or color along with the percentage of confidence
<br>
------------------------------------------------------------------------------------------------------------------------------
<br><br>
<h3>Solution</h3>
<br>
I used concept of transfer learning as the dataset was too small to train a CNN model. I used VGG19 model with imagenet weights and trained the model on local dataset provided by tech-gig. I also used data augmentation to increase number of images.
<br>
------------------------------------------------------------------------------------------------------------------------------
<br>
<h3>Results</h3>
I got an accuracy of 0.9861 and loss of 0.0592.


