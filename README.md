# Case Study: Dribble Clone
## Date:02.04.2026

## AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.


## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Design a navigation bar with links: Inspiration, Find Work, Learn Design, Go Pro, Sign In, Sign Up.

### Step 5:
Add a catchy headline with a search bar.

### Step 6:
Use ```<div>``` containers for each dribbble shot thumbnail.

### Step 7:
Include designer name and likes count below each image.

### Step 8:
Include text like “Find your next design inspiration” with a button (“Join Dribbble” or “Explore”).

### Step 9:
Create a footer with your name and register number.

### Step 10:
Publish the website in the LocalHost.

## PROGRAM :

~~~
<html lang="en">
<head>
    <title>Dribbble Clone</title>

    
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
</head>

<body>


<nav class="navbar navbar-expand-lg navbar-dark bg-dark">
  <div class="container">
    <a class="navbar-brand" href="#">Dribbble</a>

    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#nav">
      <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="nav">
      <ul class="navbar-nav me-auto">
        <li class="nav-item"><a class="nav-link active">Shots</a></li>
        <li class="nav-item"><a class="nav-link">Designers</a></li>
        <li class="nav-item"><a class="nav-link">Teams</a></li>
        <li class="nav-item"><a class="nav-link">Jobs</a></li>
      </ul>

      <form class="d-flex">
        <input class="form-control me-2" type="search" placeholder="Search">
        <button class="btn btn-outline-light">Search</button>
      </form>

      <button class="btn btn-light ms-2">Sign in</button>
      <button class="btn btn-danger ms-2">Sign up</button>
    </div>
  </div>
</nav>


<div class="container text-center mt-5">
    <h1>Find your next design inspiration</h1>
    <p class="text-muted">Dribbble is show and tell for designers</p>
    <button class="btn btn-danger">Explore</button>
</div>


<div class="container mt-5">
  <div class="row">

    
    <div class="col-md-4 mb-4">
      <div class="card">
        <img src="image1.png" class="card-img-top">
        <div class="card-body">
          <h6 class="card-title">UI Design</h6>
          <p class="card-text">❤️ 120 Likes</p>
        </div>
      </div>
    </div>

   
    <div class="col-md-4 mb-4">
      <div class="card">
        <img src="image2.png" class="card-img-top">
        <div class="card-body">
          <h6 class="card-title">App Design</h6>
          <p class="card-text">❤️ 95 Likes</p>
        </div>
      </div>
    </div>

  
    <div class="col-md-4 mb-4">
      <div class="card">
        <img src="image3.png" class="card-img-top">
        <div class="card-body">
          <h6 class="card-title">Web Design</h6>
          <p class="card-text">❤️ 150 Likes</p>
        </div>
      </div>
    </div>

  </div>
</div>


<footer class="bg-dark text-white text-center p-3 mt-5">
    Created by Arunachalam V
</footer>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>

</body>
</html>
~~~

## OUTPUT:

<img width="1920" height="1080" alt="Screenshot (24)" src="https://github.com/user-attachments/assets/ee1d977a-371f-4042-97b6-becc6fcc830a" />



## RESULT:
The project for responsive web design in creating a clone of dribble.com is completed successfully.
