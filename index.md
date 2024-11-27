---
layout: cv
title: Nathan Orick's Resume
skills:
    - typescript
    - javascript
    - astro
    - solidjs
    - nodejs
    - nestjs
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
    - playwright
    - dotnet
    - git
    - aws
    - cloudfront
    - npm
    - webpack
    - azure devops
    - scrum
    - agile
    - sql
    - dynamodb
    - ux
    - figma
    - azure
    - svelte
    - pwa
    - core web vitals
    - lighthouse
    - seo
    - mocha
    - testing
---


# Nathan Orick

Senior Software Engineer, Front-End Expert, Full-Stack Developer

<span id="webaddress">
<a href="mailto:cnathanorick@gmail.com">cnathanorick@gmail.com</a>
| <a href="http://nathanorick.com">nathanorick.com</a>
</span>


## Education

__The University of Tennessee, Knoxville__
`Graduated May 2018`

- _Bachelor of Science in Computer Science_
- _Mathematics Minor_
- GPA: **3.99/4.00**

## Experience

__Capital One - Senior Software Engineer (Principal Associate)__
`July 2022 - Present`

- Leads full-stack SEO-focused projects, delivering optimized solutions for web performance.
- Manages and mentors cross-functional teams of developers, ensuring timely delivery of complex initiatives.
- Serves as a subject matter expert in web performance optimization and testing strategies.

__Aveva / OSIsoft - Software Developer (I → II → Sr)__
`June 2018 – July 2022`

- Designed, built, and maintained Angular-based applications for multiple customer-facing platforms.
- Developed Azure-based microservices for cloud-native applications.
- Delivered intuitive UX designs, collaborating with stakeholders to meet end-user needs.
- Mentored interns and junior developers, fostering growth through regular sessions and knowledge sharing.

__OSIsoft, LLC - Development Co-op__
`January 2016 – August 2017`

- Built data-analysis tools for the company's community portal, enhancing user insights.
- Upgraded software components from Angular 1 to Angular 4, enhancing performance and maintainability.
- Created and tested Angular-based UI components using Jasmine, bolstering product quality.

## Certifications & Projects

__AWS Certified Solutions Architect__ - _Associate_
`March 2023`

- 

__Halloween Candy Machine__ - _Software/Hardware Project_
`October 2022 - Present`

- A gamified candy machine that dispenses candy after trick-or-treaters spin a virtual wheel.

__Cultivator__ - _Web Application_
`July 2023 - Present`

- Works with popular finance software, Tiller.
- Lets users monitor their transactions on the go.

__More__
- ... more projects at [nathanorick.com](https://nathanorick.com).

## (For Machines) Misc. Skills
{% assign sortedskills = page.skills | sort %}
{% for skill in sortedskills -%}
    {{ skill | downcase }}
    {%- if forloop.last == false %}, {% endif %}
{%- endfor %}
