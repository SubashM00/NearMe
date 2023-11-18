# Ex04 Places Around Me
## Date: 20.11.23

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
<title>My city</title>    
</head> 
<body>
<h1 align="center">
<font color="red"><b>Namakkal</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Subash M (23014070)</b></font>    
</h3>
<center>
<img src="image map.png" usemap="#Mycity" height="680" width="1600">
<map name="Mycity">
<area shape="rect" coords="850,350,750,300" href="home.html" tittle="My Home Town">
<area shape="rect" coords="850,350,750,300" href="temple.html" tittle="My Home Town">
<area shape="rect" coords="850,350,750,300" href="temple1.html" tittle="My Home Town">
<area shape="rect" coords="850,350,750,300" href="school.html" tittle="My Home Town">
<area shape="rect" coords="850,350,750,300" href="hospital.html" tittle="My Home Town">
</map>     
</center>
</body>   
</html>

temple.html
<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="orange">
<h1 align="center">
<font color="red"><b>Namakkal</b></font>
</h1>
<h2 align="center">
<font color="black"><b>Sri Ottadi Periyasamy Temple</b></font>
</h2>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
    Sri Ottadi Periyasamy Temple is situated at the foot of Kolli Hills, 5 km from Muthukapatti near Namakkal. Devotees say that the 300-year-old temple swami himself appeared as swayambu and blessed the devotees and the huge banyan tree there is a testimony to this.
    According to the temple's histories, the snake fell on the body of the devotee who paid obeisance at the temple and told him in a dream that an idol should be built separately for him. That's why on the left side of the entrance of the temple, the idol of Nagammal is placed in a row and a large nada idol is placed.
    
    At a distance from the temple are Karuppusamy and Muneeswarar, who sits majestically on a horse in the middle of the temple, grace the devotees. It is the belief of the devotees that the place of Ottadi Periyasamy, who is seated as the guardian deity, has a career, prosperity and if the mind melts and prays for the desired things to happen, everything will come to fruition.
    
    It is the belief of the devotees that those who are not blessed with children, those who want to get rid of witchcraft and witchcraft, can get rid of it by writing it down and tying it to vels and spears. This is the reason why devotees have placed spears, spears and beads around the temple.
</font>
</p>
</body>
</html>

hospital.html
<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="pink">
<h1 align="center">
<font color="red"><b>Namakkal</b></font>
</h1>
<h2 align="center">
<font color="black"><b>Government Medical college</b></font>
</h2>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
    Government Medical College Namakkal is one of the Best Medical Colleges in Tamil Nadu. GMC Namakkal is affiliated with The Tamilnadu Dr MGR Medical University, Chennai, and it was established in 2021. The college is popularly known as Namakkal Medical College. It follows a comprehensive curriculum that combines theoretical knowledge with practical training to produce competent and skilled medical professionals. The faculty members are experienced and dedicated, ensuring that students receive a high standard of education.
    The college is equipped with state-of-the-art facilities and infrastructure, including well-equipped laboratories, modern lecture halls, a well-stocked library, and a hospital with advanced medical equipment. The hospital attached to the college serves as a training ground for the students, where they gain hands-on experience in diagnosing and treating patients under the guidance of experienced doctors.
</font>
</p>
</body>
</html>

temple1.html
<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="green">
<h1 align="center">
<font color="red"><b>Namakkal</b></font>
</h1>
<h2 align="center">
<font color="black"><b>Namakkal Anjaneyar temple</b></font>
</h2>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
    Namakkal Anjaneyar temple is located in Namakkal, a town in Namakkal district in Tamil Nadu, India and is dedicated to the Hindu god Hanuman. It is constructed in the Tamil style of architecture. The legend of the temple is associated with Narasimha, an avatar of Hindu god Vishnu appearing for Hanuman and Lakshmi. The image of Anjaneyar is 18 ft (5.5 m) tall, making it one of the tallest images of Hanuman in India. The Agamam is followed by "Sri Vaikhanasam".
The temple has a pillared hall leading to the sanctum. Four daily rituals and many yearly festivals are held at the temple, of which fifteen-day Panguni Uthiram festival celebrated during the Tamil month of Panguni (March - April) when the image of presiding deities are taken around the streets of the temple, being the most prominent. The temple is maintained and administered by the Hindu Religious and Charitable Endowments Department of the Government of Tamil Nadu
</font>
</p>
</body>
</html>

school.html
<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="orange">
<h1 align="center">
<font color="red"><b>Namakkal</b></font>
</h1>
<h2 align="center">
<font color="black"><b>Park public school</b></font>
</h2>
<hr size="3" color="blue">
<p align="justify">
<font face="Georgia" size="5">
    This school is situated in a spectacular location in the northern part of Namakkal district. This is an ideal place for living out the ethos of allowing children to be children. There is no rush to grow up here, but the foundations are laid for nurturing the resilience of our children to achieve high standards through unrivalled activity programs and around the clock personal care. In addition to more than 20 sports, pupils have immediate access to numerous outdoor and indoor pursuits, by this process, we incubate a sense of success and achievement in every one of our children. With the 21stCentury learning environment, our grade 2 students will work confidently with iPads and the older children have access to outstanding Digital Interactive Classrooms, Modernized Computer, Science & Math's Laboratories, with teachers who are no strangers to programming, explosions, dissections & calculations.
</font>
</p>
</body>
</html>

home.html
<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="yellow">
<h1 align="center">
<font color="red"><b>Namakkal</b></font>
</h1>
<h2 align="center">
<font color="black"><b>My city </b></font>
</h2>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
    My home is situated in the city. It is not too big nor too small, just the perfect size. My family lives in the home. It comprises of my father, mother, sister and grandparents. We live in our ancestral home so my home is very vintage.

It is very old but remains to be super strong. There are six rooms in my home. Each family member has a unique room which they have decorated as per their liking. For instance, my elder sister is a big fan of music, so her walls are filled with posters of musicians like BTS, RM, and more.

Our drawing room is a large one with a high ceiling. We still use the vintage sofa set which my grandmother got as a wedding gift. Similarly, there is a vintage TV and radio which she uses till date.

Adjoining the drawing room is my bedroom. It is my favourite room because it contains everything that I love. I have a pet guinea pig which lives in a cage in my room. We also have a storeroom which is filled with things we don’t use but also cannot discard.A
</font>
</p>
</body>
</html>
```

## OUTPUT
![Alt text](<image map.png>)
![Alt text](<Screenshot (17).png>)
![Alt text](<Screenshot (18).png>)
![Alt text](<Screenshot (21).png>)
![Alt text](<Screenshot (22).png>)
![Alt text](<Screenshot (24).png>)


## RESULT
The program for implementing image maps using HTML is executed successfully.
