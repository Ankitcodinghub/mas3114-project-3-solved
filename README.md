# mas3114-project-3-solved
**TO GET THIS SOLUTION VISIT:** [MAS3114 Project 3 Solved](https://www.ankitcodinghub.com/product/mas3114-project-3-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;64836&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;3&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (3 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;MAS3114 Project 3 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (3 votes)    </div>
    </div>
Each exercise has to begin with the line <strong>Exercise#</strong>

You should also mark down the parts such as (a), (b), (c), and etc. This makes grading easier. <strong><u>Important</u>: we use the default </strong>format short<strong> for the numbers in all exercises unless it is specified otherwise</strong>. We <u>do not employ</u> format rat since it may cause problems with running the codes and displaying matrices in Live Script. <strong>If </strong><strong>format </strong><strong>long has been used, please make sure to return to the default </strong><strong>format in the next exercise.</strong>

<h1>Part I. Subspaces &amp; Bases</h1>
In this exercise, you will be given two matrices A and B. You will create a function that works with the column spaces of the matrices. First, it will determine whether Col A and Col B are subspaces of the same Euclidian vector space¡<em><sup>m</sup></em>. If yes, your code has to determine if Col A and Col B have the same dimension, and, if yes, whether Col A = Col B. Obviously, when two subspaces have the same dimension, it might not be true that they are the same set. For example, a line through the origin in ¡<sup>3</sup> is a one-dimensional subspace of ¡<sup>3</sup>, but two lines might be different.

You will use a MATLAB built-in function rank()within your code. Remember, <strong>the rank of a matrix </strong>can be defined as<strong> the dimension of the column space of the matrix</strong>.

&nbsp;

**Create a function in the file that begins with function []=columnspaces(A,B) m=size(A,1); n=size(B,1);

&nbsp;

First, your function has to check if Col A and Col B are subspaces of the same Euclidian vector space, that is, if <em>m</em> and <em>n</em> are equal.

**If Col A and Col B are subspaces of different spaces, you will output the corresponding message and <u>terminate</u> the program.

**If Col A and Col B are subspaces of the same vector space ¡<em><sup>m</sup></em>, you will code the corresponding message that also outputs the dimension of the vector space¡<em><sup>m</sup></em>, which is <em>m</em>. An example of the output message is below:

fprintf(‘Col A and Col B are subspaces of R^%i\n’,m)

**Then, your function will continue with calculating the dimensions of Col A and Col B. Output them with the corresponding messages.

**Next, check if both conditions hold: Col A is the whole ¡<em><sup>m</sup></em> and Col B is the whole ¡<em><sup>m</sup></em>. If it is the case, output a message that Col A = Col B = ¡<em><sup>m</sup></em> and <u>terminate</u> the program.

&nbsp;

If either Col A or Col B or both are not the whole ¡<em><sup>m</sup></em>, your code will continue.

**First, it will check if Col A and Col B have the same dimension. If not, output the message that the dimensions of Col A and Col B are different.

**If the dimensions are the same, the code has to check whether Col A and Col B are the same set. If it is the case, output the message that Col A = Col B.

If it is not the case, output a message that the dimensions of Col A and Col B are the same but Col A ~= Col B.

<strong>&nbsp;</strong>

<strong><u>Note</u></strong>: You <u>cannot</u> use a MATLAB built-in function colspace(sym()) within the function&nbsp; columnspaces.

This is the end of the function columnspaces.

&nbsp;

**Print the function columnspaces in your Live Script. ** Type: format

<strong>**</strong>Run the function on the choices (a)-(f) as indicated below:

<table width="616">
<tbody>
<tr>
<td width="616">%(a)

A=[2 -4 -2 3;6 -9 -5 8;2 -7 -3 9;4 -2 -2 -1;-6 3 3 4] B=rref(A)

columnspaces(A,B)

%(b)

A=[2 -4 -2 3;6 -9 -5 8;2 -7 -3 9;4 -2 -2 -1;-6 3 3 4];

B=([rref(A);zeros(5,4)])’ A=A’

columnspaces(A,B)

%(c)

A=magic(5) B=ones(5)

columnspaces(A,B)

%(d)

A=magic(4)&nbsp; B=eye(4)

columnspaces(A,B)

%(e)

A=magic(4)

B=[eye(3);zeros(1,3)] columnspaces(A,B)

%(f)

A=magic(3)

B=[hilb(3),eye(3)]
</td>
</tr>
</tbody>
</table>
columnspaces(A,B)

<strong>&nbsp;</strong>

%Based on the outputs for part (a), write a comment in the Live Script on a possible effect of the elementary row operations on the column space of a matrix.<strong> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;</strong>

In this exercise, you will create a basis for the Col A in two ways: using a built-in MATLAB function colspace(sym(A))and using a function shrink() which you will create in a file.

<strong>&nbsp;</strong>

<strong>Part 1</strong>:

The column space of a matrix A is a subspace spanned by the columns of A. It is possible that the set of columns of A is not linearly independent, that is, not all columns of A will be in a basis. The set of columns of A can be “shrunk” into a basis for Col A by using the function shrink(). Here is a code: function B=shrink(A)

[~,pivot]=rref(A); B=A(:,pivot); end

<strong>&nbsp;</strong>

**Create the function B=shrink(A)in a file.

**Print the function shrink in your Live Script.

**Input a matrix as indicated below:

A=magic(4); A(:,3)=A(:,2)

Run the command&nbsp; rref(A)

**Then, run the two lines given below (display the outputs):

[R,pivot]=rref(A)

B=A(:,pivot)

%Write a comment in the Live Script on the outputs for each of the two lines above.

&nbsp;

**Next, run the command:

[~,pivot]=rref(A)

%Explain the difference between the outputs for the last command and for the command

[R,pivot]=rref(A)

&nbsp;

**Input the matrices

A=[2 -4 -2 3;6 -9 -5 8;2 -7 -3 9;4 -2 -2 -1;-6 3 3 4]

B=shrink(A)

**Run the function columnspaces(A,B), which was created in Exercise 1 of this Project, to show that the matrices A and B have the same column space.

**Print the function columnspaces in your Live Script

&nbsp;

%Explain in the Live Script why the set of the columns of B forms a basis for the column space of A.

<strong>&nbsp;</strong>

<h2>Part 2</h2>
There is a MATLAB built-in function&nbsp; colspace(sym(A)) which creates a symbolic matrix whose columns form a basis for the column space of A.

**Input the matrix

A=[2 -4 -2 3;6 -9 -5 8;2 -7 -3 9;4 -2 -2 -1;-6 3 3 4]

**Type and run in the Live Script:

R=rref((A’))

M=shrink(R’)

B=colspace(sym(A))

**Next, run the command: D=double(B)

which converts a symbolic matrix B to a double-precision matrix D. Run the logical command indicated below to compare the matrices D and M.

<strong>&nbsp;</strong>

Next, run the command columnspaces(A,B) created in Exercise 1 of this Project to show that the column spaces of the matrices A and B are the same.

&nbsp;

<h2>BONUS: 2 points</h2>
% Analyze the outputs for Part 2 of this Exercise and determine the path that the function colspace(sym()) takes to create a basis for Col A. Justify the statement that the set of the columns of&nbsp; B forms a basis for the Col A.

&nbsp;

<h2>BONUS: 1 point</h2>
**Use the results of Part 2 of this exercise to write a new function in a file

function []=columnspaces_1(A,B)

which takes the function columnspaces() and modifies only one part of this function, the one that checks if Col A = Col B; you will need to employ a MATLAB built-in function colspace(sym())within your code for the function columnspaces_1.

<strong>**</strong>Print the function columnspaces_1&nbsp;&nbsp; in your Live Script.

&nbsp;

<u>Note</u>: You can test here that the new function columnspaces_1() gives the same outputs as the function columnspaces() by running it on the matrices in Exercise 1; however, you do not need to include these tests into Exercise 2 file for the submission.

<strong>&nbsp;</strong>

<strong>&nbsp;</strong>

<h2>Exercise 3 (4 points)&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Difficulty: Easy</h2>
In this exercise, you will be given an <em>m n</em><sub>×</sub> matrix A. Your program has to create two matrices B and D. The matrix B is formed by the pivot columns of A – the set of columns of B is a basis for Col A which is a subspace of ¡<em><sup>m</sup></em>. The set of columns of the matrix D forms a basis for

¡<em><sup>m</sup></em>. If Col A <sub>≠</sub>¡<em><sup>m </sup></em>, the matrix D is constructed by using all columns of B and some columns of the <em>m m</em><sub>× </sub>identity matrix.

&nbsp;

**Create the function in a file which begins with function [B,D]=basis(A) m=size(A,1);

&nbsp;

**First, use the function shrink() , which was created in Exercise 2 of this project, within the function basis to output (and display) the matrix B of the pivot columns of A – supply the output B with a message that ‘a basis for Col A is the set of columns of’ (display B)

**Then, your code has to check whether the set of columns of the matrix B forms a basis for

¡<em><sup>m</sup></em>. If yes, the program breaks with the message: fprintf(‘a basis for R^%i is D=B\n’,m) and assigns

D=B;

**If the set of the columns of B does not form a basis for ¡<em><sup>m</sup></em>, you should create a matrix D whose first columns are all columns of the matrix B and the rest of the columns come from the matrix eye(m), such that the set of all columns of D forms a basis for ¡<em><sup>m</sup></em>. You can use your function shrink() to create D.

**Next, you will write a set of commands within your code to verify whether the set of columns of D is, indeed, a basis for ¡<em><sup>m</sup></em>. If your code confirms that, display a corresponding message, for example:

fprintf(‘a basis for R^%i is\n’,m)

(display D).

Otherwise, an output message could be: ‘something definitely went wrong!’

<strong>&nbsp;</strong>

<strong>**</strong>Print the function basis and shrink within the Live Script.

<strong>**</strong>Run the function [B,D]=basis(A); on the following matrices (display the inputs):

%(a)

A=[1 0;0 0;0 0;0 1]

&nbsp;

%(b)

A=[0 0;2 0;3 0;0 0]

&nbsp;

%(c)

A=magic(4)

&nbsp;

%(d)

A=magic(5)

&nbsp;

%(e)

A=ones(4)

<h1>Part II. Isomorphism &amp; Change of Basis</h1>
<strong>&nbsp;</strong>

<h2>Exercise 4 (5 points)&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Difficulty: Hard</h2>
&nbsp;

DESCRIPTION: In this exercise, you will be given a set of <em>n</em> polynomials, which is denoted B. The polynomials in B are from the subspace <em>P<sub>n</sub></em><sub>−1</sub> of the polynomials whose degrees do not exceed (<em>n</em>−1). A standard basis for <em>P<sub>n</sub></em><sub>−1</sub> is <em>E</em><sub>=</sub>{<em>x</em><em><sup>n</sup></em><sup>−</sup><sup>1</sup>, <em>x</em><em><sup>n</sup></em><sup>−</sup><sup>2</sup>,…,<em>x </em>,1}. You will determine whether the given set B forms a basis for <em>P<sub>n</sub></em><sub>−1</sub>. This could be done by employing isomorphism from <em>P<sub>n</sub></em><sub>−1</sub> onto ¡<em><sup>n </sup></em>. You will create a matrix P, which is the matrix of the E-coordinates of the polynomials in B. According to the isomorphism, the set of the polynomials in B forms a basis for the subspace <em>P<sub>n</sub></em><sub>−1</sub>if and only if the set of the columns of P forms a basis for ¡<em><sup>n </sup></em>.

If the set B is a basis for <em>P<sub>n</sub></em><sub>−1</sub>, your function will continue with two more tasks: (1) you will find a vector <strong>y</strong> of the B-coordinates of a polynomial Q, where Q is given in a symbolic form through the standard basis E, and (2) you will output a polynomial R in a symbolic form (through the standard basis E), given its B-coordinate vector <strong>r</strong>.

(For a help with this exercise, please refer to lecture Module 19.)

&nbsp;

We will use the function closetozeroroundoff with a parameter p = 7 within the code. This function was created in Project 0 and you should have it in your Current Folder in MATLAB.

&nbsp;

**Create a function in a file that begins with function P=polyspace(B,Q,r) format

&nbsp;

An input <em>B B</em><sub>=</sub>[ (1), <em>B</em>(2),…,<em>B n</em>( )]&nbsp; is a vector whose components are polynomials from the vector space <em>P<sub>n</sub></em><sub>−1</sub>, Q is a single polynomial from the same space <em>P<sub>n</sub></em><sub>−1</sub>, and <strong>r</strong> is a numerical vector with <em>n</em> entries.

<u>Note on the format of input polynomials</u>: for the purpose of this program, it is required that the coefficient of the leading term <em>x</em><em><sup>n</sup></em><sup>−</sup><sup>1</sup> of a polynomial must not be zero. However, the zero leading coefficient is accepted by the definition of the subspace <em>P<sub>n</sub></em><sub>−1</sub>, and some of the given polynomials do not have term <em>x</em><em><sup>n</sup></em><sup>−</sup><sup>1</sup>, that is, the coefficient of <em>x</em><em><sup>n</sup></em><sup>−</sup><sup>1</sup> is a zero. To be able to work with such polynomials, we insert the coefficient 10^(-8) of <em>x</em><em><sup>n</sup></em><sup>−</sup><sup>1</sup>, and we will convert this leading coefficient into a 0 by running within our code the function closetozeroroundoff with p = 7 on the matrix P of the coefficients of the polynomials in B.

&nbsp;

**Continue your function polyspace with the commands:

u=sym2poly(B(1)); n=length(u);

&nbsp;

The command sym2poly(B(1)) takes the coefficients of the polynomial B(1), which is written through the standard basis E in the descending order according to the degree, and writes them as a <u>row</u> vector (a 1<sub>×</sub><em>n</em> matrix).

<u>Note</u>: The number <em>n</em> is the dimension of the vector space <em>P<sub>n</sub></em><sub>−1</sub>; thus, <em>P<sub>n</sub></em><sub>−1</sub> is isomorphic to the Euclidean space ¡<em><sup>n </sup></em>. The number <em>n</em> will be used later in this program.

&nbsp;

**To use isomorphism, you will create an <em>n n</em><sub>×</sub> matrix P, whose <u>columns</u> are the vectors of the coefficients of the polynomials in the set B – each column is generated by the commands transpose and sym2poly (as described above) – the columns of P are the E-coordinate vectors of the polynomials in B.

<u>Note</u>: to output P, you can employ a “for loop” in your code (do not display the output P here).

&nbsp;

**Then, you will convert to 0 the entries of the matrix P which are in the range of 10^(-7) from a 0 by running the function:&nbsp; P=closetozeroroundoff(P,7)

&nbsp;

**Display the new matrix P with the message:

fprintf(‘matrix of E-coordinate vectors of polynomials in B is\n’)

(display P).

&nbsp;

Then you will check if the columns of P form a basis for ¡<em><sup>n </sup></em>– use the command rank().&nbsp; **If the set of the columns of P is not a basis for ¡<em><sup>n </sup></em>, then, due to the isomorphism, the set of the polynomials B does not form a basis for <em>P<sub>n</sub></em><sub>−1</sub>. In this case, you will output a corresponding message and calculate and output matrix A=rref(P), which is the reduced echelon form of the matrix P (the matrix A should visualize the fact that the columns of P do not form a basis for

¡<em><sup>n </sup></em>). After that, the program <u>terminates</u>.

Examples of the output messages for this part are given below:

sprintf(‘the polynomials in B do not form a basis for P%d’,n-1) fprintf(‘the reduced echelon form of P is\n’) (display A).

&nbsp;

**If the set of the columns of P forms a basis for ¡<em><sup>n </sup></em>, then, due to the isomorphism, you will output a message that the polynomials in B form a basis for the subspace of the polynomials <em>P<sub>n</sub></em><sub>−1</sub>, and your function will continue with <u>two more tasks</u>:

<strong>&nbsp;</strong>

<ul>
<li>Given the polynomial Q written in a symbolic form through the standard basis E, calculate the B-coordinate vector <strong>y</strong> of Q. To calculate the vector <strong>y</strong>, you will use the Change-ofCoordinates equation.</li>
</ul>
<u>Hint</u>: use a MATLAB command sym2poly() to output the <u>row</u> vector of the E-coordinates of the polynomial Q. Then, run closetozeroroundoff with p = 7 within your code on the Ecoordinate vector to convert the leading entry into a 0, when needed. After that, you can proceed with calculation of the B-coordinate vector <strong>y</strong> of Q.

&nbsp;

Your outputs for this part will be a message and the vector <strong>y</strong>:&nbsp; fprintf(‘the B-coordinate vector of Q is\n’)

(display <strong>y)</strong>.

<strong>&nbsp;</strong>

<ul>
<li>Given the B-coordinate vector <strong>r </strong>of a polynomial R, output the polynomial R written in a symbolic form through the standard basis E.</li>
</ul>
<u>Hint</u>: you will need to calculate the E-coordinate vector of the polynomial R by the Change-ofCoordinates equation, and, then, use that vector and the command poly2sym() to output the required polynomial R.

&nbsp;

The output R should be supplied with a message, for example:

fprintf(‘the polynomial whose B-coordinates form the vector r is\n’)

(display R).

&nbsp;

For a help with this exercise, you may find it useful to review the second Example in the Lecture Notes for Module 19.

<strong>This is the end of the function </strong><strong>polyspace. </strong>

&nbsp;

**Type the functions closetozeroroundoff and polyspace in the Live Script.

**Then, type in the Live Script syms x

This command introduces a symbolic variable <em>x</em>, It will also allow you to input the polynomials in the variable <em>x</em> in your Live Script by typing (or copying and pasting) the inputs B and Q as they are given below.&nbsp; ** Run the function&nbsp; P=polyspace(B,Q,r);

on each set of the variables (a)-(c). (Display the inputs in the Live Script.)

<table width="616">
<tbody>
<tr>
<td width="616">%(a)

B=[x^3+3*x^2,10^(-8)*x^3+x,10^(-8)*x^3+4*x^2+x,x^3+x]

Q=10^(-8)*x^3-2*x^2+x-1 r=[1;-3;2;4]

%(b)

B=[x^3-1,10^(-8)*x^3+2*x^2,10^(-8)*x^3+x,x^3+x]

Q=10^(-8)*x^3-2*x^2+x-1 r=[1;-3;2;4]

%(c)

B=[x^4+x^3+x^2+1,10^(-8)*x^4+x^3+x^2+x+1,10^(-8)*x^4+x^2+x+1,10^(-

8)*x^4+x+1,10^(-8)*x^4+1]

Q=x^4-2*x+3
</td>
</tr>
</tbody>
</table>
M=magic(5);r=M(:,1)

<h1>Part III. Application to Calculus</h1>
&nbsp;

<h2>Exercise 5 (4 points)&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Difficulty:&nbsp; Moderate</h2>
In this exercise, you will approximate the definite integral of a function using both Riemann sums and a MATLAB built-in function integral.

&nbsp;

The code accepts as inputs: a function fun, a <u>column</u> vector <strong>n</strong> whose entries are the numbers of subintervals of partitions, and two scalars <em>a</em>, <em>b</em> – the endpoints of the interval of integration. Riemann sum calculations should be performed using partitions of [<em>a b</em>, ] by subintervals of the equal length h(j) defined as

h(j)=(b-a)/n(j);

where n(j)is a jth entry of <strong>n</strong>, with j=1:N and N=length(n). Each entry of the vector <strong>n, </strong>n(j), is the number of the subintervals of the corresponding partition of [<em>a b</em>, ].

&nbsp;

Your function has to return a<u> table</u> T whose first column formed by the N entries of the vector <strong>n</strong>, where&nbsp; n(j) entry of&nbsp; <strong>n </strong>defines the jth partition of [<em>a</em>, <em>b</em>]. For a jth partition (j=1:N), you will calculate the Riemann sums approximations of the definite integral by choosing the left endpoints, the middle points, and the right endpoints of each subinterval of the partition – these sums will be the jth entries of the <u>column</u> vectors L, M, and R, respectively. The vectors L, M, and R will form the columns 2, 3, and 4 of the output table T.

&nbsp;

**Write a function that begins with function T=reimsum(fun,a,b,n)

format compact

N=length(n);

&nbsp;

It has to calculate the column vectors L, M, R as described above and form a matrix

A=[n,L,M,R];

The following command converts the N-by-4 array A into an N-by-4 table T with the names of the variables as indicated below. This command should be present in your code.

&nbsp;

T=array2table(A,…

‘VariableNames’,{‘n’,’Left’,’Middle’,’Right’})

**Print the function reimsum in your Live Script.<strong>&nbsp; </strong>

&nbsp;

**Run the function T=reimsum(fun,a,b,n) in the way indicated below on the function handles. At the ends of each part (a) and (b), you will also run (and display the output) a MATLAB built-in function

Int=integral(fun,a,b)

&nbsp;

which calculates definite integral of a function fun. The output of this function will allow you to verify if your approximations of the definite integral are correct.

&nbsp;

<table width="616">
<tbody>
<tr>
<td width="616">%(a)

fun=@(x) x.*tan(x) + x + 1 a=0;b=1;

&nbsp;

n=(1:10)’;

T=reimsum(fun,a,b,n)

&nbsp;

n=[1;5;10;100;1000;10000];

T=reimsum(fun,a,b,n)

&nbsp;

Int=integral(fun,a,b)

%(b)

fun=@(x) x.^4 – 2*x – 2 a=0;b=3;

&nbsp;

n=(1:10)’;

T=reimsum(fun,a,b,n)

&nbsp;

n=[1;5;10;100;1000;10000];

T=reimsum(fun,a,b,n)

&nbsp;

Int=integral(fun,a,b)
</td>
</tr>
</tbody>
</table>
<strong>%</strong>Write a comment in your Live Script for which choice of the points on a subinterval of a partition (left endpoints, middle points, or right endpoints) the Riemann sums give the best approximation of the integral.

&nbsp;

<h2>Exercise 6 (4 points)&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Difficulty: Easy</h2>
In this exercise you are given a polynomial, and you will write a code that outputs an antiderivative of the polynomial.

&nbsp;

**Write a function in the file that begins with&nbsp; function I=polint(P) format compact syms x

<strong>&nbsp;</strong>

which accepts as an input a polynomial P. A polynomial will be written in a symbolic form through the standard basis (you may find it helpful to review Exercise 4 of the current Project).

&nbsp;

The function has to calculate indefinite integral of the polynomial assigning a value 3 to an arbitrary constant. The output I has to be a <u>polynomial written in a symbolic form through the</u> <u>standard basis</u>. Do not use a MATLAB built-in function int(P)within the function&nbsp; polint.

&nbsp;

Suggested commands within your code: sym2poly, poly2sym, length. A single “for loop” or a vectorized statement can be used.&nbsp; <strong>This is the end of the function </strong><strong>polint</strong>.

&nbsp;

**Print the function polint in your Live Script.

**Type in the Live Script:

format syms x

&nbsp;

**Run I=polint(P) on the polynomials in parts (a) and (b). (You can copy and paste each polynomial in the Live Script.)

<ul>
<li>P=6*x^5+5*x^4+4*x^3+3*x^2+2*x+6</li>
<li>P=x^5-2*x^3+3*x+5</li>
</ul>
&nbsp;

**For each part, (a) and (b), after getting (and <u>displaying</u>) the output I, run a logical command

isequal(I,int(P)+3)

to make sure that your output matches the output of a MATLAB built-in function. If it doesn’t, consider making corrections in your code.

<h1>Part IV. Application to Markov Chains</h1>
&nbsp;

<h2>Exercise 7 (4 points):&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Difficulty:&nbsp; Moderate</h2>
In this exercise, you will work with Markov Chains. Please read the part <strong>Theory</strong> and perform the tasks indicated below.

<strong>Theory</strong>: A vector with nonnegative entries that add up to 1 is called a <strong><em>probability vector</em></strong>. A <strong><em>stochastic matrix</em></strong> is a square matrix whose columns are probability vectors.

<u>Important Note</u>: in this Exercise, the definition of a stochastic matrix matches the definition of the left-stochastic matrix in Exercise 5 of Project 1.

&nbsp;

A <strong><em>Markov chain</em></strong> is a sequence of probability vectors <strong>x x x</strong><sub>0</sub>, <sub>1</sub>, <sub>2</sub>,…, together with a stochastic matrix <em>P</em>, such that

<strong>x</strong><sub>1 </sub>=<em>P</em><strong>x</strong><sub>0</sub>, <strong>x</strong><sub>2 </sub>=<em>P</em><strong>x</strong><sub>1</sub>, <strong>x</strong><sub>3 </sub>=<em>P</em><strong>x</strong><sub>2</sub>,&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; … .

In other words, a Markov chain is described by the first-order difference equation <strong>x</strong><em><sub>k</sub></em><sub>+1 </sub>=<em>P</em><strong>x</strong><em><sub>k</sub></em> for&nbsp; <em>k</em><sub>= </sub>0,1,2,…

The <em>n</em> entries of vectors <strong>x</strong><em><sub>k</sub></em> list, respectively, a probability that the system is in one the <em>n</em> possible states. For this reason, <strong>x</strong><em><sub>k</sub></em> is called a <strong><em>state vector</em></strong>. If <em>P</em> is a <em>stochastic matrix</em>, then a <strong><em>steady-state vector</em></strong> for <em>P</em> is a <em>probability vector</em> <strong>q </strong>such that <em>P</em><strong>q q</strong>= .

A <em>stochastic matrix</em> <em>P</em> is called <strong><em>regular</em></strong> if some matrix power <em>P</em><em><sup>k</sup></em> contains only strictly positive entries.

<u>Theorem</u>: If <em>P</em> is an <em>n n</em><sub>×</sub> <em>regular stochastic</em> matrix, then <em>P</em> has a <em>unique steady-state</em> vector <strong>q</strong>.

Further, if <strong>x</strong><sub>0</sub> is any initial state and <strong>x</strong><em><sub>k</sub></em><sub>+1 </sub>=<em>P</em><strong>x</strong><em><sub>k</sub></em>&nbsp;&nbsp; for&nbsp; <em>k</em><sub>= </sub>0,1,2,… , then the Markov chain

{<strong>x</strong><em><sub>k</sub></em>} converges to <strong>q</strong> as <em>k</em>→∞ .

For more on Markov Chains read the textbook: Section 4.9, Applications to Markov Chains.

&nbsp;

**Create a function in a file that begins with function q=markov(P,x0) format n=size(P,1);

**First, the function has to check whether the given <em>n n</em><sub>×</sub> matrix P, whose entries will be positive numbers, is stochastic (that is, left-stochastic). If P is not left-stochastic, the program displays a message ‘P is not a stochastic matrix’, returns q=[]; and <u>terminates</u>.

&nbsp;

**If P is left-stochastic (then it will be a regular stochastic matrix), we do the following:

<ul>
<li>Find the unique steady-state vector <strong>q</strong>.</li>
</ul>
<u>Recall</u>: the steady-state vector <strong>q</strong> is a <u>probability</u> vector which is a solution of the equation

<em>P</em><strong>q q</strong>= , or, equivalently, the equation (<em>P eye n</em><sub>− </sub>( ))<strong>q 0</strong>= . You can find a basis for the solution set of this system (which <u>has to contain only one vector</u>) by using a MATLAB function&nbsp;&nbsp; null(P-eye(n),’r’)

Then, you will need to output the probability vector <strong>q </strong>that belongs to the solution set. Display <strong>q</strong> with a message that it is the steady-state vector of the system.

&nbsp;

<ul>
<li>Next, verify that the Markov chain converges to <strong>q </strong>by calculating consecutive iterations <strong>x</strong><sub>1 </sub>= <em>P</em>*<strong>x</strong><sub>0</sub>, <strong>x</strong><sub>2 </sub>= <em>P</em>*<strong>x</strong><sub>1</sub>, <strong>x</strong><sub>3 </sub>= <em>P</em>*<strong>x</strong><sub>2</sub>, … , until, for the first time, norm(<strong>x q</strong><em><sub>k </sub></em>− )&lt; 10^(-7)</li>
</ul>
<u>Output the number of iterations <em>k</em></u> that are required to archive this accuracy – supply your output with the corresponding message.

&nbsp;

**Type the function markov in your Live Script.

**Run the function q=markov(P,x0);

on the following choices of the matrix P and the vector x0. (Display the inputs.)

<table width="616">
<tbody>
<tr>
<td width="616">%(a)

P=[.6 .3;.5 .7] x0=[.3;.7]

%(b)

P=[.5 .3;.5 .7]

x0 <sup>is the same as in part (a)</sup>

%(c)

P=[.9 .2;.1 .8] x0=[.10;.90] where P is a migration matrix between two regions.

%(d)

A migration matrix P is the same as in (c)
</td>
</tr>
</tbody>
</table>
x0=[.81;.19]

%(e)

P=[.90 .01 .09;.01 .90 .01;.09 .09 .90] x0=[.5; .3; .2]

<strong>&nbsp;</strong>

<strong>% </strong>Compare the output vectors <strong>q</strong> for parts (c) and (d), which have the same matrix P and different vectors x0, and write a comment whether a choice of the initial vector x0 has an effect on the steady-state vector q. Does a choice of x0 have an effect on the number of iterations k? Write a comment about it as well.
