---
layout: page
title: People
permalink: /people/
---


<ul>
    {% for members in site.data.members %}
    {% assign member = members[1] %}
    <div class="people-box1">
    <img class="badge" src="https://avatars2.githubusercontent.com/u/2666166?v=3&u=e9222752a65412ab2b4a0459fcb2932ae7c7620c&s=140">
    <div class="profile">
        {{ member.name }}
        ({{ member.nickname }}) <br>
                   
        {{ member.position }} <br>
        <div class="bio"> "{{ member.bio }}" </div>
        {% include icon-email.html username=member.email profile=member.nickname %} <br>
        {% include icon-github.html username=member.github %} <br>
    </div>
    </div>
    {% endfor %}
</ul>

