---
layout: page
title: past sessions
permalink: /previous/
description: Past seminar sessions
nav: true
nav_order: 3
---

{% assign upcoming = site.sessions | where_exp: "session", "session.date < site.time" %}
{% assign sorted = upcoming | sort: 'date' | reverse %}

<div class="container session-list">
    <div class="row row-cols-md-2 row-cols-sm-1">
        {% for session in sorted %}
            {% assign session_type = site.data.session_types[session.session_type] %}
            <div class="col mb-4">
                <div class="card {{ session_type.css-class }}">
                    <div class="card-header">
                        <i class="{{ session_type.icon-class }}"></i> {{ session_type.display }}
                    </div>
                    <div class="card-body">
                        <h5 class="card-title">{{ session.title }}</h5>
                        <p class="card-text"><i>Session date:</i> {{ session.date | date: "%-d %B %Y" }}</p>
                        <p class="card-text"><i>Session host:</i> <a href="{{ session.host_ref }}">{{ session.host }}</a></p>
                        <a class="btn" href="{{ session.url | relative_url }}">More info</a>
                    </div>
                </div>
            </div>
        {% endfor %}
    </div>
</div>
<hr>
