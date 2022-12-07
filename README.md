# Final-proyect-analytic-geometry-and-introduction-to-calculus
## Tangent line to a segment of a circle given an x-coordinate
### Solís Pedraza Francisco fran_sp@comunidad.unam.mx
### Type of license: GPL (General Public License v3.0)
#### Installation and execution:

#### Introduction:
The following program has the intention of reflecting the application of the knowledge acquired in the subject Analytic Geometry and Introduction to Calculus taught by Dr. Víctor Hugo De la Luz Rodríguez in the major of Technology for the information in sciences at the Escuela Nacional de Estudios Superiores unidad Morelia (ENES Morelia). 
This code works directly with data provided by the user typed in the console; the first two entrance are the center of the circumference the x-coordinate and the y-coordinate respectively (called **h** and **k**), the third entrance corresponds to the radius of the circumference (called **r**); all this information is going to be showed as a graphic where the quarter of the circumference will be displayed in an orange color and the axis in a blue one; and finally the fourth entrance is an x-coordinate (named **cx**) that could belong to a coordinate in the range of the first quarter of the circumference (displayed in the screen as a red dot), if the mentioned x-coordinate belongs to that range (the first quarter of the circumference) a y-coordinate (called **cy**) will be generated and a purple dot in the screen will appear, it is a mark with the (**cx**, **cy**) coordinate. The most important part about this program is to show a tangent line on the first quarter of the circumference that is going to cross the purple dot, to achieve this was necessary to obtain the derivative of the positive part of the circumference to get the slope of the tangent line, then two points are needed to be generated **xl (x-left) = h - r, xr (x-right) = x1 + r** `x1 corresponds to the limit of the radius in the x axis` those are the limits of the domain; and the y-coordinate dots that are just the product of the equation of the straigth line solved in a function called *recta* with the parametters of **m = slope, xr or xl respectively, cx, cy**, as the values of the codomain; with this two points finally it is possible to trace a segment of the tangent line to a segment of a circle given.
#### Metodology:
To cary out a similar proyect it is indispensable to know basic programming, the use of the imperative programming paradigm is useful enough; also is necessary a basic knowledge in analytic geometry and calculus more specific in the diferential calculus field.
#### Implementation:
This program could be useful on the understanding of primary functioning about tangent lines in a circumference in a two dimension space by the graph of the tangent line mentioned. Enlarge the code given to work in the four quarters of a circumference could contribute to a better comprehension in the same topic not only because of the graphing part but also in the mathematical comprehension separating the circumference in two functions and programming them.
#### Tests:

#### Results:
*The x-coordinate given is in the range of the limits of the circumference*


![imagen1](https://github.com/caster100701/Final-proyect-analytic-geometry-and-introduction-to-calculus/blob/main/Figure_1.png)


*The x-coordinate given is not in the range of the limits of the circumference*


![imagen2](https://github.com/caster100701/Final-proyect-analytic-geometry-and-introduction-to-calculus/blob/main/Figure_2.png)
![imagen3](https://github.com/caster100701/Final-proyect-analytic-geometry-and-introduction-to-calculus/blob/main/Figure_3.png)
![imagen4](https://github.com/caster100701/Final-proyect-analytic-geometry-and-introduction-to-calculus/blob/main/Figure_4.png)
#### Conclusion:
To work with the tangent line to a circumference, it is necessary to segment the figure into quadrants, this, because the circumference is not a function itself, doing it this way allows us to apply the tools of differential calculus to obtain the slope at the different points of the different quadrants of the circumference. In addition, there are very particular cases where the slope is infinite, that is, the line is parallel to the y-axis and as such they must be handled so as not to make mistakes and reach wrong conclusions regarding the scope of the calculus.
#### Bibliography:
1. Matplotlib documentation — Matplotlib 3.6.2 documentation. (s. f.). https://matplotlib.org/stable/index.html
2. NumPy documentation — NumPy v1.23 Manual. (s. f.). https://numpy.org/doc/stable/
3. Oteyza, E. de, Lam, E., Carlos, H., Carrillo, A., Ramírez, A. & Gallegos, J. A. J. (2015). Geometria analitica y trigonometria. Pearson Educaction.
