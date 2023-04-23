Download Link: https://assignmentchef.com/product/solved-advanced-stats-lab_-1
<br>









<strong>ML estimation with PDF</strong>

<strong>Theoretical analysis</strong>

<strong>Question 1: maximum likelihood estimator?</strong>

For n iid observations <em>x</em><em>i </em>of the height of the river, the likelihood can be written as following

<em>L</em>(<em>a</em>;<em>x</em>1<em>,…,x<sub>n</sub></em>) = ~<em>n </em><em>f</em><em>H</em>(<em>x</em><em>i</em>)

<em>i</em>=1

~                                                                                                                              <sub>i<em>n</em></sub>

<em>e</em>~ 1                                                                                                                            <em>i</em>=1 <em>x</em>2

2<em>a                                                                                                                                                                                                   i</em>

<em>x</em><em>i</em>

The log-likelihood can be derived from the likelihood as follows

<em>l</em>(<em>a</em>; <em>x</em>1<em>, …, x<sub>n</sub></em>) = <em>log</em>(<em>L</em>(<em>a</em>; <em>x</em>1<em>, …, x<sub>n</sub></em>))

<u>1 </u> ~

ln(<em>x</em><em>i</em>)  <em>n</em>ln(<em>a</em>)  2<em>a</em>

<em>i</em>=1

<em>n</em>

<em>Dl                                         n </em><u>1 </u> ~

<em>Da</em>(<em>a</em>; <em>x</em>1<em>, …, x<sub>n</sub></em>) = 


<em>a </em>2<em>a</em><sup>2</sup>

<em>i</em>=1

Then one can derive the maximum likelihood estimator by setting the partial derivative to 0.




<em>Dl</em>

<em><sub>Da</sub></em>(~<em>a</em><em>n</em>; <em>x</em>1<em>, …, x<sub>n</sub></em>) = 0 ~~

<strong>Question 2: method of moments estimator?</strong>




~<em>E</em>[<em>X</em>] =        <em>xf</em><em>H</em>(<em>x</em>)<em>dx</em>

~ 0 +0′) <em>x</em>2 <em>a_ </em><em><u>e</u></em><u>_</u><em><u>x</u></em><u>2</u>

=                      2<em>a </em><em>dx</em>

~ 0 +~ <em>e</em><u>_</u><em><u>x</u></em><u>2</u>

=               2<em>a </em><em>dx</em>

0

<u>4/</u><em><u>7ra</u></em>

= 2




One can estimate the expectation using the arithmetic mean. Hence, the method of moments estimator ~<em>a<sub>n</sub></em> is:




<table>

 <tbody>

  <tr>

   <td width="214">

    <table width="100%">

     <tbody>

      <tr>

       <td>1 <em>n</em> <em>n</em> <em>i</em>=1</td>

      </tr>

     </tbody>

    </table></td>

  </tr>

 </tbody>

</table>

<table>

 <tbody>

  <tr>

   <td width="103">

    <table width="100%">

     <tbody>

      <tr>

       <td>~<em><u>~</u></em><u>~</u><em><u>a</u></em><em><u><sub>n </sub></u></em><em>x</em><em>i </em>= 2 ~~</td>

      </tr>

     </tbody>

    </table></td>

  </tr>

 </tbody>

</table>




<strong>Question 3: properties of</strong> ~<em>a<sub>n</sub></em><strong>?</strong> <strong>a) Unbiased?</strong>




<table>

 <tbody>

  <tr>

   <td width="324">~<em>n</em>1<em>E</em>[~<em>a<sub>n</sub></em>] = 2<em>n</em><em>i</em>=1</td>

   <td width="65"><em>E</em>[<em>X</em><sup>2</sup><em>i </em>]</td>

  </tr>

 </tbody>

</table>




<table>

 <tbody>

  <tr>

   <td width="283">=</td>

   <td width="10">12</td>

   <td width="97"><em>E</em>[<em>X</em><sup>2</sup>]</td>

  </tr>

 </tbody>

</table>

1 f00 3

= I<em><sub>                                                                               e</sub></em><em>a         </em><em>dx</em>

2j0<em>             a</em>

<table>

 <tbody>

  <tr>

   <td>~</td>

  </tr>

 </tbody>

</table>

<sup>+</sup><sup>00</sup>= <em>xe</em><sup> 2<em>a</em></sup><em> dx</em> 0

<em>E</em>[~<em>a<sub>n</sub></em>] =<em> a</em>

~<em>a<sub>n</sub></em> is unbiased.

<ol>

 <li><strong>b) Optimal?</strong> Let us derive the variance of the estimator ~<em>a<sub>n</sub></em>.</li>

</ol>




<em>V ar</em>[~<em>a<sub>n</sub></em>] =

~4<em>n</em><sup>2</sup>

<em>i</em>=1

<em>Var</em>[<em>X</em><sup>2</sup>]




<u>1 </u> ~<em>E</em>[<em>X</em><sup>4</sup>] ~ <em>E</em>[<em>X</em><sup>2</sup>]<sup>2</sup>~ = 4<em>n</em>

a

(

–

We know from question a) that E[X2] =

1 <em>Thus,V ar</em>[

<em><sub>n</sub></em>] = ____

