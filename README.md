# Project Responsive Web Design using Bootstrap
## Date:25.12.2024
## AIM:
To creae a simplified clone of Dribbble (https://dribbble.com/) landing page.


## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

### Step 5:
Create a HTML file and include the needed Bootstrap components.

### Step 6:
Publish the website in the LocalHost.

## PROGRAM :
Homepage
```
<html>
    <head>
        <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
        <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
    </head>
    <body class="text-center">
        <nav class="navbar navbar-expand-lg navbar-light bg-warning">
            <div class="container-fluid">
                <a class="navbar-brand text-dark" href="#">PHARMACY COMPANY</a>
                
                <div class="collapse navbar-collapse" id="navbarNav">
                    <ul class="navbar-nav d-flex">
                        <li class="nav-item " >
                            <a class="nav-link text-white" href="C:\Users\admin\home.html">HOME</a>
                        </li>
                        <li class="nav-item ">
                            <a class="nav-link text-white" href="C:\Users\admin\product.html">PRODUCTS</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link text-white" href="C:\Users\admin\about.html">ABOUT</a>
                        </li>
                    </ul>
                </div>
            </div>
        </nav>
        <h1>DEEPSHIKA PHARMACY</h1>
        <img src="pharm logo.jpg">

<footer class="bg-light text-center py-3">
<p>Designed and Developed by Deepshika Hemanth kumar</p>
</footer>




</body>
</html>
```
Product page
```
<html>
    <head>
        <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
        <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
    </head>
    <body>
        <nav class="navbar navbar-expand-lg navbar-light bg-warning">
            <div class="container-fluid">
                <a class="navbar-brand text-dark" href="#">PHARMACY COMPANY</a>
                
                <div class="collapse navbar-collapse" id="navbarNav">
                    <ul class="navbar-nav d-flex">
                        <li class="nav-item " >
                            <a class="nav-link text-white" href="C:\Users\admin\home.html">HOME</a>
                        </li>
                        <li class="nav-item ">
                            <a class="nav-link text-white" href="C:\Users\admin\product.html">PRODUCTS</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link text-white" href="C:\Users\admin\about.html">ABOUT</a>
                        </li>
                    </ul>
                </div>
            </div>
        </nav>
       
        <div class="row">
            <div class="col-12">
                <h2>Contact Us</h2>
                <form>
                    <div class="form-group">
                        <label for="name">Your Name</label>
                        <input type="text" class="form-control" id="name" placeholder="Enter your name">
                    </div>
                    <div class="form-group">
                        <label for="email">Email address</label>
                        <input type="email" class="form-control" id="email" placeholder="Enter email">
                    </div>
                    <div class="form-group">
                        <label for="message">Message</label>
                        <textarea class="form-control" id="message" rows="3" placeholder="Your message"></textarea>
                    </div>
                    <button type="submit" class="btn btn-primary">Submit</button>
                </form>
            </div>
        </div>
    </div>
    <footer class="bg-light text-center py-3">
        <p>Designed and Developed by Deepshika Hemanth Kumar</p>
    </footer>

    
        
        
    </body>

</html>
```
About page
```
<html>
    <head>
        <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
        <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
    </head>
    <body>
        <nav class="navbar navbar-expand-lg navbar-light bg-success">
            <div class="container-fluid">
                <a class="navbar-brand text-dark" href="C:\Users\Sashmitha sree\Documents\SEM 1\web app\Practise code\homeweb.html">PHARMACY COMPANY</a>
                
                <div class="collapse navbar-collapse" id="navbarNav">
                    <ul class="navbar-nav d-flex">
                        <li class="nav-item " >
                            <a class="nav-link text-white" href=" C:\Users\Sashmitha sree\Documents\SEM 1\web app\Practise code\pharhome.html">HOME</a>
                        </li>
                        <li class="nav-item ">
                            <a class="nav-link text-white" href="C:\Users\Sashmitha sree\Documents\SEM 1\web app\Practise code\boot2.html">PRODUCTS</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link text-white" href="C:\Users\Sashmitha sree\Documents\SEM 1\web app\Practise code\about.html">ABOUT</a>
                        </li>
                    </ul>
                </div>
            </div>
        </nav>
        <nav class="navbar navbar-expand-lg navbar-light bg-light">
           
                <p class="Toggle text">
                    About Us<br>

                    Welcome to Deepshika Pharmacy, your trusted partner in health and wellness. Established in 2020, we are committed to delivering exceptional pharmaceutical care, personalized service, and expert guidance to enhance the well-being of our valued customers.           
<br><br><br>
Who We Are<br>
At Deepshika Pharmacy, we are more than just a pharmacy—we are a dedicated team of healthcare professionals devoted to improving lives. Our staff includes licensed pharmacists, knowledgeable technicians, and a friendly support team who are passionate about meeting your healthcare needs with professionalism and care.<br><br><br>
Our Mission<br>
Our mission is to provide reliable, affordable, and accessible healthcare solutions tailored to each individual. We are dedicated to building trust and long-term relationships by consistently exceeding expectations and prioritizing your health above all else<br><br><br>
What We Offer<br>
Prescription Services: Fast, accurate prescription filling with expert guidance.
Over-the-Counter Products: A comprehensive range of health and wellness items, including vitamins, supplements, and personal care essentials.
Consultation Services: One-on-one consultations for medication management, health screenings, and wellness advice.
Home Delivery: Convenient, timely delivery of medications directly to your doorstep.
<br><br><br>Why Choose Us?<br>
Customer-Centric Care: Your health and satisfaction are our top priorities.
Expert Guidance: Our pharmacists provide personalized advice to help you make informed healthcare decisions.
Quality Assurance: We adhere to the highest standards of safety and quality in every service we offer.
<br><br><br>Our Vision<br>
At Deepshika Pharmacy, we envision a healthier future where everyone has access to exceptional pharmaceutical care. By embracing innovation and staying ahead in the healthcare industry, we aim to be your lifelong partner in health and wellness.<br><br><br>
                </p>
            </div>
        </nav>
        <footer class="bg-light text-center py-3">
            <p>Designed and Developed by Deepshika Hemanth kumar</p>
        </footer>
    </body>

</html>
```
## OUTPUT:
![alt text](<Screenshot 2024-12-25 144105.png>)
![alt text](<Screenshot 2024-12-25 143746.png>)
![alt text](<Screenshot 2024-12-25 143657.png>)
![alt text](<Screenshot 2024-12-25 143709.png>)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
