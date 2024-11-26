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

<div id="webaddress">
<a href="mailto:cnathanorick@gmail.com">cnathanorick@gmail.com</a>
| <a href="http://nathanorick.com">nathanorick.com</a>
</div>


## Education

`Graduated May 2018`
__The University of Tennessee, Knoxville__

- _Bachelor of Science in Computer Science_
- _Mathematics Minor_
- GPA: **3.99/4.00**

## Experience

`July 2022 - Present`
__Capital One - Senior Software Engineer (Principal Associate)__
- Leads full-stack SEO-focused projects, delivering optimized solutions for web performance.
- Manages and mentors cross-functional teams of developers, ensuring timely delivery of complex initiatives.
- Serves as a subject matter expert in web performance optimization and testing strategies.

`June 2018 – July 2022`
__Aveva / OSIsoft - Software Developer (I → II → Sr)__
- Designed, built, and maintained Angular-based applications for multiple customer-facing platforms.
- Developed Azure-based microservices for cloud-native applications.
- Delivered intuitive UX designs, collaborating with stakeholders to meet end-user needs.
- Mentored interns and junior developers, fostering growth through regular sessions and knowledge sharing.

`January 2016 – August 2017`
__OSIsoft, LLC - Development Co-op__
- Built data-analysis tools for the company's community portal, enhancing user insights.
- Upgraded software components from Angular 1 to Angular 4, enhancing performance and maintainability.
- Created and tested Angular-based UI components using Jasmine, bolstering product quality.

## Certifications & Projects

`March 2023`
__AWS Certified Solutions Architect__ - _Associate_
- 

`October 2022 - Present`
__Halloween Candy Machine__ - _Software/Hardware Project_
- A gamified candy machine that dispenses candy after trick-or-treaters spin a virtual wheel.

`July 2023 - Present`
__Cultivator__ - _Web Application_
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