4<em>aE</em>[<em>X</em><sup>2</sup>]

<em>E</em>[<em>X</em><sup>2</sup>]<sup>2</sup>

4<em>n</em>

2<em>E</em>[~<em>a<sub>n</sub></em>] = 2<em>a</em>.

<table>

 <tbody>

  <tr>

   <td width="89"><em>a</em><sup>2</sup><em>V ar</em>[~<em>a<sub>n</sub></em>] =<em>n</em></td>

  </tr>

 </tbody>

</table>

Let us now compute the Fisher information<em> I</em>(<em>a</em>)

<em>a</em>2                                        <em>n </em>1<em> n </em>~

<em>~a</em>2_____ <em>l</em>(<em>a</em>; <em>x</em>1<em>~ ~~~~ x</em><em>n</em>)=<em> a</em><sup>2</sup> –<em> a</em><sup>3</sup>

<em>i</em>=1

= <em>E</em>[~<em><sub>Da</sub></em><sub>2</sub><em>l</em>(<em>a</em>;<em>x</em>1<em>,~~~~x<sub>n</sub></em>)](  1


<table>

 <tbody>

  <tr>

   <td width="11">

    <table width="100%">

     <tbody>

      <tr>

       <td></td>

      </tr>

     </tbody>

    </table></td>

  </tr>

 </tbody>

</table>

= <em>a</em>2                              <em>aI<sub>n</sub></em>(<em>a</em>) = <em>n</em>

<em>a</em>2

a2

In(a)

n

1E[X2])

~ +00 x5

E[X4] =             a e~x2

2a dx

0= 4 f+00x3edx

0= 4aE[X2]

)

2




<table>

 <tbody>

  <tr>

   <td width="106">1<em>V ar</em>[~<em>a<sub>n</sub></em>] = <em>I</em><em>n</em>(<em>a</em>)</td>

  </tr>

 </tbody>

</table>

Its variance equals the Cramer–Rao lower bound and it is unbiased. Hence, ~<em>a<sub>n</sub></em> minimizes the mean squared error. So ~<em>a<sub>n</sub></em> is both optimal.

<ol>

 <li><strong>Efficient? </strong>Since ~<em>a<sub>n</sub></em> is unbiased and optimal. Therefore, ~<em>a<sub>n</sub></em> is efficient because its variance is equal to the Cramer-Rao lower bound.</li>

 <li><strong>Asymptotically Gaussian? </strong>The maximum likelihood estimator is asymptotically gaussian. Hence, ~<em>a<sub>n</sub></em> is asymptotically gaussian. <em>I</em>(<em>a</em>) = <em><u>I</u></em><em><u>n</u></em><u>(</u><em><u>a</u></em><u>) </u></li>

</ol>

<em>n </em>= <em>a</em>2 1

<table>

 <tbody>

  <tr>

   <td width="108">/<em>n</em>(~<em>a<sub>n</sub></em>  <em>a</em>) <em>d</em>~~~~~<em>n</em>boo</td>

   <td width="50"><em>N</em>(0<em>, a</em>2)</td>

  </tr>

 </tbody>

</table>

<strong>Application on real data</strong>

<strong>Question 1: p function of a?</strong>

Let <em>p </em>the probability that a disaster happens during one year.

<em>p </em>= 1 – <em>F</em><em>H</em>(6)

~ ~ <em>x a e</em>~ <em><sup>x</sup></em><sup>2</sup>=                                  2<em>a </em><em>dx</em>

~ 6 – <em>e</em><em> x</em>2 ~~

2<em>a</em>

=

6

18

<em>p </em>= <em>e</em>~ <em>a</em>

<strong>Question 2: probability of at most one disaster?</strong>

During one thousand years, if at most one disaster happened, it means either there was no disasters, or therewas only one. Let us derive <em>p</em>1, the probability that at most one disaster happens during one thousand years.

<em>p</em>1 = (1 – <em>p</em>)<sup>999</sup> = (1 ~ <em>e</em>~ 18 <em>a </em>)999

<strong>Question 3: estimation of the probability?</strong>

<table>

 <tbody>

  <tr>

   <td width="633">X = c(2.5, 1.8, 2.9, 0.9, 2.1, 1.7, 2.2, 2.8) n = length(X)a = sum(X~2)/(2*n)p = (1-exp(-18/a))~999</td>

  </tr>

 </tbody>

</table>

Regarding the set of 8 observations, one can estimate <em>a</em>~ = 2<em>.</em>42. The probability <em>p</em>1 can be estimated:

<em>p</em>1 = 0<em>.</em>557 .

<strong>Exercise 1: Rayleigh distribution</strong>

<strong>(a)</strong>

The parameter <em>a </em>of the Rayleigh distribution was estimated with the maximum likelihood estimator ~<em>a<sub>n</sub></em>. It was found that <em>a </em>2<em>.</em>42.




<strong>(b)</strong>

implemented in R. One has to be careful that the scale <em>a </em>used in R corresponds to i/<em>a</em>.

One can generate more samples following a Rayleigh distribution by using the Rayleigh distribution function

n = 100000

X = rrayleigh(n, scale=sqrt(a))

