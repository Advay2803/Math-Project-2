# Design of PFR
For the reaction of propyne with chlorine is as followed:

Propyne + Chlorine = Allyl chloride + hydrogen chloride (Reaction-1)
Propyne + chlorine = Dichloropropene  (Reaction-2)

**The major design equation are:**
The mole balance equation of species j:
    dFpdL = A*(-r1-r2)
    dFcdL = A*(-r1-r2)
    dFadL = A*(r1)
    dFddL = A*(r2)
    dFhdL = A*(r1)
    
The energy balance equation for the reactor:
    dTdL = A*(-(delH1*r1 + delH2*r2) + U*Al*(T-Ta))/(Ft*Cpt)
    
**The experimental data for the given reaction is:**
![download(file-7)] (https://github.com/Advay2803/Math-Project-2/blob/main/file-7.png)
![download(file-8)] (https://github.com/Advay2803/Math-Project-2/blob/main/file-8.png)

**I couldnt fit the parameters well, as i have a bad parameter guess,
The result is as followed:**
![download(file-2)] (https://github.com/Advay2803/Math-Project-2/blob/main/file-2.png)
![download(file-1)] (https://github.com/Advay2803/Math-Project-2/blob/main/file-1.png)

**Sensitivity Analysis**
The sensitivity analysis is done on U (Heat transfer coefficient of coolant) as, temperature inside the reactor is a strong function of U.
Thus the variation in T, by changing the parameters by 20% above and below its actual value,
![download(file-3)] (https://github.com/Advay2803/Math-Project-2/blob/main/file-3.png)

**For effect of each parameter**
![download(file-4)] (https://github.com/Advay2803/Math-Project-2/blob/main/file-4.png)

**The linear model is shown as**
![download(file-9)] (https://github.com/Advay2803/Math-Project-2/blob/main/file-9.png)

**Conclusion:**
This study is very useful as for this case we consider temperature of reactor(T) as a major important factor.
It would be more essential to have a control over the temperature in reactor (T) as it can help maximize the conversion in the given reactor volume.
It’s also important to control temperature, when the product is temperature sensitive and can degrade at high T.


