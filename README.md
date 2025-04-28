# 70-511-statistical-programming-programming-assignment-7---aggregating-acs-pums-data-solved
**TO GET THIS SOLUTION VISIT:** [70-511: Statistical Programming Programming Assignment 7 – Aggregating ACS PUMS Data Solved](https://www.ankitcodinghub.com/product/70-511-statistical-programming-programming-assignment-7-aggregating-acs-pums-data-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;10890&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;70-511: Statistical Programming  Programming Assignment 7 – Aggregating ACS PUMS Data Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (1 vote)    </div>
    </div>
<h1>Introduction</h1>
For this assignment, you will work again with the same ACS PUMS dataset as for assignment 6 to produce several tables which aggregate the data.

&nbsp;

<h1>Requirements</h1>
You are to create a program in Python that performs the following using the pandas packages:

<ol>
<li>Loads the csv file that contains the PUMS dataset (assume it’s in the current directory) and create a DataFrame object from it.</li>
</ol>
&nbsp;

<ol start="2">
<li>Create 3 tables:</li>
</ol>
TABLE 1: Statistics of HINCP – Household income (past 12 months), grouped by HHT – Household/family type

<ul>
<li>Table should use the HHT types (text descriptions) as the index</li>
<li>Columns should be: mean, std, count, min, max</li>
<li>Rows should be sorted by the mean column value in descending order</li>
</ul>
&nbsp;

TABLE 2: HHL – Household language vs. ACCESS – Access to the Internet (Frequency Table)

<ul>
<li>Table should use the HHL types (text descriptions) as the index</li>
<li>Columns should the text descriptions of ACCESS values</li>
<li>Each table entry is the sum of WGTP column for the given HHL/ACCESS combination, divided by the sum of WGTP values in the data. Entries need to be formatted as percentages.</li>
<li>Table should include marginal values (‘All’ row and column).</li>
<li>Any rows containing NA values in HHL, ACCESS, or WGTP columns should be excluded.</li>
</ul>
&nbsp;

TABLE 3: Quantile Analysis of HINCP – Household income (past 12 months)

<ul>
<li>Rows should correspond to different quantiles of HINCP: low (0-1/3), medium (1/3-2/3), high (2/3-1)</li>
<li>Columns displayed should be: min, max, mean, household_count</li>
<li>The household_count column contains entries with the sum of WGTP values for the corresponding range of HINCP values (low, medium, or high)</li>
</ul>
&nbsp;

<ol start="3">
<li>Display the tables to the screen as shown in the sample output on the last page.</li>
</ol>
&nbsp;

<strong>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;</strong>

<h1>Additional Requirements</h1>
<ol>
<li>The name of your source code file should be py. All your code should be within a single file.</li>
<li>You need to use the pandas DataFrame object for storing and manipulating data.</li>
<li>Your code should follow good coding practices, including good use of whitespace and use of both inline and block comments.</li>
<li>You need to use meaningful identifier names that conform to standard naming conventions.</li>
<li>At the top of each file, you need to put in a block comment with the following information: your name, date, course name, semester, and assignment name.</li>
<li>The output should <strong>exactly</strong> match the sample output shown on the last page.</li>
</ol>
&nbsp;

<strong>What to Turn In </strong>

You will turn in the single tables.py file using BlackBoard.

&nbsp;

<strong>&nbsp;</strong>

<h1>HINTS</h1>
<ul>
<li>To get the right output, use the following functions to set pandas display parameters: set_option(‘display.max_columns’, 500)</li>
</ul>
pd.set_option(‘display.width’, 1000)

<ul>
<li>To display entries as percentages, use the applymap method, giving it a string conversion function as input. The string conversion function should take a float value v as an input and output a string representing v as a percentage. To do this, you can use formatting strings or the format() method</li>
</ul>
&nbsp;

&nbsp;

<strong>Sample Program Output&nbsp; </strong>

70-511, [semester] [year]

NAME: [put your name here]

PROGRAMMING ASSIGNMENT #7

&nbsp;

*** Table 1 – Descriptive Statistics of HINCP, grouped by HHT ***

mean&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;std&nbsp; count&nbsp;&nbsp;&nbsp; min&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; max HHT – Household/family type

Married couple household&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 106790.565562&nbsp; 100888.917804&nbsp; 25495&nbsp; -5100 &nbsp;1425000

Nonfamily household:Male householder:Not living alone&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 79659.567376&nbsp;&nbsp; 74734.380152&nbsp;&nbsp; 1410&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 0&nbsp;&nbsp; 625000

Nonfamily household:Female householder:Not living alone&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 69055.725901&nbsp;&nbsp; 63871.751863&nbsp;&nbsp; 1193&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 0&nbsp;&nbsp; 645000

Other family household:Male householder, no wife present&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 64023.122122&nbsp;&nbsp; 59398.970193&nbsp;&nbsp; 1998&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 0&nbsp;&nbsp; 610000

Other family household:Female householder, no husband present&nbsp;&nbsp; 49638.428821&nbsp;&nbsp; 48004.399101&nbsp;&nbsp; 5718&nbsp; -5100&nbsp;&nbsp; 609000

Nonfamily household:Male householder:Living alone&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 48545.356298&nbsp;&nbsp; 60659.516163&nbsp;&nbsp; 5835&nbsp; -5100&nbsp;&nbsp; 681000 Nonfamily household:Female householder:Living alone&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 37282.245015&nbsp;&nbsp; 44385.091076&nbsp;&nbsp; 8024 -11200&nbsp;&nbsp; 676000

<table>
<tbody>
<tr>
<td width="46"></td>
</tr>
<tr>
<td></td>
<td></td>
</tr>
</tbody>
</table>
*** Table 2 – HHL vs. ACCESS – Frequency Table ***

sum&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; WGTP

ACCESS&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Yes w/ Subsrc. Yes, wo/ Subsrc.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; No&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; All

HHL – Household language

English only&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 58.71%&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 2.93%&nbsp; 16.87%&nbsp;&nbsp; 78.51%

Spanish&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 7.83%&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;0.52%&nbsp;&nbsp; 2.60%&nbsp;&nbsp; 10.95%

Other Indo-European languages&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 5.11%&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 0.18%&nbsp;&nbsp; 1.19%&nbsp;&nbsp;&nbsp; 6.48%

Asian and Pacific Island languages&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 2.73%&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 0.06%&nbsp;&nbsp; 0.28%&nbsp;&nbsp;&nbsp; 3.08%

Other language&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 0.80%&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 0.03%&nbsp;&nbsp; 0.14%&nbsp;&nbsp;&nbsp; 0.97% All&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 75.19%&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 3.73%&nbsp; 21.08%&nbsp; 100.00%

*** Table 3 – Quantile Analysis of HINCP – Household income (past 12 months) ***

min&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; max&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; mean&nbsp; household_count HINCP&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; low&nbsp;&nbsp;&nbsp; -11200&nbsp;&nbsp;&nbsp; 37200&nbsp;&nbsp; 19599.486904&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 1629499 medium&nbsp; 37210&nbsp;&nbsp;&nbsp; 81500&nbsp;&nbsp; 57613.846298&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 1575481 high&nbsp;&nbsp;&nbsp; 81530&nbsp; 1425000&nbsp; 159047.588900&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1578445
