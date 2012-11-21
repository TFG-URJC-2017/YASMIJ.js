# YASMIJ.js - Yet Another Simplex Method Library for Javascript.

The purpose of this project is to provide a simple Simplex Method library for Javascript.
The simplex method is a popular algorithm for linear programming.
It is used to solve optimization by using of artifical variables and/or branch and bound.

## Example:

Objective: Maximize `5x1 + 3x2 + x3`

Subject to <br/>
`5x1 + 3x2 + 6x3 = 15`<br/>
`x1 + x2 + x3 = 6`<br/>
<br/>
where 0 <= `x1`,`x2`, `x3`<br/>

<b>Input</b><br/>

	var input = {
		type: "maximize",
		objective : "x1 + 2x2 - x3",
		constraints : [
			"2x1 + x2 + x3 <= 14",
			"4x1 + 2x2 + 3x3 <= 28",
			"2x1 + 5x2 + 5x3 <= 30"
		]
	};
	YASMIJ.solve( input );
	
<b>Output</b><br/>

## Version Roadmap:

- 0.2.5 - Complete the Matrix Class (In Progress) <br/>
- 0.3 - Complete the Tableau Class (In Progress)<br/>
- 0.4 - Complete the Output Class (In Progress)<br/>
- 0.5 - Complete the Simplex and YASMIJ Classes<br/>
- 0.6 - Get Feedback<br/>

## TODO

- Need documentation.