# arab-clothes-image-classifcation
This project expands on the TensorFlow tutorial "Basic classification: Classify images of clothing" by training the model to recognize three new labels that represent Muslim/Arab clothing.

For more information about me, please visit my LinkedIn:

[![LinkedIn][LinkedIn.js]][LinkedIn-url]


<div align="center">
  <h3 align="center">A brief Read.me introducing the project and its contents</h3>
    <br />
  </p>
</div>



<!-- ABOUT THE PROJECT -->
## About The Project

The "Basic classification" Clasify images of clothing" Tensorflow tutorial trains a neural network model to classify images of clothing, like sneaker and shirts. The guide uses the Fashion MNIST dataset which contains 70,000 grayscale images in 10 categories.

For this project, I've create a new dataset that includes additional labels not present in the current algorithm. Specifically, I've added three labels - abaya, thobe, and hijab - which are types of clothing commonly associated with Islamic and Arabic cultures.

After generating the new dataset with the additional labels, I've retrained the model using this updated data. I then evaluated the performance of the retrained model to assess its accuracy and effectiveness in classifying the new labels.

### What are Hijabs, Abayas, and Thobes? 

Hijab generally refers to headcoverings worn by some Muslim women. It is similar to the wimple, apostolnik, and mantilla worn by some Christian women.

The abaya is a simple, loose over-garment, essentially a robe-like dress, worn by some women in parts of the Muslim world including North Africa, the Arabian Peninsula, and most of the Middle East.

The Thobe, also written as "Thawb", is an ankle-length robe, usually with long sleeves. It is commonly worn in the Arabian Peninsula, the Middle East, North Africa, and other neighbouring Arab countries, and some countries in East and West Africa.

Heres a demonstration of each clothing garment, along with their classification:
![image](https://user-images.githubusercontent.com/112829375/235896519-90dc82e1-8552-4081-9eed-20241fad5ff0.png)




### Built With

The frameworks and libraries used within this project are:

* [![TensorFlow][Tensorflow.js]][Tensorflow-url]
* [![Keras][Keras.js]][Keras-url]
* [![NumPy][NumPy.js]][NumPy-url]
* [![Matplotlib][Matplotlib.js]][Matplotlib-url]
* [![Open In Colab](https://img.shields.io/badge/Open%20In-Colab-yellowgreen?style=for-the-badge&logo=googlecolab)](https://colab.research.google.com/)


<!-- Dataset -->
### Dataset

The Fashion MNIST is split into a training set of 60,000 images and a test set of 10,000 images.

The 10 different clothing item classes in it are:
1. T-shirt/top
2. Trouser
3. Pullover
4. Dress
5. Coat
6. Sandal
7. Shirt
8. Sneaker
9. Bag
10. Ankle boot

The 3 clothing item classes that I've added are:

11. Abaya
12. Thobe
13. Hijab

Due to limited resources, only a 100 images of each class were collected. The images were collected from google, in .PNG format, then later converted in the code to fit the image format found in the fashion MNIST dataset. 

This includes preprocessing the data to be a 28x28 pixels, converting the images to greyscale, and normalizing the pixel values to be between 0 and 1.

<!-- GETTING STARTED -->
## Getting Started

To get the project running, there's a couple of programs and steps needed. here are the steps: 

### Prerequisites

If using Google colab to test the project, you need:

1. a Google colab account
2. Access to a GPU
3. Internet/Wi-Fi

If you plan on running it on python, you need to install on your computer the following:

1. Python
2. pip 
3. PyCharm 
4. Tensorflow, Keras, NumPy, Matplotlib


### Steps to run the code:

1. Open the following google drive link where you can access all the files for the project, such as the original images, oral live presentation, and the "arab-clothes-image-classification.ipynb" colab notebook.

google drive link: https://drive.google.com/drive/folders/1PVoEKWw9CZA9c138N9SMYqJP9WvL-T1K?usp=share_link

2. download the "arab-clothes-image-classification.ipynb" notebook.
3. Make sure the correct google drive is mounted
4. run the "arab-clothes-image-classification.ipynb" notebook

if you prefer to run the code on your own, without accessing the google drive link provided earlier, simply download the attached files in this repository, and create your own google drive file with all the files uploaded into it.
   

<!-- NEW LABELS IMAGE EXAMPLES -->
## Image examples

Here is a snapshot of how the images for the new labels, after they've been preprocessed, look like:

![image](https://user-images.githubusercontent.com/112829375/235897301-c6795324-af8c-4a87-a9ea-fc7425dda553.png)

![image](https://user-images.githubusercontent.com/112829375/235897529-89753437-1842-477f-b3a4-319e2e482a8c.png)

![image](https://user-images.githubusercontent.com/112829375/235896781-38f344dc-1cea-4d6f-8505-53e09542459f.png)

<!-- LICENSE -->
## License

No License used.

<!-- CONTACT -->
## Contact

Sali E-loh - [@Sali El-loh](https://www.linkedin.com/in/salielloh12/) - ellohsali@gmail.com


<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

This project was inspired by the TensorFlow, "Basic classification: Classify images of clothing" tutorial.

* [TensoFlow: Clothes Image Classification Tutorial](https://www.tensorflow.org/tutorials/keras/classification)

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[LinkedIn.js]: https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white
[LinkedIn-url]: https://www.linkedin.com/in/salielloh12/
[Tensorflow.js]: https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white
[Tensorflow-url]: https://www.tensorflow.org/
[Keras.js]: https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white
[Keras-url]: https://keras.io/
[NumPy.js]: https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white
[NumPy-url]: https://numpy.org/
[Matplotlib.js]: https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black
[Matplotlib-url]: https://matplotlib.org/

