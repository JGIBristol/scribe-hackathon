---
title: Hackathon registration
menu_title: Registration
menu_icon: clipboard-check
event_status:
 - soon
---

{:.lead}
Participation is open to researchers and staff from any research institution, and we encourage contributions from early and mid-career researchers[<sup>(?)</sup>][faq]{:title="What do we mean by an Early Career Researcher (ECR)?"}, including PhD students and Postdocs.
{% if site.registration_status == "soon" or site.registration_status == "demo" %}Registration opens on <span class="nowrap">{{ site.registration_opens_date }}</span>.{% endif %}

<div class="aside" markdown="1">
Check the [commitment required](#what-commitment-is-required) and that you can attend both workshop dates: <span class="nowrap">{{ site.event_date }}</span> and <span class="nowrap">{{ site.event_date_2 }}</span>.

{% if site.registration_status == "soon" or site.registration_status == "demo" %}
  <a class="btn disabled">Registration opens soon</a>
{% endif %}
{% if site.registration_status == "open" or site.registration_status == "demo" %}
  [Complete the application form](https://forms.office.com/e/Yi7abz3bbF){:.btn target="_blank"}
{% endif %}
{% if site.registration_status == "closed" or site.registration_status == "demo" %}
  <a class="btn disabled">Registration has closed</a>
{% endif %}

Applications will be reviewed on a rolling basis.
</div>

## Who we are looking for

We're looking for dynamic individuals who love working with data to address difficult interdisciplinary questions.
You might have expertise in microbiology, climate data, migration, economics, AI, public health, or something different.
Supported by an expert team, participants will be responding to real-world questions from key decision-makers in UK Government and beyond.

Participation is open to researchers and staff from any research institution, and we encourage contributions from **early and mid-career researchers**[<sup>(?)</sup>][faq]{:title="What do we mean by an Early Career Researcher (ECR)?"}, including PhD students and Postdocs.

We anticipate that you'll have some experience in working with data, which may include scientific programming (in languages such as _Python_ or _R_), data mining, data cleaning, statistics or data visualisation.
We'd like to welcome a broad range of participants, and technical support and guidance will be provided by the [Jean Golding Institute](https://bristol.ac.uk/golding/).

If you're still unsure whether you have the right skills, you are welcome to [email us for advice](mailto:{{ site.mailbox_address }}).

## Why join the event

Over two sessions, you'll hear from practitioners and researchers working on some of the most complex problems and existential threats we face today.
By joining the hackathon, you'll become part of a dynamic community of interdisciplinary researchers, exposure to security and defence thinking, and identify future ways to collaborate as the project evolves.

We also hope that by participating you will build strong relationships with peers from other research areas. 

## What commitment is required

- Approximately 1 hour of preparation before the first workshop (watching video briefings for the challenge areas and following any reading links).
- Attendance in-person at the full-day kick off workshop on **<span class="nowrap">{{ site.event_date }}</span>**.
- Work on your challenge area during the period of exploration to develop ideas/resources (as much as you can reasonably contribute).
- Attendance either in-person or online at the half-day review workshop on **<span class="nowrap">{{ site.event_date_2 }}</span>**.

## How to apply

If you are interested in applying and having the opportunity to engage with like-minded researchers, then please complete the application form by clicking the link above.

Applications will be reviewed on a rolling basis.
If you have any queries, or have any difficulties completing the registration form, please email: <span class="nowrap"><{{ site.mailbox_address }}></span>.

[faq]: {{ site.baseurl }}{% link faq.md %}
