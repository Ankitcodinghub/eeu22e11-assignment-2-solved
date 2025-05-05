# eeu22e11-assignment-2-solved
**TO GET THIS SOLUTION VISIT:** [EEU22E11 Assignment 2 Solved](https://www.ankitcodinghub.com/product/eeu22e11-assignment-2-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;99809&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;EEU22E11 Assignment 2 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
The compressive properties of human muscle tissue are sig- nificant for impact biomechanics, surgical simulation and re- habilitation engineering. The most important loading direction is transverse to the muscle fibre direction, and tests performed at TCD on pig muscle samples using a universal testing ma- chine showed nonlinear anisotropic behavior under quasi-static loading conditions 1. In this assignment you will fit regression curves to data from a compression test on a sample performed in the transverse (or cross fibre XF) direction, i.e. correspond- ing to the blue curve in the figure below. You will see that

the relationship between stress and strain is not linear, and therefore defining a constant value for slope of the stress strain curve (ie assuming that there is a Young’s Modulus) will not give a very good fit to the data.

The data is stored in a file muscle_data_2017.xls. Use the following Matlab code to read in the data.

<pre>  raw_data = xlsread(’muscle_data_2017.xlsx’);
  strain = raw_data(:,3);
  stress = raw_data(:,4);
</pre>
</div>
<div class="column">
1 M. Van Loocke, C.G. Lyons, and C.K. Simms. A validated model of passive muscle in compression. Journal of Biomechanics, pages 2999–3009, October 2005

</div>
</div>
<div class="layoutArea">
<div class="column">
You will now explore two different models for the data. We will use the model formulation yˆ = f(φ ) where yˆ is our

</div>
</div>
<div class="layoutArea">
<div class="column">
kkk estimated stress given the measured strain, φk, for the kth

</div>
</div>
<div class="layoutArea">
<div class="column">
measurement. The error between the observed stress yk and

the modelled (estimated) stress yˆ is therefore e = y − yˆ . k kkk

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="section">
<div class="layoutArea">
<div class="column">
1. Plot in figure 1, a plot of the observed stress (on the y- axis) yk Vs strain (on the x-axis) (φk). Use a blue line of thickness 3.

2. You are required to fit the data to a polynomial model. The problem is to estimate the best or appropriate model order m. Test 5 model orders m = [1 : 5]. For each polyno- mial model with order m use the polyfit function in Mat- lab to estimate the coefficients of the polynomial fit to the data. Calculate the sum squared error for each polynomial fit and assign the resulting data to the vector sse_per_m. That vector should be 5 elements long because you will have tested 5 model orders. In figure 2, plot sse_per_m versus model order and use that to select the optimal model order mˆ for this problem. Use a red line of thickness 3. Label the figure and axes appropriately. Assign your selected model order to the variable my_m.

3. Using your selected model order mˆ , calculate the estimated signal yˆk and superimpose that line in red on the plot in figure 1. Assign your estimated signal yˆk to the variable est_stress.

4. Calculate the error between your estimate and the observed stress, plot a histogram in figure 3 showing the distribu-

tion of errors. Your plot should look something like the plot shown on the side panel (no need for the title though). Note that the values shown in that plot may be different from your estimates. Calculate the coefficient of determination for this polynomial fit and assign that to the variable ccoef_p.

5. Now fit the data to a different nonlinear model as follows. (You will have to use fminsearch see the notes below).

yˆ = 1 − a − (a exp(a φ )) (1) k201k

where yˆ is the estimated stress given a strain measurement φ. You must start from an initial estimate [0.3, 0.3, 0.3]. Using your estimated values for a0, a1, a2 calculate the esti- mated signal yˆk and superimpose that line in black/dashed on the plot in figure 1. Your final figure 1 should look some- thing like the plot in the side panel shown here.

</div>
<div class="column">
You will have to use your notes or the book by Chapra to find the definition for the coefficient of determination.

</div>
</div>
<div class="layoutArea">
<div class="column">
70 60 50 40 30 20 10

0 -0.04

</div>
<div class="column">
-0.03 -0.02

Error in Polynomial fit

</div>
<div class="column">
0.03 0.04

</div>
</div>
<div class="layoutArea">
<div class="column">
curve fitting 2

</div>
</div>
<div class="layoutArea">
<div class="column">
Std error = 0.010037r = 0.99943

</div>
</div>
<div class="layoutArea">
<div class="column">
-0.01 0

</div>
<div class="column">
0.01 0.02

</div>
</div>
<div class="layoutArea">
<div class="column">
0 -0.2 -0.4 -0.6 -0.8 -1

-1.2

-0.4 -0.3

</div>
<div class="column">
-0.2 -0.1 0 Strain

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Stress (kPa) Frequency

</div>
</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
6. Calculate the error between your estimate and the observed stress, and assign it to the variable err_nl . Plot a his- togram in figure 4 showing the distribution of errors. (Just use the hist command in Matlab e.g. hist(err_nl)). Hence calculate the coefficient of determination for this non- linear fit, and assign that to the variable ccoef_nl.

Notes

Use » help fminsearch and » help polyfit from the matlab command line (») to find out more about these mat- lab functions and how to use them. For fminsearch you will need to pass arguments to your optimisation function which are not being estimated i.e. the data itself stress, strain. You may do this using the syntax coefs = fminsearch(@(x) func(x, stress, strain),[0.3;0.3;0.3]);. In this in- vocation you are declaring to fminsearch that the error mea- surement is in the function func(), and the @(x) is declar- ing that only the variable x in this function is being opti- mised. You will have to define the function func() your-

self. It will be based on the model you are testing. In this

case x should be a vector with your three model parameters x(1) = a0, x(2) = a1, x(3) = a2. Hence func() then should calculate the sum squared error between the estimated stress using the model given (using your parameters x) and the actual measured stress, given the measured strain.

You might find it useful to know that Matlab string handling uses vector syntax like this.

<pre> str = [’This variable =’, num2str(number), ’while that = ’, num2str(value)];
</pre>
The num2str function turns a number into a string for use in string handling like this. The string itself is in str and it just concatenates all the strings in the vector. You can then use this string for auto-composition of a title. For instance e.g. title(str, ’fontsize’ , 20) will create a title that has the text as follows.

<pre> This variable = 78.2 while that = 7.1
</pre>
When submitting your code for this assignment, please

</div>
</div>
<div class="layoutArea">
<div class="column">
curve fitting 3

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
note that it must obey the Matlab style rules as per the document in the MatlabGuides area of Blackboard.

References

[1] M. Van Loocke, C.G. Lyons, and C.K. Simms. A validated model of passive muscle in compression. Journal of Biome- chanics, pages 2999–3009, October 2005.

</div>
</div>
</div>
