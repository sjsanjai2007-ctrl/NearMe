# Ex04 Places Around Me
## Date: 05:12:2025
## REFERENCE NUMBER: 25007032
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
<img src="Screenshot 2025-12-05 103801.png" usemap="#image-map">
<map name="image-map">
    <area target="" alt="VELLORE FORT" title="VELLORE FORT" href="fort.html" coords="84,416,331,485" shape="rect">
    <area target="" alt="GOVERNMENT MUSEUM" title="GOVERNMENT MUSEUM" href="museum.html" coords="138,594,350,683" shape="rect">
    <area target="" alt="CMC HOSPITAL" title="CMC HOSPITAL" href="cmc.html" coords="786,52,1006,111" shape="rect">
    <area target="" alt="OLD BUS STAND" title="OLD BUS STAND" href="oldbus.html" coords="413,278,662,355" shape="rect">
</map>
~~~

~~~
<html>
    <body>
        <title>OLD BUS STAND</title>
        <img src="download.jpg" alt="OLD BUS STAND">
    </body>
</html>
~~~

~~~
<html>
    <body>
        <title>CMC HOSPITAL</title>
        <img src="cmc_hospital.jpg" alt="CMC HOSPITAL">
    </body>
</html>
~~~

~~~
<html>
    <body>
        <title>GOVERNMENT MUSEUM</title>
        <img src="musume.jpg" alt="GOVERNMENT MUSEUM">
    </body>
</html>
~~~

~~~
<html>
    <body>
        <title>VELLORE FORT</title>
        <img src="vellore_fort.jpg" alt="VELLORE FORT">
    </body>
</html>
~~~

## OUTPUT

<img width="1050" height="727" alt="Screenshot 2025-12-05 103801" src="https://github.com/user-attachments/assets/38706301-d9ae-4434-8fac-f3d120c9bb5e" />



<img width="1050" height="727" alt="Screenshot 2025-12-05 103801" src="https://github.com/user-attachments/assets/e1a4c432-c468-4f84-80a1-a566b207d9f7" />



## RESULT
The program for implementing image maps using HTML is executed successfully.
