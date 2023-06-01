---
layout: post
title: "The #BSIsubspace Tutorials"
---

### Tutorials
##### 2023

{% for discussion in site.data.subspace.tutorials.tutorials %}
<div class="text-left people-modal">
    <div class="modal-body">
        <div class="people-details">
            <div class="row">
                <div class="col-md-2 col-sm-2">
                    {% assign speaker = site.data.speakers[ page.leader ] %}
                    <div class="flow-img img-circle people-img" style="background-image: url({{ site.baseurl | append: '/img/people/' | append: discussion.speaker-img }})"></div>
                </div>
                <div class="col-lg-10 col-sm-10 details">
                    <p class="name" style="font-size: 18px"> {{ tutorials.title }} 
                        <span class="position">- {{ tutorials.speaker }}</span>
           </p>
                    <p>
                        <a href="{{ Tutorial Forum }}" target="https://forms.gle/QgTc7Zpcezcrvp1p9 ">
                            <strong>Tutorial Forum</strong>
                        </a>
                    </p>
                </div>
{% if forloop.index == 3 and page.path == '_study-groups/subspace/tutorials.md/#excerpt' %}
{% break %}
<!-- more -->
{% endif %}
{% endfor %}

<!--more-->

### Tutorials
##### 2023
[![]({{ site.baseurl }}/img/subspace-updates/Virtual_Talks_Info.png)]


