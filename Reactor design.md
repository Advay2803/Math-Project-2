# Design of PFR
For the reaction of propyne with chlorine is as followed:

Propyne + Chlorine = Allyl chloride + hydrogen chloride (Reaction-1)
Propyne + chlorine = Dichloropropene  (Reaction-2)

The major design equation are:
The mole balance equation of species j:
    dFpdL = A*(-r1-r2)
    dFcdL = A*(-r1-r2)
    dFadL = A*(r1)
    dFddL = A*(r2)
    dFhdL = A*(r1)
    
The energy balance equation for the reactor:
    dTdL = A*(-(delH1*r1 + delH2*r2) + U*Al*(T-Ta))/(Ft*Cpt)

I couldnt fit the parameters well, as i have a bad parameter guess,
The result is as followed:
![file-1] (https://github.com/Advay2803/Math-Project-2/blob/main/file-1.png)

