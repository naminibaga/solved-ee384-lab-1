Download Link: https://assignmentchef.com/product/solved-ee384-lab-1
<br>
<h1>Problem 1: Common sequence (turn in your codes)</h1>

1.1) Create a ‘unit_impulse’ <strong>function</strong> that creates a unit impulse sequence y(n). The function should accepts input arguments of  n_p, n1, and n2 where n1 and n2 are the start and the end of the sequence; n_p is the position of the pulse. Note that for each value of n:




1.2) Create a ‘unit_step’ <strong>function</strong> that creates a unit step sequence y(n). The function should accepts input arguments of  n_s, n1, and n2 where n1 and n2 are the start and the end of the sequence; n_s is the step position. Note that for each value of n:




<h1>Problem 2: Time-shift and Time-reversal (turn in your codes and plots)</h1>

2.1) Create a ‘time_shift’ <strong>function</strong> that create an output sequence y(n) as a delayed version of the input sequence x(n). The function should accept input arguments of x, n, and n_d where n_d is the number of samples delayed.

2.2) Let x(n) = 2n + 3, where n = -10:10.

<ol>

 <li>Plot x(n).</li>

 <li>Plot a time delayed version of x(n) delayed by 3 samples.</li>

 <li>Plot the time-reversal of x(n)</li>

</ol>

2.3) Plot y(n) = 5*δ(n + 4) – 2* δ(n -2); n = -10:10 2.4) Plot z(n) = u(n) – u(n-4)   ; n = -10:10 where δ(n) is the unit impulse sequence and u(n) is the unit step sequence.

<h1>Problem 3: Systems (turn in your codes and plots)</h1>

The additional file ‘SAMPLE_ECG.mat’ stores a sequence of Electrocardiography, an interpretation of the electrical activity of the heart over a period of time.

3.1) Load and Plot the signal. Call this signal x(n)

3.2) Using for loop, write a program that creates an output y(n) where

3.3) Plot both x(n) and y(n) in a same figure using the subplot command. The vertical axis varies from 100 to 200 and the horizontal axis varies from 0 to 2000 for both plots. Hint: use the command axis([0 2000 100 220]). Your figure should look similar to the following: (remember to put titles for each plots)

3.4) Does y(n) look smoother than x(n)? You have just filtered the original signal using a low-pass filter. The filter is supposed to remove high frequency components of the signal.

Read:

<ol>

 <li>Direct form-II implementation of a standard difference equation.</li>

 <li>Convolution of two discrete-time signals.</li>

 <li>Nyquist theorem</li>

</ol>