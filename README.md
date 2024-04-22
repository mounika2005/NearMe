# Ex04 Places Around Me
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

## CODE
~~~
#map.html
<!DOCTYPE html>
<html>
<head>
    <title>kadapa</title>
</head>
<body>
    <h1 align="center">
    <font color="black"><b>Lakshmi mounika (212223100026)</b></font>
    </h1>
    <img src="map1.png" alt="Workplace" usemap="#workmap" height="650" width="1465">
    <map name="workmap">
        <area shape="circle" coords="350,300,50" alt="pulivendula" href="pulivendula.html">
        <area shape="circle" coords="750,175,50" alt="yerraguntla" href="yerraguntla.html">
        <area shape="circle" coords="1050,350,50" alt="vontimitta" href="vontimitta.html">
        <area shape="circle" coords="820,50,50" alt="mydukur" href="mydukur.html">
        <area shape="circle" coords="1100,50,50" alt="badvel" href="badvel.html">
    </map>
</body>
</html> 
~~~
~~~
#badvel.html
<html>
    <head>
        <title>badvel</title>
    </head>
    <body style="background-color: deepskyblue;">
        <center>
            <h1 style="color: rgb(255, 0, 128);letter-spacing: 2px;">kadapa</h1>
            <h3 style="color: white; letter-spacing: 2px;">badvel</h3>
            <hr>
            <p style="font-size: 20px;">Badvel is a Municipality in Kadapa district of the Indian state of Andhra Pradesh. Badvel Town is located in Two mandals. It is the headquarters of Badvel revenue division.[2] Major portion of Town comes under Badvel mandal and remaining portion of Town comes under Gopavaram Mandal. It comes under Badvel revenue division.[3]</p>
        </center>
    </body>
</html>pa district of t
~~~
~~~
#mydukur.html
<html>
    <head>
        <title>mydukur</title>
    </head>
    <body style="background-color: deepskyblue;">
        <center>
            <h1 style="color: rgb(255, 0, 128);letter-spacing: 2px;">kadapa</h1>
            <h3 style="color: white; letter-spacing: 2px;">mydukur</h3>
            <hr>
            <p style="font-size: 20px;">Mydukur is a Municipality in YSR Kadapa district of the Indian state of Andhra Pradesh. It is located in Mydukur mandal of Badvel revenue division.[2] Mydukur is located on Main Junction of NH-40 and NH-67. It is a junction point for Kurnool, Kadapa, Proddatur, Markapur, and Nellore Highways.</p>
        </center>
    </body>
</html>
~~~
~~~
#vontimita.html
<html>
    <head>
        <title>vontimita</title>
    </head>
    <body style="background-color: deepskyblue;">
        <center>
            <h1 style="color: rgb(255, 0, 128);letter-spacing: 2px;">kadapa</h1>
            <h3 style="color: white; letter-spacing: 2px;">vontimita</h3>
            <hr>
            <p style="font-size: 20px;">The village is well-known for the Kodandarama Swamy Temple, Vontimitta, famous for its architecture and art. French traveler Jean-Baptiste Tavernier described the temple as ,“one of the grandest pagodas in the whole of India”. The temple is considered to be a centrally protected monument</p>
        </center>
    </body>
</html>
~~~
~~~
#yerraguntla.html
<html>
    <head>
        <title>yerraguntla</title>
    </head>
    <body style="background-color: deepskyblue;">
        <center>
            <h1 style="color: rgb(255, 0, 128);letter-spacing: 2px;">kadapa</h1>
            <h3 style="color: white; letter-spacing: 2px;">yerraguntla</h3>
            <hr>
            <p style="font-size: 20px;">Yerraguntla is a town and Nagar Panchayat in YSR Kadapa District. It is an industrial area in YSR Kadapa district, Andhra Pradesh. It is located in Yerraguntla mandal of Kadapa revenue division.[2]</p>
        </center>
    </body>
</html>`
~~~
~~~
#pulivendula.html
<html>
    <head>
        <title>pulivendula</title>
    </head>
    <body style="background-color: deepskyblue;">
        <center>
            <h1 style="color: rgb(255, 0, 128);letter-spacing: 2px;">kadapa</h1>
            <h3 style="color: white; letter-spacing: 2px;">pulivendula</h3>
            <hr>
            <p style="font-size: 20px;">Pulivendula is a city in Andhra Pradesh, India. It has many popular attractions, including MARUTHI THEATER,pulivendula Poola Angallu, Indoor Stadium Pulivendula, perfect for a trip!</p>
        </center>
    </body>
</html>
~~~


## OUTPUT

![alt text](<Screenshot 2024-04-22 082526-1.png>)
![alt text](<Screenshot 2024-04-22 082716-2.png>)
![alt text](<Screenshot 2024-04-22 082716-1.png>)
![alt text](<Screenshot 2024-04-22 082731.png>)
![alt text](<Screenshot 2024-04-22 082751.png>)
![alt text](<Screenshot 2024-04-22 083832.png>)
## RESULT
The program for implementing image maps using HTML is executed successfully.
