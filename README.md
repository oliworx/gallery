Remove Exif data from source images:

    exiftool -all= *.jpg *.JPG

Create gallery: 

    thumbsup --input ./src/ --output ./gallery --title Gallery \
             --albums-output-folder a --albums-from "%path" \
             --cleanup true --photo-quality 80 --sort-media-by filename \
             --sort-albums-by title --theme-path ./theme-classic/theme/
see https://thumbsup.github.io/docs/ 
