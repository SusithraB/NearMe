# Ex04 Places Around Me
## Date:30/03/2024

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

```
map.html

<html>
<head>
<title>My City</title>
</head>
<body>
<h1 align="center">
<font color="red"><b>Vellore</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Aravind Kumar (Reg No)</b></font></h3>
<center>
<img src="map.png" usemap="#MyCity" height="610" width="1450">
<map name="MyCity">
<area shape="rect" coords="433,432,633,486" href="school.html" title="Sree jayam school">
<area shape="rect" coords="888,186,1088,240" href="college.html" title="Dkm college">
<area shape="rect" coords="473,23,673,77" href="place1.html" title="Venus cinemas">
<area shape="circle" coords="773,514,54" href="place2.html" title="Blue cinemas">
<area shape="circle" coords="769,283,78" href="address.html" title="Krishna Nagar">
</map>
</center>
</body>
</html>


school.html

<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="red">
<h1 align="center">
<font color="red"><b>Vellore</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Sree Jayam School</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
As of my last update in January 2022, there isn't specific information available about a school named "Sree Jayam School" that I can provide. It's possible that this school might be a local institution or one that hasn't gained widespread recognition or documentation in sources available up to my last update.

If "Sree Jayam School" is a newly established institution or one that gained prominence after my last update, I would recommend searching for more recent information online or through local directories and educational authorities in the relevant region.
</p>
</body>
</html>

college.html

<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="red">
<h1 align="center">
<font color="red"><b>Vellore</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Dkm college</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
DKM College for Women, located in Vellore, Tamil Nadu, India, is a well-known institution affiliated with Thiruvalluvar University. Established in 1972, the college offers undergraduate and postgraduate courses in various fields including arts, science, commerce, and management.

DKM College has earned a reputation for academic excellence and holistic development of its students. The institution is known for its strong emphasis on providing quality education, fostering research and innovation, and promoting extracurricular activities for overall personality development.
</p>
</body>
</html>

place1.html

<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="red">
<h1 align="center">
<font color="red"><b>Vellore</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Venus cinemas</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
Venus Cinemas is a well-known cinema chain in India, particularly in the state of Tamil Nadu. It operates several multiplex theaters in various cities, including Chennai. Venus Cinemas is known for its modern facilities, comfortable seating, and a wide range of movie offerings, including both regional and international films.

The chain is popular among moviegoers for its state-of-the-art technology, including advanced sound systems and projection equipment, providing an immersive cinematic experience. Venus Cinemas also often hosts special screenings, events, and film festivals to cater to diverse audience preferences.

For the most accurate and up-to-date information about Venus Cinemas, including locations, movie schedules, and special events, it's recommended to visit their official website or follow them on social media platforms where they regularly update their followers about their offerings and promotions.
</p>
</body>
</html>

place2.html

<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="red">
<h1 align="center">
<font color="red"><b>Vellore</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Blue cinemas</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
As of my last update in January 2022, there isn't specific information available about a cinema chain or entity named "Blue Cinemas" that I can provide. It's possible that "Blue Cinemas" might be a local cinema chain, a newly established entity, or one that hasn't gained widespread recognition or documentation in sources available up to my last update.

If "Blue Cinemas" is a newly established cinema chain or one that gained prominence after my last update, I would recommend searching for more recent information online, checking local directories, or visiting their official website or social media pages for details about their locations, offerings, and other relevant information.
</p>
</body>
</html>

address.html

<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="red">
<h1 align="center">
<font color="red"><b>Vellore</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Krishna Nagar</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
Krishna Nagar is a common place name in India, and there are several areas, localities, and neighborhoods across the country with this name. Without more context or specifics about which Krishna Nagar you're referring to, it's challenging to provide detailed information.

Krishna Nagar is often a residential area and may have amenities such as schools, parks, markets, and transportation facilities. It could be located in various cities or towns across India.

If you could provide more details or specify which Krishna Nagar you're interested in, I could offer more tailored information about that particular location.
</p>
</body>
</html>
```
## OUTPUT
![alt text](1-1.png)
![alt text](2-1.png)
![alt text](3-1.png)
![alt text](4-1.png)
![alt text](5-1.png)
![alt text](6-1.png)
## RESULT
The program for implementing image maps using HTML is executed successfully.
