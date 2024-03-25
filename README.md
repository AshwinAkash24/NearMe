# Ex04 - Places Around Me
## Date: 25-03-2024

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

## PROGRAM
#### map.html
```
<!DOCTYPE html>
 <html lang="en">
 <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title align="center">HOSUR</title>
    <h1 align="center">HOSUR</h1>
    <h1 align="center">Ashwin Akash M (212223230024)</h1>
 </head>
 <body align="center" bgcolor="silver">
   <img src="MAP.png" usemap="#image-map" >

<map name="image-map">
    <area target=""  alt="Arulmighu Sri Chandra Choodeshwara"  title="Arulmighu Sri Chandra Choodeshwara" href="temple.html" coords="1125,608,789,563" shape="rect">
    <area target="" alt="Grand Cinemas" title="Grand Cinemas" href="cinema.html"  coords="487,832,69"  shape="circle">
    <area target="" alt="Hotel Hills" title="Hotel Hills" href="hotel.html" coords="683,258,58" shape="circle">
    <area target="" alt="Grand Continent" title="Grand Continent" href="cont.html" coords="943,403,1203,446" shape="rect">
    <area target="" alt="Inplace Design Studio" title="Inplace Design Studio" href="studio.html" coords="555,369,706,410" shape="rect">
</map>
 </body>
 </html>
```
#### temple.html
```
<!DOCTYPE html>
 <html lang="en">
 <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Arulmughu Sri Chandra Choudeswaran Temple</title>
 </head>
 <body bgcolor="E6E6FA">
    <h1 align="center">Arulmughu Sri Chandra Choudeswaran Temple</h1>
    <br>
    <br>
    <hr size="3" color="black">
    <br><br>
    <p><h2>The temple has grown during the time of the Cholas, Hoysala and Vijayanagara Emperors. The Chandra Choodeshwara Temple structure may have been built by the Hoysala king, Thirupuvanamalla Barvatharaja Anthiyazhvar, in the year 1260. The 13th-century inscription found during Chandra Choodeshwara temple patronage.</h2></p>
    
 </body>
 </html>
```
#### cinema.html
```
<!DOCTYPE html>
<html lang="en">
<head>
   <meta charset="UTF-8">
   <meta name="viewport" content="width=device-width, initial-scale=1.0">
   <title>Grand Cinema</title>
</head>
<body bgcolor="#ADFF2F">
   <h1 align="center">Grand Cinema</h1>
   <br>
   <br>
   <hr size="3" color="black">
   <br><br>
   <p><h2>The Tacoma Film Festival has been proudly hosted by The Grand Cinema in Tacoma, WA, since the festival's inception in 2006. Located on the edge of downtown Tacoma's theater district, The Grand Cinema is Pierce County's only nonprofit, art-house cinema showcasing independent, foreign, and local films. The cinema is supported by dedicated volunteers, committed members, a vibrant Board of Directors, and small but mighty staff team.</h2></p>
</body>
</html>
```
#### hotel.html
```
<!DOCTYPE html>
 <html lang="en">
 <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hotel Hills</title>
 </head>
 <body bgcolor="#7FFF00">
    <h1 align="center">Hotel Hills</h1>
    <br>
    <br>
    <hr size="3" color="black">
    <br><br>
    <p><h2>Best hotel located in the Hosur, beside the Bangalore — Chennai highway which is 70 kms drive from Kempegowda International Airport, Bengaluru and 40 kms drive from Majestic Railway Station,Bengaluru.

        The hotel welcomes you with its fresh interiors as well as crisp and clean rooms and delights you with its unbeatable value and reliable safety standards.
        
        The hotel remain stylish, modern, forward thinking global leaders of hospitality and we help make traveling easier with our smart design, innovative restaurant concepts, unique activities, nature and authentic hospitality.
        
        Stay active in our fitness centre or take a refreshing dip in the outdoor pool.
        
        Our meeting rooms and banquet halls provide the perfect venue for all your professional & social needs.</h2></p>
 </body>
 </html>
```
#### cont.html
```
<!DOCTYPE html>
 <html lang="en">
 <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Grand Continent</title>
 </head>
 <body bgcolor="azure">
    <h1 align="center">Grand Continent</h1>
    <br>
    <br>
    <hr size="3" color="black">
    <br><br>
    <p><h2>Every Sarovar hotel is designed to meet the contemporary requirements of today's traveler. From tech-enabled spaces to inspired design, from affordable luxury to chic boutiques, from value-driven essentials to pampered indulgence, over 100 hotels across 67+ destinations in India and abroad promise you a stay that is delightful and memorable.

        Each property celebrates the unique essence of its destination to give you a personalized experience with a thoughtfulness you'll find only in the best hotels in the world.</h2></p>
 </body>
 </html>
```
#### studio.html
```
<!DOCTYPE html>
 <html lang="en">
 <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Grand Continent</title>
 </head>
 <body bgcolor="aqua">
    <h1 align="center">Grand Continent</h1>
    <br>
    <br>
    <hr size="3" color="black">
    <br><br>
    <p><h2>inPLACE Design is an architecture, planning, and design firm with the experience and capabilities to create engaging mixed-use, retail, and resort destinations. We are dedicated to places that engage people, nurtures community and enhances urban lifeinPLACE Design provides the combination of highly-personalized service found at a small shop with the global reach and creative experience of an international firm. We work closely with developers who understand the importance great places have on the value of their assets. Investigating, analyzing, and guiding our client’s development strategy helps our firm stand out from the crowd.,</h2></p>
 </body>
 </html>
```
## OUTPUT
## map.html
![map html](https://github.com/AshwinAkash24/NearMe/assets/144979248/60c6b89c-6f77-4699-9e7b-f6553e7db1a2)
## temple.html
![temple](https://github.com/AshwinAkash24/NearMe/assets/144979248/ebf586a0-a7ff-4b66-a603-5d5bd5c799fd)
## cinema.html
![cinema](https://github.com/AshwinAkash24/NearMe/assets/144979248/3ae7ae23-0f39-463b-b963-935b64525a62)
## hotel.html
![hotel](https://github.com/AshwinAkash24/NearMe/assets/144979248/0a3982dd-8d58-4b66-ae8d-3225b52a274b)
## cont.html
![cont](https://github.com/AshwinAkash24/NearMe/assets/144979248/720ec027-e1ba-49ae-bb50-83e3eb807575)
## studio.html
![inplace](https://github.com/AshwinAkash24/NearMe/assets/144979248/ea218fd6-a216-4b48-98f6-d9ebfc050f30)



## RESULT
The program for implementing image maps using HTML is executed successfully.
