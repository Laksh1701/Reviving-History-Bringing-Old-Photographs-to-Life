# Reviving-History-Bringing-Old-Photographs-to-Life
"Reviving History: Bringing Old Photographs to Life" is a project that focuses on using deep learning techniques to enhance and colorize old and historical photographs. The project aims to breathe new life into these images by leveraging advanced computer vision algorithms.

The project involves training deep neural networks to learn the patterns and characteristics of historical photographs, allowing them to intelligently fill in missing details, enhance image quality, and add color information to grayscale images. 

The project works with two different colorization models: ECCV16 and SIGGRAPH17. These models are pre-trained deep learning models that can generate color information for grayscale images. ECCV16 and SIGGRAPH17 are the names of the respective models.

The ECCV16 model is based on the ECCV 2016 paper titled "Deep Colorization" and utilizes a CNN architecture to predict the chrominance (color) information for grayscale images.

The SIGGRAPH17 model is based on the SIGGRAPH 2017 paper titled "Learning Representations for Automatic Colorization" and also employs a CNN architecture to perform image colorization.

The code loads the specified image, preprocesses it, and then passes it through the selected colorization model. The colorized output is then postprocessed and displayed using the matplotlib library. Additionally, the colorized image is saved as a file.

# Modules Knowledge
* torch
* skimage
* numpy
* matplotlib
* argparse
* PIL