hist(X, nclass=50, xlim = c(0,10), main = “Rayleigh implemented in R”)

<strong>Rayleigh implemented in R</strong>

0                      2                     4                     6                      8                    10

X

If one has only access to uniform distribution and would like to output a Rayleigh distribution, one can use

the inverse distribution function.

~ <em>x</em>

<em>ae</em>~ <em><sup>t</sup></em><sup>2</sup>

<em>t</em>

<em>   F </em>(<em>x</em>) =                              2<em>a </em><em>dt</em>

0

<table>

 <tbody>

  <tr>

   <td width="432">= 1 – <em>e</em>~</td>

   <td width="201"><em><sub>x</sub></em>22<em>a</em></td>

  </tr>

 </tbody>

</table>




/

<em>F </em>(<em>x</em>) = <em>u </em>~~ <em>x </em>= -2<em>a </em>ln(1 – <em>u</em>)

If <em>U </em>follows a uniform distribution on [0<em>, </em>1], one can generate samples following the Rayleigh distribution

using the uniform distribution.

/

<em>U U</em>[0<em>, </em>1] =~ -2<em>a </em>ln(<em>U</em>) <em>Rayleigh</em>(<em>a</em>)

n = 100000

U = runif(n)

X = sqrt(-2*a*log(U))

hist(X, nclass=50, xlim = c(0,10), main = “Simulated Rayleigh”)




<strong>Simulated Rayleigh</strong>

0                      2                     4                      6                     8                    10

X

<strong>(c)</strong>

Empirically, one can verify that the MLE is unbiased by averaging <em>N </em>samples of the MLE ~<em>a</em><em>n,</em>1<em>, …, </em>~<em>a</em><em>n,N </em>with whatever value for <em>n</em>. For computing resources reasons, let’s take <em>n </em>= 10 and average over <em>N </em>= 100000 samples of <em>n </em>observations.

<table>

 <tbody>

  <tr>

   <td width="324"><sub>&gt;J</sub><em><sup>N</sup></em><u>1 </u><em>E</em>[~<em>a<sub>n</sub></em>  <em>a</em>]<em>N</em><em>k</em>=1</td>

   <td width="309">(~<em>a</em><em>n,k </em>– <em>a</em>)</td>

  </tr>

 </tbody>

</table>




<table>

 <tbody>

  <tr>

   <td width="286">=</td>

   <td width="17">1<em>N</em></td>

   <td width="22"><sub>&gt;J</sub><em><sup>N</sup></em><em></em><em>k</em>=1</td>

   <td width="45"><sub>&gt;J</sub><em><sup>n</sup></em>(  12<em>n</em><em>i</em>=1</td>

   <td width="264"><em>x</em>2 <em>i~k </em>– <em>a</em>)</td>

  </tr>

 </tbody>

</table>




<table>

 <tbody>

  <tr>

   <td width="633">N = 100000n = 10E = 0<strong>for</strong> (k<strong> in</strong> 1:N){X = rrayleigh(n, scale=sqrt(a))E = E + 1/(2*n)*sum(X~2) – a}E = E/NE</td>

  </tr>

 </tbody>

</table>

## [1] -0.002336315

<table>

 <tbody>

  <tr>

   <td width="49"><em>E</em>[~<em>a</em><em>,</em><em>a</em>]<em>a</em></td>

   <td width="584">~ 9<em>.</em>7 x 10<sup></sup><sup>4</sup> &lt;&lt; 1. Hence, empirically, the estimator is unbiased.</td>

  </tr>

 </tbody>

</table>




<ul>

 <li></li>

</ul>

Empirically, one can verify the efficiency of the MLE estimator by computing its variance and compare it to the inverse of the Fisher information. One needs an unbiased estimator of the variance, knowing that the mean is <em>a</em>.

<table>

 <tbody>

  <tr>

   <td width="316"><sub>X</sub><em>N</em><u>1 </u><em>V ar</em>[~<em>a<sub>n</sub></em>]<em>N</em><em>k</em>=1</td>

   <td width="317">(~<em>a</em><em>n~k </em>– <em>a</em>)<sup>2</sup></td>

  </tr>

 </tbody>

</table>




<table>

 <tbody>

  <tr>

   <td width="278">=</td>

   <td width="17">1<em>N</em></td>

   <td width="21"><sub>X</sub><em>N</em><em>k</em>=1</td>

   <td width="45"><sub>X</sub><em>n</em>(  12<em>n</em><em>i</em>=1</td>

   <td width="46"><em>x</em>2 <em>i~k </em>– <em>a</em></td>

   <td width="226"><sub>)</sub>2</td>

  </tr>

 </tbody>

</table>




<table>

 <tbody>

  <tr>

   <td width="633">N = 100000 n = 10I = n/a~2<em> # Fisher information</em>V = 0<strong>for</strong> (k<strong> in</strong> 1:N){X = rrayleigh(n, scale=sqrt(a))dV = 1/(2*n)*sum(X~2) – aV = V + dV~2}V = V/NV</td>

  </tr>

 </tbody>

</table>

## [1] 0.5887242

