---
layout: default
title: Home

# Asset Paths
headshot_path: /assets/headshot.jpeg
amazon_path: /assets/amazon.png
ford_path: /assets/ford.png
resume_path: /assets/resume.pdf

# Links
cs3251: https://www.vanderbilt.edu/catalogs/kuali/undergraduate-23-24.php#/courses/BJVHrw6hhO?bc=true&bcCurrent=CS3251%20-%20Intermediate%20Software%20Design&bcGroup=Computer%20Science&bcItemType=courses
cs2201: https://www.vanderbilt.edu/catalogs/kuali/undergraduate-23-24.php#/courses/Hy3itpn2O?bc=true&bcCurrent=CS2201%20-%20Program%20Design%20and%20Data%20Structures&bcGroup=Computer%20Science&bcItemType=courses
cs1100: https://www.vanderbilt.edu/catalogs/kuali/undergraduate-23-24.php#/courses/rJG3otahn_?bc=true&bcCurrent=CS1100%20-%20Applied%20Programming%20and%20Problem%20Solving%20with%20Python&bcGroup=Computer%20Science&bcItemType=courses
emr: https://aws.amazon.com/emr/
aqt: https://portal.us-west-2.amazon-aqt.com/
ford: https://artisan.ford.com/
---


<div style="display: flex; justify-content: space-between;">
  <div>
    <h1 style="margin: 0;">{{ site.author.name }}</h1>
      <a href="mailto:{{ site.author.email }}">{{ site.author.email }}</a><br><br>
      <a href="https://www.github.com/{{ site.author.github }}/">GitHub</a>,
      <a href="https://www.linkedin.com/in/{{ site.author.linkedin }}/">LinkedIn</a><br>
      <a href="{{ page.resume_path }}">Curriculum Vitae</a>
  </div>
  <img style="max-width: 100%; height: auto;" src="{{ page.headshot_path }}" width=225>
</div>

<br>
<hr>

## <ins>**About**</ins>
I am an incoming first year M.S. student in Computer Science at Duke University.

Previously, I obtained my bachelor's degree in Computer Science (honors) and Mathematics at Vanderbilt University.
I worked with [Daniel Balasubramanian](https://www.isis.vanderbilt.edu/team/71) at the 
[Institute for Software Integrated Systems](https://www.isis.vanderbilt.edu/), where I developed security enhancements for legacy UAV
software.

<br>
<hr>

## <ins>**Work Experience**</ins>

<div style="display: flex; flex-direction: row; align-items: center; align-content: space-between;">
  <p style="margin: 1rem 10px 0 0"><strong>Amazon</strong></p>
  <img style="margin: 25px 0 0 0" src="{{ page.amazon_path }}" width=20 height= 20>
</div>

<p style="float: right;">June 2024 - Aug. 2024</p>
Software Engineer Intern, [AWS EMR]({{ page.emr }})
<p style="margin-top: 0; float: right;">May 2023 - Aug. 2023</p>
<p style="margin-top: 0">
  Software Engineer Intern,
  <a href="{{ page.aqt }}">Alexa Qualification Tool</a>
</p>

<div style="display: flex; flex-direction: row; align-items: center; align-content: space-between;">
  <p><strong>Ford Motor</strong></p>
  <img style="margin: 20px 0 0 10px" src="{{ page.ford_path }}" width=50 height= 20>
</div>

<p style="float: right;">June 2022 - Aug. 2022</p>
Software Engineer Intern, [Software Excellence]({{ page.ford }})

<br>
<hr>

## <ins>**Teaching Experience**</ins>

- [CS 3251]({{ page.cs3251 }}): Intermediate Software Design, Teaching Assistant, Fall 2022
- [CS 2201]({{ page.cs2201 }}): Program Design and Data Structures, Teaching Assistant, Spring 2022
- [CS 1100]({{ page.cs1100 }}): Applied Programming and Problem Solving with Python, Teaching Assistant, Fall 2021
