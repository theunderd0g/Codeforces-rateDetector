# Codeforces-rateDetector
play a file sound - song- once the rating changes at all the participants  of some round. Also if a handle was given the program will output the the changes to that handle
<h4>This is only working on windows; However line 35 can be tweaked to work on linux - I just don't know how ¯\_O_/¯ -</h4>
<h3>How to use:<h3/>
<dl>
<dt>Easy way (pip)</dt>
<dd>
<ol>
<li><code>pip install cfrate</code></li>
<li><code>cfrate [contest-id] [handle(optional)]</code></li>
<li>example</li><br>cfrate 1066 theunderdog</li>
</ol>
</dd>
<dl>not-so-easy way (clone)</dl>
<dd>
<ol>
<li>navigate to the folder that contain this script</li>
<li>add the file to be played</li>
 <li>name the sound file "so.mp3" or change the variable "file" in the script to the file name</li>
 <li>(optional) Change the variables "secs" to the number of seconds between requests</li>
 <li>run in the command line <code>python run.py [contest id] [handle(optional)]</code>
 <li><h4>example</h4>
 <code>python run.py 1047 theunderdog</code>
 <br>
 <code>python run.py 1047</code>
 </dd></li>
 </dl>
