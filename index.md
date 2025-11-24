---
layout: default
---

<section class="hero">
  <img src="{{ '/assets/images/gold-c-logo.png' | relative_url }}" alt="The Chemical Catalyst Logo" class="hero-logo">
  <h1>CRASH COURSE</h1>
  <h1>JEE MAINS Chemistry</h1>
  <p class="tagline">Enrolment Started!! Limited Seats Only.</p>
  <a href="tel:{{ site.phone | remove: ' ' }}" class="cta-button">Book Your Seat Now</a>
</section>

<section id="about">
  <h2>Taught By: The Chemical Catalyst</h2>
  <p>Learn from the best to become the best. Our lead instructor brings years of experience from top-tier institutes.</p>
  <p class="faculty-credentials">Ex Faculty of FITJEE, Narayana, Physics Wallah</p>
</section>

<section id="course-details">
  <h2>Course Duration</h2>
  <p>Mark your calendars for intensive preparation.</p>
  <div class="course-dates">
    {{ site.course_dates }}
  </div>
</section>

<section id="contact" class="contact-info">
  <h2>Contact & Location</h2>
  <p>📍 <strong>Address:</strong><br>{{ site.address }}</p>
  <p>📞 <strong>To Book Your Seat:</strong><br><a href="tel:{{ site.phone | remove: ' ' }}">{{ site.phone }}</a></p>
</section>