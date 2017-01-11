
# Lecture 1-Introduction

Tag： Note

---

### **1. Visual Perception**

 - How do we know that the objects that we see
are for?
 - Can people “see” without being aware of
what they see?
 - Why do objects appear colored?

**Definition:** Process of acquiring knowledge about environmental objects
and events by extracJng informaJon from the light they emit or reflect
[Palmer, 2012].

 ![img1.1](https://raw.githubusercontent.com/Mr0Moonlight/Computer-Vision-Course-Note/master/relevant%20materials/picture/1.1.JPG)

 ![img1.2](https://raw.githubusercontent.com/Mr0Moonlight/Computer-Vision-Course-Note/master/relevant%20materials/picture/1.2.JPG)
 
     `Perception is analogous to taking a picture! (credit: Palmer, 2012)`

Vision is a process in which temporally changing intensity and color values in the image plane have to be interpreted as processes in the real world that happen in 3D space over time.

### **2. Vision-Eye-Light**

 ![img1.3](https://raw.githubusercontent.com/Mr0Moonlight/Computer-Vision-Course-Note/master/relevant%20materials/picture/1.3.JPG)
 
    `Credit: Schwarts, 2009`
 
**Retinal Processing:** Photoreceptors absorb Light quanta and convert. This radiant energy into Electrical activity. They synapse on bipolar cells, which in turn, can stimulate ganglion cells, thereby sending action potentials along the optic nerve to the LGN(lateral Geniculte nucleus).

### **3. Vision and Image Understanding**

**Visual tasks:** We use vision to interact with environments and survive – to navigate and avoid obstacles, to recognize and pick up objects, to iden8fy food and danger, friends and enemies, …

### **4. What is a (digital) Image?**

**Definition:** A digital image is defined by integraJng and sampling continuous (analog) data in a spa8al domain [Kleve, 2014] .

![img1.4](https://raw.githubusercontent.com/Mr0Moonlight/Computer-Vision-Course-Note/master/relevant%20materials/picture/1.4.JPG)

**Picture Elements - PIXEL**

![img1.5](https://raw.githubusercontent.com/Mr0Moonlight/Computer-Vision-Course-Note/master/relevant%20materials/picture/1.5.JPG)

`PIXELS are ATOMIC ELEMENTS of an image. In late 1960s, 
terminology ‘pixel’ was introduced by a group of scientist 
at JPL in California!`

###**5. Image Types**

**Scalar and Binary**

 - A scalar image has integer values:
  $$\mu \epsilon \begin{bmatrix}0,1,...,2^{\alpha }-1\end{bmatrix}$$
 - a: level (bit)
  Ex. If 8 bit (a=8), image spans from 0 to 255
  **0:black
  255:white**
Ex. If 1 bit (a=1), it is binary image, 0 and 1 only.

**RGB (red, green, blue)**

 - Image has three channels (bands), each channel spans a-bit values.

**Image Format**

 - **Some formats:** TIF, PGM, PBM, GIF, JPEG, PNG, RAW,…
 - **Medical Images:** DICOM, Analyze, NIFTI,…

 - **HEADER:** contains image informa8on, image size, pixel size, …
 - **DATA:** integer, double, float, unsigned integer, char,…

###**6. Color**

 - If there is no light, there is no color!
 - Human vision can only discriminate a few dozens of grey levels on a screen, but hundreds of thousands of different colors.
  - RED -> ~625 to 780 nm [long wavelength]
  - ORANGE -> ~ 590 to 625 nm [long wavelength]
  - YELLOW -> ~565 to 590 nm [middle range wavelength]
  - GREEN -> ~ 500 to 565 nm [middle range wavelength]
  - CYAN -> ~485 to 500 nm [ middle range wavelength]
  - BLUE -> ~440 to 485 nm [short wavelength]
  - VIOLET -> ~330 to 440 nm [very short wavelength]
 - **Color vision has evolved over millions of years.**
 
![img1.6](https://raw.githubusercontent.com/Mr0Moonlight/Computer-Vision-Course-Note/master/relevant%20materials/picture/1.6.JPG)

###**7. Retina of Human Eye**

![img1.7](https://raw.githubusercontent.com/Mr0Moonlight/Computer-Vision-Course-Note/master/relevant%20materials/picture/1.7.JPG)

 - There are three different types of color-sensi8ve cones corresponding to (roughly) RED (64% of the cones), GREEN (about 32%), and BLUE (about 2%).
 - 6-7 million cones, 120 million rods

###**8. Example Projects from Fall 2015**

- SIFT-Flow (ECCV 2008 paper) [Joshua]
- Grab-Cut [Karan]
- CamShie (tracking cars) [Krushhal]
- MRF Op8mization by Graph Approximation [Kirsche]
- Canny Edge Detection as a smartphone app [Zixia]
- Mul8-object tracking [Hong Zhang]
- Several mobile phone applications (with Processing)
 - Finger, color, face tracking with mobile phone..
 
 
 <img src="http://latex.codecogs.com/gif.latex?\frac{\partial J}{\partial \theta_k^{(j)}}=\sum_{i:r(i,j)=1}{\big((\theta^{(j)})^Tx^{(i)}-y^{(i,j)}\big)x_k^{(i)}}+\lambda \theta_k^{(j)}" />  

