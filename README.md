Program to segment images into at least 2  
And at most 7 segments of greyscale  
The program will automatically save single and double thresholded segmentations  

<h2>To run from the terminal/command line</h2>  
`git clone https://github.com/aretheregods/multisegmentpython  
cd multisegmentpython`  
  
<h3>_Initialize virtualenv in project folder (Must have virtualenv installed)_</h3>  
`_pip install virtualenv` ###to install virtualenv on your system  
`virtualenv env`  
  
<h3>_Activate virtualenv_</h3>  
<h3>windows</h3>  
`env/Scripts/activate`  
  
<h3>osx/linux</h3>  
`source env/bin/activate`  
  
<h3>To use the program,</h3>  
<h3>call the main.py file followed by the image you want to segment</h3>  
`python main.py my_image.imagefile`  
  
  
<h2>If you want to have more image classes saved</h2>  
<h2>Just call it from the terminal like so</h2>  
`python main.py my_image.imagefile number_of_segments` [[You can have up to 7]]  
  
The program will then output your resulting images titled like so "my_image_segmented_#.imagefile"  
Where "#" is the number of classes used in the image.  
