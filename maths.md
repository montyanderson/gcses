# Maths

a<sup>b</sup> / a<sup>c</sup> = a<sup>b - c</sup>

a<sup>b</sup> * a<sup>c</sup> = a<sup>b + c</sup>

## Pre-calculus

* y = mx + c
* m = slope
* c = coefficient

* Slope = m = &Delta;y / &Delta;x = (y<sub>1</sub> - y<sub>0</sub>) / (x<sub>1</sub> - x<sub>0</sub>)
<table>
    <tr>
        <td rowspan="2" nowrap="nowrap">
            Slope (*m*) =
        </td>

        <td>&Delta;y</td>
        <td>y<sub>1</sub> - y<sub>0</sub></td>
    </tr>
    <tr>
        <td>&Delta;x</td>
        <td>x<sub>1</sub> - x<sub>0</sub></td>
    </tr>
</table>

* A straight line will always have a constant slope.

* A line that intersects two points on a curve is known as a *secant* line.

But how to we find out the instantaneous rate of change?

### Secant Line Question 1

* **A curve has an equation *y = ln x* and passes through the points *P = (e, 1)* and *Q = (x, ln x)***.

* **Write an expression in *x* that gives the slope of the secant joining *P* and *Q*.**

* Equation = y = ln(x)

* Point P = (e, 1)
* Point Q = (x, ln x)
<table>
    <tr>
        <td>x<sub>0</sub></td>
        <td>e</td>
    </tr>
    <tr>
        <td>x<sub>1</sub></td>
        <td>x</sub></td>
    </tr>
    <tr>
        <td>y<sub>0</sub></td>
        <td>1</td>
    </tr>
    <tr>
        <td>y<sub>1</sub></td>
        <td>ln(x)</td>
    </tr>
</table>
<table>
    <tr>
        <td rowspan="2" nowrap="nowrap">
            Slope (*m*) =
        </td>

        <td>&Delta;y</td>
        <td>y<sub>1</sub> - y<sub>0</sub></td>
        <td>ln(x) - 1</td>
    </tr>
    <tr>
        <td>&Delta;x</td>
        <td>x<sub>1</sub> - x<sub>0</sub></td>
        <td>x - e</td>
    </tr>
</table>

YAY! That's the answer!

### Secant Line Question 2

* **The data for three points on a smooth function *f* is given in the table**
<table>
    <tr>
        <th>x</th>
        <th>f(x)</th>
    </tr>
    <tr>
        <td>6.5</td>
        <td>108.25</td>
    </tr>
    <tr>
        <td>7</td>
        <td>109.45</td>
    </tr>
    <tr>
        <td>7.5</td>
        <td>110.15</td>
    </tr>
</table>

* **What is the average rate of change of *f* with respect to *x* as *x* goes from 6.5 to 7?**
* **7 to 7.5?**
* **6.5 to 7.5?**
<table>
    <tr>
        <th>Interval</th>
        <th>Average Rate of Change</th>
    </tr>
    <tr>
        <td>[6.5, 7]</td>
        <td>? 2.4</td>
    </tr>
    <tr>
        <td>[7, 7.5]</td>
        <td>? 1.4</td>
    </tr>
    <tr>
        <td>[6.5, 7.5]</td>
        <td>? 1.9</td>
    </tr>
</table>
<table>
    <tr>
        <td>&Delta;y</td>
        <td>109.45 - 108.25</td>
        <td>110.15 - 109.45</td>
        <td>110.15 - 108.25</td>
    </tr>
    <tr>
        <td>&Delta;x</td>
        <td>7 - 6.5</td>
        <td>7.5 - 7</td>
        <td>7.5 - 6.5</td>
    </tr>
</table>

* **What is the average rate of these changes?**
<table style="text-align: center">
    <tr>
        <td rowspan="2">f(7) &asymp;</td>
        <td>2.4 - 1.9</td>
    </tr>
    <tr>
        <td>2</td>
    </tr>
</table>

## Calculus

[https://www.youtube.com/watch?v=54_XRjHhZzI](https://www.youtube.com/watch?v=54_XRjHhZzI)

Two goals of Calculus:

* Find the slope (tangent) at the point of a curve

* Find the area under a curve between two points

### Terminology

* **Secant Line** a

### Tangent (Slope)

* If you give me any arbitrary curve and a point (P), I want to find the tangent (slope) at that point.

How do you make the equasion of a line, when you only have a single point?
