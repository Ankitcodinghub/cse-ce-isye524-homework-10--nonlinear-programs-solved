# cse-ce-isye524-homework-10--nonlinear-programs-solved
**TO GET THIS SOLUTION VISIT:** [CSE-CE-ISyE524 Homework 10- Nonlinear Programs Solved](https://www.ankitcodinghub.com/product/cse-ce-isye524-homework-10-nonlinear-programs-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;120318&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE-CE-ISyE524 Homework 10- Nonlinear Programs Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
Note: for this Homework set, I suggest using the Ipopt solver in JuMP. I verified that it works on my system (after running Pkg.update() and restarting Julia). Be sure to make use of the macros @NLconstraint and @NLobjective when specifying nonlinear constraints or objectives respectively.

1. Hexagon construction. The goal is to figure out the optimal geometry of a hexagon such that (1) the hexagon’s area is maximized and (2) the hexagon’s diameter does not exceed 1. The diameter of the hexagon is the largest distance between any pair of points belonging to the hexagon. There are many different ways to solve this problem. A few suggestions/hints:

• Place one of the vertices at the origin so that you don’t need as many decision variables. • A simple way of computing the area of a hexagon is to split it into four triangles that share a common vertex. The area of the hexagon is then the sum of the areas of the four triangles. • The optimal solution will look like a legitimate hexagon. It will not be degenerate (no coincident vertices), nor will it be perfectly regular (all sidelengths equal).

Plot a picture of the optimal hexagon.

2. Fertilizer influence model. A series of experiments is conducted to determine the effect of a particular fertilizer on wheat crop yield. Here are the results: Such situations typically involve some sort

fertilizer rate (x) crop yield (y)

−5 127

−3 151

−1 379

1 421

3 460

5 426

of “diminishing returns”. So there is a limit to how much the fertilizer can boost the yield. A popular model for this relationship is the following:

y = k1 + k2 exp(k3x)

Use nonlinear least squares to determine the values of (k1,k2,k3) that provide the best fit to the data. We are expecting coefficients in the neighborhood of (500,−200,−1).

To display your result, produce a plot of the original data points and the best-fit curve.

1 of 1
