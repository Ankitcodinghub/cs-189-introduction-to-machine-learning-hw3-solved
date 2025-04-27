# cs-189-introduction-to-machine-learning-hw3-solved
**TO GET THIS SOLUTION VISIT:** [CS 189 Introduction to Machine Learning HW3 Solved](https://www.ankitcodinghub.com/product/cs-189-introduction-to-machine-learning-hw3-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;32232&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;5&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (5 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS 189&nbsp;Introduction to Machine Learning HW3 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (5 votes)    </div>
    </div>
Deliverables:

<ol>
<li>Submit your predictions for the test sets to Kaggle as early as possible. Include your Kaggle scores in your write-up (see below). The Kaggle competition for this assignment can be found at:
<ul>
<li><a href="https://www.kaggle.com/c/cs189-hw3-mnist">https://www.kaggle.com/c/cs189-hw3-mnist</a></li>
<li><a href="https://www.kaggle.com/c/cs189-hw3-spam">https://www.kaggle.com/c/cs189-hw3-spam</a></li>
</ul>
</li>
<li>Submit a PDF of your homework, with an appendix listing all your code, to the Gradescope assignment entitled “HW3 Write-Up”. You may typeset your homework in LaTeX or Word (submit PDF format, not .doc/.docx format) or submit neatly handwritten and scanned solutions. Please start each question on a new page. If there are graphs, include those graphs in the correct sections. Do not put them in an appendix. We need each solution to be self-contained on pages of its own.
<ul>
<li>In your write-up, please state with whom you worked on the homework. • In your write-up, please copy the following statement and sign your signature next to it. (Mac Preview and FoxIt PDF Reader, among others, have tools to let you sign a PDF file.) We want to make it <em>extra </em>clear so that no one inadverdently cheats. <em>“I certify that all solutions are entirely in my own words and that I have not looked at another student’s solutions. I have given credit to all external sources I consulted.”</em></li>
</ul>
</li>
<li>Submit all the code needed to reproduce your results to the Gradescope assignment entitled “HW3 Code”. Yes, you must submit your code twice: once in your PDF write-up (above) so the readers can easily read it, and once in compilable/interpretable form so the readers can easily run it. Do NOT include any data files we provided. Please include a short file named README listing your name, student ID, and instructions on how to reproduce your results. Please take care that your code doesn’t take up inordinate amounts of time or memory. If your code cannot be executed, your solution cannot be verified.</li>
<li>The assignment covers concepts on Gaussian distributions and classifiers. Some of the material may not have been covered in lecture; you are responsible for finding resources to understand it.</li>
</ol>
<h1>1&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Gaussian Classification</h1>
Let <em>P</em>(<em>x </em>| <em>C<sub>i</sub></em>) ∼ N(µ<em><sub>i</sub></em>,σ<sup>2</sup>) for a two-category, one-dimensional classification problem with classes <em>C</em><sub>1 </sub>and <em>C</em><sub>2</sub>, <em>P</em>(<em>C</em><sub>1</sub>) = <em>P</em>(<em>C</em><sub>2</sub>) = 1/2, and µ<sub>2 </sub>&gt; µ<sub>1</sub>.

<ul>
<li>Find the Bayes optimal decision boundary and the corresponding Bayes decision rule.</li>
<li>The Bayes error is the probability of misclassification,</li>
</ul>
<em>P<sub>e </sub></em>= <em>P</em>((misclassified as <em>C</em><sub>1</sub>) | <em>C</em><sub>2</sub>) <em>P</em>(<em>C</em><sub>2</sub>) + <em>P</em>((misclassified as <em>C</em><sub>2</sub>) | <em>C</em><sub>1</sub>) <em>P</em>(<em>C</em><sub>1</sub>). Show that the Bayes error associated with this decision rule is

1 Z ∞ −<em>z</em>2/2

<em>P<sub>e </sub></em>= <span style="text-decoration: line-through;">√&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span><em>e&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; dz</em>

2π&nbsp;&nbsp;&nbsp; <em>a</em>

µ2 − µ1 where <em>a </em>= .

2σ

<h1>2&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Isocontours of Normal Distributions</h1>
Let <em>f</em>(µ,Σ) be the probability density function of a normally distributed random variable in R<sup>2</sup>. Write code to plot the isocontours of the following functions, each on its own separate figure. You’re free to use any plotting libraries available in your programming language; for instance, in Python you can use Matplotlib.

 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  11 and Σ = 10&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 20.

<ul>
<li><em>f</em>(µ,Σ), where µ =</li>
</ul>
&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 

−1&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 2&nbsp;&nbsp; 1

<ul>
<li><em>f</em>(µ,Σ), where µ =  2  and Σ = 1 3.</li>
</ul>
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 

<ul>
<li>2 2&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 1</li>
</ul>
<ul>
<li><em>f</em>(µ<sub>1</sub>,Σ<sub>1</sub>) − <em>f</em>(µ2,Σ2), where µ1 = 2, µ2 = 0 and Σ1 = Σ2 = 1 1.</li>
</ul>
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 

<ul>
<li>2 2&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 1&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 2&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 1</li>
</ul>
<ul>
<li><em>f</em>(µ<sub>1</sub>,Σ<sub>1</sub>) − <em>f</em>(µ2,Σ2), where µ1 = 2, µ2 = 0, Σ1 = 1 1 and Σ2 = 1&nbsp;&nbsp;&nbsp;&nbsp; 3. </li>
<li><em>f</em>(µ<sub>1</sub>,Σ<sub>1</sub>) − <em>f</em>(µ2,Σ2), where µ1 = 11, µ2 = −−11, Σ1 = 20 10 and Σ2 = 12&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 12.</li>
</ul>
<h1>3&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Eigenvectors of the Gaussian Covariance Matrix</h1>
Consider two one-dimensional random variables <em>X</em><sub>1 </sub>∼ N(3,9) and <em>X</em> 4), where N(µ,σ<sup>2</sup>) is a Gaussian distribution with mean µ and variance σ<sup>2</sup>. Write a program that draws <em>n </em>= 100 random two-dimensional sample points from (<em>X</em><sub>1</sub>, <em>X</em><sub>2</sub>) such that the <em>i</em>th value sampled from <em>X</em><sub>2 </sub>is calculated based on the <em>i</em>th value sampled from <em>X</em><sub>1</sub>. In your code, make sure to specify the Random Number Generator seed that was used so your simulation is reproducible. For each of the following parts, include the corresponding output of your program.

