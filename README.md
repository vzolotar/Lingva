# Lingva

### 📝 Description 
The project presents a proof of concept of implementation consisting the Computer Atlas of the Iberian Peninsula including the following elements: the dimensional database of geographical maps and the analytical engine - Lingva. The purpose of the project to demonstrate how linguistic maps can be compared, combined forming the new maps to present the similarities and differences between the areas in research. The application also provides the statistics related to the maps and comparisons. In this project the maps of the  Iberian Peninsula presented as a combination of 6117 fields or points on the map. Each field has a unique address which is used to map and compare the same regions from different maps. 

-----

##### Tools / Languages  
<img src="https://img.shields.io/badge/C-00599C?logo=c&logoColor=white" />

##### Platform 
<img height="20" src="https://img.shields.io/badge/MS DOS-000000?logo=dos&logoColor=white" /> <img height="20" src="https://img.shields.io/badge/Windows-0078D6?logo=windows&logoColor=white" /> System requirements: Windows x86 (Rus)

##### Data Sources  
- The Atlas Lingüístico de la Península Ibérica [Linguistic Atlas of the Iberian Peninsula] (ALPI), Ramón Menéndez Pidal, 1962, [CSIC - Consejo Superior de Investigaciones Científicas](http://alpi.csic.es/en/)

-----

<img src="https://github.com/vzolotar/Lingva/blob/master/images/Lingva_diagram.JPG" >

### ✔️ Usage

### 1️⃣ Main Menu
(transalated)
````markdown
To return to the main MENU please press Esc

			MENU

	1. Review Map IDs and descriptions 
	2. Linear distribution - Maps
	3. Secondary Variable - Function 
	
	4. Create new Maps - Combine
	5. Contingency table
	6. Full Map review and Linear distribution
	
	7. Map review with selected characteristics 
	8. Review list of Maps
	9. Map Database Administration

	10. Exit
	
	Please select:
````



### 2️⃣ Linear distribution - Maps
Provides the Linear distribution of the characteristics included in a map. Example below: Map of pronunciation variations: Z at the end of a word (1 - normative, 2 - extra-short, 3 - palatalized, 4 - excluded, 5 - aspirated, 6 - S-like)

````markdown
  =======================================
  Linear distribution - Maps
  =======================================

Project Name: Linguistic Geography: Spain and Portugal 
Number of fields on the map: 6117

Enter Map ID: 10/

Map Id: 10
====================================
Description: Z at the end of a word


````
<img src="https://github.com/vzolotar/Lingva/blob/master/images/lin_distr.JPG" width="600" height="100">

### 3️⃣ Create new Maps - Combine
This feature allows to combine and compare two or more maps and save the results as a new map. In the example below we are combining the maps of pronunciation: 21 - "La O de Boca" and 14 - "L at the end of a word".  We save the new map and assign ID 23 to the new map.  

````markdown
  =======================================
  Create new Maps - Combine
  =======================================

Project Name: Linguistic Geography: Spain and Portugal 
Number of fields on the map: 6117

Ender IDs of the Maps you want to combine: 21 14/
* 21* La O de Boca
* 14* L at the end of a word

Next available Map ID is: 23
Enter the new Map ID numner: 23/
````
Here is the comparison of the maps (manually painted) to better illustrate the results of map compare. The maps bellow represent a part of the Iberian Peninsula: first map on the left – map 21, second on the right – map 14 and the last map in the center is the map of comparison (21 and 14) 

<img src="https://github.com/vzolotar/Lingva/blob/master/images/compare_col.JPG" width="400" height="250">

### 4️⃣ Full Map review and Linear distribution
Review a map (stored in the database or any new / combined maps) and the corresponding linear distribution. Since a map does not actually fit into the DOS window the program reviews the map in eight parts. The example below represents the combined version of the map. 

````markdown
  =======================================
  Full Map review and Linear distribution
  =======================================

Project Name: Linguistic Geography: Spain and Portugal 
Number of fields on the map: 6117

Ender Map ID: 16/
```` 
<img src="https://github.com/vzolotar/Lingva/blob/master/images/Spain_Portugal_map.jpg" width="650" height="500">
<img src="https://github.com/vzolotar/Lingva/blob/master/images/Spain_Portugal_disr.jpg" width="400" height="200">
