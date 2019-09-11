# Design Technologist - CSS task

## Introduction

Welcome to the September 2019 King's Online design technologist task. This is a short CSS-based task that is designed to see how you approach responding to a simple brief. Please clone this repository and commit changes to your own git repository and then email the link to louise.bennett@kcl.ac.uk by **Thursday, September 12th at 17.00**. 

## The task

The King's Online UX team is currently producing a design system that will be used across all King's Online programmes. The design system covers everything from the navigation of our Moodle courses to the layout and bootstrap-based components used within them for presenting content and activities. 

As each component of the design is finished, the UX designers produce documents detailing the specs of each element within them, so that the development team can produce the CSS that will style them. 

For this task, you will be given the spec for one component (a carousel), as well as the html code that builds it. Your task is to produce the CSS to ensure the component output matches the spec. 

Additionally, as this carousel will be used to present learning material, you should ensure that the carousel does not automatically cycle or loop. 

## The spec

The [spec for this project is here](/assets/Carousel.pdf).

Please note: we have NOT provided the font files used in the spec. In this instance, please replace with the following: 

*Headings* - Impact, regular weight

*Body text* - Georgia

## The code

```html
<div id="ph-m1-carousel-1" class="carousel slide">
  <ol class="carousel-indicators">
    <li data-target="#ph-m1-carousel-1" data-slide-to="0" class="active"></li>
    <li data-target="#ph-m1-carousel-1" data-slide-to="1"></li>
    <li data-target="#ph-m1-carousel-1" data-slide-to="2"></li>
  </ol>
  <div class="carousel-inner">
    <div class="carousel-item active">
    <img src="https://placekitten.com/800/400" class="w-100" alt="An adorable kitten">
    <div class="carousel-caption">
      <p>
        Carousel slide #1 text
      </p>
    </div>
  </div><div class="carousel-item">
    <img src="https://placekitten.com/800/400" class="w-100" alt="An adorable kitten">
    <div class="carousel-caption">
      <p>
        Carousel slide #2 text
      </p>
    </div>
  </div><div class="carousel-item">
    <img src="https://placekitten.com/800/400" class="w-100" alt="An adorable kitten">
    <div class="carousel-caption">
      <p>
        Carousel slide #3 text
      </p>
    </div>
  </div>
  </div>
  <a class="carousel-control-prev" href="#ph-m1-carousel-1" role="button" data-slide="prev">
    <span class="carousel-control prev-icon" aria-hidden="true"><i class="fas fa-angle-left"></i></span>
    <span class="sr-only">Previous</span>
  </a>
  <a class="carousel-control-next" href="#ph-m1-carousel" role="button" data-slide="next">
    <span class="carousel-control next-icon" aria-hidden="true"><i class="fas fa-angle-right"></i></span>
    <span class="sr-only">Next</span>
  </a>
</div>
```

## Resources 

* [Bootstrap v4](https://getbootstrap.com/)
* [FontAwesome](https://fontawesome.com/)
