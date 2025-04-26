# csc384-assignment-4--variable-elimination-for-bayes-nets-solved



**<span style='color:red'>TO GET THIS SOLUTION VISIT:</span>** https://www.ankitcodinghub.com/product/csc384-assignment-4-variable-elimination-for-bayes-nets-solved/

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;51567&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSC384 Assignment 4- variable elimination for Bayes Nets Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">
            
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
In this assignment you will implement variable elimination for Bayes Nets.

What is supplied: Python code that implements Variable, Factor, and BN objects. The file bnetbase.py

contains the class definitions for these objects. The code supports representing factors as tables of values

indexed by various settings of the variables in the factor’s scope.

The template file bnetbase.py also contains function prototypes for the functions you must implement.

Question 1. Implement Variable Elimination (worth 60/100 marks)

Implement the following functions that operate on Factor objects and then use these functions to implement

VE (variable elimination):

• multiply factors (worth 10 points). This function takes as input a list of Factor objects; it creates

and returns a new factor that is equal to the product of the factors in the list. Do not modify any of

the input factors.

• restrict factor (worth 10 points). This function takes as input a single factor, a variable V and a

value d from the domain of that variable. It creates and returns a new factor that is the restriction of

the input factor to the assignment V = d. Do not modify the input factor.

• sum out variable (worth 10 points). This function takes as input a single factor, and a variable V;

it creates and returns a new factor that is the result of summing V out of the input factor. Do not

modify the input factor.

• VE (worth 30 points). This function takes as input a Bayes Net object (object of class BN), a variable

that is the query variable Q, and a list of variables E that are the evidence variables (all of which

have had some value set as evidence using the variable’s set evidence interface). Compute the

probability of every possible assignment to Q given the evidence specified by the evidence settings

of the evidence variables. Return these probabilities as a list, where every number corresponds the

probability of one of Q’s possible values. Do not modify any factor of the input Bayes net.

Assignment 4, University of Toronto, CSC384 – Intro to AI, Winter 2020 3

Question 2: Problem Solving with your VE Implementaion (worth 40/100

marks)

For the following questions, you will submit your answers using the Google form that is located at https:

//forms.gle/suJ2eVbusTimJb359.

1. Use your implementation to answer questions regarding the following Bayesian network. All variables are binary, with values Dom(A) = {a,a˜}, Dom(B) = {b,b˜}, etc.

The probability table values are as follows (probabilities add to one so you can compute the remaining probability values):

P(a) = 0.9

P(b|ah) = 1.0;P(b|ah˜) = 0.0;P(b|a˜;h) = 0.5;P(b|a˜h˜) = 0.6

P(c|bg) = 0.9;P(c|bg˜) = 0.9;P(c|b˜;g) = 0.1;P(c|b˜g˜) = 1.0

P(d|c f) = 0.0;P(d|c ˜f) = 1.0;P(d|c˜; f) = 0.7;P(d|c˜

˜f) = 0.2

P(e|c) = 0.2;P(e|c˜) = 0.4

P(f) = 0.1

P(g) = 1.0

P(h) = 0.5

P(i|b) = 0.3;P(i|b˜) = 0.9

Using your Variable Elimination implementation (or by hand!), compute the following probabilities

and post these to the Google Form (worth 10 points):

(a) P(b|a)

(b) P(c|a)

(c) P(c|ae˜)

(d) P(c|a ˜f)

Assignment 4, University of Toronto, CSC384 – Intro to AI, Winter 2020 4

2. Next, examine the file carDiagnosis.py. This specifies a Bayes Net for diagnosing various reasons

why a car might not start. The layout of this Bayes Net is shown below, and the various CPTs for the

Net are specified in carDiagnosis.py as Factors:

Each variable of the Net is shown in a square box along with the values that the variable can take.

For example, The variable BatteryVoltage (which is the variable bv in the file carDiagnosis.py)

can take on one of three different values: “strong”, “weak” and “dead”.

The numbers and bars show the unconditional probabilities of the variables taking on their different values. For example, in the Net we have P(BatteryVoltage = dead) = 0.41. For the various

CPTs for the Net, see carDiagnosis.py.

Using your Variable Elimination implementation (or based on inspection!), answer the following

questions and post your answers to the Google Form:

(a) (worth 5 points) Show a case of conditional independence in the Net where knowing some

evidence item V1 = d1 makes another evidence item V2 = d2 irrelevant to the probability of

some third variable V3. (Note that conditional independence requires that the independence

holds for all values of V3).

(b) (worth 5 points) Show a case of conditional independence in the Net where two variables are

independent given NO evidence at a third variable yet dependent given evidence at the third

variable.

Assignment 4, University of Toronto, CSC384 – Intro to AI, Winter 2020 5

(c) (worth 10 points) Show a sequence of accumulated evidence items V1 = d1,…,V k = dk (i.e.,

each evidence item in the sequence is added to the previous evidence items) such that each

additional evidence item increases the probability that some variable V has the value d. (That

is, the probability of V = d increases monotonically as we add evidence items). What is P(V =

d—V1 = d1,…,Vk = dk)?

(d) (worth 10 points) Show a sequence of accumulated evidence items V1 = d1,…,V k = dk (i.e.,

each evidence item in the sequence is added to the previous evidence items) such that each

additional evidence item decreases the probability that some variable V has the value d. (That

is, the probability of V = d decreases monotonically as we add evidence items). What is P(V =

d—V1 = d1,…,Vk = dk)?
