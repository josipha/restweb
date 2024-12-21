# Ex.07 Restaurant Website
## Date:21.12.2024

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
<!DOCTYPE html>
<html lang="en">

<head>
    <title> FOOD HUB </title>
    <link rel="stylesheet" href="style.css">
    <style>
        img{
            margin-top: 4%;
            margin-bottom: 4%;
            align-self: center;
        }

        body{
            height: 50%
        }
    </style>
</head>

<body>
    <header>
        <div class="header-container">
            <h1> FOOD HUB </h1>
        </div>

        <div class="josh">
            <a href="resta.html">Home</a>
            <a href="menu.html" target="_blank">Menu</a>
            <a href="admin.html" target="_blank">Administration</a>
            <a href="contact.html" target="_blank">Contact Us</a>

        </div>
    </header><br><br><br>
    <center><img src="menu main.jpg" alt=" food hub Logo"></center>
    <section class="banner">
        <h2>Welcome To food hub Restaurant</h2>
        <h1>30% Off This Weekend </h1>

    </section>
    <footer>
        <p>Designed by Josipha</p>
    </footer>

</body>

</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> Menu| FOOD HUB </title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1> Our Menu </h1>
        
    </header>
    <div class="menu-sectionn">
        <h2>Food Items</h2>
        <div class="menu-items">
          <h2>paanipoori</h2>
          <img src="pani puri.jpg" alt="paanipoori" style="width:25%; height: 50%;">
          <h2>pastha</h2>
          <img src="pasta.jpg" alt="pastha" style="width:25% ;height:50%;">
          <h2>noodles</h3>
          <img src="noodles.jpg" alt="noodles" style="width:25%">
          <h2>chicken</h2>
            <img src="chicken.jpg" alt="chicken" style="width:25%">
          <h2>combo checkin</h2>
          <img src="combo chicken.jpg" alt="combo checkin" style="width:25%">
          <h2>veg salet </h2>
          <img src="veg salet.jpg" alt="veg salet" style="width:25%">
          <h2>veg noodles</h2>
          <img src="veg noodles.jpg" alt="veg noodles" style="width:25%">
          <h2>moshroom</h2>
          <img src="mushroom.jpg" alt="mushroom" style="width:25%">
          <h2>fridrice</h2>
          <img src="friedrice.jpg" alt="friedrice" style="width: 25%;height: 30%;">
          <h2>masalpoori</h2>
          <img src="masalpoori.jpg" alt="masalpoori" style="width:25%">
          <h2>meals</h2>
          <img src="meals.jpg" alt="meals" style="width:25%">
          <h2>fishrice</h2>
          <img src="fish.jpg" alt="fishrice" style="width:25%">
      </div>
    </div>
    <footer>
        <p>Designed by Josipha</p>
    </footer>
    
</body>
</html>
!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Administration | FOOD HUB </title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1> Meet our Teem </h1>
    
           
    </header>
    <section class="admin-section">
        <h2>Our Administrators</h2>
            <div class="admin-box">
                <p>Sushmitha - Founder</p>
            </div>
            <div class="admin-box">
               
                <p>Anisha - CO founder</p>
            </div>
            <div class="admin-box">
                
                <p>Jones -  Assistant Manager</p>
            </div>
            <div class="admin-box">
                
                <p> darvin- Sous chef</p>
            </div>
            <div class="admin-box">
               
                <p> Celina- Wait Staff</p>
            </div>
        
    </section>

    <footer>
        <p>Designed by Josipha</p>
    </footer>


    
</body>
</html>
style.css

 {
    margin: 20px;
    padding: 0;tyle.css

    box-sizing: border-box;
    font-family: Arial, sans-serif;
}
h1{
    text-align: center;
    font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
}  


body{ 
        font-family: Arial, sans-serif;
        background-color: white;
        color: #333;
        margin: 0;
        padding: 0;
    
}

header {
    display: flex;
    height: 200px;
    justify-content: space-between;
    align-items: center;
    text-align: center;
    padding: 5px;
    background-color:#430101 ;
    color:white;
    
}


