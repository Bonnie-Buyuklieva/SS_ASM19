---
layout: default
---

## Syllabus and Tutors

The objective of the syllabus is to warm participants up to key quantitative methods and introduce them to core spatial modelling methods. There will be a strong focus on demonstrating these methods with code snippets and coding demonstrations which participants can experiment with and build upon. Over half the lesson time on the first two days is assigned to hands on coding and analysis with the support of the course tutors.

***

### Day 1

Day 1 will start by introducing important statistical measures, modelling techniques and cluster analysis. The second part of the day will cover working with vector spatial data and key spatial statistics.

<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}

/* Create two equal columns that floats next to each other */
.column {
  float: left;
  width: 50%;
  padding: 10px;
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}
</style>
</head>
<body>

<div class="row">
  <div class="column" style="background-color:#ffffff;">
    <p><b>Statistics 1: tbc</b><br>Descriptive statistic<br>Regression<br><br>
    	<b>Statistics 2: tbc</b><br>Linear regression models<br>Other statistical models<br><br>
    	<b>Cluster analysis: tbc</b><br></p>
  </div>
  <div class="column" style="background-color:#ffffff;">
    <p><b>Spatial data and statistics 1: tbc</b><br>Spatial data formats and databases<br><br>
    	<b>Spatial data and statistics 2: tbc</b><br>Spatial statistics<br><br>
    	<b>Spatial data and statistics 3: tbc</b><br>Data validation</p>
  </div>
</div>
</body>
</html>

### Day 2

Day 2 will start by covering the skills required to perform network analysis on geographic data. The second part of the day will cover working with raster data and satellite imagery.

<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
  /*border-color: white;
  background-color: white;*/
}

/* Create two equal columns that floats next to each other */
.column {
  float: left;
  width: 50%;
  padding: 10px;
  height: 300px; /* Should be removed. Only for demonstration */
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}
</style>
</head>

<body>

<div class="row">
  <div class="column" style="background-color:#ffffff;">
    <p><b>Networks 1: tbc</b><br>Directed vs undirected graphs<br>Adjacency matrices, node degree<br>Degree distribution<br>Connectivity<br><br>
    	<b>Networks 2: Elsa Arcatue</b><br>Centrality and betweenness<br><br>
    	<b>Networks 3: Gareth Simons</b><br>Working with road network data<br>OSMnx Python library<br>cityseer Python library<br><br>
    </p>
  </div>
  <div class="column" style="background-color:#ffffff;">
    <p><b>Classifying satellite imagery 1: tbc</b><br>Sources of raster data<br>Stack, mosaic and clip raster data<br><br>
    	<b>Classifying satellite imagery 2: tbc</b><br>Normalised differencing<br>Thresholding and sub-setting images<br><br>
    	<b>Classifying satellite imagery 3: tbc</b><br>Unsupervised classification<br>Supervised classification<br>Model evaluation<br><br>
    </p>
  </div>
</div>
</body>
</html>

<br> <!--- An extra line break needed here --->

### Day 3

Hackathon!

***

### Timetable

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
  background: #ffffff; /*433E4C*/
}

/* controls header */
#timetable th {
  padding-top: 12px;
  padding-bottom: 12px;
  text-align: left;
}

#timetable tr {
  border-bottom: 2px solid #ddd;
  padding: 8px;
}

td:nth-child(2) {
  color: white;
}

td:nth-child(3) {
  color: white;
}

td:nth-child(4) {
  color: white;
}

td[colspan="3"] {
    text-align: center;
}


</style>
</head>
<body>
<table id="timetable">
<colgroup>
    <col class="timecol" />
    <col class="day1col" />
    <col class="day2col" />
    <col class="day3col" />
  </colgroup>
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
		<td bgcolor="#575795">Statistics 1</td>
		<td bgcolor="#b3cce9">Networks 1</td>
		<td rowspan="6" bgcolor="#6d9e8e">Group project</td>
	</tr>
	<tr>
		<td>10:30</td>
		<td bgcolor="#575795">Statistics 2</td>
		<td bgcolor="#b3cce9">Networks 2</td>
	</tr>
	<tr>
		<td>11:00</td>
		<td bgcolor="#575795">Cluster analysis</td>
		<td bgcolor="#b3cce9">Networks 3</td>
	</tr>
	<tr>
		<td>11:30</td>
		<td rowspan="3" bgcolor="#53a9aa">Practical examples</td>
		<td rowspan="3" bgcolor="#53a9aa">Practical examples</td>
	</tr>
	<tr>
		<td>12:00</td>
	</tr>
	<tr>
		<td>12:30</td>
	</tr>
	<tr>
		<td>13:00</td>
		<td rowspan="2" bgcolor="#aaa9a9">Lunch</td>
		<td rowspan="2" bgcolor="#aaa9a9">Lunch</td>
		<td rowspan="2" bgcolor="#aaa9a9">Lunch</td>
	</tr>
	<tr>
		<td>13:30</td>
	</tr>
	<tr>
		<td>14:00</td>
		<td bgcolor="#463c71">Spatial data and statistics 1</td>
		<td bgcolor="#92afd8">Classifying satellite imagery 1</td>
		<td rowspan="3" bgcolor="#6d9e8e">Group project</td>
	</tr>
	<tr>
		<td>14:30</td>
		<td bgcolor="#463c71">Spatial data and statistics 2</td>
		<td bgcolor="#92afd8">Classifying satellite imagery 2</td>
	</tr>
	<tr>
		<td>15:00</td>
		<td bgcolor="#463c71">Spatial data and statistics 3</td>
		<td bgcolor="#92afd8">Classifying satellite imagery 3</td>
	</tr>
	<tr>
		<td>15:30</td>
		<td bgcolor="#aaa9a9">Break</td>
		<td bgcolor="#aaa9a9">Break</td>
		<td bgcolor="#aaa9a9">Break</td>
	</tr>
	<tr>
		<td>16:00</td>
		<td rowspan="4" bgcolor="#6d9e8e">Group project</td>
		<td rowspan="4" bgcolor="#6d9e8e">Group project</td>
		<td rowspan="4" bgcolor="#6d9e8e">Group project</td>
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
		<td rowspan="4" colspan="3" bgcolor="#e9cbc7">Evening events</td>
	</tr>
		<tr>
		<td>18:30</td>
	</tr>
		<tr>
		<td>19:00</td>
	</tr>
		<tr>
		<td>19:30</td>
	</tr>
</table>
</body>
</html>

[back](./)
