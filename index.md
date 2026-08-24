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
    - lambda
    - s3
    - waf
    - iam
    - akamai
    - redis
    - openfeature
    - opentelemetry
    - new relic
    - splunk
    - optimizely
    - pager duty
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

<span class="subtitle-part">Lead Software Engineer</span> <span class="subtitle-sep">|</span> <span class="subtitle-part">Web Performance & Full-Stack Tech Lead</span>

<span id="webaddress">
<a href="mailto:cnathanorick@gmail.com">cnathanorick@gmail.com</a>
| <a href="http://nathanorick.com">nathanorick.com</a>
</span>


## Experience

__Capital One__ _Senior Software Engineer, Auto Navigator_
`August 2022 - Present`

- Unblocked a stalled strategic initiative by directing a rotating team of engineers, negotiating scope with Product, and defining a CMS-agnostic BFF architecture that enabled a seamless zero-frontend-change CMS migration.
- Designed and own the high-throughput Content BFF (NestJS/Node): architected a delta-updating in-memory caching strategy that reduced search/list response times from 12.2s to 78.4ms (~99.4% latency reduction).
- Served as Web Performance Lead across the platform — doubled search Lighthouse scores (26 → 65) and cut Largest Contentful Paint by 50%; presented architectural strategy to executive leadership and recognized with top enterprise engineering awards.
- Executed complex production platform cutovers, including an 8+ app AWS CloudFront Gen2→Gen3 account migration (~1s cutover downtime) and a multi-phase CMS migration validated by 148 automated parity tests.
- Appointed Testing Champion, leading the org to become the first team to achieve top-tier enterprise testing standards ahead of deadline; authored the 2026 SEO indexation architecture projected to reclaim ~8.2M Google crawl budget URLs.

__Aveva / OSIsoft__ _Software Developer (I → II → Sr)_
`June 2018 – July 2022`

- Designed, built, and maintained enterprise Angular applications and Azure cloud microservices across customer platforms.
- Promoted through 3 engineering tiers while leading UX/UI design initiatives and collaborating with cross-functional stakeholders.
- Mentored interns and junior developers, establishing code review practices and regular technical knowledge-sharing sessions.

__OSIsoft, LLC__ _Development Co-op_
`January 2016 – August 2017`

- Upgraded community portal UI components from Angular 1 to Angular 4, significantly improving performance and maintainability.
- Built data-analysis tools and automated component unit testing using Jasmine to ensure high product quality.

## Certifications

__AWS Certified Solutions Architect__ _Professional_
`May 2025`

## Projects

__The Neighbours__ _Venice Biennale 2024 Art Installation_
`May 2024`

- Engineered Python IoT media streaming software and Home Assistant failsafe orchestration for the Bulgarian Pavilion at the 60th Venice Art Biennale.

__Cultivator__ _Angular PWA Companion_
`July 2023 - Present`

- Built an Angular PWA mobile companion for Tiller spreadsheets with client-side Google API OAuth and zero-backend storage.

__Auto Guest Login__ _Home Assistant Add-On_
`January 2023`

- Created an open-source Docker & Node.js Home Assistant Add-on enabling frictionless guest account authentication via QR code & URL.

## Education

__The University of Tennessee, Knoxville__
`Graduated May 2018`

- _Bachelor of Science in Computer Science_ | _Mathematics Minor_ | GPA: **3.99/4.00**

## Skills

{% assign sortedskills = page.skills | sort %}
{% for skill in sortedskills -%}
    {{ skill | downcase }}
    {%- if forloop.last == false %}, {% endif %}
{%- endfor %}
