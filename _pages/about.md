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
<div style="max-width: 900px; margin: 0 auto; text-align: center; padding: 20px;">
  <p style="font-size: 22px; font-weight: 500; line-height: 1.6;">
    We investigate non-equilibrium emergent behaviors in <b>soft matter</b> and <b>biophysics</b> with <b>computer simulations</b>, <b>machine learning techniques</b>, and <b>theory</b>.
  </p>
  <p style="font-size: 22px; font-weight: 500; line-height: 1.6;">
    Our goal is to formulate theoretical frameworks that unveil the interplay of activity, force generation, and emergent architectures.
  </p>
</div>

<!-- Research Topics Section -->
<div style="max-width: 900px; margin: 0 auto; text-align: center; padding: 10px;">
  <span style="font-size: 20px; color: #007acc; line-height: 1.6; display: inline-block; font-weight: 600;">
    • Self-organization in Cytoskeletal Networks • Biological Ice Nucleation <br>
    • Nucleation in Active Biophysics Systems • Driven Soft Matter and Amorphous Materials <br>
    • Statistical Mechanics • Non-Equilibrium Thermodynamics • Machine Learning <br>
    • Agent-based Simulations • Coarse-Grained Models • Molecular Dynamics • Kinetic Monte Carlo
  </span>
</div>

<!-- Slideshow Container -->
<div class="slideshow-container" style="margin-top: 30px; text-align: center; position: relative; max-width: 800px; margin: 30px auto; display: flex; justify-content: center; align-items: center;">
    <!-- Slideshow Content Wrapper -->
    <div style="position: relative; width: 100%; height: 400px; overflow: hidden; border-radius: 12px; box-shadow: 0 4px 8px rgba(0,0,0,0.1); display: flex; justify-content: center; align-items: center;">
        <img src="../images/cyto.svg" class="slide active" alt="Slide 1" style="width: 100%; height: 100%; object-fit: contain; position: absolute; transition: opacity 1s;">
        <img src="../images/ice.svg" class="slide" alt="Slide 2" style="width: 100%; height: 100%; object-fit: contain; position: absolute; opacity: 0; transition: opacity 1s;">
        <img src="../images/proposal.svg" class="slide" alt="Slide 3" style="width: 100%; height: 100%; object-fit: contain; position: absolute; opacity: 0; transition: opacity 1s;">
    </div>

    <!-- Manual Navigation Buttons -->
    <button class="prev" onclick="changeSlide(-1)" style="background-color: rgba(0,0,0,0.5); color: white; border: none; padding: 12px 18px; cursor: pointer; font-size: 24px; position: absolute; left: 10px; top: 50%; transform: translateY(-50%); border-radius: 50%;">❮</button>
    <button class="next" onclick="changeSlide(1)" style="background-color: rgba(0,0,0,0.5); color: white; border: none; padding: 12px 18px; cursor: pointer; font-size: 24px; position: absolute; right: 10px; top: 50%; transform: translateY(-50%); border-radius: 50%;">❯</button>
</div>

<!-- JavaScript for Slideshow -->
<script>
    let currentSlide = 0;
    const slides = document.querySelectorAll(".slide");
    function showSlide(index) {
        slides.forEach((slide, i) => {
            slide.style.opacity = (i === index) ? "1" : "0";
        });
    }
    function changeSlide(direction) {
        currentSlide = (currentSlide + direction + slides.length) % slides.length;
        showSlide(currentSlide);
    }
    setInterval(() => changeSlide(1), 3000);
</script>

