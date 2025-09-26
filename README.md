# Ex04 Places Around Me
## Date: 26.09.2025

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
<html>
    <head>
        <title>map</title>
    </head>
    <body>
        <center>
        <h1>RAMESWARAM-SASIKUMAR S(25015350)</h1>
        </center>

        <img src="Screenshot 2025-09-20 141913.png" usemap="#image-map">


<map name="image-map">
    <area target="" alt="Hotel Ganesh Palace" title="Hotel Ganesh Palace" href="hotelganesh.html" coords="1048,408,113" shape="circle">
    <area target="" alt="Rameshwaram Sea Shore" title="Rameshwaram Sea Shore" href="seashore.html" coords="1423,122,97" shape="circle">
    <area target="" alt="New Grace AG Church" title="New Grace AG Church" href="AGchurch.html" coords="1,331,241,126" shape="rect">
    <area target="" alt="The Residency Towers" title="The Residency Towers" href="residencytowers.html" coords="358,231,607,423" shape="rect">
    <area target="" alt="Rameswaram Fishing Harbour and Boat Jetty" title="Rameswaram Fishing Harbour and Boat Jetty" href="fishing harbour" coords="1180,496,1458,611,1193,611,1129,533,1256,437,1507,532,1460,613,1198,609" shape="poly">
</map>
</body>
</html>
AGchurch.html

<html>
    <head>
        <title>AGchurch</title>
    </head>
    <body bgcolor="lightblue">
        <center>
            <h1>AGchurch</h1>
            <hr><br>
        </center>
        <p>The new Grace AG Church in Rameswaram is an Assemblies of God (AG) church focused on spreading the message of Christ's crucifixion and holding various community events, including youth activities and prayer meetings, as evidenced.</p>
    </body>

fishing harbour.html

<html>
    <head>
        <title>fishing harbour</title>
    </head>
    <body bgcolor="green">
        <center>
            <h1>fishing harbour</h1>
            <hr><br>
        </center>
        <p>The Rameswaram Fishing Harbour on Pamban Island serves as a crucial fishing base in Ramanathapuram district, Tamil Nadu, facilitating the berthing of mechanised and country boats and the landing of catches by fishermen from the region.</p>
    </body>
</html>

hotelganesh.html

<html>
    <head>
        <title>hotelganesh</title>
    </head>
    <body bgcolor="yellow">
        <center>
            <h1>hotelganesh</h1>
            <hr><br>
        </center>
        <p>Hotel Ganesh Palace is a business-style hotel in Rameswaram, India, located near the Ramanathaswamy Temple and Dr. Abdul Kalam's House. Guests often praise its spacious, clean, and comfortable rooms, as well as the prompt and helpful service provided by the polite staff.</p>
    </body>
</html>

residencytowers.html

<html>
    <head>
        <title>residencytowers</title>
    </head>
    <body bgcolor="pink">
        <center>
            <h1>residencytowers</h1>
            <hr><br>
        </center>
        <p>The Residency Towers Rameswaram is a 5-star hotel, formerly JKR Resort and Spa, located in Rameswaram, Tamil Nadu, near the iconic Ramanathaswamy Temple and Agnitheertham. It offers luxurious rooms, a 24-hour vegetarian restaurant, a 24-hour gym, a swimming pool, an on-site spa, and extensive meeting spaces.</p>
    </body>
</html>

seashore.html

<html>
    <head>
        <title>seashore</title>
    </head>
    <body bgcolor="red">
        <center>
            <h1>seashore</h1>
            <hr><br>
        </center>
        <p>The Rameswaram Sea Shore isn't a specific location but refers to the rich maritime environment surrounding Rameswaram, particularly its abundant marine life, including diverse fish, corals, and marine mammals like dugongs and dolphins.</p>
    </body>
</html>



## OUTPUT
![alt text](<Screenshot 2025-09-26 211943-1.png>)
![alt text](<Screenshot 2025-09-26 201720.png>)
![alt text](<Screenshot 2025-09-26 202342.png>)
![alt text](<Screenshot 2025-09-26 202550.png>)
![alt text](<Screenshot 2025-09-26 202756.png>)
![alt text](<Screenshot 2025-09-26 203457.png>)

## RESULT
The program for implementing image maps using HTML is executed successfully.
