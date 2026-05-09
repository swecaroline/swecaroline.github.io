---
layout: default
title: "GaiaXus Mobile App"
date: 2025-09-26 -0500
date_range: "AUG 2024 - PRESENT"
description: "I joined a startup and scaled its mobile app for operating water quality monitoring sensors, collecting data, and viewing educational content, while maintaining ease of use and offline-first functionality."
category: "current-work"
skillsets:
- Hardware-software integration
- Mobile
- UI/UX
image: "assets/images/gaiaxus/gaiaxusInAction.gif"
alt: "Mobile"
published: true
---

# GaiaXus Mobile App
Developing a cross-platform mobile app for students, teachers, citizen scientists, and researchers to collect water quality data, participate in projects, and calibrate their instruments.
<hr>

**Role:** Full-stack developer, UI designer
<hr>

**Organization:** GaiaXus, Inc. (Early-stage startup)
<hr>

**Tech stack:** AWS Lambda, S3, DynamoDB, GraphQL, React Native, TypeScript, Android Studio, XCode
<hr>

**Approaches:** Hardware-software integration, mobile app development, UI/UX
<hr>

## Challenge & Impact

As the first full-time software engineer to join an early-stage startup, my challenge was to transform 
the prototype app used primarily by our engineers into a fast and user-friendly mobile companion to our
Bluetooth-controlled environmental sensors. I improved the usability of our instrument control interface,
refactored backend architecture to more efficiently load instructional content, and expanded the 
compatibility of the app from its original Android build to Chromebooks and iOS (and [caught a bug](https://github.com/aws-amplify/amplify-js/issues/14459){:target="_blank"} in AWS Amplify's handling of authentication in ChromeOS while at it).

My work carried the output of a **[$250,000 SBIR Phase 1 grant](https://ies.ed.gov/use-work/awards/transforming-stem-learning-local-ecosystems-classrooms){:target="_blank"}** and was tested by hundreds 
of educational users around the country. 

Alongside software development, I was responsible for training educators on using our technology, managing 
distribution and release through the Google Play and Apple stores, and maintaining VPAT documentation to 
evaluate our app's compliance with WCAG 2.2 accessibility standards.  

<a class="img-button m-auto center" href="https://play.google.com/store/apps/details?id=com.gaiaxus" target="_blank">
<img src="/assets/images/gaiaxus/googlePlayButton.png">
</a>

<a class="img-button m-auto center" href="https://apps.apple.com/us/app/gaiaxus/id6748620502" target="_blank">
<img src="/assets/images/gaiaxus/appStoreButton.png">
</a>

<hr>

## Features I shipped

### Data review and filtering interface

I designed and implemented a graphical interface for reviewing and filtering past data, and for previewing
data sets on an interactive chart.

<div class="flex-row gap-4">
    <div class="mockup-phone rounded-xl aspect-1/2">
            <div class="mockup-phone-display bg-white rounded-md">
                <img alt="wallpaper" src="/assets/images/gaiaxus/reviewscreens/review3.jpg" class="object-fit" />
        </div>
    </div>
    <div class="mockup-phone rounded-xl aspect-1/2">
    <div class="mockup-phone-display bg-white rounded-md">
    <img alt="wallpaper" src="/assets/images/gaiaxus/reviewscreens/review1.jpg" class="object-fit" />
    </div>
    </div>
    <div class="mockup-phone rounded-xl aspect-1/2">
            <div class="mockup-phone-display bg-white rounded-md">
                <img alt="wallpaper" src="/assets/images/gaiaxus/reviewscreens/review4.jpg" class="object-fit" />
        </div>
    </div>
    <div class="mockup-phone rounded-xl aspect-1/2">
        <div class="mockup-phone-display bg-white rounded-md">
                <img alt="wallpaper" src="/assets/images/gaiaxus/reviewscreens/review2.jpg" class="object-fit" />
        </div>
    </div>
</div>

### Offline-first education workflows

I refactored the backend architecture of our multimedia instructional modules (Labs) to reduce loading time from minutes to 
seconds, enabling practical use of this feature. I also designed and implemented step-by-step components 
within the instructional modules for operating and calibrating the sensors.

<div class="flex-row gap-4">
    <div class="mockup-phone rounded-xl aspect-1/2">
            <div class="mockup-phone-display bg-white rounded-md">
                <img alt="wallpaper" src="/assets/images/gaiaxus/labscreens/labs1.jpg" class="object-fit" />
        </div>
    </div>
    <div class="mockup-phone rounded-xl aspect-1/2">
    <div class="mockup-phone-display bg-white rounded-md">
    <img alt="wallpaper" src="/assets/images/gaiaxus/labscreens/labs2.jpg" class="object-fit" />
    </div>
    </div>
    <div class="mockup-phone rounded-xl aspect-1/2">
            <div class="mockup-phone-display bg-white rounded-md">
                <img alt="wallpaper" src="/assets/images/gaiaxus/labscreens/labs3.jpg" class="object-fit" />
        </div>
    </div>
    <div class="mockup-phone rounded-xl aspect-1/2">
        <div class="mockup-phone-display bg-white rounded-md">
                <img alt="wallpaper" src="/assets/images/gaiaxus/labscreens/measurementCaptureGif.gif" class="object-fit" />
        </div>
    </div>
</div>

### Responsive, intuitive sensor calibration

I translated a command-line internal tool developed by our engineers into a responsive, intuitive
graphical interface that allows users to calibrate our sensors with minimal training. I collaborated
with engineers on my team and external scientists to validate the calibrations, and designed for 
compliance with WCAG's guidelines on moving and auto-updating content.

<div class="flex-row gap-4">
    <div class="mockup-phone rounded-xl aspect-1/2">
    <div class="mockup-phone-camera"></div>
    <div class="mockup-phone-display bg-white rounded-md">
    <img alt="wallpaper" src="/assets/images/gaiaxus/calibrationscreens/calibration.gif" class="object-contain" />
    </div>
    </div>
    <div class="mockup-phone rounded-xl aspect-1/2">
        <div class="mockup-phone-camera"></div>
            <div class="mockup-phone-display bg-white rounded-md">
            <img alt="wallpaper" src="/assets/images/gaiaxus/calibrationscreens/calibration_list2.jpg" class="object-contain" />
        </div>
    </div>
    <div class="mockup-phone rounded-xl aspect-1/2">
        <div class="mockup-phone-camera"></div>
        <div class="mockup-phone-display bg-white rounded-md">
            <img alt="wallpaper" class="object-contain" src="/assets/images/gaiaxus/calibrationscreens/calibration_success.jpg" />
        </div>
    </div>
    <div class="mockup-phone rounded-xl aspect-1/2">
        <div class="mockup-phone-camera"></div>
            <div class="mockup-phone-display bg-white rounded-md">
            <img alt="wallpaper" src="/assets/images/gaiaxus/calibrationscreens/calibration_failure.jpg" class="object-contain" />
        </div>
    </div>
</div>
<div class="flex-row gap-4">
</div>


### Project participation interface

I developed an interface for participating in projects, allowing for classroom and community collaboration and
sharing of educational content and water data.

<div class="flex-row gap-4">
    <div class="mockup-phone rounded-xl aspect-1/2">
    <div class="mockup-phone-camera"></div>
    <div class="mockup-phone-display bg-white rounded-md">
    <img alt="wallpaper" src="/assets/images/gaiaxus/projectscreens/projects1.jpg" class="object-contain" />
    </div>
    </div>
    <div class="mockup-phone rounded-xl aspect-1/2">
        <div class="mockup-phone-camera"></div>
            <div class="mockup-phone-display bg-white rounded-md">
    <img alt="wallpaper" src="/assets/images/gaiaxus/projectscreens/projects2.jpg" class="object-contain" />
        </div>
    </div>
    <div class="mockup-phone rounded-xl aspect-1/2">
        <div class="mockup-phone-camera"></div>
        <div class="mockup-phone-display bg-white rounded-md">
    <img alt="wallpaper" src="/assets/images/gaiaxus/projectscreens/projects3.jpg" class="object-contain" />
        </div>
    </div>
    <div class="mockup-phone rounded-xl aspect-1/2">
        <div class="mockup-phone-camera"></div>
            <div class="mockup-phone-display bg-white rounded-md">
            <img alt="wallpaper" src="/assets/images/gaiaxus/projectscreens/projects4.jpg" class="object-contain" />
        </div>
    </div>
</div>
<div class="flex-row gap-4">
</div>