.logo {
    display: block;
    margin: 0 auto;
    width: 550px; 
    height: auto;
    

}

.logo img {
    width: 70px; 
    height: 60px; 
    margin-right: 0; 

}




.nav ul {
    list-style-type:none;
    padding: 0;

    
}

.josh{
   
    width: 1300px;
    display: flex;
    align-items: center;
    gap: 80px;
    font-family: Arial, Helvetica, sans-serif;
    
}

.john a{
    font-size: 30px;
    text-decoration: none;
    color: #f9f9f9;
}

.nav ul li a {
    color: white;
    text-decoration:none;
    font-family: Arial, Helvetica, sans-serif;
}
.title h1 {
    font-size: 30px;
    font-weight: bold;
    position: relative; top: 60px;
    font-family: Georgia, 'Times New Roman', Times, serif;
}
.logo {
     display: flex;  
    align-items:flex-start;
    height: auto;
    width: 20px;
    position: relative; left: -150x;
    margin-bottom: -55px;
    
}
.banner {
    background-image: url('image\ copy.png');
    background-size:cover;
    background-position: center;
    height: 200px;
    width: 1000 px;
     
    text-align: center;
    padding: 50px ;
    color: white;
    font-size: 30px;
    font-family:'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
    border-radius: 20px;
}

.banner h2 {
    font-size: 2.5rem;
}

.banner p {
    margin-top: 10px;
    font-size: 1.2rem; 
 }
.menu-section {
    display: flex;
     justify-content: center;
     padding: 20px;

    
}

.menu-image{
    margin-top: 15px;
    width:200px;
    max-width: 50px; 
    height:auto;
    border-radius: 10px;
    
}



.menu-items{
    width: auto;
    height: auto;
    position: relative;



}

.menu-section {
    display: flex;
    flex-wrap: nowrap; 
    justify-content: space-around;
    align-items: center; 
    width: 100%; 
    height: 150px;
    gap: 20px; 
}

.info-box {
    background-color: blanchedalmond;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    text-align: center;
    width: 30%;
    
    
    display: inline-block;
}

  .menu-items { 
    display:flex;
    flex-direction: column; 
     position: relative;left: -250px;
  } 
   
  .admin-image {
    margin-top: 15px;
    width: 50%;
    max-width: 100px;
    height: 100px;
    border-radius: 10px;
      display: flex; 
     justify-content:space-around;
    flex-wrap: wrap;  
}
.working-image{
    margin-top:15px ;
    width: 50%;
    max-width: 100px;
    height: 111px;
    border-radius: 10px;
}
  .menu-section ul{
    list-style-type: none ;
    padding: 0;
  }
  .menu-section ul li {
    margin: 10px 0;
    font-size: 18px;
  }



  .admin-section {
    display: flex;
    flex-wrap: nowrap;
    width: 100%; 
    margin: 10px 0;
    justify-content: space-around; 
    text-align: center;
    padding: 20px;
}

.admin.person img {
    width: 100px;
    height: 100px;
    border-radius: 50%; 
}

.admin-box {
    margin: 10px;
    text-align: center;
}

.admin-box img {
    width: 150px;
    height: 150px;
    border-radius: 50%; 
}

.contact-section{
    text-align: center;
    padding: 20px;
}
.menu-section {
    display: grid;
    grid-template-columns: repeat(1, 1fr); 
    gap: 20px;
    padding: 20px;
    justify-content: center;
    align-items: start;
}

.menu-section h2 {
    text-align: center;
    font-size: 18px;
}

.menu-items img {
    max-width: 20%; 
    max-height: 100px; 
    border-radius: 10px;
    display: block;
    margin: 10px auto; 
}

.menu-items {
    text-align: center;
    background-color: #f9f9f9;
    padding: 10px;
    border-radius: 10px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}



footer {
    background-color: #430101;
    color: white;
    padding: 10px 0;
    text-align: center;
}