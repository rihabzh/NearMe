# Ex04 Places Around Me
## Date: 10-12-2025

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
map.html
```
<html>
<head>
<title>My city</title>
</head>
<body>
<h1 style ="text-align: center;">
    <b>Tiruvannamalai</b>
</h1>
<h3 style ="text-align: center;">
<b>BALAMURUGAN S (25017904)</b>
</h3>
<center>
<img src="map.jpg" usemap="#Mycity">
<map name="Mycity">
<area target="" alt="polur" title="polur" href="polur.html" coords="365,158,470,219" shape="rect">
<area target="" alt="kalasapakkam" title="kalasapakkam" href="kalasapakkam.html" coords="243,520,401,568" shape="rect">
<area target="" alt="kunnathur" title="kunnathur" href="kunnathur.html" coords="409,61,532,107" shape="rect">
<area target="" alt="karaipoondi" title="karaipoondi" href="karaipoondi.html" coords="508,186,642,233" shape="rect">
<area target="" alt="villvarani" title="villvarani" href="villvarani.html" coords="26,473,159,522" shape="rect">
</map>
</center>
</body>
</html>
```
polur.html
```
<html>
<head>
<title>polur</title>
</head>
<body bgcolor="skyblue">
<h1 align ="centre">
<front colour="red"><b>POLUR</b></front>
</h1>
<hr size="3" colour="red">
<p align="justify">
<font face="polur" size="5">
    Polur is a historic town in Tamil Nadu known for its religious significance and vibrant culture. 
    It is located at the foot of the Javadi Hills and is home to the famous Arunachalaeshwarar temple.
    Polur is also a transport and trade hub for nearby villages.
</font>
</p>
</body>
</html>
```
kalasapakkam.html
```
<html>
<head>
<title>kalasapakkam</title>
</head>
<body bgcolor="yellow">
<h1 align ="centre">
<front colour="red"><b>KALASAPAKKAM</b></front>
</h1>
<hr size="3" colour="red">
<p align="justify">
<font face="kalasapakkam" size="5">
    Kalasapakkam is a serene town located south of Polur, known for its agricultural background and peaceful surroundings. The town lies along the Cheyyar River, providing fertile lands and scenic views. It’s a calm and beautiful location away from city life.</font>
</p>
</body>
</html>
```
kunnathur.html

```
<html>
<head>
<title>kunnathur</title>
</head>
<body bgcolor="purple">
<h1 align ="centre">
<front colour="red"><b>KUNNATHUR</b></front>
</h1>
<hr size="3" colour="red">
<p align="justify">
<font face="kunnathur" size="5">
    Kunnathur is a small village near Polur known for its green fields and rural charm. It is surrounded by small water bodies and is mainly inhabited by farmers. It serves as a quiet escape for those looking for natural beauty and simplicity.
</font>
</p>
</body>
</html>
```

karaipoondi.html
```
<html>
<head>
<title>karaipoondi</title>
</head>
<body bgcolor="pink">
<h1 align ="centre">
<front colour="red"><b>KARAIPOONDI</b></front>
</h1>
<hr size="3" colour="red">
<p align="justify">
<font face="karaipoondi" size="5">
    Karaipoondi is a village to the east of Polur, famous for its paddy fields and traditional Tamil lifestyle. The community is close-knit, and festivals are celebrated with great enthusiasm. The calm village roads and clear skies make it a scenic spot.
</font>
</p>
</body>
</html>
```
vilvarani.html
```
<html>
<head>
<title>villvarani</title>
</head>
<body bgcolor="orange">
<h1 align ="centre">
<front colour="red"><b>VILLVARANI</b></front>
</h1>
<hr size="3" colour="red">
<p align="justify">
<font face="villvarani" size="5">        
    Villvarani is a peaceful village located southwest of Polur. It is known for its friendly residents and its natural beauty. With access to local farming lands and traditional houses, it gives a true picture of Tamil Nadu's rural life.
</font>
</p>
</body>
</html>
```

## OUTPUT
<img width="1389" height="911" alt="{262ADE9E-5D6E-4040-B4DF-FEEDC09F62C9}" src="https://github.com/user-attachments/assets/9af018eb-cee6-4057-8f58-19dc86a79edc" />
<img width="1446" height="208" alt="{97FE636A-D69B-4FA1-B207-FC89335835D0}" src="https://github.com/user-attachments/assets/df9e6895-ba43-4e08-be57-b0e7de5f2105" />
<img width="1447" height="226" alt="image" src="https://github.com/user-attachments/assets/e663842b-9b14-498f-be11-cfe6c423b78e" />
<img width="1448" height="212" alt="image" src="https://github.com/user-attachments/assets/0bfdfd65-9b5c-4eea-8f57-8866562805f8" />
<img width="1446" height="222" alt="image" src="https://github.com/user-attachments/assets/ca5cce9e-15f9-4ba4-9354-01d6e82f3320" />
<img width="1447" height="208" alt="image" src="https://github.com/user-attachments/assets/aabf55a5-21c9-4a62-8bcf-429f4d5b7c88" />

## RESULT
The program for implementing image maps using HTML is executed successfully.
