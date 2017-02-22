
# Lecture2  Filtering

##  ** Outline **
 - ** Image as a function **
 - ** Extracting useful information from Images **
  - Edges
  - Smoothing/Removing noise
  - Convolution/Correlation
  - Image Derivatives/Gradient
  - Histogram
 - ** Some coding examples **

##  ** Correlation and Convolution **


![2.1](https://raw.githubusercontent.com/LoserSun/Computer-Vision-Course-Note/master/relevant%20materials/picture/2.1.JPG)

![2.2](https://raw.githubusercontent.com/LoserSun/Computer-Vision-Course-Note/master/relevant%20materials/picture/2.2.JPG)

![2.3](https://raw.githubusercontent.com/LoserSun/Computer-Vision-Course-Note/master/relevant%20materials/picture/2.3.JPG)


##  ** [Unsharp masking](https://en.wikipedia.org/wiki/Unsharp_masking) **

![2.4](https://raw.githubusercontent.com/LoserSun/Computer-Vision-Course-Note/master/relevant%20materials/picture/2.4.JPG)

![2.5](https://raw.githubusercontent.com/LoserSun/Computer-Vision-Course-Note/master/relevant%20materials/picture/2.5.JPG)

![2.6](https://raw.githubusercontent.com/LoserSun/Computer-Vision-Course-Note/master/relevant%20materials/picture/2.6.JPG)

## ** Noise and Denoising **

 - ** Low-pass filtering is normally thought of as
    the elimination of signal component with high
    spatial frequencies. **
    
    ![2.7](https://raw.githubusercontent.com/LoserSun/Computer-Vision-Course-Note/master/relevant%20materials/picture/2.7.JPG)
    
 ###  ** Noise **
 
 
  - ** Iobserved = Ioriginal + n additive **
  - ** Iobserved = Ioriginal*n multiplicative **
  - ** Light/brightness variations, camera **
    - ** hardware/lenses, surface reflectance **
  - ** Random in nature, occurring with some 
    probability **
  - ** It has a distribution (Gaussian (white), Poisson,..) **
  
   ![2.8](https://raw.githubusercontent.com/LoserSun/Computer-Vision-Course-Note/master/relevant%20materials/picture/2.8.JPG)
   
 ### ** Why Gaussian Assumption? **

- ** Most common natural model **
- ** Smooth function, it has infinite number of derivatives **
- ** It is Symmetric **
- ** Fourier Transform of Gaussian is Gaussian. **
- ** Convolution of a Gaussian with itself is a Gaussian. **
- ** Gaussian is separable; 2D convolution can be
  performed by two 1-D convolutions. **
- ** There are cells in eye that perform Gaussian filtering. **
   
  
