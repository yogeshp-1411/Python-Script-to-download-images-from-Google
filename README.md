# Python-Script-to-download-images-from-Google
This python scripts takes they keyword as an input, searches it on google and downloads the images into a folder.  This script has been developed to create custom database for my Hobby project.

The attached .ipynb file contains Python script to download images from Google. Beautiful Soap is used to parse the HTML. 

If the "img" class is not found in your HTML then you would need to inspect the image you want to download and check for the class which contains the appropriate link. 

The attached screenshot illustrates how the image should be inspected on your Google Chrome Browser. Right click on the image and press inspect. You can hover over the source link to verify the image link which is to be downloaded. 

I have ommitted the links which do not contain https:// or http:// as I was not able to download those links; reason being the links were compressed while parsing. 
