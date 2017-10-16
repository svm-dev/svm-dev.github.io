---
layout: page
title: People
permalink: /people/
---


<ul>
    {% for members in site.data.members %}
    {% assign member = members[1] %}
    <div class="people-box1">
        <img class="badge" src="{{ member.image }}">
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

