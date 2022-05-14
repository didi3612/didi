# didi

%matplotlib inline
import numpy as np
import sympy as sp
import matplotlib.pyplot as plt

x=np.linspace(-5,5 ,1000)
y=np.sinc(x)
plt.plot(x,y,c="purple")
