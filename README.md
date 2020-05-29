# Simple-linear-regression
Simple linear regression without using any external module 
we use math formula

regression line equation
    y = mx + c
    
    where:
      m = slop line
      x = independent variable
      c = intercept point
      y = dependent vaiable
     { 
    m = (((len(x)*xy.sum()))-(x.sum()*y.sum()))/(((len(x)*x2.sum())-x.sum()*x.sum()))
    c = ((y.sum()*x2.sum())-(x.sum()*xy.sum()))/(((len(x)*x2.sum())-(x.sum()*x.sum())))
    }
