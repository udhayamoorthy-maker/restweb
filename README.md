# Ex.06 Restaurant Website
## Date:19/12/25

## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
```
home.html

<html>
<head>
  <title>The Flavor Fusion</title>
</head>
<body style="margin:0; font-family:'Times New Roman', Times, serif; background-image:url('r1.jpg'); background-size:cover; width:1370px; height:650px; padding:20px;">

  <div style="width:550px; height:25px; border:2px solid black; padding:10px; background-color:white; text-align:center; position:relative; top:5px; left:900px; word-spacing:70px;">
    <a href="home.html">HOME</a>
    <a href="menu.html">MENU</a>
    <a href="admin.html">ADMIN</a>
    <a href="contact.html">CONTACT</a>
  </div>

  <div style="color:goldenrod; font-family:Verdana; text-align:left; position:relative; font-weight:bolder; font-size:xx-large; top:-50px;">
    <h1><b>The Flavor Fusion</b></h1>
  </div>

  <div style="color:rgb(241, 227, 227); text-align:left; position:relative; font-size:large; font-weight:bold; bottom:80px; left:10px;">
    A Golden Taste of India
  </div>

  <div style="color:rgb(238, 228, 228); text-align:center; position:relative; font-weight:bolder; bottom:100px; font-size:large; right:10px;">
    <i>A Taste of Elegance</i>
    <p>The Flavor Fusion is a cozy and stylish restaurant where great taste meets warm hospitality.<br>
    We serve freshly made dishes with rich flavors, offering a place where family and friends can enjoy good food together.<br>
    At The Flavor Fusion , every meal is special, simple, and satisfying.</p>

    <div style="position:relative; top:50px; left:5px; background-size:contain;">
      <img src="r2.jpg" width="550" height="260">
    </div>
  </div>

  <footer style="width:1410px; height:20px; color:white; background-color:black; text-align:center; position:relative; top:50px; left:-20px;">
    &copy;UDHAYAMOORTHY A (25004153)
  </footer>

</body>
</html>


menu.html

<html>
<head>
  <title>Menu</title>
</head>
<body style="margin:0; font-family:'Times New Roman', Times, serif; background-image:url('r6.jpg'); background-size:cover; width:1370px; height:650px; color:black; padding:20px;">

  <div style="width:550px; height:25px; border:2px solid black; padding:10px; background-color:white; text-align:center; position:relative; top:5px; left:900px; word-spacing:70px; font-weight:bold;">
    <a href="home.html">HOME</a>
    <a href="menu.html">MENU</a>
    <a href="admin.html">ADMIN</a>
    <a href="contact.html">CONTACT</a>
  </div>

  <div style="color:rgb(236, 226, 226); font-family:Verdana; text-align:center; position:relative; font-weight:bold; font-size:large; top:-50px;">
    <h1><b>MENU</b></h1>
  </div>

  <div style="display:grid; grid-template-columns:repeat(auto-fit, minmax(90px, 1fr)); gap:50px; justify-items:center; padding:20px; margin-top:30px;">
    <div style="background-color:white; border-radius:10px; text-align:center; padding:20px; width:100%;">
      <img src="dosa.webp" style="border-radius:10px; width:100%; height:180px; object-fit:cover;">
      <h1 style="font-size:1.5em; color:black; margin-top:15px;">Dosa</h1>
      <p style="color:black; margin-bottom:0;">Rs. 100</p>
    </div>

    <div style="background-color:white; border-radius:10px; text-align:center; padding:20px; width:100%;">
      <img src="mousse.jpg" style="border-radius:10px; width:100%; height:180px; object-fit:cover;">
      <h1 style="font-size:1.5em; color:black; margin-top:15px;">Mousse</h1>
      <p style="color:black; margin-bottom:0;">Rs. 1000</p>
    </div>

    <div style="background-color:white; border-radius:10px; text-align:center; padding:20px; width:100%;">
      <img src="biriyani.jpg" style="border-radius:10px; width:100%; height:180px; object-fit:cover;">
      <h1 style="font-size:1.5em; color:black; margin-top:15px;">Briyani</h1>
      <p style="color:black; margin-bottom:0;">Rs. 500</p>
    </div>
    <div style="background-color:white; border-radius:10px; text-align:center; padding:20px; width:100%;">
      <img src="tea.webp" style="border-radius:10px; width:100%; height:180px; object-fit:cover;">
      <h1 style="font-size:1.5em; color:black; margin-top:15px;">Tea</h1>
      <p style="color:black; margin-bottom:0;">Rs.20</p>
    </div>
    <div style="background-color:white; border-radius:10px; text-align:center; padding:20px; width:100%;">
      <img src="rose.jpg" style="border-radius:10px; width:100%; height:180px; object-fit:cover;">
      <h1 style="font-size:1.5em; color:black; margin-top:15px;">Rose pudding</h1>
      <p style="color:black; margin-bottom:0;">Rs. 300</p>
    </div>
    <div style="background-color:white; border-radius:10px; text-align:center; padding:20px; width:100%;">
      <img src="noodel.jpg" style="border-radius:10px; width:100%; height:180px; object-fit:cover;">
      <h1 style="font-size:1.5em; color:black; margin-top:15px;">Noodels</h1>
      <p style="color:black; margin-bottom:0;">Rs. 350</p>
    </div>
    <div style="background-color:white; border-radius:10px; text-align:center; padding:20px; width:100%;">
      <img src="veg.jpg" style="border-radius:10px; width:100%; height:180px; object-fit:cover;">
      <h1 style="font-size:1.5em; color:black; margin-top:15px;">Veg lunch</h1>
      <p style="color:black; margin-bottom:0;">Rs. 450</p>
    </div>
 
</body>
</html>

admin.html

<html>
<head>
  <title>Admin</title>
</head>
<body style="margin:0; font-family:'Times New Roman', Times, serif; background-image:url('r5.jpg'); background-size:cover; width:1450px; height:630px; color:black; padding:20px;">

  <div style="width:490px; height:25px; border:2px solid black; padding:10px; background-color:white; text-align:center; position:relative; top:5px; left:950px; word-spacing:50px; font-weight:bold;">
    <a href="home.html">HOME</a>
    <a href="menu.html">MENU</a>
    <a href="admin.html">ADMIN</a>
    <a href="contact.html">CONTACT</a>
  </div>

  <div style="color:black; font-family:Verdana; text-align:center; position:relative; font-weight:bold; top:10px;">
    <h1><b>EXECUTIVE TEAM</b></h1>
  </div>

  <div style="display:grid; grid-template-columns:repeat(auto-fit, minmax(90px, 1fr)); gap:50px; justify-items:center; padding:10px; margin-top:10px;">
    
    <div style="background-color:#f4c005; border-radius:10px; text-align:center; padding:20px; width:90%;">
      <img src="sk.jpg" style="border-radius:50% / 35%; width:100%; height:250px; object-fit:cover;">
      <h1 style="font-size:1em; color:black; margin-top:15px;">SIVAKARTHIKEYAN</h1>
      <p style="color:black; margin-bottom:0; font-size:1.5em; background-color:azure;">Founder & Owner</p>
    </div>

    <div style="background-color:#f4c005; border-radius:10px; text-align:center; padding:20px; width:90%;">
      <img src="vijay.jpg" style="border-radius:50% / 35%; width:100%; height:250px; object-fit:cover;">
      <h1 style="font-size:1em; color:black; margin-top:15px;">VIJAY</h1>
      <p style="color:black; margin-bottom:0; font-size:1.5em; background-color:azure;">CEO</p>
    </div>

    <div style="background-color:#f4c005; border-radius:10px; text-align:center; padding:20px; width:90%;">
      <img src="vkd.jpg" style="border-radius:50% / 35%; width:100%; height:250px; object-fit:cover;">
      <h1 style="font-size:1em; color:black; margin-top:15px;">VIJAY DEVERAKONDA</h1>
      <p style="color:black; margin-bottom:0; font-size:1.5em; background-color:azure;">General Manager</p>
    </div>

    <div style="background-color:#f4c005; border-radius:10px; text-align:center; padding:20px; width:90%;">
      <img src="soori.avif" style="border-radius:50% / 35%; width:100%; height:250px; object-fit:cover;">
      <h1 style="font-size:1em; color:black; margin-top:15px;">SOORI</h1>
      <p style="color:black; margin-bottom:0; font-size:1.5em; background-color:azure;">Executive Chef</p>
    </div>

    <div style="background-color:#f4c005; border-radius:10px; text-align:center; padding:20px; width:90%;">
      <img src="sp.jpeg" style="border-radius:50% / 35%; width:100%; height:250px; object-fit:cover;">
      <h1 style="font-size:1em; color:black; margin-top:15px;">SAI PALLAVI</h1>
      <p style="color:black; margin-bottom:0; font-size:1.5em; background-color:azure;">Finance Manager</p>
    </div>

    <div style="background-color:#f4c005; border-radius:10px; text-align:center; padding:20px; width:90%;">
      <img src="ds.jpg" style="border-radius:50% / 35%; width:100%; height:250px; object-fit:cover;">
      <h1 style="font-size:1em; color:black; margin-top:15px;">DULQUER SALMAN</h1>
      <p style="color:black; margin-bottom:0; font-size:1.5em; background-color:azure;">Marketing Manager</p>
    </div>
     <div style="background-color:#f4c005; border-radius:10px; text-align:center; padding:20px; width:90%;">
      <img src="S.jpg" style="border-radius:50% / 35%; width:100%; height:250px; object-fit:cover;">
      <h1 style="font-size:1em; color:black; margin-top:15px;">MRUNAL THAKUR</h1>
      <p style="color:black; margin-bottom:0; font-size:1.5em; background-color:azure;">HR</p>
    </div>
</body>
</html>
    
contact.html

<html>
<head>
  <title>Contact</title>
</head>
<body style="margin:0; font-family:'Times New Roman', Times, serif; background-image:url('r5.jpg'); background-size:cover; width:1470px; height:680px; color:black; padding:20px;">

  <div style="width:550px; height:25px; border:2px solid rgb(239, 233, 233); padding:10px; background-color:white; text-align:center; font-weight:bold; position:relative; top:5px; left:900px; word-spacing:70px;">
    <a href="home.html">HOME</a>
    <a href="menu.html">MENU</a>
    <a href="admin.html">ADMIN</a>
    <a href="contact.html">CONTACT</a>
  </div>

  <div style="color:rgb(238, 235, 235); font-family:Verdana; text-align:center; position:relative; font-weight:bold; top:-50px;">
    <h1><b>CONTACT</b></h1>
  </div>

  <div style="color:rgb(228, 223, 223); font-family:'Times New Roman'; position:relative; top:-10px; text-align:center; font-weight:bold;">
    <h1>Reach The Flavor Fusion:</h1>
    <p>MMDA COLONY<br>Arumbakkam<br>Chennai-600106</p>
    <br>
    <h1>Contact us:</h1>
    <p>+91 8889991112</p>
    <br>
    <h1>Email Id:</h1>
    <p>theflavorfusion@gmail.com</p>
  </div>

</body>
</html>
```

## OUTPUT:
<img width="1035" height="504" alt="Screenshot 2025-12-22 225420" src="https://github.com/user-attachments/assets/95a66666-ef7c-4cb6-96e8-7dbfd44208b2" />
<img width="1036" height="547" alt="Screenshot 2025-12-22 225434" src="https://github.com/user-attachments/assets/ad179ddc-1302-436d-8bbe-f6d07bd87441" />
<img width="1035" height="554" alt="Screenshot 2025-12-22 225449" src="https://github.com/user-attachments/assets/04647e87-d18a-4518-b500-157adca6f317" />
<img width="1138" height="595" alt="Screenshot 2025-12-22 225505" src="https://github.com/user-attachments/assets/50398396-f4ae-4d20-8e73-1e6334d96bac" />


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
