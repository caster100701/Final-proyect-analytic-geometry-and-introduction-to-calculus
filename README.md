# Final-proyect-analytic-geometry-and-introduction-to-calculus
## Tangent line to a segment of a circle given an x-coordinate
### Solís Pedraza Francisco fran_sp@comunidad.unam.mx
### Type of license: GPL (General Public License v3.0)
#### Installation and execution:

#### Introduction:
The following program has the intention of reflecting the application of the knowledge acquired in the subject Analytic Geometry and Introduction to Calculus taught by Dr. Víctor Hugo De la Luz Rodríguez in the major of Technology for the information in sciences at the Escuela Nacional de Estudios Superiores unidad Morelia (ENES Morelia). 
This code works directly with data provided by the user typed in the console; the first two entrance are the center of the circumference the x-coordinate and the y-coordinate respectively (called **h** and **k**), the third entrance corresponds to the radius of the circumference (called **r**); all this information is going to be showed as a graphic where the quarter of the circumference will be displayed in an orange color and the axis in a blue one; and finally the fourth entrance is an x-coordinate (named **cx**) that could belong to a coordinate in the range of the first quarter of the circumference (displayed in the screen as a red dot), if the mentioned x-coordinate belongs to that range (the first quarter of the circumference) a y-coordinate (called **cy**) will be generated and a purple dot in the screen will appear, it is a mark with the (**cx**, **cy**) coordinate. The most important part about this program is to show a tangent line on the first quarter of the circumference that is going to cross the purple dot, to achieve this was necessary to obtain the derivative of the positive part of the circumference to get the slope of the tangent line, then two points are needed to be generated **xl (x-left) = h - r, xr (x-right) = x1 + r** `x1 corresponds to the limit of the radius in the x axis` those are the limits of the domain; and the y-coordinate dots that are just the product of the equation of the straigth line solved in a function called *recta* with the parametters of **m = slope, xr or xl respectively, cx, cy**, as the values of the codomain; with this two points finally it is possible to trace a segment of the tangent line to a segment of a circle given
#### Metodology:

#### Implementation:

#### Tests:

#### Results:

#### Conclusion:

#### Bibliography:
1. Matplotlib documentation — Matplotlib 3.6.2 documentation. (s. f.). https://matplotlib.org/stable/index.html
2. NumPy documentation — NumPy v1.23 Manual. (s. f.). https://numpy.org/doc/stable/
3. Oteyza, E. de, Lam, E., Carlos, H., Carrillo, A., Ramírez, A. & Gallegos, J. A. J. (2015). Geometria analitica y trigonometria. Pearson Educaction.
