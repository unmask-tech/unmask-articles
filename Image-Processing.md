# Image Processing 

Before we dive into what is image processing lets first understand the fundamental element of Image Processing that is "The Image".

So __What is The Image?__
The Image is a visual representation of a subject in two or three dimensions, usually a physical object, which provides a deception of it.
The image can be two-dimensions such as photograph or three-dimensions such as a hologram, objects in the VR system.

Definition of image changes based on context such as in [signal processing an image is an example of a two-dimensional signal, with the horizontal and vertical coordinates of the image representing the two dimensions.] [1]

In the field of Image Processing, we generally deal with __Digital Images__.
Digital Image is an image composed of _picture elements_, also known as __*pixels*__, each with a numerical representation of its _intensity_ or _gray level_.

We can use optical devices such as cameras, mirrors, lenses, telescopes, microscopes, etc. to capture or software such as Gimp, Paint, Adobe Photoshop, to produce digital images.

(examples of images from different sources)


Digital images get divided into two types "Vector" and "Raster". 
_The terms digital image generally represents raster images._

Raster image (Digital Image/Image) contains a finite set of pixels.
The digital image contains a fixed number of rows and columns of pixels.

[__The Pixel__][2] is the _smallest addressable_ element in the digital image. Pixels hold a _brightness_ of a given color at any specific point. In color imaging system color is represented by three or four component intensities such as _red, green, blue_ (RGB) or _cyan, magenta, yellow, and black_ (CMYK).

As mentioned before, the digital image contains a fixed number of rows and columns of pixels. It means the digital image is a two or three-dimensional _array or matrix_ of pixels or intensity values. 

By performing the various mathematical operations on these matrices, we can extract different pieces of information from the image, such as the number of objects in the image their relative position, shape, size, etc. 

The process of _extracting information_ from the digital image using computation is known as __Digital Image Processing__.



[1]: <https://ieeexplore-ieee-org.ezproxy.lib.monash.edu.au/stamp/stamp.jsp?tp=&arnumber=8454362>
[2]: we will discuss pixel, color, the intensity in later articles

