# Project Responsive Web Design using Bootstrap
# Name: SARAVANA KUMAR S
# Reg no: 212224220090
# Date:15-12-2024
# AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.

# DESIGN STEPS:
## Step 1:
Clone the repository from GitHub.

## Step 2:
Create Django Admin project.

## Step 3:
Create a New App under the Django Admin project.

## Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

## Step 5:
Create a HTML file and include the needed Bootstrap components.

## Step 6:
Publish the website in the LocalHost.

# PROGRAM :
```Home page
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Creative O</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">
</head>
<body>
<nav class="navbar navbar-expand-lg navbar-light bg-light shadow-light">
  <div class="container">
    <a class="navbar-brand text-primary" href="#"><strong>Creative O</strong></a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav ms-auto">
        <li class="nav-item">
          <a class="nav-link text-dark active" href="#">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link text-dark" href="#">Shots</a>
        </li>
        <li class="nav-item">
          <a class="nav-link text-dark" href="file:///C:/Users/admin/Desktop/VS%20CODE/designer.html">Designers</a>
        </li>
        <li class="nav-item">
          <a class="nav-link text-dark" href="file:///C:/Users/admin/Desktop/VS%20CODE/sign%20up.html">Sign Up</a>
        </li>
      </ul>
    </div>
  </div>
</nav>
<section class="text-center text-white" style="background-image: linear-gradient(to bottom right, #5c67f5, #7091ff); padding: 100px 0;">
  <div class="container">
    <h1 style="font-weight: bold; font-size: 2.5rem;">Discover the World’s Top Designers & Creatives</h1>
    <p style="font-size: 1.1rem;">Join the Creative O community to showcase your work, inspire others, and find design inspiration.</p>
    <a href="#" class="btn btn-primary btn-lg mt-3">Get Started</a>
  </div>
</section>
<section class="featured-section">
  <div class="container">
    <h2 class="text-center text-primary mb-5">Featured UI/UX Shots</h2>
    <div class="row">
      <div class="col-md-4 mb-4">
        <div class="card border-light shadow">
          <img src="creative img.jpg" class="card-img-top" alt="Shot 1">
          <div class="card-body">
            <h5 class="card-title text-primary">Creative App Interface</h5>
            <p class="card-text text-secondary">A brief description of the app interface design.</p>
          </div>
        </div>
      </div>
      <div class="col-md-4 mb-4">
        <div class="card border-light shadow">
          <img src="Modern Dashboard UI.webp" class="card-img-top" alt="Shot 2">
          <div class="card-body">
            <h5 class="card-title text-info">Modern Dashboard UI</h5>
            <p class="card-text text-secondary">A sleek, modern dashboard design for data visualization.</p>
          </div>
        </div>
      </div>
      <div class="col-md-4 mb-4">
        <div class="card border-light shadow">
          <img src="e commerce.jpg" class="card-img-top" alt="Shot 3">
          <div class="card-body">
            <h5 class="card-title text-success">E-commerce Web Design</h5>
            <p class="card-text text-secondary">An attractive e-commerce landing page for a smooth user experience.</p>
          </div>
        </div>
      </div>
      <div class="col-md-4 mb-4">
        <div class="card border-light shadow">
          <img src="freelance.jpg" class="card-img-top" alt="Shot 3">
          <div class="card-body">
            <h5 class="card-title text-success">Freelance web designers</h5>
            <p class="card-text text-secondary">A freelance developer works with clients, businesses, or organizations on a contract or project basis to make apps or websites, test them, and put them online</p>
          </div>
        </div>
      </div>
      <div class="col-md-4 mb-4">
        <div class="card border-light shadow">
          <img src="agency.jpg" class="card-img-top" alt="Shot 3">
          <div class="card-body">
            <h5 class="card-title text-success">Agency Web Designers</h5>
            <p class="card-text text-secondary">An agency website is a digital platform representing a business that provides professional services to other businesses or individuals. </p>
          </div>
        </div>
      </div>
      <div class="col-md-4 mb-4">
        <div class="card border-light shadow">
          <img src="in home.png" class="card-img-top" alt="Shot 3">
          <div class="card-body">
            <h5 class="card-title text-success">In-house Web Designers.</h5>
            <p class="card-text text-secondary">In-house designers are graphic designers who work directly for your company or organization, as part of your staff.</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>
<footer class="footer text-white" style="background-color: #333; padding: 30px 0; text-align: center;">
  <div class="container">
    <p>&copy; 2024 Creative O. All rights reserved.</p>
    <p>Created by Bala B</p>
    <p>
      <a href="#" style="color: #b5b5b5;">Privacy Policy</a> |
      <a href="#" style="color: #b5b5b5;">Terms of Service</a>
    </p>
  </div>
</footer>
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```
``` designer page
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Famous Web Designers and Their Works</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f9;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #2094dc;
            color: white;
            padding: 20px 0;
            text-align: center;
        }
        header h1 {
            margin: 0;
        }
        .container {
            width: 90%;
            margin: 20px auto;
            max-width: 1200px;
        }
        section {
            margin-bottom: 40px;
        }
        h2 {
            font-size: 24px;
            color: #2094dc;
            border-bottom: 2px solid #4CAF50;
            padding-bottom: 10px;
        }
        .designer {
            display: flex;
            flex-wrap: wrap;
            margin-top: 20px;
        }
        .designer-card {
            background-color: white;
            padding: 20px;
            margin: 10px;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            width: calc(33% - 20px);
            box-sizing: border-box;
            text-align: center;
        }
        .designer-card img {
            width: 100%;
            border-radius: 8px;
        }
        .designer-card h3 {
            margin-top: 15px;
            font-size: 20px;
            color:#2094dc;
        }
        .designer-card p {
            color: #666;
        }
        .works {
            margin-top: 10px;
        }
        .works a {
            color: #4CAF50;
            text-decoration: none;
            font-weight: bold;
        }
        .works a:hover {
            text-decoration: underline;
        }
        footer {
            background-color: #2094dc;
            color: white;
            text-align: center;
            padding: 15px;
            margin-top: 40px;
        }
    </style>
</head>
<body>

    <header>
        <h1>Designers</h1>
    </header>

    <div class="container">
        <section>
            <h2>Top Web Designers</h2>

            <div class="designer">
                <div class="designer-card">
                    <img src="Jeffrey Zeldman.jpg" alt="Designer 1 Image">
                    <h3>Jeffrey Zeldman</h3>
                    <p>Jeffrey Zeldman is a pioneer in web design and a strong advocate for web standards. He is the founder of A List Apart, a popular design and development publication.</p>
                    <div class="works">
                        <p>Notable Works: <a href="https://alistapart.com/" target="_blank">A List Apart</a>, <a href="https://www.zeldman.com/" target="_blank">Zeldman.com</a></p>
                    </div>
                </div>
                <div class="designer-card">
                    <img src="Chris Coyier.jpg" alt="Designer 2 Image">
                    <h3>Chris Coyier</h3>
                    <p>Chris Coyier is the founder of CSS-Tricks, a go-to resource for front-end web development, and he has contributed significantly to the web design community.</p>
                    <div class="works">
                        <p>Notable Works: <a href="https://css-tricks.com/" target="_blank">CSS-Tricks</a>, <a href="https://codepen.io/chriscoyier" target="_blank">Chris on CodePen</a></p>
                    </div>
                </div>
                <div class="designer-card">
                    <img src="lukewroblewski.jpg" alt="Designer 3 Image">
                    <h3>Luke Wroblewski</h3>
                    <p>Luke Wroblewski is a web designer and product strategist best known for his work on mobile-first design and user experience.</p>
                    <div class="works">
                        <p>Notable Works: <a href="https://www.lukew.com/" target="_blank">LukeW</a>, <a href="https://www.amazon.com/Designing-Interface-Elements-Luke-Wroblewski/dp/0321683682" target="_blank">Designing for Mobile</a></p>
                    </div>
                </div>
            </div>
        </section>

        <section>
            <h2>More Famous Designers</h2>

            <div class="designer">
                <div class="designer-card">
                    <img src="rachel-andrew.avif" alt="Designer 4 Image">
                    <h3>Rachel Andrew</h3>
                    <p>Rachel Andrew is a front-end developer and web designer, widely recognized for her expertise in CSS Grid and modern web layout techniques.</p>
                    <div class="works">
                        <p>Notable Works: <a href="https://rachelandrew.co.uk/" target="_blank">Rachel Andrew Blog</a>, <a href="https://a11y-project.com/" target="_blank">A11y Project</a></p>
                    </div>
                </div>
                <div class="designer-card">
                    <img src="Tim-Brown-600x600-1.jpg" alt="Designer 5 Image">
                    <h3>Tim Brown</h3>
                    <p>Tim Brown is known for his work in web typography and as a key figure in developing Google Fonts. He advocates for high-quality typography on the web.</p>
                    <div class="works">
                        <p>Notable Works: <a href="https://timknewton.design/" target="_blank">Tim Brown Design</a>, <a href="https://fonts.google.com/" target="_blank">Google Fonts</a></p>
                    </div>
                </div>
                <div class="designer-card">
                    <img src="jensimmons.jpg" alt="Designer 6 Image">
                    <h3>Jen Simmons </h3>
                    <p>Jen Simmons is a design advocate at Mozilla and one of the major contributors to the development and popularization of CSS Grid Layout.</p>
                    <div class="works">
                        <p>Notable Works: <a href="https://jensimmons.com/" target="_blank">Jen Simmons Blog</a>, <a href="https://www.youtube.com/watch?v=Y5VhHZddX2o" target="_blank">CSS Grid Video</a></p>
                    </div>
                </div>
            </div>
        </section>
    </div>
    <footer>
        <p>&copy; 2024 Famous Web Designers. All rights reserved.</p>
    </footer>
</body>
</html>

```
``` sign up page
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Creative O - Sign Up</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f9;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }
        .container {
            background-color: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            width: 300px;
        }
        h1 {
            text-align: center;
            font-size: 24px;
            color:  #2094dc;
            margin-bottom: 20px;
        }
        h2 {
            text-align: center;
            margin-bottom: 20px;
            font-size: 18px;
            color: #333;
        }
        label {
            font-weight: bold;
            margin-bottom: 8px;
            display: block;
        }
        input {
            width: 100%;
            padding: 10px;
            margin: 8px 0;
            border: 1px solid #ddd;
            border-radius: 4px;
            font-size: 16px;
        }
        input[type="submit"] {
            background-color:  #2094dc;
            color: white;
            border: none;
            cursor: pointer;
        }
        input[type="submit"]:hover {
            background-color: #2094dc;
        }
        .error-message {
            color: red;
            font-size: 12px;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Creative O</h1> 
        <h2>Sign Up</h2>
        <form action="/submit" method="POST">
            <div>
                <label for="name">Full Name</label>
                <input type="text" id="name" name="name" required placeholder="John Doe">
                <div class="error-message" id="name-error"></div>
            </div>
            <div>
                <label for="email">Email Address</label>
                <input type="email" id="email" name="email" required placeholder="example@mail.com">
                <div class="error-message" id="email-error"></div>
            </div>
            <div>
                <label for="password">Password</label>
                <input type="password" id="password" name="password" required placeholder="********">
                <div class="error-message" id="password-error"></div>
            </div>
            <div>
                <label for="confirm-password">Confirm Password</label>
                <input type="password" id="confirm-password" name="confirm-password" required placeholder="********">
                <div class="error-message" id="confirm-password-error"></div>
            </div>
            <div>
                <input type="submit" value="Sign Up">
            </div>
        </form>
    </div>

    <script>
        const form = document.querySelector('form');
        form.addEventListener('submit', function(event) {
            let valid = true;
            document.querySelector('#name-error').textContent = '';
            document.querySelector('#email-error').textContent = '';
            document.querySelector('#password-error').textContent = '';
            document.querySelector('#confirm-password-error').textContent = '';
            const name = document.querySelector('#name').value;
            if (name.trim() === '') {
                valid = false;
                document.querySelector('#name-error').textContent = 'Full Name is required.';
            }
            const email = document.querySelector('#email').value;
            const emailPattern = /^[a-zA-Z0-9._%+-]+@[a-zA-Z0-9.-]+\.[a-zA-Z]{2,}$/;
            if (!emailPattern.test(email)) {
                valid = false;
                document.querySelector('#email-error').textContent = 'Please enter a valid email address.';
            }
            const password = document.querySelector('#password').value;
            if (password.length < 6) {
                valid = false;
                document.querySelector('#password-error').textContent = 'Password must be at least 6 characters long.';
            }
            const confirmPassword = document.querySelector('#confirm-password').value;
            if (confirmPassword !== password) {
                valid = false;
                document.querySelector('#confirm-password-error').textContent = 'Passwords do not match.';
            }
            if (!valid) {
                event.preventDefault();
            }
        });
    </script>
</body>
</html>

```
# OUTPUT:
![Screenshot 2024-12-25 141937](https://github.com/user-attachments/assets/476685da-3ae6-4a71-ba72-61b8c2d8c8ec)
![Screenshot 2024-12-25 142006](https://github.com/user-attachments/assets/008f570b-29a8-4e77-850a-19db4e19cf7d)
![Screenshot 2024-12-25 142030](https://github.com/user-attachments/assets/4b49d449-2086-409b-b5c6-084911841b5a)
![Screenshot 2024-12-25 142047](https://github.com/user-attachments/assets/02632f8b-c491-45af-9ee6-7117af60d4ce)
![Screenshot 2024-12-25 142109](https://github.com/user-attachments/assets/a88bccb4-49c0-4e0b-9822-8e1ea10748d8)


# RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
