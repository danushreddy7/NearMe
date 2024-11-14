# Ex04 Places Around Me
## REG NO:212223040029
# NAME:T DANUSH REDY
## Date: 

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google.

### STEP 3
Using ```<map>``` tag name the map.

### STEP 4
Create clickable regions in the image using ```<area>``` tag.

### STEP 5
Write HTML programs for all the regions identified.

### STEP 6
Execute the programs and publish them.

## CODE:
```
map.html

<html>
<head>
<title>My city</title>
</head>
<body>
<h1 align="center">
<font color="red"><b>kuppam</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Danush Reddy T (212223040029)</b></font> 
</h3>
<center>
<img src="map.png" usemap="#MyCity" height="610" width="1450">
<map name="MyCity">
<area shape="rect" coords="1150,200,,1250,150" href="home.html" title="My Home Town">
<area shape="rect" coords="550,450,,650,550" href="temple.html" title="Thanjai PeriyaKovil">
<area shape="rect" coords="700,200,,800,150" href="Musuem.html" title="Royal Palace Musuem">
<area shape="rect" coords="660,230,,740,280" href="Palace.html" title="Thanjavur Maratha Palace">
<area shape="rect" coords="1000,200,,1100,100" href="school.html" title="Crescent Nursery and Primary school">
</map>
</center>    
</body>
</html>
```
## OUTPUT:
![image](https://github.com/user-attachments/assets/82661678-fa01-4d69-9d52-1437c0bf282c)

## RESULT
The program for implementing image maps using HTML is executed successfully.
