---
layout: page
title: SCRIBE Hackathon
menu_title: Home
menu_icon: house-door
---

{:.secondary}
# {{ site.event_date }} -- {{ site.event_date_2 }}, in association with the Jean Golding Institute

<div class="aside">
    <h2><i class="bi bi-calendar3"></i> Event timeline</h2>
    <dl>
        {% if site.registration_status == "soon" or site.registration_status == "open" or site.registration_status == "demo" %}
            <dt>{{ site.registration_opens_date }}</dt>
            <dd>
                Applications open for participants<br>
                {% if site.registration_status == 'open' %}
                    <a href="{{ site.baseurl }}{% link registration.md %}" class="btn">Register now</a>
                {% elsif site.registration_status == 'closed' %}
                    <a class="btn disabled">Registration has closed</a>
                {% elsif site.registration_status == 'soon' %}
                    <a class="btn disabled">Registration opens soon</a>
                {% endif %}
            </dd>
        {% endif %}

        <dt>{{ site.registration_closes_date }}</dt>
        <dd>Applications close</dd>

        <dt>{{ site.event_date }}, 9:30am – 4pm</dt>
        <dd>Full-day kick off workshop (in-person)</dd>

        <dt>{{ site.event_date }} – {{ site.event_date_2 }}</dt>
        <dd>Period of exploration</dd>

        <dt>{{ site.event_date_2 }}, 2–4pm</dt>
        <dd>Half-day review workshop (hybrid)</dd>
    </dl>
</div>

{% if site.event_status != "over" %}

{:.lead}
The SCRIBE Hackathon is a **biothreat datathon** to explore access, nature, and integration of data relating to **biothreats in complex environments**.

This initiative, in partnership with the UK Science and Innovation Network, addresses real-world challenges faced by high-risk regions affected by climate change, instability, and displacement.

Working with expert partners from across life sciences, we will be uncovering how best to unite complex data sources relating to fragile settings including criminal activity, conflict-affected regions, climate vulnerability, and complex socio-political landscapes.

Participants can work on three **[challenge areas]({{ site.baseurl }}{% link challenges.md %})** including transboundary One Health threats, resistant infections, and more.
Challenge owners will provide briefings to the attendees, and an expert team will be available throughout for advice.

The hackathon will commence on **{{ site.event_date }}** with a full-day kick off workshop (in-person).
There will them be a period of exploration, followed by a half-day review workshop (hybrid) on **{{ site.event_date_2 }}**.

[**Participation is open to researchers and staff**]({{ site.baseurl }}{% link registration.md %}) from any research institution, and we encourage contributions from **early and mid-career researchers**[<sup>(?)</sup>][faq]{:title="What do we mean by an Early Career Researcher (ECR)?"}, including PhD students and Postdocs.

[faq]: {{ site.baseurl }}{% link faq.md %}

{% else %}

...

{% endif %}