<ul>
<li>Compute the mean (in R<sup>2</sup>) of the sample.</li>
<li>Compute the 2 × 2 covariance matrix of the sample.</li>
<li>Compute the eigenvectors and eigenvalues of this covariance matrix.</li>
<li>On a two-dimensional grid with a horizonal axis for <em>X</em><sub>1 </sub>with range [−15,15] and a vertical axis for <em>X</em><sub>2 </sub>with range [−15,15], plot
<ul>
<li>all <em>n </em>= 100 data points, and</li>
<li>arrows representing both covariance eigenvectors. The eigenvector arrows should originate at the mean and have magnitudes equal to their corresponding eigenvalues.</li>
</ul>
</li>
<li>Let <em>U </em>= [<em>v</em><sub>1 </sub><em>v</em><sub>2</sub>] be a 2 × 2 matrix whose columns are the eigenvectors of the covariance matrix, where <em>v</em><sub>1 </sub>is the eigenvector with the larger eigenvalue. We use <em>U</em><sup>&gt; </sup>as a rotation matrix to rotate each sample point from the (<em>X</em><sub>1</sub>, <em>X</em><sub>2</sub>) coordinate system to a coordinate system aligned with the eigenvectors. (As <em>U</em><sup>&gt; </sup>= <em>U</em><sup>−1</sup>, the matrix <em>U </em>reverses this rotation, moving back from the eigenvector coordinate system to the original coordinate system). <em>Center </em>your sample points by subtracting the mean µ from each point; then rotate each point by <em>U</em><sup>&gt;</sup>, giving <em>x</em><sub>rotated </sub>= <em>U</em><sup>&gt;</sup>(<em>x </em>− µ). Plot these rotated points on a new two dimensional-grid, again with both axes having range [−15,15].</li>
</ul>
<h1>4&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Classification</h1>
Suppose we have a classification problem with classes labeled 1,…,<em>c </em>and an additional “doubt” category labeled <em>c </em>+ 1. Let <em>r </em>: R<em><sup>d </sup></em>→ {1,…,<em>c </em>+ 1} be a decision rule. Define the loss function

