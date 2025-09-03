**About the Project:** In this repo, we explore the world of Image Processing using popular libraries OpenCV and Pillow. 

**Libraries Installed:** 
- Pillow: [Installation Guide](https://pillow.readthedocs.io/en/stable/installation.html)
- Numpy: [Installation Guide](https://numpy.org/install/)
- Matplotlib: [Installation Guide](https://matplotlib.org/stable/users/installing.html)
- OpenCV: [Intro to OpenCV](https://docs.opencv.org/4.x/d0/de3/tutorial_py_intro.html)

**Description of files:**
- **Image_rotation_manipulation.ipynb** : Learn how to load images using PIL and Save the manipulated images in different file formats (png and jpg). We apply multiple transformations to an image and understand the impact of each operation on the image data. To perform basic image manipulation operations using NumPy arrays.
- **Image_Noise.ipynb** : Here, we become familiar with different types of noise and filtering. To study the impact of different noises on image like Salt and Pepper, Gaussian noise. We implement convolution algorithm using numpy and investigate OpenCV's image filtering functions to denoise the image.
- **Image_filter_banks.ipynb** : We will combine filters into filter banks, with the objective to extract textures from an image. First, the OpenCV functions are used for the filter bank implementation. Then, the filter banks should be implemented without using the OpenCV, solely relying on numpy.
- **Edge_Corner_detection.ipynb** : The goal is to implement the Harris Corner Detector and compare the Laplacian of Gaussian (LoG) with the Difference of Gaussian (DoG) for texture extraction on the generated data.
- **SIFT_Algorithm.ipynb** : The attempt is to program the SIFT algorithm from scratch using the numpy (although it is not very efficient and still in progress. Open to any feedbacks). The refereces are:
[1]  David G. Lowe 2004, *Distinctive Image Features from Scale-Invariant Keypoints*, available at: https://www.cs.ubc.ca/~lowe/papers/ijcv04.pdf
[2] Ives Rey Otero 2014, *Anatomy of SIFT*, available at: https://www.researchgate.net/publication/283754272_Anatomy_of_the_SIFT_method

**Credits:** Special thanks to my professors at FAU Erlangen Germany for giving me the opportunity to explore Computer Vision algorithms during the course period.
