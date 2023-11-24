# MVSK

* M - Mean
* V - Variance (square the standard deviation)
* S - Skew
* K - Kurtosis

![image](https://github.com/iseahound/MVSK/assets/9779668/a1638a62-ff08-4b56-94f8-c3f0fa0710bc)

Notes: I believe this uses the Edgeworth series.

This is not the ONLY way a distribution could generate skewedness or kurtosis. It's one of many "continuations" of the Gasussian Distribution. 

Additional Note: If you change the standard deviation from 3.25 to 3.16 (which is the squarerot of 10), the MVSK function will match the Gaussian. However, I chose to use 3.25 to show the 2 functions visually.

See: https://www.statsmodels.org/stable/generated/statsmodels.sandbox.distributions.extras.pdf_mvsk.html