<table width="324">
<tbody>
<tr>
<td width="165">

λ0<em>r</em>

<em>L</em>(<em>r</em>(<em>x</em>) = <em>i</em>,<em>y </em>= <em>j</em>) =

λ<em>s</em>
</td>
<td width="159">if <em>i </em>= <em>j i</em>, <em>j </em>∈ {1,…,<em>c</em>}, if <em>i </em>= <em>c </em>+ 1,

otherwise,
</td>
</tr>
</tbody>
</table>
where λ<em><sub>r </sub></em>≥ 0 is the loss incurred for choosing doubt and λ<em><sub>s </sub></em>≥ 0 is the loss incurred for making a misclassification. Hence the risk of classifying a new data point <em>x </em>as class <em>i </em>∈ {1,2,…,<em>c </em>+ 1} is

<em>c</em>

X

<em>R</em>(<em>r</em>(<em>x</em>) = <em>i</em>|<em>x</em>) =&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <em>L</em>(<em>r</em>(<em>x</em>) = <em>i</em>,<em>y </em>= <em>j</em>) <em>P</em>(<em>Y </em>= <em>j</em>|<em>x</em>).

<em>j</em>=1

<ul>
<li>Show that the following policy obtains the minimum risk when λ<em><sub>r </sub></em>≤ λ<em><sub>s</sub></em>.
<ul>
<li>Choose class <em>i </em>if <em>P</em>(<em>Y </em>= <em>i</em>|<em>x</em>) ≥ <em>P</em>(<em>Y </em>= <em>j</em>|<em>x</em>) for all <em>j </em>and <em>P</em>(<em>Y </em>= <em>i</em>|<em>x</em>) ≥ 1 − λ<em><sub>r</sub></em>/λ<em><sub>s</sub></em>;</li>
<li>Choose doubt otherwise.</li>
</ul>
</li>
<li>What happens if λ<em><sub>r </sub></em>= 0? What happens if λ<em><sub>r </sub></em>&gt; λ<em><sub>s</sub></em>? Explain why this is consistent with what one would expect intuitively.</li>
</ul>
<h1>5&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Maximum Likelihood Estimation</h1>
Let <em>X</em><sub>1</sub>,…, <em>X<sub>n </sub></em>∈ R<em><sup>d </sup></em>be <em>n </em>sample points drawn independently from a multivariate normal distribution N(µ,Σ).

<ul>
<li>Suppose the normal distribution has an unknown diagonal covariance matrix</li>
</ul>
Σ = σ<sub>2</sub>1 σ22&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; σ23 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; … 



&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; σ<em>d</em>2



and an unknown mean µ. Derive the maximum likelihood estimates, denoted ˆµ and ˆσ<em><sub>i</sub></em>, for µ and σ<em><sub>i</sub></em>. Show all your work.

