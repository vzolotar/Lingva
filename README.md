# Lingva

### 📝 Description 
The project presents a proof of concept of implementation consisting the Computer Atlas of the Iberian Peninsula including the following elements: the dimensional database of geographical maps and the analytical engine - Lingva. The purpose of the project to demonstrate how linguistic maps can be compared, combined forming the new maps to present the similarities and differences between the areas in research. The application also provides the statistics related to the maps and comparisons. In this project the maps of the the Iberian Peninsula presented as a combination of 6117 fields or points on the map. Each field has a unique address which is used to map and compare the same regions from different maps. 

-----

##### Tools / Languages  
<img src="https://img.shields.io/badge/C-00599C?logo=c&logoColor=white" />

##### Platform 
<img height="20" src="https://img.shields.io/badge/MS DOS-000000?logo=dos&logoColor=white" /> <img height="20" src="https://img.shields.io/badge/Windows-0078D6?logo=windows&logoColor=white" /> System requirements: Windows x86 (Rus)

##### Data Sources  
- The Atlas Lingüístico de la Península Ibérica [Linguistic Atlas of the Iberian Peninsula] (ALPI), Ramón Menéndez Pidal, 1962, [CSIC - Consejo Superior de Investigaciones Científicas](http://alpi.csic.es/en/)

##### Date:  
1991-02

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
	
	7. Map review with selected charecterists 
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
This feature allows to combine and compare two or more maps and save the results as a new map. In the example below we are combining the political map  of the Iberian Peninsula (9) and the linguistic map  - the variations of "Aguja" (19).  We save the new map and assign ID 26 to the new map.  

````markdown
  =======================================
  Create new Maps - Combine
  =======================================

Project Name: Linguistic Geography: Spain and Portugal 
Number of fields on the map: 6117

Ender IDs of the Maps you want to combine: 9 19/
* 9* Country
* 19* AGUJA

Next available Map ID is: 26
Enter the the new Map ID numner: 26/
````


### 4️⃣ Contingency table
Description (Section 2)

````markdown
  =======================================
  Contingency table
  =======================================

Project Name: Linguistic Geography: Spain and Portugal 
Number of fields on the map: 6117

Ender IDs of the Maps you want to use: 10 11/
* 10* Z at the end of a word
* 11* S at the end of a word

First map includes characteristics from 0 through 6 (total 7)
Second map includes characteristics from 0 through 4 (total 5)

Next available Map ID is: 26
Enter the the new Map ID numner: 26/
```` 
<img src="https://github.com/vzolotar/Lingva/blob/master/images/Contingency.JPG" width="230" height="230">

### 5️⃣ Full Map review and Linear distribution
Description (Section 2)

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
