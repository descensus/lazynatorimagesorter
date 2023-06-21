# lazynatorimagesorter
Sort your images the way I want it.


## Go to your image folder and remove all dupes

fdupes -r -N -d .

## Sort all images from the incoming folder into date folders based on exif.
exiftool '-Directory<CreateDate' -d years/%Y/%Y-%m -r incoming/