<ul>
<li>Suppose the normal distribution has a known covariance matrix Σ and an unknown mean <em>A</em>µ, where Σ and <em>A </em>are known <em>d </em>× <em>d </em>matrices, Σ is positive definite, and <em>A </em>is invertible. Derive the maximum likelihood estimate, denoted ˆµ, for µ.</li>
</ul>
<h1>6&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Covariance Matrices and Decompositions</h1>
As described in lecture, the covariance matrix Var(<em>R</em>) ∈ R<em><sup>d</sup></em><sup>×<em>d </em></sup>for a random variable <em>R </em>∈ R<em><sup>d </sup></em>with mean µ is

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 

<sub></sub><sub> </sub>Var(<em>R</em>1)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Cov(<em>R</em>1,<em>R</em>2)&nbsp;&nbsp;&nbsp;&nbsp; …&nbsp;&nbsp; Cov(<em>R</em>1,<em>R</em><em>d</em>) 

Var(<em>R</em>) = Cov(<em>R</em>,<em>R</em>) = E[(<em>R </em>− µ)(<em>R </em>− µ)<sup>&gt;</sup>] = <sup></sup><sub></sub><sup> </sup>Cov(<em>R</em>..<sup>2</sup>,<em><sub>R</sub></em><sup>1</sup>)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <sub>Var(<em>R</em></sub><sup>2</sup>)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; … Cov(Var(<em>R</em>…<em>R</em><sub>2</sub>,<em><sub>d</sub>R</em>)<em><sub>d</sub></em>) ,

<h1><sub></sub></h1>
<sub> </sub>Cov(<em>R</em>.<em><sub>d</sub></em>,<em>R</em><sub>1</sub>) Cov(<em>R<sub>d</sub></em>,<em>R</em><sub>2</sub>)&nbsp;&nbsp;&nbsp;&nbsp; …

where Cov(<em>R<sub>i</sub></em>,<em>R<sub>j</sub></em>) = E[(<em>R<sub>i </sub></em>− µ<em><sub>i</sub></em>)(<em>R<sub>j </sub></em>− µ<em><sub>j</sub></em>)] and Var(<em>R<sub>i</sub></em>) = Cov(<em>R<sub>i</sub></em>,<em>R<sub>i</sub></em>).

If the random variable <em>R </em>is sampled from the multivariate normal distribution N(µ,Σ) with the PDF

<em>f</em>(<em>x</em>) =&nbsp;&nbsp;&nbsp; 1&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <em>e</em>−((<em>x</em>−µ)<sup>&gt;</sup>Σ<sup>−1</sup>(<em>x</em>−µ))/2, p(2π)<em>d</em>|Σ|

then Var(<em>R</em>) = Σ.

Given <em>n </em>points <em>X</em><sub>1</sub>, <em>X</em><sub>2</sub>,…, <em>X<sub>n </sub></em>sampled from N(µ,Σ), we can estimate Σ with the maximum likelihood estimator

<em>n</em>

ˆ 1 X(<em>X<sub>i </sub></em>− µ)(<em>X<sub>i </sub></em>− µ)<sub>&gt;</sub>, Σ =

<em>n</em>

<em>i</em>=1

which is also known as the covariance matrix of the sample.

<ul>
<li>The estimate Σˆ makes sense as an approximation of Σ only if Σˆ is invertible. Under what circumstances is Σˆ not invertible? Make sure your answer is complete; i.e., it includes all cases in which the covariance matrix of the sample is singular. Express your answer in terms of the geometric arrangement of the sample points <em>X<sub>i</sub></em>.</li>
<li>Suggest a way to fix a singular covariance matrix estimator Σˆ by replacing it with a similar but invertible matrix. Your suggestion may be a kludge, but it should not change the covariance matrix too much. Note that infinitesimal numbers do not exist; if your solution uses a very small number, explain how to calculate a number that is sufficiently small for your purposes.</li>
<li>Consider the normal distribution N(0,Σ) with mean µ = 0. Consider all vectors of length 1; i.e., any vector <em>x </em>for which |<em>x</em>| = 1. Which vector(s) <em>x </em>of length 1 maximizes the PDF <em>f</em>(<em>x</em>)? Which vector(s) <em>x </em>of length 1 minimizes <em>f</em>(<em>x</em>)? (Your answers should depend on the</li>
</ul>
properties of Σ.) Explain your answer.

