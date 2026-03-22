---
title: "Small Business Management App"
excerpt: "A production-grade Flutter app for inventory tracking, sales, and invoice generation."
header:
  teaser: /assets/images/sbapp-1.png
gallery:
  - url: /assets/images/sbapp-1.png
    image_path: /assets/images/sbapp-1.png
    alt: "Inventory management view"
  - url: /assets/images/sbapp-2.png
    image_path: /assets/images/sbapp-2.png
    alt: "Sale screen with numpad"
  - url: /assets/images/sbapp-3.png
    image_path: /assets/images/sbapp-3.png
    alt: "Bulk price editing"
  - url: /assets/images/sbapp-4.png
    image_path: /assets/images/sbapp-4.png
    alt: "Product creation form"
  - url: /assets/images/sbapp-5.png
    image_path: /assets/images/sbapp-5.png
    alt: "Bulk add workflow"
gallery2:
  - url: /assets/images/sbapp-1.png
    image_path: /assets/images/sbapp-1.png
    alt: "Inventory management view"
  - url: /assets/images/sbapp-2.png
    image_path: /assets/images/sbapp-2.png
    alt: "Sale screen with numpad"
  - url: /assets/images/sbapp-3.png
    image_path: /assets/images/sbapp-3.png
    alt: "Bulk price editing"
tags: [Flutter, Dart, Firebase, Riverpod, Docker, GitHub Actions, Mobile]
---

{% include gallery id="gallery2" layout="third" %}

## Overview
A fully functional cross-platform mobile application for small business owners to 
manage their products, track inventory in real time, record sales, and generate 
invoices — built to production engineering standards with a clean architecture and 
automated CI/CD pipeline.

## Features
- **Product Catalog** — List, search, and filter products
- **Inventory Tracking** — Real-time stock levels with low-stock indicators
- **CRUD Operations** — Add, edit, and delete products with full validation
- **Invoice & Receipt Generation** — PDF generation and email delivery *(in progress)*
- **Authentication** — Firebase Auth with role-based access planned

## Engineering Highlights
This isn't a tutorial app. It's built with the same patterns used in professional 
mobile development:

- **MVVM Architecture** — Clean separation between UI, business logic, and data layers
- **Riverpod** — Scalable, testable state management throughout
- **Dockerized Firebase Emulator** — Consistent local development environment, 
  no cloud dependency during development
- **GitHub Actions CI/CD** — Automated `flutter analyze` and `flutter test` 
  runs on every push

## Tech Stack
- **Frontend:** Flutter (Dart)
- **State Management:** Riverpod
- **Backend:** Firebase Firestore + Authentication
- **Infrastructure:** Docker, GitHub Actions
- **Platform:** iOS & Android

## Source Code
The source code is private but available upon request for recruitment purposes.

[Portfolio Repo →](https://github.com/KingSherriff/SBApp-Portfolio)  
[Request Source Access →](mailto:sherriff.kadiri@outlook.com)

{% include gallery caption="App screenshots" %}