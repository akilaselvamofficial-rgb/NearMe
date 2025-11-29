# Ex03 Places Around Me
## Date:29/11/2025 

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
app.html

<html>
    <head>
        <title>HOME TOWN</title>
    </head>
    <body bgcolor="yellow">
        <h1 align="center"> SIVAGANGAI </h1>
        <h3 align="center">AKILA S (25018659)</h3>
        <img src="Screenshot 2025-11-26 113601.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="SIVAGANGAI PARK" title="SIVAGANGAI PARK" href="park.html" coords="675,136,769,192" shape="rect">
    <area target="" alt="OXFORD MATRICULATION" title="OXFORD MATRICULATION" href="school.html" coords="1006,269,69" shape="circle">
    <area target="" alt="KEEZHADI ARTS AND SCIENCE" title="KEEZHADI ARTS AND SCIENCE" href="krafts.html" coords="469,55,534,88,531,150,410,154,399,70" shape="poly">
    <area target="" alt="COFFEE SHOP" title="COFFEE SHOP" href="coffee.html" coords="630,267,739,318" shape="rect">
    <area target="" alt="OYO LODGE" title="OYO LODGE" href="oyo.html" coords="1131,565,75" shape="circle">
</map>
  
        
    </boby>
</html>

park.html

<html>
    <head>
        <title>park.html</title>
    </head>
    <body bgcolor="green">
        <h1 align="center">SIVAGANGAI</h1>
        <h3 align="center">SIVAGANGAI PARK</h3>
        <hr>
        <h3>DESCRIPTION</h3>
        <p>Sivagangai Park in Thanjavur is a recreational area located next to the Brihadeeswarar Temple, featuring gardens, play equipment, boating on the Sivaganga Tank, and a mini-train. Recently renovated, it includes granite pathways, a fountain, and structures like a "Kadhai Mutram" (Story Telling Arena) that replaced the former deer enclosure. Visitors can also enjoy a canteen and other amenities within the park.</p>
    </body>
</html>

school.html

<html>
    <head>
        <title>school</title>
    </head>
    <body bgcolor="red">
        <h1 align="center"> SIVAGANGAI</h1>
        <h3 align="center"> OXFORD MATRICULATION</h3>
        <hr>
        <h3>DESCRIPTION</h3>
        <p>
Holistic Development: The school emphasizes a child-centered approach to education, aiming to nurture creativity, collaboration, and critical thinking among students. It strives to prepare students for a globalized world by fostering curiosity and compassion. 
1
Curriculum: The school follows the State Board Higher Secondary curriculum, ensuring that students receive a well-rounded education that includes both academic and moral development. </p>
    </body>
</html>

krafts.html

<html>
    <head>
        <title>krafts.html</title>
    </head>
    <body bgcolor="green">
        <h1 align="center">SIVAGANGAI</h1>
        <h3 align="center">KEEZHADI ATRS AND KRAFTS</h3>
        <hr>
        <h3>DESCRIPTION</h3>
        <p>The Keezhadi region in Sivagangai district is famous for its rich archaeological discoveries that highlight the artistic skills of the ancient Tamil civilization. The artefacts found in the Keezhadi excavation—such as pottery, terracotta beads, spindle whorls, etched stones, metal tools, and beautifully designed clay objects—show the high craftsmanship and cultural development of the people who lived there more than 2,000 years ago. The fine pottery with geometric designs, well-polished beads, and household tools reflect their everyday life, creativity, and advanced knowledge of art and craft. Keezhadi’s findings prove that the people of the Sangam age were skilled artisans who practiced weaving, pottery-making, metalwork, and bead-making with great precision. Today, Keezhadi stands as a proud symbol of Tamil Nadu’s artistic heritage and continues to inspire interest in ancient crafts and culture.</p>
    </body>
</html>

coffee.html

<html>
    <head>
        <title>coffee.html</title>
    </head>
    <body bgcolor="purple">
        <h1 align="center">SIVAGANGAI</h1>
        <h3 align="center">COFFEE SHOP</h3>
        <hr>
        <h3>DESCRIPTION</h3>
        <p>A coffee shop is a warm and inviting place where people come to enjoy freshly brewed coffee, tasty snacks, and a peaceful atmosphere. The aroma of roasted coffee beans, soft music, and comfortable seating make it a perfect spot to relax, study, or meet friends. Many people visit coffee shops to take a break from their busy day, read a book, or work on their laptops while sipping their favourite drink. It is a place that brings comfort, creativity, and connection together.</p>
    </body>
</html>

oyo.html

<html>
    <head>
        <title>oyo.html</title>
    </head>
    <body bgcolor="orange">
        <h1 align="center">SIVAGANGAI</h1>
        <h3 align="center"> GK LODGE</h3>
        <hr>
        <h3>DESCRIPTION</h3>
        <p>OYO Flagship GK Lodge is a budget-friendly accommodation located at 188/6-1 Thondi Road, near the MPTC Depot in Maruthupandiar Nagar, Sivagangai — just a short walk (about 5–6 minutes) from the local railway station, which makes it convenient for travellers arriving by train. 

 The rooms are equipped with basic amenities such as air conditioning, television, free WiFi, power backup and toiletries. 

 Hospitality is oriented toward affordability, and the lodge is listed as a “mid-range / budget” stay under the OYO network. 
 The hotel’s check-in time is 12:00 PM and check-out is 11:00 AM.</p>
    </body>
</html>

```
## OUTPUT
![alt text](<Screenshot (23).png>)

![alt text](<Screenshot (25).png>)

![alt text](<Screenshot (24).png>)

![alt text](<Screenshot (28).png>)

![alt text](<Screenshot (29).png>)

![alt text](<Screenshot (27).png>)

## RESULT
The program for implementing image maps using HTML is executed successfully.
