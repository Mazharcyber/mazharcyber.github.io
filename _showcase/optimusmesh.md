---
title: "OptimusMesh: Autoregressive Mesh Generation from Point Clouds"
show: true
group: "Featured Projects"
width: 12
date: 2026-01-01
---

<div class="card-body">

  <h3 class="mb-3">OptimusMesh</h3>

  <!-- 🔥 Carousel (3D Models + Images) -->
  <div id="optimusCarousel" class="carousel slide mb-4" data-ride="carousel">

    <!-- Indicators -->
    <ol class="carousel-indicators">
      <li data-target="#optimusCarousel" data-slide-to="0" class="active"></li>
      <li data-target="#optimusCarousel" data-slide-to="1"></li>
      <li data-target="#optimusCarousel" data-slide-to="2"></li>
      <li data-target="#optimusCarousel" data-slide-to="3"></li>
      <li data-target="#optimusCarousel" data-slide-to="4"></li>
    </ol>

    <!-- Slides -->
    <div class="carousel-inner rounded">

      <!-- Model 1 -->
      <div class="carousel-item active">
        <iframe 
          width="100%" height="420"
          src="https://sketchfab.com/models/176bc348b500424a967fd6d57753368c/embed"
          frameborder="0" allow="autoplay; fullscreen; vr">
        </iframe>
      </div>

      <!-- Model 2 -->
      <div class="carousel-item">
        <iframe 
          width="100%" height="420"
          src="https://sketchfab.com/models/723fa2d3f5614cd7900ba124a06e9c29/embed"
          frameborder="0" allow="autoplay; fullscreen; vr">
        </iframe>
      </div>

      <!-- Model 3 -->
      <div class="carousel-item">
        <iframe 
          width="100%" height="420"
          src="https://sketchfab.com/models/99115d99c77a4e40a57e040fba3c042e/embed"
          frameborder="0" allow="autoplay; fullscreen; vr">
        </iframe>
      </div>

      <!-- Model 4 -->
      <div class="carousel-item">
        <iframe 
          width="100%" height="420"
          src="https://sketchfab.com/models/65118724718e4f9282df63947159f2c8/embed"
          frameborder="0" allow="autoplay; fullscreen; vr">
        </iframe>
      </div>

      <!-- Pipeline Image (optional but STRONG) -->
      <div class="carousel-item">
        <img src="{{ '/assets/images/fig1.png' | relative_url }}" 
             class="d-block w-100" 
             style="max-height: 420px; object-fit: contain;">
      </div>

    </div>

    <!-- Controls -->
    <a class="carousel-control-prev" href="#optimusCarousel" role="button" data-slide="prev">
      <span class="carousel-control-prev-icon"></span>
    </a>
    <a class="carousel-control-next" href="#optimusCarousel" role="button" data-slide="next">
      <span class="carousel-control-next-icon"></span>
    </a>

  </div>

  <!-- 🔥 Description -->
  <p>
    <strong>OptimusMesh</strong> is a research project focused on generating compact and high-quality triangle meshes 
    directly from point clouds using autoregressive modeling and sparse latent pivots.
  </p>

  <p>
    The method learns structured 3D representations and generates mesh geometry through transformer-based decoding, 
    enabling efficient and scalable 3D content generation.
  </p>

  <p>
    <strong>Key Areas:</strong> 3D Computer Vision, Generative AI, Geometric Deep Learning
  </p>

  <p>
    <strong>Applications:</strong> Robotics, 3D Scene Understanding, VR/AR, Game Development, Digital Content Creation
  </p>

</div>
