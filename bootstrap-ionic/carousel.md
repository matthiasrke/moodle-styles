# Carousel

### Bootstrap & Ionic

### Browser
![carousel-browser](screenshots/carousel-browser.png)

### Moodle App
![carousel-app](screenshots/carousel-app.png)

```
<div id="carouselExampleIndicators" class="carousel slide pointer-event" data-ride="carousel" data-interval="false">
    <ol class="carousel-indicators ion-hide">
        <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
        <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
        <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
    </ol>
    <ion-slides pager="true" class="carousel-inner">
        <ion-slide class="carousel-item active">
            <img src="..." class="d-block w-100" alt="First slide">
        </ion-slide>
        <ion-slide class="carousel-item">
            <img src="..." class="d-block w-100" alt="Second slide">
        </ion-slide>
        <ion-slide class="carousel-item">
            <img src="..." class="d-block w-100" alt="Third slide">
        </ion-slide>
    </ion-slides>
    <a class="carousel-control-prev shadow-none" href="#carouselExampleIndicators" role="button" data-slide="prev">
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="sr-only">Previous</span>
    </a>
    <a class="carousel-control-next shadow-none" href="#carouselExampleIndicators" role="button" data-slide="next">
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="sr-only">Next</span>
    </a>
</div>
```

### Links
- https://getbootstrap.com/docs/4.6/components/carousel/
- https://ionicframework.com/docs/api/slides
