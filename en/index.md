---
layout: layouts/cv.njk
title: CV
templateClass: tmpl-cv
---


Jessy Govart
Halsendallaan 36
1652 Alsemberg Belgium
jessy.govart@pinnemouche.be
+32 456 02 56 70
[Linkedin](https://www.linkedin.com/in/jessy-govart-4b1389b/)
[Github](https://github.com/PolPasop)

## Objective:

Passionate front-end developer with 12 years of experience crafting user-friendly and visually appealing web interfaces. Proficient in HTML, CSS, and JavaScript, with a keen eye for design and a dedication to creating seamless user experiences. Seeking to contribute expertise to a dynamic team focused on creating innovative web solutions.

## Skills:


## Work Experience:

Front-End Developer | [Company Name] | [Dates of Employment]
- Collaborated with designers and back-end developers to create interactive and visually stunning user interfaces for [X] web applications.
- Implemented responsive design principles to ensure seamless user experiences across various devices and screen sizes.
- Utilized HTML, CSS, and JavaScript to translate design mockups into functional and pixel-perfect web pages.
- Optimized website performance by reducing page load times, minimizing HTTP requests, and implementing lazy loading techniques.
- Conducted thorough cross-browser and cross-device testing to identify and resolve compatibility issues.
- Implemented web accessibility best practices, ensuring compliance with WCAG guidelines and enhancing usability for all users.

Front-End Intern | [Company Name] | [Dates of Internship]
- Assisted senior front-end developers in building and maintaining [X] projects, gaining hands-on experience in modern front-end technologies.
- Participated in code reviews, providing feedback and suggestions for code quality improvements.
- Collaborated with the design team to refine UI/UX elements and ensure consistent design implementation.
- Contributed to the development of [X] feature enhancements, demonstrating a strong ability to learn and adapt quickly.

Education:
-------------
Bachelor's Degree in Web Design / Multimedia | Haute école ALbert Jacquard | 2007-2010

Certifications:
-------------
- Microsoft Specialist: Programming in HTML5 with JavaScript and CSS3

## Experience:

{% for project in projectslist | reverse %}
  {{ project.data.startDate}} - {{ project.data.endDate}}
  {{ project.data.projectName }}
  {{ project.data.client}}
  {{ project.data.position}}
{% endfor %}

## Portfolio:

jessygovart.be

## References:

Available upon request.