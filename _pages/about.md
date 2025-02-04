---
permalink: /
title:  "Qiu Research Group at UTK"
author_profile: false
redirect_from:
  - /about/
  - /about.html
        
header:
  overlay_image: "../images/mountain.jpg"
  overlay_filter: 0.3
  caption: "Welcome to Qiu Research Group at UTK"
---
<!-- Research Group Description -->
<div style="width: 150%; margin: 0 auto; text-align: center;  margin-left: -25%;">
  <p style="font-size: 24px;">
    We investigate non-equilibrium emergent behaviors in <b>soft matter</b> and <b>biophysics</b> with <b>computer simulations</b>, <b>machine learning techniques</b>, and <b>theory</b>.
  </p>

  <p style="font-size: 24px;">
    We aim to formulate theoretical frameworks that unveil the interplay of activity, force generation, and emergent architectures.
  </p>
</div>

<!-- Research Topics Section -->
<div style="width: 150%; text-align: center; margin-left: -30%;">
  <span style="font-size: 24px; color: lightblue; line-height: 1.5; display: inline-block; width: 100%;">
    • Self-organization in Cytoskeletal Networks • Biological Ice Nucleation  <br>
    • Nucleation in Active Biophysics Systems • Driven Soft Matter and Amorphous Materials <br>
    • Statistical Mechanics • Non-Equilibrium Thermodynamics • Machine Learning  <br>
    • Agent-based Simulations • Coarse-Grained Models • Molecular Dynamics • Kinetic Monte Carlo
  </span>
</div>



<!-- Slideshow Container -->
<div class="slideshow-container" style="margin-top: 22px; text-align: center; position: relative; max-width: 80%; margin-left: auto; margin-right: auto; height: 500px;">

    <!-- Slideshow Content Wrapper -->
    <div style="display: flex; align-items: center; justify-content: center; gap: 20px;">

        <!-- Manual Navigation Buttons (Left) -->
        <button class="prev" onclick="changeSlide(-1)" style="background-color: rgba(0,0,0,0.5); color: white; border: none; padding: 10px 15px; cursor: pointer; font-size: 25px; height: 40px; position: absolute; left: -5%; top: 50%; transform: translateY(-50%); z-index: 2;">❮</button>

        <!-- Images for the slideshow -->
        <div style="position: relative; width: 120%; height: auto; text-align: center;">
            <img src="../images/cyto.svg" class="slide active" alt="Slide 1" style="width: 160%; height: auto; opacity: 1; transition: opacity 1s;">
            <img src="../images/ice.svg" class="slide" alt="Slide 2" style="width: 160%; height: auto; opacity: 0; position: absolute; top: 0; left: 0; transition: opacity 1s;">
               <img src="../images/proposal.svg" class="slide" alt="Slide 2" style="width: 160%; height: auto; opacity: 0; position: absolute; top: 0; left: 0; transition: opacity 1s;">
        </div>

        <!-- Manual Navigation Buttons (Right) -->
        <button class="next" onclick="changeSlide(1)" style="background-color: rgba(0,0,0,0.5); color: white; border: none; padding: 10px 15px; cursor: pointer; font-size: 25px; height: 40px; position: absolute; right: -5%; top: 50%; transform: translateY(-50%); z-index: 2;">❯</button>
    </div>

</div>

<!-- JavaScript for Slideshow -->
<script>
    let currentSlide = 0;
    const slides = document.querySelectorAll(".slide");
    const captions = ["Cytoskeletal Networks", "Bryce Canyon Research", "Cytoskeletal Networks"];
    const slideText = document.getElementById("slide-text");

    function showSlide(index) {
        slides.forEach((slide, i) => {
            slide.style.opacity = (i === index) ? "1" : "0";
        });
        slideText.innerText = captions[index];
    }

    function changeSlide(direction) {
        currentSlide = (currentSlide + direction + slides.length) % slides.length;
        showSlide(currentSlide);
    }

    // Auto-slide every 3 seconds  
    setInterval(() => changeSlide(1), 2000);
</script>

