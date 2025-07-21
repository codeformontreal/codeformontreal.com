---
layout: default
title: Home
description: We build civic tech projects to make Montreal better for everyone.
---

<section id="mission" class="py-5">
  <div class="container">
    <h2 class="text-center mb-4">Our Mission</h2>
    <p class="lead text-center">
      We bring together developers, designers, public servants, and residents to build open-source civic tech that addresses the unique challenges and opportunities of {{ site.location | default: "Montreal" }}.
      Our goal is to create inclusive, impactful tools that improve how our city works and how citizens engage.
    </p>
  </div>
</section>

<section id="projects" class="py-5 bg-light">
  <div class="container">
    <h2 class="text-center mb-5">Current Projects</h2>
    <div class="row g-4">
      <div class="col-md-4">
        <div class="card h-100 shadow-sm">
          <div class="card-body">
            <h5 class="card-title">Bixi Tracker</h5>
            <p class="card-text">Live maps and analytics for Montreal’s bike-share program to promote eco-friendly commuting.</p>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card h-100 shadow-sm">
          <div class="card-body">
            <h5 class="card-title">Service Access Map</h5>
            <p class="card-text">A tool to help residents locate free and low-cost social services across Montreal’s boroughs.</p>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card h-100 shadow-sm">
          <div class="card-body">
            <h5 class="card-title">Open Budget Montreal</h5>
            <p class="card-text">Making the city’s annual budget interactive and transparent for everyone to explore and understand.</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>

<section id="join" class="py-5">
  <div class="container text-center">
    <h2 class="mb-4">Join the Movement</h2>
    <p class="lead mb-4">
      Whether you're a coder, a communicator, or a curious citizen — we need your voice and your skills to build a better {{ site.location | default: "Montreal" }}.
    </p>
    <a href="#" class="btn btn-primary btn-lg">Join Our Discord</a>
  </div>
</section>
