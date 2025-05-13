# computer-vision-project-1-image-processing-on-threshold-solved
**TO GET THIS SOLUTION VISIT:** [Computer-Vision Project 1-Image Processing on Threshold Solved](https://www.ankitcodinghub.com/product/computer-vision-project-1-image-processing-on-threshold-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;93338&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Computer-Vision Project 1-Image Processing on Threshold Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
<pre>Project 1:  Given a grey-scale image, you are to perform the following tasks:
</pre>
<pre>     1. Compute histogram of the input image and display the histogram in two
        formats, see the output description below.
</pre>
<pre>     2. Perform binary threshold operation on the input image with a given
         threshold value via argv[].
</pre>
<pre>     3. Output the result of the threshold in two formats, see the output
         description below.
</pre>
************************************** Language: C++ ************************************** Project points: 10 pts

<pre>Due Date: Soft copy (*.zip) and hard copies (*.pdf):
           -0 2/14/2021 Sunday before midnight
</pre>
<pre>           -1 for 1 day late: 2/15/2021 Monday before midnight
           -2 for 2 days late: 2/16/2021 Tuesday before midnight
           -10/10: 2/16/2021 Tuesday after midnight
</pre>
<pre>*** Name your soft copy and hard copy files using the naming convention as
given in the project submission requirement discussed in a lecture and is
posted in Google Classroom.
</pre>
*** All on-line submission MUST include Soft copy (*.zip) and hard copy (*.pdf) in the same email attachments with correct email subject as stated in the email requirement; otherwise, your submission will be rejected.

<pre>1. Run your program on data1 with threshold 5
2. Run your program on data2 with threshold 38.
3. Include in your hard copy *.pdf file as follows:
</pre>
<pre>     - Cover page.
     - source code.
     - Output outFile1 for data 1.
     - Output outFile2 for data 1.
     - Output outFile3 for data 1.
     - Output outFile4 for data 1.
     - Output outFile1 for data 2.
     - Output outFile2 for data 2.
     - Output outFile3 for data 2.
     - Output outFile4 for data 2.
</pre>
<pre>**********************************************
I. Input: There are two inputs to the program.
**********************************************
</pre>
a) inFile1 (argv[1]):

a txt file representing a grey-scale image, where

the first text line (4 integers) is the “header” of the input image then follows by rows and cols of integers.

For example,

<pre>     4  6  1 12    // image has 4 rows,6 cols, min is 1, max is 12
     2  3  4 11  2  9
     5  6 11  2 10  7
     1  1 12  1  9  9
</pre>
456999

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>b) a threshold value (argv[2])
</pre>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
******************************************* II. Outputs: There are four output files. *******************************************

<pre>   a) OutFile1 (use argv[3]): For the output of histogram in the following
     format (to be used in the future project):
     The first text-line is the image header, follows by a list of pairs &lt;i, j&gt;
     where i = 0 to max and j is the hist(i)
     For example:
</pre>
4 6 1 12 00 13 23 31 42 52 62 71 80 96

10 1 11 2 12 1

b) OutFile2 (use argv[4]): Display the histogram (for visual) as follows: first text line is the image header then follows by a list of : greyScale (numpixels): number of +’s

for example, the output of the histogram of the above image would be: Use the maximum of 70 +’s for all counts greater than 70. Use small font size so that 70 +’s can be printed on one text line.

<pre>      4 6 1 12
     0  (0):
     1  (3):+++
     2  (3):+++
     3  (1):+
     4  (2):++
     5  (2):++
     6  (2):++
     7  (1):+
     8  (0):
</pre>
<pre>     9  (6):++++++
     10 (1):+
     11 (2):++
     12 (1):+
</pre>
<pre>c) outFile3 (use argv[5]): The result of the threshold of the input image. (To
     be used for future processing.)
</pre>
<pre>    Note: The output binary image also needs to have the image header.
     For example, given the above image and 6 as the threshold value
     then the binary image would be:
</pre>
4 6 0 1 // notice the min and max values have changed 0 and 1. 000101

011011

001011

001111

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
d) outFile4 (use argv[6]): (For nice visual purposes).

For example, given the above threshold image, the pretty print replace 0 with a period.

4601 …1.1 .11.11 ..1.11 ..1111

<pre>*******************************
III. Data structure:
*******************************
- image class
</pre>
<pre>     - numRows (int)
     - numCols (int)
     - minVal (int)
     - maxVal (int)
     - histAry(int*) //a 1D integer array, size of maxVal + 1
</pre>
<pre>                      // need to be dynamically allocated at run time
     - thresholdValue (int) // via argv[2]
</pre>
<pre>     Methods:
     - computeHist(...) // The algorithm is given in the lecture note
     - printHist (...)// on your own; see the above example
     - dispHist (...)// on your own; see the above example
     - threshold(...) // The algorithm is given below
</pre>
*******************************

IV. main (…) *******************************

step 0: inFile  open input file use argv[1]

<pre>        open all 4 outFiles via argv[3], argv[4], argv[5], argv[6]
</pre>
step 1: numRows, numCols, minVal, maxVal  read from inFile step 2: histAry  dynamically allocate and initialize to 0 step 3: ComputeHist (…)

step 4: printHist(outFile1)

<pre>Step 5: dispHist (outFile2)
</pre>
<pre>step 6: close inFile
        reopen inFile
</pre>
Step 7: thrVal  get from argv[2]

outFile3  “The threshold value uses is ” thrVal

outFile4  “The threshold value uses is ” thrVal Step 8: threshold (inFile, outFile3, outFile4, thrVal) step 9: close all files

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
************************************************* V. threshold (inFile, outFile3, outFile4, thrVal) ************************************************* Step 0: minVal  0

maxVal  1

Step 1: outFile3, outFile4  output numRows, numCols, minVal and maxVal Step 2: pixelVal read from inFile one integer at a time

<pre>Step 3: if pixelVal &gt;= thrVal
               outFile3 &lt;-- write 1 follows by a blank
</pre>
<pre>               outFile4 &lt;-- write 1 follows by a blank
        else
</pre>
<pre>               outFile3 &lt;-- write 0 follows by a blank
               outFile4 &lt;-- write . follows by a blank
</pre>
<pre>Step 4: repeat step 2 to 3 until the inFile is empty
</pre>
</div>
</div>
</div>
