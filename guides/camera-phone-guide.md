## Camera Phone Guide

You phone's camera is a powerful for two reasons:
1. It lives in your pocket - "the best camera you have is the one that you have on you"
2. Spatial Metadata - your photos (if location services are enabled) will have location data and other metadata about where the photo was taken.
3. The "data" is easily stored and organized. 


### DATA COLLECTION

On a simple level, you can think of your camera phone as:
1. point
2. shoot

To get a bit more detailed, you can start defining rules like:
1. All photos are taken in landscape mode (vs. portrait mode).
2. All subjects in the photo are centered directly in the middle of the frame.
3. All photos will be in color (as opposed to black and white).
4. Photos can be taken in nighttime and daytime.
5. The GPS location data must always be available in the metadata of the image.

   
And to get even more detailed still, you can add to your list of rules:
1. The subject will be at least 6ft (~2m) away from the camera. 
2. The camera must always be level with ground and not angled more than X degrees upwards or downwards.
3. The focal length of the camera must always be set at Xmm. 
4. ... ( and you can continue defining the details)

### DATA PROCESSING

On a simple level, you can process your data like:
1. All photos will be stored in a folder called "Paying Attention Project"
2. All photos will be added to a blog post with a caption.

To get a bit more detailed:
1. All photos will be named like so: `YYYYMMDD__name-of-object__latitude__longitude.jpg`
2. All photos will include metadata description of the information in the image and any notes collected about that image.

To get even more detailed and sophisticated:
1. Every time a photo is loaded to my computer, I will run a script that will export a JSON file that includes, for each image, the name of the image, the location information, and any associated metadata. The script will also generate an interactive map of those locations. You can use tools like [img2meta by @JoeyKlee](https://github.com/joeyklee/img2meta) to get the metadata from your images.

### Helpful Tools

* [How to See an Image’s EXIF Data in Windows and macOS, How-To Geek](https://www.howtogeek.com/289712/how-to-see-an-images-exif-data-in-windows-and-macos/)
* [img2meta by @JoeyKlee](https://github.com/joeyklee/img2meta)
  * Commandline tool to get the image metadata from your images (tested on iphone 5 and 7)
* [MacOS Photos App](https://www.apple.com/macos/photos/)
* [Carrying a Camera, Tom MacWright](https://macwright.org/2017/11/03/carrying-a-camera.html) // I do agree that a dedicated camera creates intentionality about what we are looking at, however, I do think the camera phones, particularly those with GPS enabled, provide us different outcomes than just capturing what is in our field of view. 