<table>

 <tbody>

  <tr>

   <td width="31">1</td>

   <td width="36"><em><sub>a</sub></em>2</td>

   <td rowspan="3" width="309">~ 0<em>.</em>5847</td>

  </tr>

  <tr>

   <td width="31"> </td>

   <td width="36"> </td>

  </tr>

  <tr>

   <td width="31"><em>I<sub>n</sub></em>(<em>a</em>)</td>

   <td width="36"><em>n</em></td>

  </tr>

 </tbody>

</table>




<table>

 <tbody>

  <tr>

   <td width="320"><em>V ar</em>[~<em>a<sub>n</sub></em>] – <u><sup> 1 </sup></u><em>I</em><em>,</em>(<em>a</em>)<u>1 </u> <em>I</em><em>,</em>(<em>a</em>)</td>

   <td width="313">~ 0<em>.</em>00683 &lt;&lt; 1</td>

  </tr>

 </tbody>

</table>




Hence, one can say that <em>V ar</em>[~<em>a<sub>n</sub></em>] = <u> 1 </u>

<em>I</em><em>,</em>(<em>a</em>) and the estimator is efficient empirically.

<ul>

 <li></li>

</ul>

<table>

 <tbody>

  <tr>

   <td width="108">v’<em>n</em>(~<em>a<sub>n</sub></em>  <em>a</em>) <em>d</em>~~~~~<em>n</em>boo</td>

   <td width="50"><em>N</em>(0<em>, a</em>2)</td>

  </tr>

 </tbody>

</table>

The asymptotic normality means that for <em>n </em>large, /<em>n</em>(~<em>a<sub>n</sub></em> – <em>a</em>) <em>N</em>(0<em>, a</em><sup>2</sup>). Thus one can plot several samples of the random variable <em>Z<sub>n</sub></em> = ~<em>n</em>(~<em>a<sub>n</sub></em> – <em>a</em>) and check whether the distribution looks Gaussian.

<table>

 <tbody>

  <tr>

   <td width="639">

    <table width="100%">

     <tbody>

      <tr>

       <td> </td>

      </tr>

     </tbody>

    </table></td>

  </tr>

 </tbody>

</table>

n = 10000<em> # Size of the observations for each a_n </em>N = 10000<em> # Number of samples of Z_n</em>

Z_n = rep(0,N)

<strong>for</strong> (k<strong> in</strong> 1:N){

X = rrayleigh(n, scale=sqrt(a))

a_n = 1/(2*n)*sum(X~2)

Z_n[k] = sqrt(n)*(a_n – a)

}

hist(Z_n, breaks=40, main = “Asymptotic normality”)




<strong>Asymptotic normality</strong>

−5                              0                              5                             10

Z_n

The MLE estimator is asymptotically normal. One can verify the standard deviation <em>a </em>= 2<em>.</em>418.

<strong>ML estimation with PMF</strong>

<strong>Statistical modelling and theoretical analysis</strong>

<strong>Question 1: Belonging to exponential family</strong>

