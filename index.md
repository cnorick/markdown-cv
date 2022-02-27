---
layout: cv
title: Nathan Orick's Resume
skills:
    - typescript
    - javascript
    - html
    - css
    - c#
    - c
    - c++
    - python
    - angular
    - angularjs
    - jasmine
    - jest
    - dotnet
    - git
    - aws
    - npm
    - webpack
    - azure devops
    - scrum
    - agile
    - sql
    - dynamodb
    - redis
    - eventhub
    - servicebus
    - ux
    - figma
    - azure
    - svelte
    - pwa
---


# Nathan Orick

Senior Software Engineer, Experienced Front-End Developer

<div id="webaddress">
<a href="mailto:cnathanorick@gmail.com">cnathanorick@gmail.com</a>
| <a href="http://nathanorick.com">nathanorick.com</a>
</div>


## Education

`May 2018`
__The University of Tennessee, Knoxville__

- _Bachelor of Science in Computer Science_
- _Mathematics Minor_
- GPA: **3.99/4.00**

## Experience

`June 2018 – Present`
__Aveva / OSIsoft - Software Developer I/II/Sr__
- Builds/Maintains Angular apps for multiple customer-facing products
- Writes Azure-based microservices to support cloud applications
- Creates UX designs and presents to stakeholders
- Mentors interns/jr developers
- Facilitates team learning through presentations and lunch-and-learns

`January 2016 – August 2017`
__OSIsoft, LLC - Development Co-op__
- Developed data-analysis software for company’s community website
- Developed and tested Angular UI for customer-facing software
- Migrated a project from Angular 1 to Angular 4
- Wrote UI tests using Jasmine and Angular testing tools

## Activities / Projects
`October 2020 - Present`
__Home Assistant__ - _Open Source Contributions_

`May 2019 - August 2020`
__Five in the Hive__ - _Personal Project_
- Competitive fantasy sports social app

`January 2018 – May 2018`
__Teaching Assistant__ - _UT EECS Dept._
- Led Data Structures and Algorithms lab section of 25 students

... more projects at [nathanorick.com](https://nathanorick.com)

## Hackathons / Conferences

`November 2019`
- _Angle Brackets / AngularMix_ \| Las Vegas, NV

`March 2018`
- _Lambda Squared_ \| Knoxville, TN

`September 2017`
- _VolHacks_ \| Knoxville, TN (Volunteer)

## Favorite Tech
Angular, Typescript, Jekyll, Svelte, C# (.NET Core),

## (For Machines) Misc. Skills
{% assign sortedskills = page.skills | sort %}
{% for skill in sortedskills -%}
    {{ skill | downcase }}
    {%- if forloop.last == false %}, {% endif %}
{%- endfor %}
