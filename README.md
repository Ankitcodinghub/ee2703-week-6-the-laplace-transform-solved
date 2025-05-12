# ee2703-week-6-the-laplace-transform-solved
**TO GET THIS SOLUTION VISIT:** [EE2703 Week 6-The Laplace Transform Solved](https://www.ankitcodinghub.com/product/ee2703-week-6-the-laplace-transform-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;90810&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;EE2703 Week 6-The Laplace Transform Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
Python 7 assignment The Laplace Transform

In this assignment, we will look at how to analyse “Linear Time-invariant Systems” with numerical tools in Python. LTI systems are what Electrical Engineers spend most of their time thinking about – linear circuit analysis or communication channels for example. In this assignment we will use mostly mechanical examples, but will move on to circuits in the next assignment.

All the problems will be in “continuous time” and will use Laplace Transforms. Python has a Signals toolbox which is very useful and complete. In this assignment, we will explore the following commands:

Command Description

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
poly1d

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Defines polynomials &gt;&gt;&gt; p = poly1d([1, 2, 3]) &gt;&gt;&gt; print poly1d(p)

1×2 +2x+3

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
polyadd

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
&gt;&gt;&gt; polyadd([1, 2], [9, 5, 4])

array([9, 6, 6])

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
polymul

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
&gt;&gt;&gt; polymul([1,2],[9,5,4])

array([ 9, 23, 14, 8])

</div>
</div>
</td>
</tr>
<tr>
<td></td>
<td>
<div class="layoutArea">
<div class="column">
Using poly1d objects:

&gt;&gt;&gt; p1 = np.poly1d([1, 2]) &gt;&gt;&gt; p2 = np.poly1d([9, 5, 4]) &gt;&gt;&gt; print p1 + 2

&gt;&gt;&gt; print p2

29 x + 5 x + 4

&gt;&gt;&gt; print p1 + p2

29 x + 6 x + 6

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
signal toolbox import scipy.signal as sp

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
sp.lti

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
&gt;&gt;&gt; s=sp.lti(Num,Den) defines a transfer function &gt;&gt;&gt; H=sp.lti([1,2,1],[1,2,1,1]) &gt;&gt;&gt; w,S,phi=H.bode()

&gt;&gt;&gt; subplot(2,1,1)

&gt;&gt;&gt; semilogx(w,S)

&gt;&gt;&gt; subplot(2,1,2)

&gt;&gt;&gt; semilogx(w,phi)

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
sp.impulse

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
&gt;&gt;&gt; t,x=sp.impulse(H,None, linspace(0,10,101))

Computes the impulse response of the transfer function

&gt;&gt;&gt; plot(t,x)

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Command Description

Next week we will explore sympy, which has powerful symbolic capabilities. For now we will use the simple tools in scipy. Unfortunately, scipy has poly1d but cannot define rational functions. That is why we define transfer functions using Num,Den rather than as a rational function of s.

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
sp.lsim

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
&gt;&gt;&gt; t=linspace(0,10,101)

&gt;&gt;&gt; u=sin(t)

&gt;&gt;&gt; t,y,svec=sp.lsim(H,u,t)

This simulates y=convolution of u and h

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
1

1.

2.

3.

4.

5.

</div>
<div class="column">
The Assignment

The Laplace transform of f(t) = cos(1.5t)e−0.5tu0(t) is given by F(s)= s+0.5

(s + 0.5)2 + 2.25 Solve for the time response of a spring satisfying

x ̈+2.25x= f(t)

with x(0) = 0 and x ̇ = 0 for t going from zero to 50 seconds. Use system.impulse to

do the computation

Solve the above problem with a much smaller decay:

f(t) = cos(1.5t)e−0.05tu0(t)

Consider the problem to be an LTI system. f(t) is the input, and x(t) is the output. Obtain the system transfer function X(s)/F(s). Now use signal.lsim to simulate the problem. In a for loop, vary the frequency of the cosine in f(t) from 1.4 to 1.6 in steps of 0.05 keeping the exponent as exp(−0.05t) and plot the resulting responses. Explain what is happening.

Solve for a coupled spring problem:

x ̈+(x−y) = 0

y ̈+2(y−x) = 0

where the initial condition is x(0) = 1, x ̇(0) = y(0) = y ̇(0) = 0. Substitute for y from the first equation into the second and get a fourth order equation. Solve for its time evolution, and from it obtain x(t) and y(t) for 0 ≤ t ≤ 20.

Obtain the magnitude and phase response of the Steady State Transfer function of the following two-port network.

</div>
</div>
<div class="layoutArea">
<div class="column">
R

100 Ω

</div>
<div class="column">
L

1uH inductor

</div>
</div>
<div class="layoutArea">
<div class="column">
C

1.0 uF

</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
6. Consider the problem in Q5. suppose the input signal vi(t) is given by vi(t) = cos􏰁103t􏰂u(t)−cos􏰆106t􏰇u(t)

Obtain the output voltage v0(t) by defining the transfer function as a system and obtaining the output using signal.lsim.

How do you explain the output signal for 0 &lt; t &lt; 30μs? Can you explain the long term response on the msec timescale?

Note: You need to capture the fast variation, which means your time step should be smaller than 10−6. Yet you need to see the slow time, which means you must simulate till about 10 msec. Use an appropriate time vector.

Note: Since the network is resistive, the current at t = 0− will have decayed to zero, which gives you your initial condition.

</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</div>
