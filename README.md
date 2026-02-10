# Ex03 Places Around Me
## Date: 10.02.2026

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google as an image.

### STEP 3
Insert the image using ```<img>``` tag and link it to the map.

### STEP 4
Using ```<map>``` tag name the map.

### STEP 5
Create clickable regions in the image using ```<area>``` tag.

### STEP 6
Write HTML programs for all the regions identified.

### STEP 7
Execute the programs and publish them.

## CODE
```
<html>
    <head>
        <title>Jegan S K</title>
    </head>
    <body text="red" bgcolor="orange">

        <h1 align="center"> <b>Otteri-Chennai</b></h1>
        <h3  align="center"><b>Jegan S K- 25010598</b></h3>
        <img src="Screenshot 2026-02-09 085218.png" usemap="#image-map" alt= class="center">

        <map name="image-map">
            <area target="" alt="ESI hospital" title="ESI hospital" href="ESI.html" coords="32,64,131,129" shape="rect">
            <area target="" alt="Saravana Stores" title="Saravana Stores" href="saravana.html" coords="570,345,52" shape="circle">
            <area target="" alt="Kandasamty temple" title="Kandaswamy temple" href="temple.html" coords="543,118,556,82,518,66,498,86,494,112,517,121,560,101,541,62" shape="poly">
            <area target="" alt="sandhiyappan" title="sandhiyappan" href="street.html" coords="319,48,378,108" shape="rect">
            <area target="" alt="Water Tank" title="Water Tank" href="tank.html" coords="59,24,33" shape="circle">
        </map>
    </body>
</html>

ESI.html

<html>
    <head>
        <title>ESI HOSPITAL</title>

    </head>
    <body bgcolor="lightblue" text="orange">
        <h1 align="center"><b>ESI HOSPITAL</b></h1>
        ---------------------------------------------------------------------------------------------------------
        <br><br><br>
        <b>ESI hospital is a hospital in ayanavaram. It is near my home.But I don't go there.I don't know why.</b>
    </body>
</html>

saravana.html

<html>
    <head>
        <title>SARAVANA STORES</title>

    </head>
    <body bgcolor="lightgreen" text="red">
        <h1 align="center"><b>SARAVANA STORES</b></h1>
        ---------------------------------------------------------------------------------------------------------
        <br><br><br>
        <b>Saravana Stores is a well established shopping mall in Chennai. One of its branch is in purasaiwalkam,which is near my house.It sells wide range of products  from brush to pillows.Iy acts as a one-stop lovation for buying essentials and luxuries.Although the purasaiwalkam branch is near me, I would go to the padi branch</b>
    </body>
</html>

street.html

<html>
    <head>
        <title>My street</title>

    </head>
    <body bgcolor="grey" text="black">
        <h1 align="center"><b>My Street</b></h1>
        ---------------------------------------------------------------------------------------------------------
        <br><br><br>
        <b>My street is Sandhiyappan street .My house is located in sandhiyappan street. It is my neighbourhood</b>
    </body>
</html>

tank.html

<html>
    <head>
        <title>Water Tank</title>

    </head>
    <body bgcolor="lightorange" text="pink">
        <h1 align="center"><b>Medavakkam water Tank</b></h1>
        ---------------------------------------------------------------------------------------------------------
        <br><br><br>
        <b>A water tank is located in medavakkam,neighbouring area,It is a well-known landmark in medavakkam.</b>
    </body>
</html>

temple.html

<html>
    <head>
        <title>SRI KANDASWAMY TEMPLE</title>

    </head>
    <body bgcolor="lightgreen" text="red">
        <h1 align="center"><b>SRI KANDASWAMY TEMPLE</b></h1>
        ---------------------------------------------------------------------------------------------------------
        <br><br><br>
        <b>Sri Kandaswamy temple is a temple near my home, poojas will be conducted during auspicious days
            But I have never visited the temple.
        </b>
    </body>
</html>
```


## OUTPUT

![alt text](<Screenshot (103).png>)

![alt text](<Screenshot (108).png>) 

![alt text](<Screenshot (107).png>) 

![alt text](<Screenshot (106).png>) 

![alt text](<Screenshot (105).png>) 

![alt text](<Screenshot (104).png>)





## RESULT
The program for implementing image maps using HTML is executed successfully.
