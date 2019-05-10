---
layout: default
---

## Timetable

<!---
<div style="width:100%;height:0;padding-bottom:56%;position:relative;"><iframe src="https://giphy.com/embed/DNpWCDNx03IXlETSac" width="100%" height="100%" style="position:absolute" frameBorder="0" ></iframe></div><p><a href="https://giphy.com/gifs/mailchimp-dance-teamwork-conga-line-DNpWCDNx03IXlETSac">Site still under construction.</a></p>
--->

<!---
	Possibly useful template: https://codepen.io/oltika/pen/GNvdgV
	--->

<html>
<head>
<style>
#timetable table {
  font-family: "Trebuchet MS", Arial, Helvetica, sans-serif;
  border-collapse: collapse;
  width: 100%;
  table-layout: auto;
}

#timetable thead {
  background: #433E4C;
  color: white;
}

#timetable th {
  padding-top: 12px;
  padding-bottom: 12px;
  text-align: left;
  color: white;
}

/* stop alternate colouring
#timetable tr:nth-child(even){background-color: #f2f2f2;}
*/

#timetable td:hover {background-color: #ddd;}


#timetable tr {
  border-bottom: 2px solid #ddd;
  padding: 8px;
}


/*
#timetable td {
  border: 1px solid #ddd;
  padding: 8px;
}
*/

</style>
</head>
<body>
<table id="timetable">
	<thead>
	<tr>
		<th>Time</th>
		<th>Day 1</th>
		<th>Day 2</th>
		<th>Day 3</th>
	</tr>
	</thead>
	<tr>
		<td>10:00</td>
		<td>Statistics: Descriptives and regression</td>
		<td>Networks: Introduction to graph theory</td>
		<td rowspan="6">Group project</td>
	</tr>
	<tr>
		<td>10:30</td>
		<td>Statistical models: Linear regression, ANOVA</td>
		<td>Networks: Centrality and betweeness</td>
	</tr>
	<tr>
		<td>11:00</td>
		<td>Clustering</td>
		<td>Networks: Analysing road networks</td>
	</tr>
	<tr>
		<td>11:30</td>
		<td rowspan="3">Practicle examples</td>
		<td rowspan="3">Practicle examples</td>
	</tr>
	<tr>
		<td>12:00</td>
	</tr>
	<tr>
		<td>12:30</td>
	</tr>
	<tr>
		<td>13:00</td>
		<td rowspan="2">Lunch</td>
		<td rowspan="2">Lunch</td>
		<td rowspan="2">Lunch</td>
	</tr>
	<tr>
		<td>13:30</td>
	</tr>
	<tr>
		<td>14:00</td>
		<td>Spatial statistics</td>
		<td>Raster data intro</td>
		<td rowspan="3">Group project</td>
	</tr>
	<tr>
		<td>14:30</td>
		<td>Spatial data formats/spatial databases</td>
		<td>Raster data classification</td>
	</tr>
	<tr>
		<td>15:00</td>
		<td>Data validation</td>
		<td>Working with satelite imagery</td>
	</tr>
	<tr>
		<td>15:30</td>
		<td>Break</td>
		<td>Break</td>
		<td>Break</td>
	</tr>
	<tr>
		<td>16:00</td>
		<td rowspan="4">Group project</td>
		<td rowspan="4">Group project</td>
		<td rowspan="4">Group project</td>
	</tr>
	<tr>
		<td>16:30</td>
	</tr>
	<tr>
		<td>17:00</td>
	</tr>
	<tr>
		<td>17:30</td>
	</tr>
	<tr>
		<td>18:00</td>
		<td>Day end</td>
		<td>Day end</td>
		<td>Day end</td>
	</tr>
</table>
</body>
</html>


## Syllabus and Tutors


### Day 1

Statistics 1: tbc
* Descriptive statistics
* Regression

Statistics 2: tbs
* Linear regression models
* Other statistical modesl

Statistics 3: tbc
* Cluster analysis

Spatial data and statistics 1: tbc
* Spatial data formats and databases

Spatial data and statistics 2: tbc
* Spatial statistics

Spatial data and statistics 3: tbc
* Data validation

### Day 2

Networks 1: tbc
* Directed vs undirected graphs
* Adjacency matrices and node degree
* Degree distribution
* Connectivity

Networks 2: Elsa Arcatue
* Centrality and betweeness

Networks 3: Gareth Simons
* Constructing graphs from road network data
* Introduction to the OSMnx Python library
* Introduction to the cityseer library


Raster data and satelite imagery 1: tbc
* What is Raster data?

Raster data and satelite imagery 2: tbc
* Raster data classification

Raster data and satelite imagery 3: tbc
* Working with satelite imagery


[back](./)