We study the random variable <em>X </em>that follows a geometric distribution with parameter <em>q </em>E ]0; 1[. We have :V<em>k </em>E N<em><sup>*</sup></em><em>, P</em>(<em>X </em>= <em>k</em>) = <em>q</em>(1 _ <em>q</em>)<em><sup>k</sup></em><sup>_</sup><sup>1</sup>

The likelihood function can be written as :

<em>L</em>(<em>x,q</em>) = <strong>1</strong>N<em>*</em>(<em>x</em>) x <em>q</em>(1 _ <em>q</em>)<em><sup>x</sup></em><sup>_</sup><sup>1</sup>

= <strong>1</strong>N<em>*</em>(<em>x</em>) x <em>q </em>x (<em>x</em>_1) ln(1_<em>q</em>)

= <strong>1</strong>N<em>*</em>(<em>x</em>) x <em> q</em>

1 <em>q </em>x <em>xln</em>(1_<em>q</em>)

We can notice that the model is dominated and the distribution domain where <em>L</em>(<em>x, q</em>) <em>&gt; </em>0 is N<em><sup>*</sup></em> which does not depend on q. Thus the distribution domain is homogeneous. We then define:




We can then write the likelihood like :

<em>L</em>(<em>x, q</em>) =<em> h</em>(<em>x</em>)<em>φ</em>(<em>q</em>) exp (<em>Q</em>(<em>q</em>)<em>S</em>(<em>x</em>))

We can conclude that a geometric distribution belongs to the exponential family and<em> S</em> is a sufficient statistic.Since<em> S</em> is linearly independent with itself, we also deduce that the model is identifiable. <strong>Question 2: Computation of the Fisher Information Matrix</strong>

We saw in question 1 that the model was dominated and the distribution domain was homogeneous. We can also easily show that<em> L</em>(<em>x, q</em>) is twice differentiable for variable q and integrable, since it is a polynomial function. Thus the model is regular. We note<em> l</em>(<em>x, q</em>) the log-likelihood of the model:

V<em>x</em> E N<em>*</em><em> l</em>(<em>xq</em>) = ln(<em>q</em>(1 –<em> q</em>)<em>x</em>_1)

= ln(<em>q</em>) + (<em>x</em>  1) ln(1 <em> q</em>)

We can now deduce the score function:

V<em>x </em>E N<em><sup>*</sup></em><em>,s<sub>q</sub></em>(<em>x</em>) = <em><sup>a</sup></em><em>l</em>(<em>x,q</em>)

<em>aq</em>

1

=

<em>q</em> We can note that the score function is an affine transform of<em> X</em>, thus it is square-integrable because<em> X</em> is, so the Fisher Information Matrix is well-defined. We showed previously that the model was regular, thus we have:

<em>I</em>(<em>q</em>) =<em> E<sub>q</sub></em> (<em>s<sub>q</sub></em>(<em>X</em>)<sup>2</sup>)

= <em>E</em><em>q</em> ( <em>aq</em>2 2<em>___ </em><em>l</em>(<em>X,q</em>))

<em>Eq</em><u> (</u><u>–</u><u>1</u><em><u> X </u></em>1 <em><sub>q</sub></em>2                                                                                       (1 _<em>q</em>)2)<em></em><em>E<sub>q</sub></em>(<em>X</em>)_1                                                                                                    1

<em>and E</em>(<em>X</em>) =

(1<em>q</em>)<sup>2</sup><em>                                                                                                      </em><em>q</em>




<table>

 <tbody>

  <tr>

   <td width="250"></td>

  </tr>

  <tr>

   <td></td>

   <td></td>

  </tr>

 </tbody>

</table>

<table>

 <tbody>

  <tr>

   <td width="639">

    <table width="100%">

     <tbody>

      <tr>

       <td> </td>

      </tr>

     </tbody>

    </table></td>

  </tr>

 </tbody>

</table>

<table>

 <tbody>

  <tr>

   <td width="9">

    <table width="100%">

     <tbody>

      <tr>

       <td>1<em>q</em></td>

      </tr>

     </tbody>

    </table></td>

  </tr>

 </tbody>

</table>

<table>

 <tbody>

  <tr>

   <td width="23">

    <table width="100%">

     <tbody>

      <tr>

       <td>1</td>

      </tr>

     </tbody>

    </table></td>

  </tr>

 </tbody>

</table>

<table>

 <tbody>

  <tr>

   <td width="221">

    <table width="100%">

     <tbody>

      <tr>

       <td>=</td>

      </tr>

     </tbody>

    </table></td>

  </tr>

 </tbody>

</table>

<table>

 <tbody>

  <tr>

   <td width="30">

    <table width="100%">

     <tbody>

      <tr>

       <td>1<em>q</em>2 +</td>

      </tr>

     </tbody>

    </table></td>

  </tr>

 </tbody>

</table>

<table>

 <tbody>

  <tr>

   <td width="48">

    <table width="100%">

     <tbody>

      <tr>

       <td>(1<em>q</em>)<sup>2</sup></td>

      </tr>

     </tbody>

    </table></td>

  </tr>

 </tbody>

</table>




(1<em>q</em>)<sup>2</sup><em>                </em><em>q</em><em>q</em><sup>2</sup>

<em>q</em><sup>2</sup>(1 –<em> q</em>)2 +<em> q</em><sup>2</sup>(1 –<em> q</em>)<sup>2</sup>

1<em>q</em><sup>2</sup>(1 –<em> q</em>)

<strong>Question 3: Maximum likelihood estimator</strong>

Let<em> X</em>1<em>, …, X<sub>n</sub></em> a n-sample following the same distribution as<em> X</em>. The likelihood of the model is :

<em>L</em>(<em>x</em>1<em>,…,x<sub>n</sub>,q</em>) = ~<em>n </em><em>q</em>(1 – <em><sub>q</sub></em>)<em>x</em><em>i</em>_1

<em>i</em>=1

( <em><u> q</u></em>                        (1

–<em> q</em>)

<em>q</em>)

<em>n</em>

= <em>nln </em>( 1____ <em>q</em>) + ln(1 <em> q</em>)          <em>x</em><em>i</em>

<table>

 <tbody>

  <tr>

   <td width="20">

    <table width="100%">

     <tbody>

      <tr>

       <td></td>

      </tr>

     </tbody>

    </table></td>

  </tr>

 </tbody>

</table>

<em>i</em>=1




We look for ~<em>q<sub>n</sub></em> that maximizes the likelihood of the n-sample. Thus it satisfies two equations :




<em>aq</em>

<em>a</em><sup>2</sup>

<em>___ l</em>(<em>x</em>1<em>,…,x<sub>n</sub>,</em>~<em>q<sub>n</sub></em>)<em> &lt; </em>0               (2)




<table>

 <tbody>

  <tr>

   <td width="244">

    <table width="100%">

     <tbody>

      <tr>

       <td>From equation (1) we deduce:</td>

      </tr>

     </tbody>

    </table></td>

  </tr>

 </tbody>

</table>




~ <u>1</u> __________ ~ ~<em><sub>n</sub></em>

+  1                <em><u>i</u></em><u>=1</u><em>__ </em><em>x</em><em>i</em>

<em>n                                 </em>~                                                                = 0

~<em>q<sub>n</sub></em> 1 ~ ~<em>q<sub>n</sub></em>                                 ~<em>q<sub>n</sub></em>

~<em><sub>n</sub></em>

<em>                                                                                            n                      </em><em>i</em>=1<em> x</em><em>i</em>

~<em>q<sub>n</sub></em>(1 ~<em>q<sub>n</sub></em>)                    1 

<table>

 <tbody>

  <tr>

   <td width="355">~~</td>

   <td width="36"><em>n </em>= ~<em>q<sub>n</sub></em></td>

   <td width="21"><em>n</em><em>i</em>=1</td>

   <td width="228"><em>x</em><em>i</em></td>

  </tr>

 </tbody>

</table>







1 <sub>=</sub>1

~~ ~<em>q<sub>n</sub> n</em>




The maximum likelihood estimator<em> q</em><sup>—</sup><em><sub>n</sub></em> is




<strong>Question 4: Asymptotic behavior of the estimator</strong>

Now we are going to study the asymptotic behavior of the estimator. According to the Central limit theorem, we have:

<em>      n</em> (<em>X</em><em>n </em>(0<em>,V </em>(<em>X</em>))    <em>where            V </em>(<em>X</em>) = 1 <em> q</em>

<em>q </em>)<em>  </em><em>q</em><sup>2</sup>

~                         ~                      ~                        ~

<em>L</em>

~~ ~<em>n X<sub>n</sub></em> ~ 1          0<em>, </em>1 ~ <em>q</em>

~~ N __

<em>q                            q</em>2

Then, we use the delta method. We define:<em> g</em> :<em> x</em>         1 which is differentiable in<sup>1</sup>. We have:

<em>x                                                                               q</em>

<em>n</em>(<em>g </em>(<em>X</em><em>n</em>)<em>g</em>(1))<em>L          </em>0<em>‘g</em>,()2 <u>1 </u><u></u><em><u>q</u></em>)

