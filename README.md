![image](https://github.com/NSArjun/NearMe/assets/148233801/532c434f-ca19-4cea-b10e-6c91a434cd62)# Ex04 Places Around Me
## Date: 21-03-2024

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

## CODE

# 0-map.html
```
<html>
<head>
<title>~Chennai~</title>
</head>
<body>
<h1 align="center"><b> Chennai </b></h1>
<h3 align="center"><b> ARJUN N S(212223230020)</b></h3>
<center>
<img src="map.png" usemap="#MyCity" height="610" width="1450">
<map name="MyCity">
    <area alt="Sri Harish's Home" title="Sri Harish's Home" href="home.html" coords="779,138,804,157" shape="rect">
    <area alt="Hussain Memorial School" title="Hussain Memorial School" href="myschool.html" coords="816,123,836,140" shape="rect">
    <area alt="Chennai,Marina Beach" title="Chennai,Marina Beach" href="marina.html" coords="1294,374,1438,403" shape="rect">
    <area alt="Saveetha Engineering College" title="Saveetha Engineering College" href="mycollege.html" coords="281,477,354,511" shape="rect">
    <area alt="Pachaiamman Temple" title="Pachaiamman Temple" href="localtemple.html" coords="516,52,728,91" shape="rect">
</map>
</center>
</body>
</html>
```

# 1-home.html
```
<html>
<head>
<title>My Home</title>
</head>
<body bgcolor="black">
<h1 align="center" style="color: white;"><b>Chennai</b></h1>
<h3 align="center" style="color: white;"><b>My Home</b></h3>
<hr size="3" color="white">
<p align="center" style="color: white;">
<font face="Georgia" size="5" color="white">
1) Nestled in a vibrant suburban community, the area surrounding my home exudes a sense of warmth and friendliness, with tree-lined streets and well-maintained sidewalks.<br>
2) The neighborhood boasts convenient access to essential amenities such as grocery stores, schools, parks, and recreational facilities, making daily errands and leisure activities easily accessible.<br>
3) Residents in the area share a strong sense of community spirit, often coming together for neighborhood events, block parties, and other social gatherings, fostering a welcoming and inclusive atmosphere.<br>
</p>
<div style="text-align: center;">
    <img src="home.png" width="1200" height="500">
</div>
</body>
</html>
```

# 2-myschool.html
```
<html>
<head>
<title>My School</title>
</head>
<body bgcolor="black">
<h1 align="center" style="color: white;"><b>Chennai</b></h1>
<h3 align="center" style="color: white;"><b>My School</b></h3>
<hr size="3" color="white">
<p align="center" style="color: white;">
<font face="Georgia" size="5" color="white">
1) My school is a small local school filled with memories of my childhood.<br>
2) Eventhough it might be small it's a very decent School.<br>
3) It is a friendly school filled with teachers who give a good amount of freedom.<br>
</p>
<div style="text-align: center;">
    <img src="school.png" width="1200" height="500">
</div>
</body>
</html>
```

# 3-marina.html
```
<html>
<head>
<title>Marina Beach</title>
</head>
<body bgcolor="black">
<h1 align="center" style="color: white;"><b>Chennai</b></h1>
<h3 align="center" style="color: white;"><b>Marina Beach</b></h3>
<hr size="3" color="white">
<p align="center" style="color: white;">
<font face="Monaco" size="5" color="white">
1) This is the second largest beach in the world, located at India, TamilNadu, Chennai.<br>
2) A good Basic beach.<br>
3) the food in this beach is really good, it is kind of messy due to bad garbage handling.<br>
</p>
<div style="text-align: center;">
    <img src="marina.png" width="1200" height="500">
</div>
</body>
</html>
```

# 4-mycollege.html
```
<html>
<head>
<title>My College</title>
</head>
<body bgcolor="black">
<h1 align="center" style="color: white;"><b>Chennai</b></h1>
<h3 align="center" style="color: white;"><b>My College</b></h3>
<hr size="3" color="white">
<p align="center" style="color: white;">
<font face="Monaco" size="5" color="white">
1) I just completed my first sem on this college.<br>
2) A good College with a good amount offreedom provided, not very pressury like other colleges.<br>
3) Friendly Staffs.<br>
</p>
<div style="text-align: center;">
    <img src="college.png" width="1200" height="500">
</div>
</body>
</html>
```

# 5-localtemple.html
```
<html>
<head>
<title>Local Temple</title>
</head>
<body bgcolor="black">
<h1 align="center" style="color: white;"><b>Chennai</b></h1>
<h3 align="center" style="color: white;"><b>Local Temple</b></h3>
<hr size="3" color="white">
<p align="center" style="color: white;">
<font face="Monaco" size="5" color="white">
1) A big temple with a peaceful ambience to walk in, and visit the gods.<br>
2) I've been here when i was young, i used to go there with my mom.<br>
3) Helps find peace.<br>
</p>
<div style="text-align: center;">
    <img src="localtemple.png" width="1200" height="500">
</div>
</body>
</html>
```
## OUTPUT

![image](https://github.com/NSArjun/NearMe/assets/148233801/14572c7d-8e09-48a7-8748-55a4b2a2ea56)

![image](https://github.com/NSArjun/NearMe/assets/148233801/b59f1aae-3a96-4a49-bbc5-23f9efc9efe6)

![image](https://github.com/NSArjun/NearMe/assets/148233801/80f6dd4d-15db-4165-984a-ea9a8a19bf08)

![image](https://github.com/NSArjun/NearMe/assets/148233801/a7244d99-74d1-498e-9d8f-5ca1d85dfd98)

![image](https://github.com/NSArjun/NearMe/assets/148233801/e4b88160-54da-42b5-a5f3-4be2e4c1523a)


## RESULT
The program for implementing image maps using HTML is executed successfully.
