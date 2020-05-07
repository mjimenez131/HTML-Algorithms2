Class Section - 02
Project #1 Cella Rule 150 
Team Name -  TJMM
Members - Thomas Clark, Justin Nguyen, Mike Oun, Michael Jimenez 

Intro  -  Multicolored box moves from cell to cell and will change change the color on the cells it moves over when the requirements of the algorithm is met. Can use a mouse click to pause the function. We are using HTML, Javascript and p5.js.
	
Algo: Edge cases - both edges are considered false. The array is evaluated by the row above making the first row the initial condition. If the 3 values above the position being evaluated have 1 or 3 true values set the position to true, else false. Step through the 2d array in this fashion until all positions in the array have been evaluated.

Zip Contents - 	cell.css:	Sample cascading style sheet used in html
		index.html:	HTML for basic webpage and loading js scripts
		p5.js:		p5 drawing for basic graphics in javascript
		Project1.js:	Coded javascript to replicate cella rule 150

External Requirements - Javascript capable web browser

Setup and Installation -Extract all contents of archive into a folder. Double click or drag the .html file into a browser. Program will then start running immediately.

Features - Displays as expected. Fully animated. Has a feature to click on the page in order to pause the draw function and keyboard to skip animation (All features needed are met)

Bugs - Script occurs below the footer, div tags >:(
