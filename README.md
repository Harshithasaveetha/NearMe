# Ex04 Places Around Me
## Date: 27.11.2024

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
```<html>
<body>
<h1>Krishnagiri</h1>
<h2>Harshitha</h2>
<img src="map.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="Hotel Velan International" title="Hotel Velan International" href="velan.html" coords="869,768,1077,824" shape="rect">
    <area target="" alt="Thangamayil Jewellery" title="Thangamayil Jewellery" href="jewel.html" coords="1173,658,76" shape="circle">
    <area target="" alt="Hotel Mangalam Non veg A/C" title="Hotel Mangalam Non veg A/C" href="mangalam.html" coords="567,370,737,451" shape="rect">
    <area target="" alt="TTDC Hotel Tamilnadu" title="TTDC Hotel Tamilnadu" href="TTDC.html" coords="1666,463,66" shape="circle">
    <area target="" alt="Church Town" title="Church Town" href="church.html" coords="348,763,518,844" shape="rect">
</map>
</body>
</html>

velan.html

<html>
    <body bgcolor="cyan">
        <h1>city</h1>
        <h2>Hotel velan international</h2>
        <p>A business class hotel centrally located in the heart of krishnagiri .spacious rooms with plush interiors aiming to make your visit as relaxing and enjoyable as possible</p>
    </body>
</html>

jewel.html

<html>
    <body bgcolor="yellow">
        <h1>city</h1>
        <h2>Thagamayil Jewellery Limited</h2>
        <p>Thangamayil jewellery showrooms in krishnagiri;Thangamayil jewelllery Ltd opposite taluk office krishnagiri courts.Thangamayil jewellery is india's leading online gold jewellery store</p>
         
    </body>
</html>

mangalam.html

<html>
    <body bgcolor="green">
    <h1>city</h1>
    <h2>Hotel Mangalam Non veg A/C</h2>
    <p>The traditional Tamil thali ,served on banana leaf,with each item in particular sequence was superb! The lamb fry was delicious</p>

    </body>
</html>

TTDC.html

<html>
    <body bgcolor="brown">
        <h1>city</h1>
        <h2>TTDC Hotel Tamilnadu Krishnagiri</h2>
        <p>The accommodation is free of charge for children up to 8 years, sharing a bed with parents.Additional charges are applied on the request of extra beds</p>

    </body>
</html>

church.html

<html>
    <body bgcolor="red">
        <h1>city</h1>
        <h2>Church Town</h2>
        <p>church town in krishnagiri,Tamil nadu, is a serene locality known for its peaceful environment and spiritual ambiance.it houses several churches and is significant for its christian community</p>
    </body>
</html>
```




## OUTPUT
[text](harshu/myapp/static/map.html)
![alt text](<html 2.png>)
![alt text](<html 2-2.png>)
![alt text](<html 3.png>)
![alt text](<html 4.png>)
![alt text](<html 5.png>)







## RESULT
The program for implementing image maps using HTML is executed successfully.
