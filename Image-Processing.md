# Image Processing 

Before we dive into what is image processing lets first understand the fundamental element of Image Processing that is "The Image".

So __What is The Image?__
The image is a visual representation of a subject in two or three dimensions, usually a physical object, which provides a depiction of it.
The image can be two-dimensional such as a photograph or three-dimensional such as a hologram, objects in the VR system. The Definition of image changes based on context for instance in signal processing an image is an example of a two-dimensional signal, with the horizontal and vertical coordinates of the image representing the two dimensions.[^1]

In the field of Image Processing, we generally deal with __Digital Images__.
A digital image is an image composed of _picture elements_, also known as __*pixels*__, each with a numerical representation of its _intensity_ or _gray level_. We acquire digital images using cameras (os in some cases using scanned photo acquisition method), which can couple to optical devices such as telescopes, microscopes, etc. to capture.  Or we can use software such as Gimp, Paint, Adobe Photoshop, to produce digital images.

(examples of images from different sources)


Digital images get divided into two types "Vector" and "Raster". _The terms *Digital Image* generally represents raster images._ Raster image (digital image/image) contains a finite set of pixels. The digital image has a fixed number of rows and columns of pixels.

__The Pixel__ is the _smallest addressable_ element in the digital image. Pixels hold a _brightness_ of a given color at any specific point. In color imaging system color is represented by three or four component intensities such as _red, green, blue_ (RGB) or _cyan, magenta, yellow, and black_ (CMYK). To store these pixels in files, we use specific formate compressed or raw (as it is). These file formats are known as image file formats. Some well-known file formats are JPEG, PNG, TIFF, etc. [^2]

As mentioned before, the digital image contains a fixed number of rows and columns of pixels. It means the digital image is a two or three-dimensional _array or matrix_ of pixels or intensity values. 

By performing the various mathematical operations on these matrices, we can extract different pieces of information from the image, such as the number of objects in the image their relative position, shape, size, etc. 

The process of _extracting information_ from the digital image using computation is known as __Digital Image Processing__.



[^1]: [What is a Signal?](https://doi.org/10.1109%2FMSP.2018.2832195 "What is a Signal?")
[^2]: we will discuss pixel, color, the intensity and file formats in later articles
