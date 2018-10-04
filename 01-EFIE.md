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

Additionally,this operator can be regarded as an impedance operator because the operator can be expressed as:

![L-Operator-Z1](http://latex.codecogs.com/png.latex?%5Cdpi%7B120%7D%20%5Cmathcal%7BL%7D%5Cleft%5B%5Cmathbf%7BJ%7D%5Cleft%28%5Cmathbf%7Br%7D%20%5Cright%20%29%20%5Cright%20%5D%3Dj%5Comega%5Cmu_0%5Ccdot%5Cfrac%7B1%7D%7B4%5Cpi%7D%5Cleft%5B%5Cint_S%5Cmathbf%7BJ%7D%5Cleft%28%5Cmathbf%7Br%7D%27%20%5Cright%20%29G%5Cleft%28%5Cmathbf%7Br%7D%2C%20%5Cmathbf%7Br%7D%27%20%5Cright%20%29dS%27%20&plus;%20%5Cfrac%7B1%7D%7Bk%5E2_0%7D%20%5Cnabla%5Cint_S%20G%5Cleft%28%5Cmathbf%7Br%7D%2C%20%5Cmathbf%7Br%7D%27%20%5Cright%20%29%20%5Cnabla%27%20%5Ccdot%20%5Cmathbf%7BJ%7D%5Cleft%28%5Cmathbf%7Br%7D%27%20%5Cright%20%29%20dS%27%5Cright%20%5D)

The integral part of this expression can be analogous to the inductance in the formula of impedance. Therefore, one can use Z to express this operator.

![L-Operator-Z2](http://latex.codecogs.com/png.latex?%5Cdpi%7B120%7D%20%5Cmathcal%7BL%7D%5Cleft%5B%5Cmathbf%7BJ%7D%5Cleft%28%5Cmathbf%7Br%7D%20%5Cright%20%29%20%5Cright%20%5D%3D%5Cmathbf%7BZ%7D%5Cleft%5B%5Cmathbf%7BJ%7D%5Cleft%28%5Cmathbf%7Br%7D%20%5Cright%20%29%20%5Cright%5D)

On the surface:

![BC-With-Operator](http://latex.codecogs.com/png.latex?%5Cdpi%7B120%7D%20%5Cleft%5B%20%5Cmathcal%7BL%7D%5Cleft%20%5B%20%5Cmathbf%7BJ%7D%5Cleft%20%28%20%5Cmathbf%7Br%7D%20%5Cright%20%29%20%5Cright%20%5D%20-%20%5Cmathbf%7BE%7D%5Ei%5Cleft%20%28%20%5Cmathbf%7Br%7D%20%5Cright%20%29%20%5Cright%20%5D_%7B%5Ctext%7Btan%7D%7D%20%3D%200%2C%20%5Cmathbf%7Br%7D%5Cin%20S)

---

**Poynting Theorem**

For a PEC surface equivalent problem: no magnetic current source.

![Poynting-1](http://latex.codecogs.com/png.latex?%5Cdpi%7B120%7D%20-%5Cfrac%7B1%7D%7B2%7D%5Cint_V%20%5Cmathbf%7BE%7D%5Ccdot%5Cmathbf%7BJ%7D_i%5E*%20dV%20%3D%20%5Cfrac%7B1%7D%7B2%7D%5Coint_S%5Cmathbf%7BE%7D%5Ctimes%5Cmathbf%7BH%7D%5E*%20dS%20&plus;j%5Cfrac%7B%5Comega%7D%7B2%7D%5Cint_V%5Cleft%28%20%5Cmu%5Cleft%20%7C%20%5Cmathbf%7BH%7D%20%5Cright%20%7C%5E2%20-%5Cepsilon%5Cleft%20%7C%20%5Cmathbf%7BE%7D%20%5Cright%20%7C%5E2%20%5Cright%20%29%20dV)

Then use Z operator to substitute it:

![Poynting-2](http://latex.codecogs.com/png.latex?%5Cdpi%7B120%7D%20%5Cmathbf%7BE%7D%20%3D%20-%5Cmathbf%7BZ%7D%5Cleft%28%5Cmathbf%7BJ%7D%20%5Cright%20%29)

![Poynting-3](http://latex.codecogs.com/png.latex?%5Cdpi%7B120%7D%20-%5Cfrac%7B1%7D%7B2%7D%5Cint_V%5Cmathbf%7BE%7D%5Ccdot%5Cmathbf%7BJ%7D%5E*%20dV%20%3D%20%5Cfrac%7B1%7D%7B2%7D%20%5Cleft%20%5Clangle%20%5Cmathbf%7BZ%7D%5Ccdot%5Cmathbf%7BJ%7D%2C%20%5Cmathbf%7BJ%7D%5E*%20%5Cright%20%5Crangle)

Then:

![Poynting-4](http://latex.codecogs.com/png.latex?%5Cdpi%7B120%7D%20%5Cfrac%7B1%7D%7B2%7D%20%5Cleft%20%5Clangle%20%5Cmathbf%7BZ%7D%5Ccdot%5Cmathbf%7BJ%7D%2C%20%5Cmathbf%7BJ%7D%5E*%20%5Cright%20%5Crangle%20%3D%20%5Cfrac%7B1%7D%7B2%7D%20%5Cleft%20%5Clangle%20%5Cmathbf%7BR%7D%5Ccdot%5Cmathbf%7BJ%7D%2C%20%5Cmathbf%7BJ%7D%5E*%20%5Cright%20%5Crangle%20&plus;%20j%5Cfrac%7B1%7D%7B2%7D%20%5Cleft%20%5Clangle%20%5Cmathbf%7BX%7D%5Ccdot%5Cmathbf%7BJ%7D%2C%20%5Cmathbf%7BJ%7D%5E*%20%5Cright%20%5Crangle)

Radiated power:

![Poynting-4a](http://latex.codecogs.com/png.latex?%5Cdpi%7B120%7D%20%5Cfrac%7B1%7D%7B2%7D%20%5Cleft%20%5Clangle%20%5Cmathbf%7BR%7D%5Ccdot%5Cmathbf%7BJ%7D%2C%20%5Cmathbf%7BJ%7D%5E*%20%5Cright%20%5Crangle%20%3D%20%5Cfrac%7B1%7D%7B2%7D%5Coint_S%5Cleft%28%20%5Cmathbf%7BE%7D%5Ctimes%5Cmathbf%7BH%7D%5E*%20%5Cright%20%29dS)

Stored power:

![Poynting-4b](http://latex.codecogs.com/png.latex?%5Cdpi%7B120%7D%20%5Cfrac%7B1%7D%7B2%7D%20%5Cleft%20%5Clangle%20%5Cmathbf%7BX%7D%5Ccdot%5Cmathbf%7BJ%7D%2C%20%5Cmathbf%7BJ%7D%5E*%20%5Cright%20%5Crangle%20%3D%20%5Cfrac%7B%5Comega%7D%7B2%7D%5Cint_V%5Cleft%28%20%5Cmu%5Cleft%20%7C%20%5Cmathbf%7BH%7D%20%5Cright%20%7C%5E2%20-%20%5Cepsilon%5Cleft%20%7C%20%5Cmathbf%7BE%7D%20%5Cright%20%7C%5E2%20%5Cright%20%29dV)

---
**Weighted eigenvalue equation:**

![WEE-1](http://latex.codecogs.com/png.latex?%5Cdpi%7B120%7D%20%5Cmathbf%7BZ%7D%5Ccdot%5Cmathbf%7BJ%7D_n%20%3D%20%5Cnu_n%20%5Cmathbf%7BW%7D%5Ccdot%5Cmathbf%7BJ%7D_n)

The operator **W** is a weighting variable. If **W** is set to **R** and expand **Z** to **R+jX**, then the original weighted eigenvalue equation is:

![WEE-2](http://latex.codecogs.com/png.latex?%5Cdpi%7B120%7D%20%5Cmathbf%7BX%7D%5Ccdot%5Cmathbf%7BJ%7D_n%20%3D%20%5Clambda_n%20%5Cmathbf%7BR%7D%5Ccdot%5Cmathbf%7BJ%7D_n)

where

![WEE-3](http://latex.codecogs.com/png.latex?%5Cdpi%7B120%7D%20%5Cnu_n%20%3D%201%20&plus;%20%5Clambda_n)

The absolute value of eigenvalue is proportional to the total stored energy within a radiation or scattering problem.

Resonant mode:

![WEE-R](http://latex.codecogs.com/png.latex?%5Cdpi%7B120%7D%20%5Clambda_n%20%3D%200)

Inductive mode:

![WEE-L](http://latex.codecogs.com/png.latex?%5Cdpi%7B120%7D%20%5Clambda_n%20%3E%200)

Capacitive mode:

![WEE-C](http://latex.codecogs.com/png.latex?%5Cdpi%7B120%7D%20%5Clambda_n%20%3C%200)

---
**Orthogonality:**

![Orthogonality](http://latex.codecogs.com/png.latex?%5Cdpi%7B120%7D%20%5Cleft%20%5Clangle%20%5Cmathbf%7BJ%7D_m%2C%20%5Cmathbf%7BZ%7D%5Ccdot%5Cmathbf%7BJ%7D_n%20%5Cright%20%5Crangle%20%3D%20%5Cleft%20%5Clangle%20%5Cmathbf%7BJ%7D_m%5E*%2C%20%5Cmathbf%7BZ%7D%5Ccdot%5Cmathbf%7BJ%7D_n%20%5Cright%20%5Crangle%3D%5Cleft%281&plus;j%5Clambda_n%20%5Cright%20%29%5Cdelta_%7Bmn%7D)
