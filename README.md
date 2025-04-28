# csci2202-lab-d--integration-matrix-application-solved
**TO GET THIS SOLUTION VISIT:** [CSCI2202 Lab D- Integration & Matrix Application Solved](https://www.ankitcodinghub.com/product/csci2202-integration-matrix-application-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;116973&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSCI2202 Lab D- Integration \u0026amp; Matrix Application Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (2 votes)    </div>
    </div>
(1) Representing Networks as Matrices:

Graphs are an important tool used to model problems in many areas of applied sciences. Graphs are defined to be sets of vertices V = {v1,v2,v3,v4,v5} together with the connections (edges) between them, represented as ordered pairs:



1

0

0 if (vi,vj) is an edge

if no edge between vi

if i = j and vj

Create the adjacency matrix A for the graph. Note that A is symmetric (i.e. ai,j = aj,i). A walk on a graph is a sequence of edges linking one vertex to another. In general, we can determine the number of walks of length k between any two vertices, by taking the kth power of A.

Write a program to calculate the number of walks of length k, entered by the user, between vertices of the above graph. Report your results for k = 3.

(2) Numerical Integration (Empirical approach):

In this exercise, you are going to experimentally examine the errors in the the two rules of integration we examined in class: The Trapezoidal Rule and the Midpoint Rule, using the integral:

which has the exact value: ln2 (the natural log of 2).

, to divide the domain of integration into.

Note:The Trapezoidal Rule is obtained by approximating the integrand over each sub-interval in x by a straight line, between the left endpoint and the right endpoint of the interval (see fig. on Slide 5b Integration.)

1

2

(i) Test your implementation on the integral above for n = 2,10,50,250.

(ii) In each case, record the Error = True Value – Approximated Value to 7 places after the decimal.

(iii) Calculate the ratio of the errors for the adjacent values of n (i.e. Calculate Error(2)/Error(10); Error(10)/Error(50) etc.) What does this tell you about the error?

Summarize your results in a table with columns: ) n, Error Ratio-of-Errors.

(b) Add a function midpoint(f, a, b, n) to integrate.py. The Midpoint Rule is given by evaluating the integrand at the mid-point of the subinterval.

(i) Test your implementation on the integral above for n = 2,10,50,250. (ii) In each case, record the

Error = True Value – Approximated Value to 7 places after the decimal.

(iii) Calculate the ratio of the errors for the adjacent values of n (i.e.. Calculate Error(2)/Error(10); Error(10)/Error(50) etc.) What does this tell you about the error?

(c) Finally, add a function main() to integrate.py. This function should test each of the integration routines in the module (write the test commands you used above into main). Add the (global) line: if name == ‘ main ’:main().

This line should be outside the main() function definition (it is usually put at the end of the file, outside all function definitions).

You have created your first module. You can now import this module into any python programs as you would any other module, and use the functions available within. If you run integrate.py it will run the main() function within the module.

Note: Next lab, we will continue with integration. In the next lab, you will learn about vectorizing your code (this is a way to eliminate loops using Python &amp; numpy). You will also implement a Monte-Carlo method for integration.
