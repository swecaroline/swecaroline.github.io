---
layout: default
title: "GaiaXus Web Portal"
slug: gaiaxus-web-portal
date: 2025-09-25 -0500
date_range: "AUG 2024 - MAY 2026"
description: "I joined a startup and built the main features of a web application managing and sharing water quality data, educational content, and projects."
category: "current-work"
skillsets:
- SaaS
- Data modeling
- Data visualization
- Mapping
- Frontend
- Web
image: "assets/images/gaiaxus/allDevicesMockup.png"
alt: "Mobile"
published: true
---

# GaiaXus Web Portal

Developing a web platform for students, educators, and community scientists to explore and share water quality data.  
<hr>

**Role:** Full-stack developer, UI designer
<hr>

**Organization:** GaiaXus, Inc. (Early-stage startup)
<hr>

**Tech stack:** AWS Lambda, S3, DynamoDB, GraphQL, React.js, Next.js, TypeScript, Mapbox  
<hr>

**Approaches:** SaaS, data modeling, data visualization, mapping, frontend, web
<hr>

## Challenge & Impact

As the sole full-time developer in an early-stage startup, my challenge was to transform their 
prototype web app into a usable, scalable SaaS platform from architecture to implementation. My work 
carried the output of a **[$250,000 SBIR Phase 1 grant](https://ies.ed.gov/use-work/awards/transforming-stem-learning-local-ecosystems-classrooms){:target="_blank"}** and was tested by hundreds 
of educational users around the country. Alongside software development, I was responsible for training 
educators how to use our technology in their classroom lessons, and my interactions with the teachers 
shaped the features that went into the product.  

<a class="button m-auto center" href="https://portal.gaiaxus.com/" target="_blank">Explore project</a>

<hr>

## Features I shipped

### Data review and visualization

I refactored the database schema and indexes for more efficient filtering, and re-designed the user interface which was previously built for our engineers. Now, customers can log into the platform and easily identify and review their data.

<div class="mockup-browser border border-base-300 w-full">
  <div class="mockup-browser-toolbar">
    <div class="input bg-white">https://portal.gaiaxus.com</div>
  </div>
    <img
      alt="daisy"
       src="/assets/images/gaiaxus/DataReview.jpg" />
</div>
<p class="image-caption">Data review interface</p>

<div class="mockup-browser border border-base-300 w-full">
  <div class="mockup-browser-toolbar">
    <div class="input bg-white">https://portal.gaiaxus.com</div>
  </div>
<div>
<figure class="diff aspect-2554/1289" tabindex="0">
  <div class="diff-item-1" role="img" tabindex="0">
    <img
      alt="daisy"
       src="/assets/images/gaiaxus/DataListAfter.jpg" />
  </div>
  <div class="diff-item-2" role="img">
    <img alt="daisy" src="/assets/images/gaiaxus/DataListBefore.jpg" 
        style="width:100cqi"
    />
  </div>
  <div class="diff-resizer"></div>
</figure>
</div>
</div>
<p class="image-caption">Comparison - data filtering interface before (right) and after</p>

### Version-controlled, AI-powered instructional modules

I refactored the backend architecture of our Labs (multimedia instructional modules) to handle version control 
and more efficient file storage and built an interface to view submissions. I also shipped a RAG/LLM integration 
called the Navigator, which looks up verified citizen science data from a third party API to help teachers 
build hyperlocal place-based activities, while training middle school science teachers how to use this feature 
in their curriculum development.  

<div class="mockup-browser border border-base-300 w-full">
  <div class="mockup-browser-toolbar">
    <div class="input bg-white">https://portal.gaiaxus.com</div>
  </div>
    <img
      alt="daisy"
       src="/assets/images/gaiaxus/LabBuilder2.jpg" />
</div>
<p class="image-caption">Lab builder</p>

<div class="mockup-browser border border-base-300 w-full">
  <div class="mockup-browser-toolbar">
    <div class="input bg-white">https://portal.gaiaxus.com</div>
  </div>
    <img
      alt="daisy"
       src="/assets/images/gaiaxus/LabBuilder3.jpg" />
</div>
<p class="image-caption">Lab builder components</p>

<div class="mockup-browser border border-base-300 w-full">
  <div class="mockup-browser-toolbar">
    <div class="input bg-white">https://portal.gaiaxus.com</div>
  </div>
    <img
      alt="daisy"
       src="/assets/images/gaiaxus/LabResults.jpg" />
</div>
<p class="image-caption">Lab result table organized by lab version</p>

### Project management for classrooms and community science

I designed the database schema and user interface for our Projects feature, allowing classroom and community science
groups to collaborate on data and workflows.

<div class="mockup-browser border border-base-300 w-full">
  <div class="mockup-browser-toolbar">
    <div class="input bg-white">https://portal.gaiaxus.com</div>
  </div>
    <img
      alt="daisy"
       src="/assets/images/gaiaxus/Projects.jpg" />
</div>
<p class="image-caption">Card-based project list</p>

<div class="mockup-browser border border-base-300 w-full">
  <div class="mockup-browser-toolbar">
    <div class="input bg-white">https://portal.gaiaxus.com</div>
  </div>
    <img
      alt="daisy"
       src="/assets/images/gaiaxus/Projects2.jpg" />
</div>
<p class="image-caption">Project detail page</p>

### Interactive data mapping

I built an interactive map interface to collect participants' responses to a lab module and
summarize the outcome of the activity with LLM assistance.

<div class="mockup-browser border border-base-300 w-full">
  <div class="mockup-browser-toolbar">
    <div class="input bg-white">https://portal.gaiaxus.com</div>
  </div>
    <img
      alt="daisy"
       src="/assets/images/gaiaxus/LabReport.jpg" />
</div>