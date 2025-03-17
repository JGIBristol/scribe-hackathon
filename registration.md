---
title: Hackathon registration
menu_title: Registration
menu_icon: clipboard-check
event_status:
 - soon
---

{:.lead}
Participation is open to researchers and staff from any research institution, and we encourage contributions from early career researchers[<sup>(?)</sup>][faq]{:title="What do we mean by an Early Career Researcher (ECR)?"}, including PhD students and Postdocs.
{% if site.registration_status == "soon" or site.registration_status == "demo" %}Registration opens on {{ site.registration_opens_date }}.{% endif %}
The closing date for applications is {{ site.registration_closes_date }}.

<div class="aside" markdown="1">
Check the [commitment required](#what-commitment-is-required) and that you can attend both workshop dates: {{ site.event_date }} and {{ site.event_date_2 }}.

{% if site.registration_status == "soon" or site.registration_status == "demo" %}
  <a class="btn disabled">Registration opens soon</a>
{% endif %}
{% if site.registration_status == "open" or site.registration_status == "demo" %}
  [Complete the application form](https://forms.office.com/...){:.btn target="_blank"}
{% endif %}
{% if site.registration_status == "closed" or site.registration_status == "demo" %}
  <a class="btn disabled">Registration has closed</a>
{% endif %}

The closing date for applications is {{ site.registration_closes_date }}.
</div>

## Who we are looking for

We're looking for dynamic individuals who love working with data to address difficult interdisciplinary questions.
Supported by an expert team, participants will be responding to real-world questions from key decision-makers in UK Government and beyond.

Participation is open to researchers and staff from any research institution, and we encourage contributions from **early career researchers**[<sup>(?)</sup>][faq]{:title="What do we mean by an Early Career Researcher (ECR)?"}, including PhD students and Postdocs.

We anticipate that you'll have some experience in working with data, which may include scientific programming (in languages such as _Python_ or _R_), data mining, data cleaning, statistics or data visualisation.
We'd like to welcome a broad range of participants, and technical support and guidance will be provided by the [Jean Golding Institute](https://bristol.ac.uk/golding/).

If you're still unsure whether you have the right skills, you are welcome to [email us for advice](mailto:{{ site.mailbox_address }}).

## Why join the event

Over two sessions, you'll hear from practitioners and researchers working on some of the most complex problems and existential threats we face today.
By joining the hackathon, you'll become part of a dynamic community of interdisciplinary researchers, exposure to security and defence thinking, and identify future ways to collaborate as the project evolves.

We also hope that by participating you will build strong relationships with peers from other research areas. 

## What commitment is required

- Approximately ?? hours of preparation before the first workshop.
- Attendance in-person at the full-day kick off workshop on **{{ site.event_date }}**.
- Work on your challenge area during the period of exploration (we anticipate ?? hours, however as much as you can reasonably contribute).
- Attendance either in-person or online at the half-day review workshop on **{{ site.event_date_2 }}**.

## How to apply

If you are interested in applying and having the opportunity to engage with like-minded researchers, then please complete the application form by clicking the link above.

The closing date for the applications is {{ site.registration_closes_date }}.
If you have any queries, or have any difficulties completing the registration form, please email: <{{ site.mailbox_address }}>.

[faq]: {{ site.baseurl }}{% link faq.md %}
