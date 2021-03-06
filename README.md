Program to segment images into at least 1  
And at most 7 segments of greyscale  
The program will automatically save single and double thresholded segmentations  

<h2>To run from the terminal/command line</h2>  
<pre>git clone https://github.com/aretheregods/multisegmentpython  
cd multisegmentpython</pre>  
  
<h3>Initialize virtualenv in project folder <em>(Must have virtualenv installed)</h3>  
<pre>pip install virtualenv</pre> <h3>To install virtualenv on your system</h3></em>  
<pre>virtualenv env</pre>  
  
<h3><em>Activate virtualenv</em></h3>  
<h3>Windows</h3>  
<pre>env/Scripts/activate</pre>  
  
<h3>osx/linux</h3>  
<pre>source env/bin/activate</pre>  
  
<h3>To use the program,</h3>  
<h3>Call the main.py file followed by the image you want to segment  
And <em>(optionally)</em> add the initial number of segmentations followed by the total number.<br />
For instance, if you wanted only a 3 segmented image, you'd enter</h3>  
<pre>python main.py my_image.imagefile 3 3</pre>  
<h3>If you wanted a single, double and 3 segmented image</h3>  
<pre>python main.py my_image.imagefile 1 3</pre>
  
  
<h2>If you want to have more than 2 image segmentations saved</h2>  
<h2>Just call it from the terminal like so</h2>  
<pre>python main.py my_image.imagefile initial_segmentation total_number_of_segments</pre>  
<em>You can have up to 7 segmentations</em>  
  
The program will then output your resulting images titled like so "my_image_segmented_#.imagefile"  
Where "#" is the number of classes used in the image.  
