# Nephthis-BP-VBO---Extended-Image-Manipulation
VB Object to fill gaps left by the OOB Image Manipulation VBO

## Crop
Returns the specified part of an image. If width and height are not specified (ie, zero) then it'll return the rest of the image past the crop coordinates.

### Inputs:
* Image - Image
* Crop X - Number
* Crop Y - Number
* Crop Width - Number
* Crop Height - Number

### Outputs:
* Cropped - Image

## Get SubImage Position (Fast)
Finds whether the main image contains a sub image, and if found gives the X,Y coordinates of the sub image. Can be faster than the default version of this function, since the image bits are locked before comparing.

### Inputs:
* Main Image - Image
* Potential SubImage - Image

### Outputs:
* X Index - Number
* Y Index - Number
* Contained - Flag

## Screenshot Desktop
Takes a screenshot of the desktop

### Outputs:
* Image Out - Image

## Save Image
Saves an image to the specified file

### Inputs:
* Image - Image
* Path - Text
* Image Format - Text

### Outputs:
* Success - Flag
* Message - Text
