<h1>Airline Routing and Scheduling Optimization</h1>

This repository presents a two-part optimization project focused on airline operations, specifically profit-maximizing route selection and cost-efficient flight scheduling. The work was completed as part of the MSDS 460 Decision Analytics course at Northwestern University.

<h3>Repository Contents</h3>
  <ul>
    <li><b>Airline_Routing.ipynb</b>: A fully executable Jupyter Notebook containing the data preparation, optimization model implementations, assumptions, and results.</li>
    <li><b>MSDS460 Flight Optimization Paper.pdf</b>: A comprehensive research paper detailing the problem formulation, methods, assumptions, results, and insights behind the models implemented in the notebook.</li>
  </ul>
	
<h3>Project Overview</h3>

<p>The objective of this project was to optimize airline routing and scheduling to enhance profitability and operational efficiency. Inspired by real-world data from Southwest Airlines, the project is broken down into two main modeling efforts:</p>
	
<ol>
<h5><li>Routing Optimization Model</li></h5>
 
 <p>A linear programming model built to:</p>
   <ul>
     <li>Identify the most profitable direct routes between selected airports</li>
     <li>Analyze fare revenue and operating costs</li>
     <li>Recommend which routes to operate or drop</li>
   </ul>

<h5><li>Flight Scheduling Model</li></h5>
  <p>A mixed-integer programming (MIP) model designed to:</p>
    <ul>
      <li>Satisfy passenger demand through direct and one-stop connecting flights</li>
      <li>Schedule flights at discrete hourly intervals</li>
      <li>Minimize operating costs while observing layover constraints and aircraft capacities</li>
    </ul>
</ol>

<p>Both models are implemented in Python using PuLP (for the routing model) and Google OR-Tools (for the scheduling model).</p>

<h3>Key Features</h3>
  <ul>
    <li>Real-world inspired datasets based on Southwest Airlines routes, fares, and operational expenses<br></li>
    <li>Simplified network of the 15 largest U.S. airports (subset used for computational feasibility)<br></li>
    <li>Fully documented assumptions for aircraft, costs, demand, and scheduling<br></li>
    <li>Demonstration of scaling challenges and discussion of potential heuristic approaches for large-scale problems<br></li>
  </ul>

<h3>Results Summary</h3>
  <ul>
    <li>The routing model identified 18 out of 21 routes as profitable, with a projected profit of $441,188.80 in a one-day scenario</li>
    <li>The scheduling model successfully routed all passengers across 3 cities within defined constraints, validating feasibility on a small network</li>
    <li>Performance analysis highlighted exponential growth in solution space with increased network complexity</li>
  </ul>

<h3>Technologies Used</h3>
  <ul>
    <li>Python 3</li>
    <li>Jupyter Notebook</li>
    <li>PuLP (Linear Programming Solver</li>
    <li>Google OR-Tools (MIP Solver)</li>
    <li>Matplotlib, NumPy, pandas</li>
  </ul>

<h3>Citation</h3>

If using this work, please cite the following:

	Drenkova, K., Joshi, A., Moskowitz, B., & Rana, L. (2024). Airline Optimization. Northwestern University, MSDS 460: Decision Analytics.

<h3>Contact</h3>

For questions or collaboration opportunities, please contact any of the authors listed in the paper.
