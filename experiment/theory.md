<script src='https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.4/MathJax.js?config=default'></script>

<strong>Theory:</strong>A first order system is one in which highest power of ‘s’ in denominator if transfer function defines order of the system.
					<br>For first order system,
					$${\frac{C(s)}{R(s)}=\frac{1}{sT+1}}$$ <span style="float: right;">...... (1),</span><br>
					$${C(s)=\frac{1}{sT+1}R(s)}$$
					<ol>
						<strong><li><em>For the unit-step input:</em></li></strong>
						<br>R(t)=1,<br>R(s)=1/s <span style="float: right;">(a),</span><br>
						Since the Laplace transform of the unit step function is 1/s , substituting R(s)=1/s in equation (1),
						$${\frac{C(s)}{R(s)}=\frac{1}{sT+1}\frac{1}{s}}$$ 
						Substitute the value of R(s)<br>
						Expanding C(s) into partial fractions gives,
						$${\frac{C(s)}{R(s)}=\frac{1}{s}-\frac{1}{sT+1}}$$<span style="float:right;">...... (2),</span><br>
						$${\frac{C(s)}{R(s)}=\frac{1}{s}-\frac{1}{s+(\frac{1}{T})}}$$
						Taking the inverse Laplace t+-ransform of equation (2),we get,<br>
						C(t) = 1- e<sup>-t/T</sup> for t ≥ 0 <span style="float:right;">...... (3),</span><br>
						Equation (3) shows that initially (when t=0), the output C(t) is zero and finally (t→∞) e<sup>-t/T</sup> is zero and the output C(t) becomes unity. 
						<br>
						At t=T,&emsp;&emsp; C(t) = 1 – e<sup>-1</sup> = 1 – 0.368 = 0.632,<br>
						That’s , the output response has reached 63.2 % of it’s final value . T is known as the time constant. Thus, the time constant T is defined as the time required for the output response to attain 63.2% of its final value or steady state value.<br>
						Equation (3) shows that the response curve is exponential in nature as shown on figure:
						<br>
						<img src="./images/steprespo1.png">
						<strong><li><em>For the unit-impulse input:</em></li></strong><br>
						Response of the first order system with unit impulse response:
						<br>
						For the unit-impulse input<br>
						R(s) = 1
						<br>
						 $${C(s) =\frac{1}{sT+1}R(s)}$$ <span style="float: right;">...... (1),</span>
						<br>
						Subsituting the value of R(S) = 1 in equation (1), we get
						<br>
						$${C(s) =\frac{1}{sT+1}}$$
						$${C(s) =\frac{1}{T}\frac{1}{s+\frac{1}{T}}}$$ <span style="float: right;">...... (2),</span><br>
						Taking the inverse laplace transform of the equation of (2), we get the output response as
						$${C(s) = \frac{1}{T}e^\frac{-t}{T}}$$ for t >= 0 <span style="float: right;">...... (3),</span><br>
						The output response curve is shown below in the figure:<br>
						<img src="./images/impulserespo1.png">
					</ol>
