# Design of PFR

The major design equation are:
The mole balance equation of species j:
    dFpdL = A*(-r1-r2)
    dFcdL = A*(-r1-r2)
    dFadL = A*(r1)
    dFddL = A*(r2)
    dFhdL = A*(r1)
    
The energy balance equation for the reactor
    dTdL = A*(-(delH1*r1 + delH2*r2) + U*Al*(T-Ta))/(Ft*Cpt)
