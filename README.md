# Modern Insights from Microscopy Images
> An Introduction to Web-based Methodologies


[![I2K](https://www.i2kconference.org/assets/images/banner-image.png)](https://www.i2kconference.org/)

Technological evolution poises modern, web-based methods as the future of bioimage
analysis. Moreover, web-based methods are better suited to solve challenges such as
extremely large images and reproducibility. In this tutorial, we will introduce the concepts,
approaches, and tools for modern, web-based open source bioimage analysis. An introduction
to the fundamentals of web-based imaging is covered through the topics of web-based image
visualization, image data storage for the web, distributed image processing in the cloud,
asynchronous programming, and re-usable deep learning components on the web. Content will
be presented in Jupyter notebook modules consisting of oral presentations, interactive material,
and hands-on exercises. 

## Installation

[Install mambaforge](https://github.com/conda-forge/miniforge), then:

```
git clone https://github.com/thewtex/modern-insights-from-microscopy-images
cd modern-insights-from-microscopy-images
mamba env create --file environment.yml --name i2k-web-2022
conda activate i2k-web-2022
python -m jupyter notebook
```

## Sections

1. [Introduction to Modern, Web-based Methodologies](./01_Introduction.ipynb)

<a href="https://colab.research.google.com/github/thewtex/modern-insights-from-microscopy-images/blob/master/01_Introduction.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

2. [Web-based Image Visualization](./02_Visualization.ipynb)

<a href="https://colab.research.google.com/github/thewtex/modern-insights-from-microscopy-images/blob/master/02_Visualization.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

3. [Image Data Storage for the Web](./03_Data_Storage.ipynb)
4. [Distributed Image Processing in the Cloud](./04_Distributed_Processing.ipynb)
