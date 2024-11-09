---
layout: default
title: Dr. Asha Rani - National Teachers' Award 2024
---

<div class="gallery-container">
  <h1>Honoring Dr. Asha Rani</h1>

  <p>Dr. Asha Rani, a Post Graduate Teacher at Plus 2 High School Chandankiyari, Bokaro, Jharkhand, was honored with the prestigious **National Teachers' Award 2024** on September 5 at Vigyan Bhawan, New Delhi. She was one of 82 educators across the country recognized for their dedication, innovation, and impact in education. The award ceremony was a significant moment, and Dr. Asha Rani’s contributions to education have inspired many.</p>

  <p>The award includes a certificate of merit, a cash prize of ₹50,000, and a silver medal. After the ceremony, the awardees had the opportunity to interact with Prime Minister Narendra Modi, which was a memorable moment for all involved.</p>

  <p>We invite you to watch moments from the ceremony, Dr. Asha Rani’s interactions, and more in the videos below.</p>

  <h2>Video Gallery</h2>
  <div class="video-gallery">
  {% for video in site.static_files %}
    {% if video.path contains 'videos/' and video.extname == '.mp4' %}
      <div class="video-card">
        <video width="320" height="240" controls>
          <source src="{{ video.path | relative_url }}" type="video/mp4">
          Your browser does not support the video tag.
        </video>
        <a href="{{ video.path | relative_url }}" download>
          <button>Download</button>
        </a>
      </div>
    {% endif %}
  {% endfor %}
  </div>

  <p>Thank you for celebrating this achievement with us and for supporting dedicated educators like Dr. Asha Rani, who continue to shape the future of our nation.</p>
</div>
