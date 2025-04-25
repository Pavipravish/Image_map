# Ex04 Places Around Me
# Date:25/04/2025
# AIM
To develop a website to display details about the places around my house.

# DESIGN STEPS
## STEP 1
Create a Django admin interface.

## STEP 2
Download your city map from Google.

## STEP 3
Using <map> tag name the map.

## STEP 4
Create clickable regions in the image using <area> tag.

## STEP 5
Write HTML programs for all the regions identified.

## STEP 6
Execute the programs and publish them.

# CODE
```
<html>
<head>
  <title>My City</title>
</head>
<body>
  <h1 align="center">
    <font color="red"><b>Tambaram</b></font>
  </h1>

  <h3 align="center">
    <font color="blue"><b>Harshat</b></font>
  </h3>

  <center>
    <img src="map.png" usemap="#MyCity" height="610" width="1450">
    <map name="MyCity">
      <area shape="rect" coords="700,250,850,400" href="home.html" title="Home">
      <area shape="circle" coords="570,230,45" href="road.html" title="Muduchur road">
      <area shape="circle" coords="640,200,30" href="lake.html" title="Tambaram Lake">
      <area shape="circle" coords="1120,360,25" href="garden.html" title="GG Garden">
      <area shape="rect" coords="950,120,1100,140" href="stop.html" title="Pallikarani">
    </map>
  </center>
</body>
</html>

```
stop.html
```
<html>
<head>
  <title>Pallikarani</title>
</head>
<body bgcolor="blue">
  <h1 align="center">
    <font color="cyan"><b>Tambaram</b></font>
  </h1>

  <h3 align="center">
    <font color="lime"><b>Pallikarani</b></font>
  </h3>

  <hr size="3" color="cyan">

  <p align="justify">
    <font face="Georgia" size="5" color="white">
        Pallikaranai is a rapidly developing residential locality in South Chennai,
        offering excellent connectivity to OMR, ECR, and GST Road. It is renowned 
        for the Pallikaranai Marsh, one of Chennai's last remaining natural wetlands, 
        which supports over 600 species of flora and fauna, including 176 bird species .​
  </p>
</body>
</html>
```
garden.html
```
<html>
<head>
  <title>Garden</title>
</head>
<body bgcolor="blue">
  <h1 align="center">
    <font color="cyan"><b>Tambaram</b></font>
  </h1>

  <h3 align="center">
    <font color="lime"><b>GG Garden</b></font>
  </h3>

  <hr size="3" color="red">

  <p align="justify">
    <font face="Georgia" size="5" color="white">
        GG Garden in Tambaram is a peaceful residential area known for its calm surroundings.
        It offers easy access to schools, shops, and transport facilities, making life convenient.
        The neighborhood features clean streets, friendly communities, and a green environment.
        Ideal for families, GG Garden combines suburban charm with city connectivity. 
  </p>
</body>
</html>
```
lake.html
```
<html>
<head>
  <title>Lake</title>
</head>
<body bgcolor="blue">
  <h1 align="center">
    <font color="cyan"><b>Tambaram</b></font>
  </h1>

  <h3 align="center">
    <font color="lime"><b>Tambaram lake</b></font>
  </h3>

  <hr size="3" color="red">

  <p align="justify">
    <font face="Georgia" size="5" color="white">
      Lakes are generally formed as a consequence of the tectonic or glacial activity. 
      Lakes are also formed due to the meandering river or even by human activity. 
      For civilization, there are abundant reasons to point them out, this owes to the 
      resource of water, and water is a definite source to continue life on this planet. 
      This lake is also facing numerous problems such as pollution, siltation, and 
      climate change. 
  </p>
</body>
</html>
```
road.html
```
<html>
<head>
  <title>My Home Town</title>
</head>
<body bgcolor="green">
  <h1 align="center">
    <font color="gray"><b>Tambaram</b></font>
  </h1>

  <h3 align="center">
    <font color="blue"><b>MUDUCHUR ROAD </b></font>
  </h3>

  <hr size="3" color="red">

  <p align="justify">
    <font face="Georgia" size="5">
      These Roads construction started at 2017 and successfully ended on 2023.
      These Roads are constructed by L&T . These Roads are know for it's pot holes and 
      number of accidents occuring.
    </font>
  </p>
</body>
</html>
```
# OUTPUT
![image](https://github.com/user-attachments/assets/d2272d72-b9f7-4ed5-bd60-f41a019873cf)
![image](https://github.com/user-attachments/assets/5c02f286-4208-4084-9809-16dd8d2d34cb)
![image](https://github.com/user-attachments/assets/a2b98833-1f24-4b5f-9dfd-27c344bf972d)
![image](https://github.com/user-attachments/assets/def01499-18ff-4dab-9784-7aebf563e817)
![image](https://github.com/user-attachments/assets/61fce765-7342-414d-977d-ef6b2183f364)




# RESULT
The program for implementing image maps using HTML is executed successfully.
