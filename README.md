# gallery1
gallery for fun stuff - testing

For adding more sections and more images

1) To generate thumbnails and get the html code to add more images/sections, open terminal, make sure you have python installed, go to the folder with the photos, activate virtual environment(https://github.com/haltakov/simple-photo-gallery/blob/master/doc/InstallWithVenv.md) where you have installed simple-photo-gallery and run "gallery-init" and "gallery-build" (https://github.com/haltakov/simple-photo-gallery).
2) Convert HEIC images to jpeg, name your images as xxx_1_1 to xxx_1_9 and then xxx_2_1 to 2_9 and so on if you want them ordered in a particular way
3) Upload the photos and the thumbnails in the respective folders in this repository. 
4) Open on the browser the index.html file generated in the folder, and view page source. Just paste the lines of code corresponding to the new images or section where you want. 
5) Note - for each new section data-index will start from 0 as the default case but data-gallery for each new section will have to be changed to the total number of all the images in all the previous sections. 
