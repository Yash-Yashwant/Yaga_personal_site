---
layout: default
title: Projects
permalink: /projects/
---

<section class="projects-page">
    <div class="section-divider">
        <h2>Projects</h2>
    </div>

    <div class="project-grid">
        {% for project in site.projects %}
        <article class="project-card">
            <h3><a href="{{ project.url | relative_url }}">{{ project.title }}</a></h3>
            {% if project.tagline %}
            <p class="project-tagline">{{ project.tagline }}</p>
            {% endif %}
            {% if project.excerpt %}
            <p class="project-excerpt">{{ project.excerpt | strip_html | truncatewords: 30 }}</p>
            {% endif %}
            <div class="project-links">
                {% if project.github %}
                <a href="{{ project.github }}" target="_blank">GitHub →</a>
                {% endif %}
                {% if project.demo %}
                <a href="{{ project.demo }}" target="_blank">Demo →</a>
                {% endif %}
                <a href="{{ project.url | relative_url }}">Details →</a>
            </div>
        </article>
        {% endfor %}

        {% if site.projects.size == 0 %}
        <p style="grid-column: 1/-1; text-align: center; color: var(--sepia-medium); font-style: italic;">
            No projects yet. Add markdown files to <code>_projects/</code> to showcase your work!
        </p>
        {% endif %}
    </div>
</section>

