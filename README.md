Program to segment images into at least 2  
And at most 7 segments of greyscale  
The program will automatically save single and double thresholded segmentations  

##To run from the terminal/command line  
`git clone https://github.com/aretheregods/multisegmentpython  
cd multisegmentpython`  
  
###_Initialize virtualenv in project folder (Must have virtualenv installed)_  
`_pip install virtualenv` ###to install virtualenv on your system
`virtualenv env`  
  
###_Activate virtualenv_
###windows  
`env/Scripts/activate`  
  
###osx/linux  
`source env/bin/activate`  
  
###To use the program,  
###call the main.py file followed by the image you want to segment  
`python main.py my_image.imagefile`  
  
  
##If you want to have more image classes saved  
## Just call it from the terminal like so  
`python main.py my_image.imagefile number_of_segments [[You can have up to 7]]`  
  
The program will then output your image appended with "crushed_#"  
Where "#" is the number of classes used in the image.  