<h2>7&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Gaussian Classifiers for Digits and Spam</h2>
In this problem, you will build classifiers based on Gaussian discriminant analysis. Unlike Homework 1, you are NOT allowed to use any libraries for out-of-the-box classification (e.g. sklearn). You may use anything in numpy and scipy.

The training and test data can be found on in the post corresponding to this homework. Don’t use the training/test data from Homework 1, as they have changed for this homework. Submit your predicted class labels for the test data on the Kaggle competition website and be sure to include your Kaggle display name and scores in your writeup. Also be sure to include an appendix of your code at the end of your writeup.

<ul>
<li>Taking pixel values as features (no new features yet, please), fit a Gaussian distribution to each digit class using maximum likelihood estimation. This involves computing a mean and a covariance matrix for each digit class, as discussed in lecture.</li>
</ul>
<em>Hint: </em>You may, and probably should, contrast-normalize the images before using their pixel values. One way to normalize is to divide the pixel values of an image by the <em>l</em><sub>2</sub>-norm of its pixel values.

<ul>
<li>(Written answer) Visualize the covariance matrix for a particular class (digit). How do the diagonal terms compare with the off-diagonal terms? What do you conclude from this?</li>
<li>Classify the digits in the test set on the basis of posterior probabilities with two different approaches.
<ul>
<li>Linear discriminant analysis (LDA). Model the class conditional probabilities as Gaussians N(µ<sub>C</sub>,Σ) with different means µ<sub>C </sub>(for class C) and the same covariance matrix Σ, which you compute by averaging the 10 covariance matrices from the 10 classes.</li>
</ul>
</li>
</ul>
To implement LDA, you will sometimes need to compute a matrix-vector product of the form Σ<sup>−1</sup><em>x </em>for some vector <em>x</em>. You should not try to compute the inverse of Σ (nor the determinant of Σ). Instead, you should find a way to solve the implied linear system without computing the inverse.

Hold out 10,000 randomly chosen training points for a validation set. Classify each image in the validation set into one of the 10 classes (with a 0-1 loss function). Compute the error rate and plot it over the following numbers of randomly chosen training points: [100, 200, 500, 1,000, 2,000, 5,000, 10,000, 30,000, 50,000]. (Expect some variance in your error rate when few training points are used.)

<ul>
<li>Quadratic discriminant analysis (QDA). Model the class conditionals as Gaussians N(µ<sub>C</sub>,Σ<sub>C</sub>), where Σ<sub>C </sub>is the estimated covariance matrix for class C. (If any of these covariance matrices turn out singular, implement the trick you described in Q6.(b). You are welcome to use <em>k</em>-fold cross validation to choose the right constant(s) for that trick.) Repeat the same tests and error rate calculations you did for LDA.</li>
<li>(Written answer.) Which of LDA and QDA performed better? Why?</li>
<li>Using the mnistdata.mat, train your best classifier for the trainingdata and classify the images in the testdata. Submit your labels to the online Kaggle competition. Record your optimum prediction rate in your submission. You are welcome to compute extra features for the Kaggle competition. If you do so, please describe your implementation in your assignment. Please use extra features only for the Kaggle portion of the assignment.</li>
</ul>
In your submission, include plots of error rate versus number of training examples for both LDA and QDA. Similarly, include a plot of training and test error for each digit. Which digit is easiest to classify? Include written answers where indicated.

<ul>
<li>Next, apply LDA or QDA (your choice) to spam. Submit your test results to the online Kaggle competition. Record your optimum prediction rate in your submission. If you use additional features (or omit features), please describe them.</li>
</ul>
<em>Optional: </em>If you use the defaults, expect relatively low classification rates. The TAs suggest using a bag-of-words model. You may use third-party packages to implement that if you wish.

Also, normalizing your vectors might help.
