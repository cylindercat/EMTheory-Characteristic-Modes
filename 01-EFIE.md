# Electric Field  Integral Equation

A plane wave illuminates a PEC object.

**Incident field:**

![EH-Incident](http://latex.codecogs.com/png.latex?%5Cdpi%7B120%7D%20%5Clarge%20%5Cleft%20%28%20%5Cmathbf%7BE%7D%5Ei%2C%20%5Cmathbf%7BH%7D%5Ei%20%5Cright%20%29)

**Scatterring field:**

![EH-Scatterred](http://latex.codecogs.com/png.latex?%5Cdpi%7B120%7D%20%5Clarge%20%5Cleft%20%28%20%5Cmathbf%7BE%7D%5Es%2C%20%5Cmathbf%7BH%7D%5Es%20%5Cright%20%29)

**Total field:**

![EH-total-E](http://latex.codecogs.com/png.latex?%5Cdpi%7B120%7D%20%5Clarge%20%5Cmathbf%7BE%7D%3D%5Cmathbf%7BE%7D%5Ei&plus;%5Cmathbf%7BE%7D%5Es)

![EH-total-H](http://latex.codecogs.com/png.latex?%5Cdpi%7B120%7D%20%5Clarge%20%5Cmathbf%7BH%7D%3D%5Cmathbf%7BH%7D%5Ei&plus;%5Cmathbf%7BH%7D%5Es)

**Induced surface source:**

![Induced-Js](http://latex.codecogs.com/png.latex?%5Cdpi%7B120%7D%20%5Clarge%20%5Cmathbf%7BJ%7D%3D%5Chat%7B%5Cmathbf%7Bn%7D%7D%5Ctimes%5Cmathbf%7BH%7D)

**Boundary cindition:**

![BC-PEC-Surface](http://latex.codecogs.com/png.latex?%5Cdpi%7B120%7D%20%5Clarge%20%5Cleft%5B%20%5Cmathbf%7BE%7D%5Ei%5Cleft%20%28%20%5Cmathbf%7Br%7D%5Cright%20%29%20&plus;%20%5Cmathbf%7BE%7D%5Es%5Cleft%20%28%20%5Cmathbf%7Br%7D%20%5Cright%20%29%5Cright%20%5D_%7B%5Ctext%7Btan%7D%7D%20%3D%200%2C%20%5Cmathbf%7Br%7D%5Cin%20S)

---

The scatterring field can be calculated by the potential functions.

![Es-Equation1](http://latex.codecogs.com/png.latex?%5Cdpi%7B120%7D%20%5Cmathbf%7BE%7D%5Es%5Cleft%20%28%20%5Cmathbf%7Br%7D%20%5Cright%20%29%3D-j%5Comega%5Cmathbf%7BA%7D%5Cleft%20%28%20%5Cmathbf%7Br%7D%20%5Cright%20%29-%5Cnabla%5CPhi%5Cleft%20%28%20%5Cmathbf%7Br%7D%20%5Cright%20%29)

To express it by the induced surface current:

![Es-Equation2](http://latex.codecogs.com/png.latex?%5Cdpi%7B120%7D%20%5Cmathbf%7BE%7D%5Es%5Cleft%20%28%20%5Cmathbf%7Br%7D%20%5Cright%20%29%3D-%5Cfrac%7Bj%5Comega%5Cmu_0%7D%7B4%5Cpi%7D%5Cint_SG%5Cleft%20%28%20%5Cmathbf%7Br%7D%2C%20%5Cmathbf%7Br%7D%27%20%5Cright%20%29%5Cmathbf%7BJ%7D%5Cleft%20%28%20%5Cmathbf%7Br%7D%27%20%5Cright%20%29dS%27-%5Cfrac%7Bj%7D%7B4%5Cpi%5Cepsilon_0%5Comega%7D%5Cnabla%5Cint_S%20%5Cleft%5B%20%5Cnabla%27%5Ccdot%5Cmathbf%7BJ%7D%5Cleft%20%28%20%5Cmathbf%7Br%7D%27%20%5Cright%20%29%20%5Cright%5D%20G%5Cleft%20%28%20%5Cmathbf%7Br%7D%2C%20%5Cmathbf%7Br%7D%27%20%5Cright%20%29dS%27)

To use a integro-differential operator to express the scattering field:

![L-Operator](http://latex.codecogs.com/png.latex?%5Cdpi%7B120%7D%20%5Cmathcal%7BL%7D%5Cleft%5B%20%5Cmathbf%7BJ%7D%5Cleft%20%28%20%5Cmathbf%7Br%7D%20%5Cright%20%29%20%5Cright%5D%20%3D%20-%5Cmathbf%7BE%7D%5Es%5Cleft%20%28%20%5Cmathbf%7Br%7D%20%5Cright%20%29)

On the surface:

![BC-With-Operator](http://latex.codecogs.com/png.latex?%5Cdpi%7B120%7D%20%5Cleft%5B%20%5Cmathcal%7BL%7D%5Cleft%20%5B%20%5Cmathbf%7BJ%7D%5Cleft%20%28%20%5Cmathbf%7Br%7D%20%5Cright%20%29%20%5Cright%20%5D%20-%20%5Cmathbf%7BE%7D%5Ei%5Cleft%20%28%20%5Cmathbf%7Br%7D%20%5Cright%20%29%20%5Cright%20%5D_%7B%5Ctext%7Btan%7D%7D%20%3D%200%2C%20%5Cmathbf%7Br%7D%5Cin%20S)


