# Ex04 Places Around Me
# Date:26/10/2024
# AIM
To develop a website to display details about the places around my house.

# DESIGN STEPS
## STEP 1
Create a Django admin interface.

## STEP 2
Download your city map from Google.

## STEP 3
Using <map> tag name the map.

## STEP 4
Create clickable regions in the image using <area> tag.

## STEP 5
Write HTML programs for all the regions identified.

## STEP 6
Execute the programs and publish them.

# CODE
```
html code:
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>IMAGE MAP</title>
</head>
<body>
    <img  src="/static/map.png" usemap="#mymap" width="1500" height="770">
    <map name="mymap">
        <area shape="rect" coords="242,218,500,296" title=" RR Showroom" href="file:///C:/Users/admin/Desktop/imap/imagemap/mapapp/static/map1.html">
        <area shape="rect" coords="652,630,878,694" title="city Food Center" href="file:///C:/Users/admin/Desktop/imap/imagemap/mapapp/static/map2.html">
        <area shape="rect" coords="516,259,742,323" title="Education Center" href="file:///C:/Users/admin/Desktop/imap/imagemap/mapapp/static/map3.html">
        <area shape="rect" coords="206,606,377,700" title="Cotton Textile" href="file:///C:/Users/admin/Desktop/imap/imagemap/mapapp/static/map4.html">
        <area shape="rect" coords="953,41,1160,185", title="Air travels" href="file:///C:/Users/admin/Desktop/imap/imagemap/mapapp/static/map5.html">
    </map>
        
</body>
</html>

WEBSITE1:
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Royal Enfield Showroom</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
            color: #333;
        }
        header {
            background-color: #2c3e50;
            color: white;
            text-align: center;
            padding: 1rem 0;
        }
        .container {
            max-width: 1200px;
            margin: 20px auto;
            padding: 0 20px;
        }
        .image {
            text-align: center;
            margin: 20px 0;
        }
        .image img {
            max-width: 100%;
            height: auto;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }
        .description {
            background: #ffffff;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            margin-bottom: 20px;
        }
        .contact {
            background: #2c3e50;
            color: white;
            padding: 20px;
            border-radius: 10px;
            text-align: center;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        .contact a {
            color: #ffc107;
            text-decoration: none;
            font-weight: bold;
        }
        .contact a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to Royal Enfield Showroom</h1>
        <p>Experience the Thrill of the Legendary Rides</p>
    </header>

    <div class="container">
        <div class="image">
            <img src="C:\Users\admin\Desktop\imap\imagemap\mapapp\static\royal enfield showroom.webp" alt="Royal Enfield Motorcycles">
        </div>

        <div class="description">
            <h2>About Our Showroom</h2>
            <p>
                Welcome to the Royal Enfield Showroom, your gateway to the world of iconic motorcycles. 
                Explore our range of legendary bikes that combine timeless design, robust engineering, and unmatched performance. 
                From classic models like the Bullet to modern adventures with the Himalayan, we have a ride for every enthusiast.
            </p>
            <p>
                Services we offer include:
            </p>
            <ul>
                <li>Test rides for all models</li>
                <li>On-the-spot financing options</li>
                <li>Genuine Royal Enfield accessories and merchandise</li>
                <li>Dedicated service and maintenance support</li>
            </ul>
            <p>
                Step into our showroom and experience the legacy and passion of Royal Enfield.
            </p>
        </div>

        <div class="contact">
            <h2>Contact Us</h2>
            <p>
                Address: 456 Thunder Road, Motor City, MC 12345<br>
                Phone: <a href="tel:+9876543210">9874563210</a><br>
                Email: <a href="mailto:info@royalenfieldshowroom.com">info@royalenfieldshowroom.com</a>
            </p>
            <p>
                Business Hours: Monday to Saturday, 9:00 AM - 7:00 PM
            </p>
            <p>
                Follow us on: 
                <a href="#" target="_blank">Facebook</a> | 
                <a href="#" target="_blank">Instagram</a> | 
                <a href="#" target="_blank">Twitter</a>
            </p>
        </div>
    </div>
</body>
</html>

WEBSITE2:
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>City Food Centre</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #fff8e1;
            text-align: center;
        }
        header {
            background-color: #ff5722;
            color: white;
            padding: 15px 0;
        }
        .content {
            margin: 20px;
        }
        img {
            max-width: 100%;
            height: auto;
            margin: 20px 0;
        }
        .contact {
            margin: 20px;
            font-size: 18px;
        }
        footer {
            background-color: #ff5722;
            color: white;
            padding: 10px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to City Food Centre</h1>
    </header>
    <div class="content">
        <img src="C:\Users\admin\Desktop\imap\imagemap\mapapp\static\imap2.jpg" alt="City Food Centre">
        <p>Delicious food, amazing ambiance. Your favorite place to dine in the city!</p>
        <div class="contact">
            <p>Contact us at:</p>
            <p>Email: <a href="mailto:info@cityfoodcentre.com">info@cityfoodcentre.com</a></p>
            <p>Phone: <a href="tel:+1234567890">+123 456 7890</a></p>
        </div>
    </div>
    <footer>
        <p>&copy; 2024 City Food Centre. All rights reserved.</p>
    </footer>
</body>
</html>

WEBSITE3:
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bright Future Education Center</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
            color: #333;
        }
        header {
            background-color: #4caf50;
            color: white;
            text-align: center;
            padding: 1.5rem 0;
        }
        .container {
            max-width: 1200px;
            margin: 20px auto;
            padding: 0 20px;
        }
        .image {
            text-align: center;
            margin: 20px 0;
        }
        .image img {
            max-width: 100%;
            height: auto;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }
        .description {
            background: #ffffff;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            margin-bottom: 20px;
        }
        .contact {
            background: #4caf50;
            color: white;
            padding: 20px;
            border-radius: 10px;
            text-align: center;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        .contact a {
            color: #ffc107;
            text-decoration: none;
            font-weight: bold;
        }
        .contact a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <header>
        <h1>Bright Future Education Center</h1>
        <p>Empowering Minds, Shaping Futures</p>
    </header>

    <div class="container">
        <div class="image">
            <img src="C:\Users\admin\Desktop\imap\imagemap\mapapp\static\education center.webp" alt="Education Center">
        </div>

        <div class="description">
            <h2>About Us</h2>
            <p>
                Welcome to Bright Future Education Center, a place dedicated to nurturing the potential of every student. 
                Our mission is to provide high-quality education that inspires lifelong learning and empowers students to achieve their goals.
            </p>
            <p>
                We offer a variety of programs tailored to meet the needs of students of all ages:
            </p>
            <ul>
                <li>After-school tutoring for K-12 students</li>
                <li>College preparation courses (SAT, ACT, GRE, etc.)</li>
                <li>Language and skill development programs</li>
                <li>Workshops and seminars for personal growth</li>
                <li>Online and hybrid learning options</li>
            </ul>
            <p>
                With a team of experienced educators, modern facilities, and a commitment to excellence, Bright Future Education Center is your partner in academic success.
            </p>
        </div>

        <div class="contact">
            <h2>Contact Us</h2>
            <p>
                Address: 789 Knowledge Lane, Learning City, LC 98765<br>
                Phone: <a href="tel:+11234567890">9632154870</a><br>
                Email: <a href="mailto:info@brightfutureedu.com">info@brightfutureedu.com</a>
            </p>
            <p>
                Business Hours: Monday to Saturday, 8:00 AM - 8:00 PM
            </p>
            <p>
                Follow us on: 
                <a href="#" target="_blank">Facebook</a> | 
                <a href="#" target="_blank">Instagram</a> | 
                <a href="#" target="_blank">LinkedIn</a>
            </p>
        </div>
    </div>
</body>
</html>

WEBSITE4:
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cotton Textile Shop</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
            text-align: center;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 10px 0;
        }
        .content {
            margin: 20px;
        }
        img {
            max-width: 100%;
            height: auto;
            margin: 20px 0;
        }
        .contact {
            margin: 20px;
            font-size: 18px;
        }
        footer {
            background-color: #4CAF50;
            color: white;
            padding: 10px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to Cotton Textile Shop</h1>
    </header>
    <div class="content">
        <img src="C:\Users\admin\Desktop\imap\imagemap\mapapp\static\imap4.avif" alt="Cotton Fabrics">
        <p>Your one-stop shop for premium cotton textiles.</p>
        <div class="contact">
            <p>Contact us at:</p>
            <p>Email: <a href="mailto:info@cottontextileshop.com">info@cottontextileshop.com</a></p>
            <p>Phone: <a href="tel:+1234567890">+123 456 7890</a></p>
        </div>
    </div>
    <footer>
        <p>&copy; 2024 Cotton Textile Shop. All rights reserved.</p>
    </footer>
</body>
</html>

WEBSITE5:
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Skyline Air Travels</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #eaf7fe;
            text-align: center;
        }
        header {
            background-color: #1e90ff;
            color: white;
            padding: 15px 0;
        }
        .content {
            margin: 20px;
        }
        img {
            max-width: 100%;
            height: 300px;
            margin: 20px 0;
        }
        .contact {
            margin: 20px;
            font-size: 18px;
        }
        footer {
            background-color: #1e90ff;
            color: white;
            padding: 10px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to Skyline Air Travels</h1>
    </header>
    <div class="content">
        <img src="C:\Users\admin\Desktop\imap\imagemap\mapapp\static\imap5.avif" alt="Skyline Air Travels">
        <p>Your gateway to the skies. Experience seamless air travel with us!</p>
        <div class="contact">
            <p>Contact us at:</p>
            <p>Email: <a href="mailto:info@skylineairtravels.com">info@skylineairtravels.com</a></p>
            <p>Phone: <a href="tel:+1234567890">+123 456 7890</a></p>
        </div>
    </div>
    <footer>
        <p>&copy; 2024 Skyline Air Travels. All rights reserved.</p>
    </footer>
</body>
</html>

```
# OUTPUT
IMAGE MAP:
![Screenshot 2024-12-08 134741](https://github.com/user-attachments/assets/868c564e-80c2-4449-b642-dc2d9a42649d)
WEBSITE1:
![Screenshot 2024-12-08 134844](https://github.com/user-attachments/assets/c106e667-d3e7-44b4-8186-c4576abcccc9)
WEBSITE2:
![Screenshot 2024-12-08 134932](https://github.com/user-attachments/assets/515cb1a9-dfb1-44f1-afa9-fc3e8db8f597)
WEBSITE3:
![Screenshot 2024-12-08 135005](https://github.com/user-attachments/assets/61ac9c05-9631-4b6f-8f0a-e15e4bdccb43)
WEBSITE4:
![Screenshot 2024-12-08 135043](https://github.com/user-attachments/assets/3527ac5f-7623-4605-8e5c-2fc637d60d06)
WEBSITE5:
![Screenshot 2024-12-08 135147](https://github.com/user-attachments/assets/65bb4ea2-8f5b-4a0e-b6e0-84e9d0a957e2)

# RESULT
The program for implementing image maps using HTML is executed successfully.
