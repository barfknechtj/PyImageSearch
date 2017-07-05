# Goal
Identify differences between two images (e.g. Original.png and Modified.png)

# Dependencies
* skimage
* imutils
* argsparse (STL)
* opencv2 (not shown in pipfile as it was built from src) 

# Execution
`python3 image_diff.py --first Original.png --second Edited.png`

# Example
## Original Lighthouse picture
![Original](https://github.com/barfknechtj/PyImageSearch/blob/master/ImageDiff/Original.png "Original Image")

## Edited Lighthouse picture (window missing)
![Edited](https://github.com/barfknechtj/PyImageSearch/blob/master/ImageDiff/Edited.png "Edited Image")

## Processed image shows difference
![Modified](https://github.com/barfknechtj/PyImageSearch/blob/master/ImageDiff/OutputFile_Modified.png "Modified Image")
