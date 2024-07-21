---
layout: page
title: Selected Projects

url_classification_path: /assets/phishing_url_classification.pdf
fitness_path: https://github.com/casciand/physical-education-app
---

<!-- <div class="posts">
  {% for post in site.posts %}
  <div class="post">
    <h1 class="post-title">
      <a href="{{ post.url | absolute_url }}">
        {{ post.title }}
      </a>
    </h1>

    <span class="post-date">{{ post.date | date_to_string }}</span>

    {{ post.content }}
  </div>
  {% endfor %}
</div> -->

<br>

## <ins>**Onion Router**</ins>
&rarr; Developed auto-scaling network topologies with Mininet to simulate and test custom onion routing algorithm \
&rarr; Configured hosts, switches, and routers to pass bytes over TCP encrypted with AES symmetric keys

[code]

## <ins>**Phishing URL Classification**</ins>
&rarr; Classified legitimate and phishing URLs with K-Nearest Neighbors, Support Vector Machine, and Neural Network \
&rarr; Employed dimensionality reduction with Principal Component Analysis and applied filter feature selection to
achieve an accuracy of 95.9% with a dataset consisting of 11430 real URLs

[[paper]]({{ page.url_classification_path }}) [code]

## <ins>**Physical Education Tracker**</ins>
&rarr; Coordinated with client to build OS-independent mobile application for instructors to record students’ progress \
&rarr; Maintained records with Google’s Firebase to offer low latency access and authentication for data security

[[code]]({{ page.fitness_path }})
