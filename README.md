# Codeforces-rateDetector
play a file sound - song- once the rating changes at all the participants  of some round. Also if a handle was given the program will output the the changes to that handle
<h4>This is only working on windows; However line 35 can be tweaked to work on linux - I just don't know how 🤷‍♂️ -
<h3>How to use:<h3/>
<ol>
<li>navigate to the folder that contain this script</li>
<li>add the file to be played</li>
 <li>name the sound file "so.mp3" or change the variable "file" in the script to the file name</li>
 <li>(optional) Change the variables "secs" to the number of seconds between requests</li>
 <li>run in the command line <code>python run.py [contest id] [handle(optional)]</code>
 </ol>
 <h4>example</h4>
 <code>python run.py 1047 theunderdog</code>
 <br>
 <code>python run.py 1047</code>