# Project Responsive Web Design using Bootstrap
## Date:16/10/2025

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
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

### Step 5:
Create a HTML file and include the needed Bootstrap components.

### Step 6:
Publish the website in the LocalHost.

## PROGRAM :
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Dribbble</title>

  <link
    href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css"
    rel="stylesheet"
  />

  <link
    href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.1/font/bootstrap-icons.css"
    rel="stylesheet"
  />
</head>
<body>

  <nav class="navbar navbar-expand-lg bg-light shadow-sm sticky-top">
    <div class="container">
      <a class="navbar-brand fw-bold text-danger" href="#">Dribble-Dhanyamala Gokul Kumar(25011343)</a>
      <button
        class="navbar-toggler"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navbarNav"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse justify-content-end" id="navbarNav">
        <ul class="navbar-nav align-items-center">
          <li class="nav-item"><a class="nav-link" href="#">Inspiration</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Find Work</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Learn Design</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Go Pro</a></li>
          <li class="nav-item ms-3">
            <button class="btn btn-dark btn-sm">Sign Up</button>
          </li>
        </ul>
      </div>
    </div>
  </nav>

  <section class="text-center py-5 bg-light">
    <div class="container">
      <h1 class="fw-bold mb-3">Discover the world’s top designers & creatives</h1>
      <p class="text-secondary mb-4">
        Dribbble is the leading destination to find & showcase creative work and home to the world's best design professionals.
      </p>
      <button class="btn btn-danger px-4 py-2">Sign up to get started</button>
    </div>
  </section>
 
  <section class="py-5">
    <div class="container">
      <h2 class="text-center fw-bold mb-4">Trending Shots</h2>
      <div class="row g-4">
        <div class="col-md-4 col-sm-6">
          <div class="card border-0 shadow-sm">
            <img src="https://picsum.photos/400/300?random=1" class="card-img-top" alt="Design 1" />
            <div class="card-body">
              <h5 class="card-title">Creative UI Concept</h5>
              <p class="text-muted">by Designer A</p>
            </div>
          </div>
        </div>
        <div class="col-md-4 col-sm-6">
          <div class="card border-0 shadow-sm">
            <img src="https://picsum.photos/400/300?random=2" class="card-img-top" alt="Design 2" />
            <div class="card-body">
              <h5 class="card-title">Landing Page Design</h5>
              <p class="text-muted">by Designer B</p>
            </div>
          </div>
        </div>
        <div class="col-md-4 col-sm-6">
          <div class="card border-0 shadow-sm">
            <img src="https://picsum.photos/400/300?random=3" class="card-img-top" alt="Design 3" />
            <div class="card-body">
              <h5 class="card-title">Mobile App Layout</h5>
              <p class="text-muted">by Designer C</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <section class="bg-danger text-white text-center py-5">
    <div class="container">
      <h2 class="fw-bold mb-3">Join the community of talented designers</h2>
      <p class="mb-4">Showcase your work, connect with others, and find opportunities.</p>
      <button class="btn btn-light btn-lg">Join Now</button>
    </div>
  </section>

  <footer class="bg-dark text-white py-4">
    <div class="container text-center">
      <p class="mb-1">&copy; Designed by: Dhanyamala Gokul Kumar(25011343)</p>
      <div>
        <a href="#" class="text-white me-3"><i class="bi bi-twitter"></i></a>
        <a href="#" class="text-white me-3"><i class="bi bi-instagram"></i></a>
        <a href="#" class="text-white"><i class="bi bi-facebook"></i></a>
      </div>
    </div>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>

```

## OUTPUT:
<img width="1914" height="968" alt="image" src="https://github.com/user-attachments/assets/1e5a9088-2ffd-4076-aae9-dcd00e2bdd33" />
<img width="1883" height="920" alt="image" src="https://github.com/user-attachments/assets/204f15b2-e0df-4aba-a2d0-12f25975d684" />


## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
