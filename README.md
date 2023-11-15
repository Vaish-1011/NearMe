# Ex04 Places Around Me
### Date :19/10/23
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

### map.html
```
<html> 

<h3>Mapping an Image 

<body> 

<p>Click on the different continents of the map to know about them.</p> 

<img src="Screenshot 2023-10-17 090733.png" usemap="#image-map">

<map name="image-map">
    <area target="_blank" alt="Coutrallam Main Falls" title="Coutrallam Main Falls" href="courtrallam.html" coords="370,408,552,481" shape="rect">
    <area target="_blank" alt="Coutrallam Five Falls" title="Coutrallam Five Falls" href="Fivefalls.html" coords="34,382,197,467" shape="rect">
    <area target="_blank" alt="Ilanji Kumarar Kovil" title="Ilanji Kumarar Kovil" href="IlanjiTemple.html" coords="644,185,411,265" shape="rect">
    <area target="_blank" alt="Tenkasi Sivan Temple" title="Tenkasi Sivan Temple" href="Tenksi Sivan Temple.html" coords="828,68,1019,170" shape="rect">
    <area target="_blank" alt="Shenbagadevi Water Falls" title="Shenbagadevi Water Falls" href="Shenbagadevi Water Falls.html" coords="296,491,530,563" shape="rect">
</map>

</body> 
</html> 
```
### courtrallam.html
```
<!DOCTYPE html>
<html>
<head>
    <title>Courtrallam Main Falls</title>
</head>
<body bgcolor="pink">
    <h1>Courtrallam Main Falls</h1>
    <p>
        Courtrallam Main Falls, also known as Kutralam Falls, is a popular waterfall located in the southern part of India. It is a natural wonder that attracts tourists from all over the country.
    </p>

    <h2>Location</h2>
    <p>
        Courtrallam Main Falls is situated in the Western Ghats in the state of Tamil Nadu. It is in the Tirunelveli district and is surrounded by lush greenery and forests.
    </p>

    <h2>Features</h2>
    <p>
        The main falls at Courtrallam is a spectacular sight, with water cascading down from a considerable height. It is a great place to relax and enjoy the beauty of nature. There are also several other smaller falls and bathing areas in the vicinity.
    </p>

    <h2>Visiting Tips</h2>
    <ul>
        <li>Visit during the monsoon season for the best waterfall experience.</li>
        <li>Be cautious while bathing in the falls, as the currents can be strong.</li>
        <li>Respect the local environment and keep it clean by disposing of your trash properly.</li>
    </ul>
    <p>
        Plan your trip to Courtrallam Main Falls and immerse yourself in the beauty of this natural wonder.
    </p>
</body>
</html>
```
### Fivefalls.html
```
<!DOCTYPE html>
<html>
<head>
    <title>Courtrallam Five Falls</title>
</head>
<body bgcolor="lightblue">
    <h1>Courtrallam Five Falls</h1>
    <p>
        Courtrallam Five Falls is a group of five stunning waterfalls located in the southern part of India. This natural wonder is a must-visit destination for nature lovers and adventure seekers.
    </p>

    <h2>Location</h2>
    <p>
        Courtrallam Five Falls is situated in the Western Ghats of Tamil Nadu, in the Tirunelveli district. The falls are surrounded by dense forests and scenic beauty.
    </p>

    <h2>Features</h2>
    <p>
        The Five Falls at Courtrallam are a collection of five separate cascades of water. Each one has its own unique charm and beauty, making it a great place for photography and relaxation.
    </p>

    <h2>Visiting Tips</h2>
    <ul>
        <li>Visit during the monsoon season for the most impressive display of waterfalls.</li>
        <li>Wear suitable footwear as the area can be slippery.</li>
        <li>Observe safety precautions when swimming or bathing in the falls.</li>
    </ul>
    <p>
        Explore the natural beauty of Courtrallam Five Falls and experience the serenity and grandeur of these cascading wonders.
    </p>
</body>
</html>
```
### IlanjiTemple.html
```
<!DOCTYPE html>
<html>
<head>
    <title>Ilanji Kumarar Temple</title>
</head>
<body bgcolor="lightgrey">
    <h1>Ilanji Kumarar Temple</h1>
    <p>
        Ilanji Kumarar Temple is a prominent Hindu temple located in the town of Ilanji in the Tenkasi region of the Indian state of Tamil Nadu. It is dedicated to Lord Kumarar, a form of Lord Murugan, and is a place of great spiritual significance and cultural heritage.
    </p>

    <h2>Location</h2>
    <p>
        The Ilanji Kumarar Temple is situated in the town of Ilanji in the Tenkasi region of Tamil Nadu. It is surrounded by lush greenery and has a serene and peaceful atmosphere.
    </p>

    <h2>Features</h2>
    <p>
        The temple is known for its stunning architecture and intricate sculptures. It has a beautiful gopuram (entrance tower) and various mandapams. The temple hosts various religious festivals and rituals, making it a hub of cultural activities.
    </p>

    <h2>Visiting Tips</h2>
    <ul>
        <li>Respect the temple's customs and dress modestly when visiting.</li>
        <li>Learn about the temple's timings and any special events or festivals that might be taking place during your visit.</li>
        <li>Be mindful of photography restrictions within the temple premises.</li>
    </ul>
    <p>
        Visit the Ilanji Kumarar Temple in Ilanji, Tenkasi to experience the rich cultural and spiritual heritage of Tamil Nadu.
    </p>
</body>
</html>
```
### Shenbagadevi Water Falls.html
```
<!DOCTYPE html>
<html>
<head>
    <title>Shenbagadevi Water Falls</title>
</head>
<body bgcolor="pink">
    <h1>Shenbagadevi Water Falls</h1>
    <p>
        Shenbagadevi Water Falls is a beautiful natural waterfall located in the Tenkasi region of Tamil Nadu, India. It is a stunning destination for nature enthusiasts and adventure seekers.
    </p>

    <h2>Location</h2>
    <p>
        Shenbagadevi Water Falls is situated in the lush and scenic surroundings of Tenkasi, a town in the Western Ghats of Tamil Nadu. The falls are known for their serene and tranquil atmosphere.
    </p>

    <h2>Features</h2>
    <p>
        The waterfall is known for its picturesque beauty, with water cascading down a series of rocks and forming a serene pool at the base. It's an ideal place for relaxation and enjoying the natural beauty of the region.
    </p>

    <h2>Visiting Tips</h2>
    <ul>
        <li>Visit during the monsoon season for the most impressive flow of the waterfall.</li>
        <li>Wear appropriate footwear for walking on rocky terrain.</li>
        <li>Respect the natural environment by disposing of your waste properly and following local guidelines.
    </ul>
    <p>
        Explore the beauty of Shenbagadevi Water Falls in Tenkasi and experience the tranquility of this natural wonder.
    </p>
</body>
</html>
```
### Tenkasi Sivan Temple.html
```
<!DOCTYPE html>
<html>
<head>
    <title>Tenkasi Sivan Temple</title>
</head>
<body bgcolor="lightgreen">
    <h1>Tenkasi Sivan Temple</h1>
    <p>
        The Tenkasi Sivan Temple, also known as the Kasi Viswanathar Temple, is a renowned Hindu temple dedicated to Lord Shiva. It is located in the picturesque town of Tenkasi, Tamil Nadu, and is a place of great spiritual and cultural significance.
    </p>

    <h2>Location</h2>
    <p>
        The Tenkasi Sivan Temple is situated in the heart of Tenkasi, a charming town nestled in the Western Ghats of Tamil Nadu. The temple is surrounded by lush greenery and is a center of religious and cultural activities.
    </p>

    <h2>Features</h2>
    <p>
        The temple is famous for its Dravidian-style architecture, towering gopuram (entrance tower), and intricate sculptures. It hosts a variety of religious festivals and rituals, making it a hub of cultural and spiritual activities in the region.
    </p>

    <h2>Visiting Tips</h2>
    <ul>
        <li>Respect the temple's customs and dress modestly when visiting.</li>
        <li>Check the temple's opening hours and any special events or festivals that may be taking place during your visit.</li>
        <li>Photography rules within the temple premises should be observed and respected.
    </ul>
    <p>
        Explore the divine and cultural heritage of Tenkasi by visiting the sacred Tenkasi Sivan Temple.
    </p>
</body>
</html>
```

## OUTPUT

![Alt text](<Screenshot 2023-10-31 212025.png>)
![Alt text](<Screenshot 2023-10-31 212046.png>)
![Alt text](<Screenshot 2023-10-31 212108.png>)
![Alt text](<Screenshot 2023-10-31 212121.png>)
![Alt text](<Screenshot 2023-10-31 212135.png>)
![Alt text](<Screenshot 2023-10-31 212150.png>)

## RESULT
The program for implementing image maps using HTML is executed successfully.