N

<em>q                                             qq</em>2

~~~<em>n</em>(~<em>q<sub>n</sub></em>_<em>q</em>)<em><sup>L</sup></em>~*N(0<em>,</em>(1_<em>q</em>)<em>q</em><sup>2</sup>) ~~ v<em>n</em>(~<em>q<sub>n</sub></em><em>q</em>)<em><sup> L</sup></em>-~N(0<em>,I</em>~<sup>1</sup>(<em>q</em>))

This estimator is asymptotically normal and its asymptotic variance is the Cramer Rao bound, thus the estimator is asymptotically efficient. This was expected because this is a maximum likelihood estimator.

<strong>Question 5: Asymoptotic confidence interval</strong>

Finally, we build an asymptotic confidence interval for<em> q</em>. On pose:

<em>X<sub>n</sub></em> = 1 <em>n</em> <em>X</em><em>i</em>

<em>n</em> <em>i</em>=1




Then, we know that : <em><u><sup>             </sup></u></em><em><u><sup>nq</sup></u></em><em>             t</em>(<em>n </em>– 1), where t is the student law. Since the law is symmetric, we can

<em> S</em><em>n           </em><u>) </u>

~<em>n</em>(<em>X<sub>n</sub></em>~ write: ~<em>t<sup>n</sup></em>~<sup>1</sup>

<em>~~</em>2 ~ <em>       </em><em>S</em><em>n              </em>~ <em>t</em><em>n</em>~1

<em><u>     q </u></em>)          <em>~~</em>2 where<em> t<sup>k</sup></em><em> ~</em>is the unique real number that verifies<em> P</em>(<em>t</em>(<em>k</em>)<em> &lt; t<sup>k</sup></em><em>~</em>) = 1 –<em> a</em>.

Finally, we have:

–<em> t</em><em>n</em>~1

<em>~/</em>2 ~

<em><u>S<sub>n</sub></u></em>                                                                                                                                              1

~~ ~ ~<em><sub>n</sub></em><em>t<sup>n</sup></em>~<sup>1</sup>                                       ~ <em><u>S</u></em><em><u>n</u></em>

<em>~~</em>2 ~ <em>X</em><em><sub>n</sub></em> ~                                                               ~<em><sub>n</sub></em><em>t<sup>n</sup></em>~<sup>1</sup>

<em>~~</em>2

<em>q</em>




<table>

 <tbody>

  <tr>

   <td rowspan="2" width="354">1~~ _______________________________ ~ <em>q </em>~<em>X</em><em><sub>n</sub></em> + <em><u><sup>S</sup></u></em><em><u>n</u></em><u>~</u><em><u><sub>n</sub></u></em><em><u>t<sup>n</sup></u></em><u>~</u><u><sup>1</sup></u><em>~~</em>2</td>

   <td width="79">1</td>

   <td width="6"> </td>

  </tr>

  <tr>

   <td width="79"><em>X</em><em><u>            S</u></em><em><u>n</u></em><em><u>t</u></em><em><u>n</u></em><u>–</u><u>1</u><em>n </em>– V<em>n a/</em>2</td>

   <td width="6"> </td>

  </tr>

 </tbody>

</table>




<strong>Application on real data</strong>

<strong>Question 1: Estimation of the fraud probability</strong>

