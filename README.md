Download Link: https://assignmentchef.com/product/solved-stat-547-homework3
<br>
<ol>

 <li>Let {<em>W</em>(<em>t</em>)<em>, </em>0 ≤ <em>t </em>≤ 1} be a Brownian motion (Wiener process). The Brownian bridge {<em>B</em>(<em>t</em>)<em>, </em>0 ≤ <em>t </em>≤ 1} is the Brownian motion conditioned on <em>W</em>(1) = 0 and can be represented as <em>B</em>(<em>t</em>) = <em>W</em>(<em>t</em>) − <em>tW</em>(1). Derive the Karhunen–Loève representation of the Brownian bridge <em>B</em>(<em>t</em>).</li>

 <li>Simulate a sample of 50 realizations of a). the Brownian motion and b). the Brownian bridge. Each curve should have 1000 support points. Show the trajectories on two separate plots and include your R code.</li>

 <li>Let <em>X</em><sub>1</sub><em>,…,X<sub>n </sub></em>be a sample of i.i.d. real-valued random variables sharing a distribution with an unknown density <em>f </em>supported on a compact interval [<em>a,b</em>]. The kernel density estimate (KDE) of <em>f</em>(<em>x</em><sub>0</sub>) at <em>x</em><sub>0 </sub>∈ [<em>a,b</em>] is</li>

</ol>

<em>,</em>

where <em>K<sub>h</sub></em>(·) = <em>h</em><sup>−1</sup><em>K</em>(·<em>/h</em>), <em>K</em>(·) is a kernel function, <em>h &gt; </em>0 is the bandwidth. Write down an intuitive argument for why the KDE “works”. [Hint: consider a uniform kernel <em>K</em>]

<ol start="4">

 <li>Analyze the Lake Acidity data in the gss package of R. The data were extracted from the Eastern Lake Survey of 1984 conducted by the United States Environmental Protection Agency, concerning 112 lakes in the Blue Ridge. To gain access to the data, type the following commends in R:</li>

</ol>

library ( gss )

data ( LakeAcidity )

For more information check the help document about this data set.

<ol start="5">

 <li>Perform a nonparametric regression on the calcium concentration (Y) against surface ph level (X).</li>

</ol>

1

<ul>

 <li>Show a KDE and a dot plot of the ph levels.</li>

 <li>Compare the results of local polynomial estimator, smoothing spline, regression spline and penalized spline. Manually vary the tuning parameters, including bandwidth, the number of knots, and the penalty <em>λ </em>on the second derivative of the regression curve. For each smoother identify a parameter setting that i). oversmooths (the estimate is too smooth), ii) undersmooths (the estimate is too rough), and iii) smooths appropriately. Show the graphs and your code.</li>

 <li>Write a brief summary of your data analysis.</li>

</ul>