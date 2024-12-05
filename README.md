# Ex04 Places Around Me
## Date: 02/12/2024

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
**map.html**
<html>
<head>
<title>My City</title>
</head>
<body>
<h1 align="center">
<font color="black"><b>Thirumullaivoyal</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>HARSHUL SL (24900455)</b></font>
</h3>
<center>


<img src="Screenshot 2024-11-26 080605.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="Pachaiamman Temple" title="Pachaiamman Temple" href="temp.html" coords="584,269,655,324" shape="rect">
    <area target="" alt="Murugappa Polytechnic" title="Murugappa Polytechnic" href="clg.html" coords="261,459,66" shape="circle">
    <area target="" alt="Thangal Park" title="Thangal Park" href="park.html" coords="1304,432,1337,471,1342,534,1276,525,1273,460" shape="poly">
    <area target="" alt="Vcare Hair and Skin Clinic" title="Vcare Hair and Skin Clinic" href="vcare.html" coords="1055,659,63" shape="circle">
    <area target="" alt="Msk Diamond Mahal" title="Msk Diamond Mahal" href="mahal.html" coords="771,338,1074,404" shape="rect">
</map>
</center>
</body>
</html>

**clg.html**

<html>
<head>
    <title>Murugappa Polytechnic</title>
    <style>
        body {
            background-color: #f0f8ff;
            font-family: Arial, sans-serif;
            color: #333;
        }
        h1 {
            text-align: center;
            color: #004080;
            background-color: #e0f7fa;
            padding: 20px;
            margin: 0;
        }
        p {
            text-align: justify;
            margin: 20px 50px;
            font-size: 22px;
        }
    </style>
</head>
<body>

    <h1>Murugappa Polytechnic</h1>

    <p>Murugappa Polytechnic is one of the leading technical educational institutions in the region. Established to offer quality education and skill development in engineering and technology, it provides various diploma courses in fields such as mechanical, electrical, and civil engineering. The polytechnic is well-equipped with modern infrastructure and labs, offering students a hands-on learning experience.</p>

</body>
</html>
**temp.html**

<html>
<head>
    <title>Pachaiamman Temple, Thirumullaivoyal</title>
    <style>
        body {
            background-color: #e8f5e9;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            color: #424242;
        }
        h1 {
            text-align: center;
            color: #388e3c;
            background-color: #c8e6c9;
            padding: 20px;
            margin: 0;
        }
        p {
            text-align: justify;
            margin: 20px 50px;
            font-size: 16px;
        }
    </style>
</head>
<body>

    <h1>Pachaiamman Temple, Thirumullaivoyal</h1>

    <p>Pachaiamman Temple, located in Thirumullaivoyal, Chennai, is an ancient and revered temple dedicated to Goddess Pachaiamman. The temple holds great religious significance for the local community and attracts devotees throughout the year. The temple is known for its peaceful ambiance and historic architecture, featuring intricately designed pillars and a serene environment for worship. Devotees visit the temple to seek blessings for prosperity, well-being, and spiritual growth. It is an important cultural landmark in the region and a place for meditation and prayer.</p>

</body>
</html>
**park.html**

<html>
<head>
    <title>Thangal Park, Ambattur</title>
    <style>
        body {
            background-color: #fff8e1;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            color: #424242;
        }
        h1 {
            text-align: center;
            color: #2e7d32;
            background-color: #a5d6a7;
            padding: 20px;
            margin: 0;
        }
        p {
            text-align: justify;
            margin: 20px 50px;
            font-size: 16px;
        }
    </style>
</head>
<body>

    <h1>Thangal Park, Ambattur</h1>

    <p>Thangal Park, located in Ambattur, is one of the most popular recreational parks in the area. It serves as a serene space for people of all ages to relax, walk, and enjoy nature. The park is well-maintained, featuring walking paths, benches, and greenery, making it a great spot for family outings and fitness enthusiasts alike. With ample space for children to play, it is an ideal destination for those seeking a peaceful escape from the hustle and bustle of the city.</p>

</body>
</html>
**vcare.html**
<html>
<head>
    <title>Vcare</title>
    <style>
        body {
            background-color: #f8f9fa; /* Light grey background */
            font-family: 'Arial', sans-serif;
            color: #333;
        }
        h1 {
            text-align: center;
            color: #28a745; /* Green color for the header */
            background-color: #e9f7e1; /* Light green background */
            padding: 20px;
            margin: 0;
        }
        p {
            text-align: justify;
            margin: 20px 50px;
            font-size: 22px;
        }
    </style>
</head>
<body>

    <h1>Vcare</h1>

    <p>Vcare is a leading service provider in the healthcare industry, committed to delivering top-quality healthcare solutions. We offer a wide range of services, including personalized care, medical consultations, and wellness programs. With a team of dedicated professionals and state-of-the-art facilities, Vcare ensures a holistic approach to health and well-being.</p>

</body>
</html>
**mahal.html**

<html>
<head>
    <title>Marriage Mahal</title>
    <style>
        body {
            background-color: #fff0f5; /* Lavender blush background */
            font-family: 'Arial', sans-serif;
            color: #333;
        }
        h1 {
            text-align: center;
            color: #800080; /* Purple color for the header */
            background-color: #f5e6fa; /* Light purple background */
            padding: 20px;
            margin: 0;
        }
        p {
            text-align: justify;
            margin: 20px 50px;
            font-size: 22px;
        }
    </style>
</head>
<body>

    <h1>Marriage Mahal</h1>

    <p>Marriage Mahal is a premier venue offering an exquisite setting for weddings and other special occasions. With its spacious halls, luxurious decor, and top-notch amenities, it ensures that every event is memorable. Whether you're planning an intimate ceremony or a grand celebration, Marriage Mahal provides the perfect environment for your most important day.</p>

</body>
</html>
```

## OUTPUT
![alt text](image-1.png)
![Screenshot (16)](https://github.com/user-attachments/assets/61e97f76-83e6-44bf-9721-09bcb5f431c5)
![image](https://github.com/user-attachments/assets/8062ff27-5152-4936-ac2c-06e8be5af330)

![alt text](image-4.png)
![alt text](image-5.png)
![alt text](image-6.png)




## RESULT
The program for implementing image maps using HTML is executed successfully.
