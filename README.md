<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>My Awesome Website</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
  <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css" rel="stylesheet">
</head>
<body>

<!-- Navigation -->
<nav class="navbar navbar-expand-lg navbar-dark bg-primary fixed-top">
  <div class="container">
    <a class="navbar-brand fw-bold" href="#"><i class="fas fa-rocket"></i> MySite</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav ms-auto">
        <li class="nav-item"><a class="nav-link" href="#home">Home</a></li>
        <li class="nav-item"><a class="nav-link" href="#about">About</a></li>
        <li class="nav-item"><a class="nav-link" href="#services">Services</a></li>
        <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
      </ul>
    </div>
  </div>
</nav>

<!-- Hero Section -->
<section id="home" class="bg-primary text-white py-5 mb-5">
  <div class="container py-5">
    <div class="row align-items-center min-vh-100">
      <div class="col-lg-6">
        <h1 class="display-4 fw-bold mb-4 animate__animated animate__fadeInUp">Welcome to My Awesome Website</h1>
        <p class="lead mb-4">Build modern, responsive websites with Bootstrap 5. Fast, beautiful, and mobile-first.</p>
        <div class="d-flex gap-3">
          <a href="#services" class="btn btn-light btn-lg">Get Started</a>
          <a href="#contact" class="btn btn-outline-light btn-lg">Learn More</a>
        </div>
      </div>
      <div class="col-lg-6 text-center">
        <i class="fas fa-laptop-code fa-10x opacity-75"></i>
      </div>
    </div>
  </div>
</section>

<!-- About Section -->
<section id="about" class="py-5">
  <div class="container">
    <div class="row">
      <div class="col-lg-8 mx-auto text-center">
        <h2 class="display-5 fw-bold mb-4">About Us</h2>
        <p class="lead mb-5">This is a fully responsive single-page website built with Bootstrap 5.3.3. It includes navbar, hero, features, testimonials, and contact form - all ready to deploy!</p>
      </div>
    </div>
    <div class="row g-4">
      <div class="col-md-4">
        <div class="card h-100 border-0 shadow-sm">
          <div class="card-body text-center p-5">
            <i class="fas fa-code fa-3x text-primary mb-3"></i>
            <h5 class="card-title">Modern Design</h5>
            <p class="card-text">Clean, professional design using latest Bootstrap components.</p>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card h-100 border-0 shadow-sm">
          <div class="card-body text-center p-5">
            <i class="fas fa-mobile-alt fa-3x text-success mb-3"></i>
            <h5 class="card-title">Fully Responsive</h5>
            <p class="card-text">Works perfectly on desktop, tablet, and mobile devices.</p>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card h-100 border-0 shadow-sm">
          <div class="card-body text-center p-5">
            <i class="fas fa-bolt fa-3x text-warning mb-3"></i>
            <h5 class="card-title">Lightning Fast</h5>
            <p class="card-text">Optimized CDN delivery with minimal load times.</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- Services Section -->
<section id="services" class="bg-light py-5">
  <div class="container">
    <div class="row">
      <div class="col-lg-8 mx-auto text-center">
        <h2 class="display-5 fw-bold mb-5">Our Services</h2>
      </div>
    </div>
    <div class="row g-4">
      <div class="col-lg-4 col-md-6">
        <div class="card h-100 border-0 shadow">
          <div class="card-body p-4">
            <h5 class="card-title text-primary"><i class="fas fa-shield-alt"></i> Web Security</h5>
            <p class="card-text">Penetration testing and security assessments for your web applications.</p>
          </div>
        </div>
      </div>
      <div class="col-lg-4 col-md-6">
        <div class="card h-100 border-0 shadow">
          <div class="card-body p-4">
            <h5 class="card-title text-success"><i class="fas fa-search"></i> Reconnaissance</h5>
            <p class="card-text">Comprehensive OSINT and reconnaissance services.</p>
          </div>
        </div>
      </div>
      <div class="col-lg-4 col-md-6">
        <div class="card h-100 border-0 shadow">
          <div class="card-body p-4">
            <h5 class="card-title text-info"><i class="fas fa-tools"></i> Pentesting</h5>
            <p class="card-text">Full penetration testing with detailed reporting.</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- Contact Section -->
<section id="contact" class="py-5">
  <div class="container">
    <div class="row justify-content-center">
      <div class="col-lg-8">
        <div class="card shadow-lg border-0">
          <div class="card-body p-5">
            <h2 class="text-center mb-5">Get In Touch</h2>
            <form>
              <div class="row g-3">
                <div class="col-md-6">
                  <input type="text" class="form-control" placeholder="Your Name" required>
                </div>
                <div class="col-md-6">
                  <input type="email" class="form-control" placeholder="your@email.com" required>
                </div>
                <div class="col-12">
                  <textarea class="form-control" rows="5" placeholder="Your Message..." required></textarea>
                </div>
                <div class="col-12 text-center">
                  <button type="submit" class="btn btn-primary btn-lg px-5">Send Message</button>
                </div>
              </div>
            </form>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- Footer -->
<footer class="bg-dark text-white py-4 mt-5">
  <div class="container">
    <div class="row">
      <div class="col-md-6">
        <h5><i class="fas fa-rocket"></i> MySite</h5>
        <p>© 2026 All rights reserved. Built with Bootstrap 5.</p>
      </div>
      <div class="col-md-6 text-md-end">
        <a href="#" class="text-white me-3"><i class="fab fa-github"></i></a>
        <a href="#" class="text-white me-3"><i class="fab fa-twitter"></i></a>
        <a href="#" class="text-white"><i class="fab fa-linkedin"></i></a>
      </div>
    </div>
  </div>
</footer>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>
</body>
</html>
