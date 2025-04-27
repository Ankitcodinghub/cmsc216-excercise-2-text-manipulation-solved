# cmsc216-excercise-2-text-manipulation-solved
**TO GET THIS SOLUTION VISIT:** [CMSC216 Excercise 2-Text Manipulation Solved](https://www.ankitcodinghub.com/product/cmsc216-excercise-2-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;101627&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;4&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (4 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CMSC216 Excercise 2-Text Manipulation Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 138px;">
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
            5/5 - (4 votes)    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
1 Objectives

To practice strings and pointers.

2 Overview

First copy the directory text manipulation in the grace cluster under the exercises directory. It contains the .submit file that allows you to submit.

3 Specifications

For this exercise you will implement two functions that manipulate text. The prototypes for the functions can be found in file text manipulation.h.

<ol>
<li>int remove spaces(const char *source, char *result, int *num spaces removed);This function places a copy of the source string in the out parameter result where all leading and trailing spaces have been removed. If the out parameter num spaces removed is different than NULL, the func- tion will set the integer associated with the parameter to the number of spaces removed. The function will return one of two values: FAILURE or SUCCESS (see file text manipulation.h).
<ol>
<li>FAILURE – if the source string is NULL or its length is 0. In this case the result string is not assigned a new value (it keeps its original value).</li>
<li>SUCCESS – if spaces can be removed or no spaces are present.</li>
</ol>
</li>
<li>int center(const char *source, int width, char *result);This function generates a new string into the result out parameter where the source input string has been centered in a string with length specified by the width parameter. Center the string by adding (to the left and right of the original string) a number of spaces that corresponds to (width – source string length) / 2. Notice that the resulting centered string has a length that is less than width when (width – source string length) is odd. For example, if we were to center “dogs” in a field with of 7, the resulting string is “ dogs ” (1 space to the left, 1 space to the right). The function returns one of two values: SUCCESS or FAILURE (see file text manipulation.h).
<ol>
<li>FAILURE – if source is NULL, if source length is 0, or if the width is less than the source length.</li>
<li>SUCCESS – if item is centered.</li>
</ol>
</li>
</ol>
You should look at the public tests in order to understand the functionality associated with the functions you must implement. For this exercise, you can assume the user will not provide a string containing only blank characters. In addition, if a string has multiple words, the spaces between those words must be preserved.

4 Requirements

<ol>
<li>Unlike other assignments for this course, you can work together with other classmates, but you may NOT exchange any code.</li>
<li>If you are having problems with your code, use the class debugging guide available at:
<pre>     http://www.cs.umd.edu/~nelson/classes/resources/cdebugging/
</pre>
</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
<ol start="3">
<li>Your grade is based on the results obtained from the submit server. It is your responsibility to verify that your program generates the expected results on the submit server.</li>
<li>Your code must be written in the file text manipulation.c.</li>
<li>Do not add a main function to the text manipulation.c file.</li>
<li>To compile a public test, compile your text manipulation.c file along with a public test file. For example: gcc public01.c text manipulation.c</li>
<li>One source of bugs is forgetting to add a null character to a string.</li>
<li>All your C programs in this course should be written using the compiler gcc with the options defined at
<pre>   http://www.cs.umd.edu/~nelson/classes/resources/setting_gcc_alias/
</pre>
</li>
<li>Your program should be written using good programming style as defined at
<pre>   http://www.cs.umd.edu/~nelson/classes/resources/cstyleguide/
</pre>
</li>
<li>You just need to implement the two functions described above. You may write additional functions if you want, but define them as static.</li>
<li>Do not change the text manipulation.h file provided.</li>
<li>You are encourage to define your own tests (similar to public01.c, public02.c, etc.).</li>
<li>You can use the C string library (string.h).</li>
<li>Do not use any functions from ctype.h.</li>
<li>You can assume the result char array will be long enough to contain the string functions will create.</li>
<li>Do not use dynamic memory allocation.</li>
<li>The example ptr add sub overview.c reviews concepts associated with this exercise.</li>
</ol>
</div>
</div>
</div>
