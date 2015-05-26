---
title: Photoplacer
summary: A light weight Lumen application for embedding temporary images in a web template. Host your own stock images for use in your design & development workflow.
collection: portfolio
tags: 
    - PHP
    - Lumen
accent: "#009058"
---

Photoplacer is a simple PHP application for providing placeholder images for your projects. It allows you to define your own categories for organising your image bank, and also to apply various filters to your images on the fly.

![Home page](/images/portfolio/photoplacer/homepage.png)

Aiming for simplicity and speed, the Lumen PHP micro-framework was chosen as a suitable base due to its basis on the reliable and well-documented Laravel framework. The result is a lean application with a great deal of flexibility allowing for its primary users, front-end developers to quickly populate the image store and organise their images by category.

Complete with a full suite of [tests](https://github.com/Jamesyps/Photoplacer/blob/master/tests/ImageControllerRoutesTest.php), the code is robust, maintainable and 100% open source.

![UI](/images/portfolio/photoplacer/ui.png)

The UI reflects the simple URL structure for accessing images. I wished to avoid the unclear structure of /width/height/category, instead implementing the well known width x height notation. Filters continue this clear labeling of URL segments, having a prefix of filter: so at no point can users be uncertain between width, height, categories or filter types.

![Landing Page](/images/portfolio/photoplacer/project-page.png)

Accompanying this project, a [re-usable Jekyll template](https://github.com/Jamesyps/Jekyll-Project-Page) was created to serve as the products landing page, containing installation instructions, configuration help and other important documentation.

### Further Reading

You can see more by visiting the project page and source code.

* [Project Page](http://photoplacer.jameswigger.co.uk)
* [Repository](https://github.com/Jamesyps/Photoplacer)