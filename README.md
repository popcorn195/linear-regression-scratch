Developed a Linear Regression Model from scratch to understand the mathematics behind it's working. (No scikit-learn is used).

Formulas used:
y=Wx+b
Cost function J=1/m E(i=0,m) (ycap-y)^2
Mean squared error J=1/m E(i=0,m) (y-(Wx+b))^2
dJ/dW= -2/m E(i=0,m) (x(y-(mx+b)))
dJ/db= -2/m E(i=0,m) (y-(mx+b))
W=W-aplha*dW, b=b-alpha*db aplha=0.0001

This model is being used on "Age" Vs "Experience" of employee.csv file. 
