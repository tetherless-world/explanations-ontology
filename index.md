---
layout: default
title: Explanations Ontology - Treating Explanations as Primary Consideration
---

<h1 class="page-title" id="header">Explanations Ontology - Treating Explanations as Primary Consideration</h1>
<h3 style="color:dimgrey;">Shruthi Chari<sup>1</sup>, Oshani Seneviratne<sup>1</sup>, Daniel M. Gruen<sup>2</sup>, Morgan Foreman<sup>2</sup>, Deborah L. McGuinness<sup>1</sup>, Amar K. Das<sup>2</sup></h3>
<h3><a href="https://www.rpi.edu/"><sup>1</sup>Rensselaer Polytechnic Institute</a> | <a href="https://www.research.ibm.com/labs/cambridge/"><sup>2</sup>IBM Research, Cambridge</a></h3>
<p class="message">A website to navigate resources open-sourced via the associated ISWC 2020 submission</p>

<!-- <table>
  <tbody>
    <tr>
      <td><a href="#abstract">Abstract</a></td>
    </tr>
  </tbody>
</table> -->

<article class="mb-5" id="abstract">
<content>
  
  
<h2>Abstract</h2>
  <p>Explainability has been a goal for Artificial Intelligence systems since their conception, with the need for explanations only growing as machine learning models are increasingly used in critical settings such as healthcare. Currently, explanations are often treated as a nice-to-have feature added in a post-hoc manner. With greater adoption of these systems and emphasis on user-centric explainability, there is a need for a structured representation that treats explainability as a primary consideration, mapping end user needs to specfic explanation types. We design an explanations ontology to formalize the generation of explanations in a machine-readable format, accounting for the system and user attributes in the process. Within our ontology, we support the modeling of different literature-derived explanation types, whose requirements and generational needs were further refined through a requirements gathering exercise conducted with clinicians. Through this ontology, we hope to benefit system designers to include explanation generation facilities in their systems. We evaluate our ontology via competency questions that are inspired by learnings from our clinical requirements gathering exercise and are geared towards a system designer who might use our ontology to learn about the best explanation types to include, given a combination of users' needs and a system's capabilities, both in real-time and system design settings.</p>
<ul>
  
 </ul>
 </content>
 
<!-- 
<div class="posts">
  {% for post in paginator.posts %}
  <div class="post">
    <h1 class="post-title">
      <a href="{{ post.url }}">
        {{ post.title }}
      </a>
    </h1>

    <span class="post-date">{{ post.date | date_to_string }}</span>

    {{ post.content }}
  </div>
  {% endfor %}
</div>

<div class="pagination">
  {% if paginator.next_page %}
    <a class="pagination-item older" href="{{ site.baseurl }}page{{paginator.next_page}}">Older</a>
  {% else %}
    <span class="pagination-item older">Older</span>
  {% endif %}
  {% if paginator.previous_page %}
    {% if paginator.page == 2 %}
      <a class="pagination-item newer" href="{{ site.baseurl }}">Newer</a>
    {% else %}
      <a class="pagination-item newer" href="{{ site.baseurl }}page{{paginator.previous_page}}">Newer</a>
    {% endif %}
  {% else %}
    <span class="pagination-item newer">Newer</span>
  {% endif %}
</div> -->