# OCR
## This repo contains an OCR (Optical Character Recognition) based Project using PILLOW, Pytesseract and OpenCV

The main goal is to read a newspaper and recognize faces and texts from each pages and display appropriate results when user searches for any keyword in the paper.

Tools/Modules Involved:
  i.   PILLOW for Image Processing
  ii.  OpenCV for Image Processing
  iii. Pytesseract for OCR (Optical Character Recognition)
 
An examplar view of the Newspaper's first page in binarized form is provided below:

<img src = "./Images/binarized_image.png" width = "500" align = "center"/>

Faces in the newspaper is recognized via haarcascade_frontalface_default.xml file whose github link is: https://github.com/opencv/opencv/blob/master/data/haarcascades/haarcascade_frontalface_default.xml

The faces are recognized as shown in the image:

<img src = "./Images/Faces.png" width = "500" align = "center"/>

Sample result when an user searches for "Christopher"

<img src = "./Images/Sample_result.png" align = "center"/>

You can see that it renders all the detected faces from first page of the paper, since it successfully finds the keyword in the newspaper text.