<table>

 <tbody>

  <tr>

   <td width="628">X = c(44, 9, 11, 59, 81, 19, 89, 10, 24, 07, 21, 90, 38, 01, 15, 22, 29, 19, 37, 26, 219,</td>

   <td width="95">2, 57, 11, 34</td>

  </tr>

  <tr>

   <td width="628">n = length(X) p = (n)/sum(X)</td>

   <td width="95"> </td>

  </tr>

 </tbody>

</table>




The probability of fraud<em><sub> p</sub></em><em><sub>fraud</sub></em> can be estimated with the estimator studied above: <em>p</em><em>fraud</em> = 0<em>.</em>026 . We take 1 –<em> ~</em>= 0<em>.</em>95, we can deduce a confidence interval:

t_alpha = 2.021<em> #quantile for student law for n = 40, closest value available.</em>

Xn=mean(X)

Sn=sqrt(mean((X-Xn)**2)*n/(n-1))

a = 1/(Xn+Sn*t_alpha/sqrt(n))

b = 1/(Xn-Sn*t_alpha/sqrt(n))

With a 95% confidence, we know that<em><sub> p</sub></em><em><sub>fraud</sub></em> is between 0<em>.</em>019<em> and</em> 0<em>.</em>043 . If we have<em> n</em>0 = 20000 validatedtickets, we can estimate the number<em> n</em><em>fraud</em> of fraudsters. For 1000 users, there are 26 fraudsters and 974




<table>

 <tbody>

  <tr>

   <td width="638">

    <table width="100%">

     <tbody>

      <tr>

       <td>

        <table>

         <tbody>

          <tr>

           <td rowspan="2" width="169">honest users. Thus we have</td>

           <td width="68"><em>n</em>0</td>

           <td rowspan="2" width="41">= 534</td>

           <td rowspan="2" width="356">fraudsters.</td>

          </tr>

          <tr>

           <td width="68">1 –<em> p</em><em>fraud</em></td>

          </tr>

         </tbody>

        </table> </td>

      </tr>

     </tbody>

    </table></td>

  </tr>

 </tbody>

</table>




<strong>Exercise 2: Geometric distribution</strong>

<ul>

 <li></li>

</ul>

The parameter<em><sub> p</sub></em><em><sub>fraud</sub></em> of the geometric distribution was estimated with the maximum likelihood estimator ~<em>p</em><em><sub>n</sub></em>. It was found that<em><sub> p</sub></em><em><sub>fraud</sub></em> ~0<em>.</em>026 .

<ul>

 <li></li>

</ul>

One has only access to uniform distribution and would like to output a geometric distribution. We start by randomly drawing a number<em> q</em> between 0 and 1, according to the uniform distribution. Then, we realize the following segmentation of the interval [0<em>,</em> 1]:

+oo<em>k</em><sup></sup>1<em>                         </em><em>k</em>

1         I I                                        (                                  <em>i</em>1                      (                                <em>i</em>1

[

0<em>,</em> 1] = U              <em>p</em><em>f raud</em><sup>1</sup> –<em> p</em><em>fraud</em>)<em> ,     </em><em>p</em><em>f raud</em><sup>1</sup> –<em> p</em><em>fraud</em>)

<em>k</em>=1<em> i</em>=1<em>                                      </em><em>i</em>=1

= +~~ [1 (1 _ <em>p</em><em>fraud</em>)<em>k</em><sup> 1</sup><em>~</em>1 (1 _ <em>p</em><em>fraud</em>)<em><sup>k</sup></em>] <em>k</em>=1




Thus, if we draw<em> q</em>, we look for<em> k</em> that satisfies:

(                     <em>k</em>-1                                    (

1     1 <em>p</em><em>fraud</em>)<em>            </em><em>q </em>1 -1 <em>p</em><em>fraud</em>)

~~ (1<em> p</em><em>fraud</em>)<em><sup>k</sup></em><sup>–</sup><sup>1</sup> &lt;<em> q</em> 1&lt; (1<em> p</em><em>fraud</em>)<em><sup>k</sup></em> ~~ (1<em> p</em><em>fraud</em>)<em><sup>k</sup></em> &lt; 1<em> q</em> &lt;(1<em> p</em><em>fraud</em>)<em><sup>k</sup></em><sup>–</sup><sup>1</sup>

~~ <em>kln</em>(1 _ <em>p</em><em>fraud</em>) &lt;ln(1<em>q</em>) &lt; (<em>k</em>-1)ln(1<em>p</em><em>f</em><em><sub>rau</sub></em><em>d</em>) ~~ <em>k</em>-1 &lt;   ln(1<em>q</em>) &lt;<em>k</em>

ln(1 –<em> p</em><em>fraud</em>)

Since the probability to draw an integer is 0, we can choose<em> k</em> =<u> [</u><u>ln(1</u><u>–</u><em><u>q</u></em><u>) </u>

ln(1<sup>–</sup><em>p</em><em>fraud</em>)<sup>1</sup>

If<em> U</em> follows a uniform distribution on [0<em>,</em> 1], one can generate samples following the geometric distribution using the uniform distribution.

<em>U </em>~ <em>U</em>[0<em>, </em>1] =~ ~  ln(1 ~ <em><u>U</u></em><u>)</u> ln(1<em>p</em><em>fraud</em>)1 ~<em>G</em>(<em>p</em><em>fraud</em>)

n = 100000

U = runif(n)

X = ceiling(log(1-U)/log(1-p))

hist(X, nclass=800, xlim = c(0,200), main = “Simulated Geometric”)

<strong>Simulated Geometric</strong>




0                          50                        100                       150                      200

X




<strong>(c)</strong>

We have shown that:

<em>n</em>(~<em>q<sub>n</sub></em>~<em>q</em>)<em><sup> d</sup></em>~~<em>N</em>(0<em>,q</em><sup>2</sup>(1_<em>q</em>))




The asymptotic normality means that for <em>n </em>large, J<em>n</em>(~<em>a<sub>n</sub></em> – <em>a</em>) <em>N</em>(0<em>, a</em><sup>2</sup>). Thus one can plot several samples of the random variable <em>Z<sub>n</sub></em> = ~<em>n</em>(~<em>q<sub>n</sub></em> – <em>q</em>) and check whether the distribution looks Gaussian.

<table>

 <tbody>

  <tr>

   <td width="633">n = 10000<em> # Size of the observations for each q_n </em>N = 10000<em> # Number of samples of Z_n</em>Z_n = rep(0,N) <strong>for</strong> (k<strong> in</strong> 1:N) {U = runif(n)X = ceiling(log(1-U)/log(1-p))p_n = 1/mean(X)Z_n[k] = sqrt(n)*(p_n – p)}hist(Z_n, breaks=100, main = “Asymptotic normality”)</td>

  </tr>

 </tbody>

</table>

<strong>Asymptotic normality</strong>

−0.10                         −0.05                          0.00                           0.05                          0.10

Z_n

<table>

 <tbody>

  <tr>

   <td width="633">var_emp = mean(Z_n**2) var_theo = p~2*(1-p)</td>

  </tr>

 </tbody>

</table>

The MLE estimator is asymptotically normal.An estimation of the variance gives <em>a </em>= 6<em>.</em>72 x 10~<sup>4</sup>, which is close to the value : <em>p</em>2<em>fraude </em>* (1 <em>p</em><em>fraude</em>) = 6<em>.</em>67 X 10−4

<table>

 <tbody>

  <tr>

   <td rowspan="2" width="339"><strong>(d)</strong>We have shown that a 95% confidence interval is :1________________________________________________________________________________________________________________________________________________ – <em>q </em>–<em>X<sub>n</sub></em> + <em><u><sup>S,</sup></u></em><u>~</u><em><u><sub>n</sub></u></em><em><u>t</u></em><em><u><sup>n</sup></u></em><u><sup>–</sup></u><u><sup>1</sup></u><em>~~</em>2</td>

   <td width="81">1</td>

  </tr>

  <tr>

   <td width="81"><em>X<sub>n</sub></em> – <em><u><sup>S,</sup></u></em><u>~</u><em><u><sub>n</sub></u></em><em><u>t</u></em><em><u><sup>n</sup></u></em><u><sup>–</sup></u><u><sup>1</sup></u><em>~~</em>2</td>

  </tr>

 </tbody>

</table>




<u>1________________________ 1 </u>

For a 95% confidence interval. On obtain:                                            <u>~</u><em><u>n</u></em> . We use the 39 values given and

<em>X</em><em>n</em>+2<em>.</em>021_ <em><u>Sn </u></em><u>~</u><em><u>n</u></em> &lt; <em>q </em>&lt; <em>X</em><em>n</em>-2<em>.</em>021 <em><u>Sn </u></em>

we simulated 5000 times a 39 dataset, we estimate q and compute the % of q in the confidence interval.

<table>

 <tbody>

  <tr>

   <td width="633">n = 39<em> # Size of the observations for each q_n </em>N = 50000<em> # Number of samples of Z_n</em>count = 0q_n = rep(0,N)<strong>for</strong> (k<strong> in</strong> 1:N){U = runif(n)X = ceiling(log(1-U)/log(1-p))p_n = 1/mean(X)q_n[k] = p_n<strong>if</strong> (a&lt;p_n &amp; p_n&lt;b){count = count + 1}}hist(q_n, breaks=100, main = “Confidence interval”)</td>

  </tr>

 </tbody>

</table>

<strong>Confidence interval</strong>




<table>

 <tbody>

  <tr>

   <td width="564">

    <table width="100%">

     <tbody>

      <tr>

       <td> </td>

      </tr>

     </tbody>

    </table></td>

  </tr>

 </tbody>

</table>

<table>

 <tbody>

  <tr>

   <td width="501">

    <table width="100%">

     <tbody>

      <tr>

       <td></td>

      </tr>

     </tbody>

    </table></td>

  </tr>

 </tbody>

</table>

<table>

 <tbody>

  <tr>

   <td width="361">

    <table width="100%">

     <tbody>

      <tr>

       <td>0.02                           0.03                           0.04                          0.05</td>

      </tr>

     </tbody>

    </table></td>

  </tr>

 </tbody>

</table>

<table>

 <tbody>

  <tr>

   <td width="30">

    <table width="100%">

     <tbody>

      <tr>

       <td>q_n</td>

      </tr>

     </tbody>

    </table></td>

  </tr>

 </tbody>

</table>

We obtain that 0<em>.</em>986 of the simulations give an estimation of q in the confidence interv