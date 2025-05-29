---
layout: default
title: Pensjonat u Marysi i Li-Mar | umarysi.pl
---

{% include hero.html %}

<section class="booking-form-section">
    <div class="container">
        <form class="booking-form">
            <div class="form-group">
                <label for="checkin-date" class="sr-only">Zameldowanie</label>
                <input type="text" name="checkin_date" id="checkin-date" class="form-control date-picker" placeholder="Zameldowanie 27/05/2025">
            </div>
            <div class="form-group">
                <label for="checkout-date" class="sr-only">Wymeldowanie</label>
                <input type="text" name="checkout_date" id="checkout-date" class="form-control date-picker" placeholder="Wymeldowanie 27/05/2025">
            </div>
            <div class="form-group">
                <label for="guests" class="sr-only">Ilość gości</label>
                <input type="number" name="guests_count" id="guests" class="form-control" placeholder="Ilość gości" min="1">
            </div>
            <div class="form-group">
                <label for="phone" class="sr-only">Numer telefonu</label>
                <input type="tel" name="phone_number" id="phone" class="form-control" placeholder="Numer telefonu">
            </div>
            <button type="submit" class="btn btn-primary">Wyślij</button>
        </form>
        <p class="discount-info">Oferujemy atrakcyjne zniżki dla firm! Zachęcamy do skontaktowania się z nami telefonicznie, aby uzyskać szczegółowe informacje i dostosować ofertę do Państwa potrzeb.</p>
        <h2 class="form-heading">Wyślij nam zapytanie, a my do Ciebie oddzwonimy!</h2>
    </div>
</section>

{% include about.html %}

{% include amenities.html %}

{% include testimonials.html %}

<section class="rooms-section">
    <div class="container">
        <div class="column content-column">
            <h2 class="section-subtitle">POKOJE</h2>
            <h2 class="section-title">Pokoje dla Podróżujących i Rodzin</h2>
            <p>Oferujemy atrakcyjne zniżki dla firm! Zachęcamy do skontaktowania się z nami telefonicznie, aby uzyskać szczegółowe informacje i dostosować ofertę do Państwa potrzeb.</p>
            <div class="contact-info">
                <i class="icon icon-phone1"></i>
                <div class="info-content">
                    <p class="info-title">Rezerwacja</p>
                    <p class="info-description"><a href="tel:730 294 158">+48 730 294 158</a></p>
                </div>
            </div>
        </div>
        <div class="column image-column">
            </div>
    </div>

    <div class="room-types-grid">
        <div class="room-type-item" style="background-image: url('https://umarysi.pl/wp-content/uploads/2024/04/514675285.jpg');">
            <div class="overlay"></div>
            <h3>Jednoosobowy</h3>
        </div>
        <div class="room-type-item" style="background-image: url('https://umarysi.pl/wp-content/uploads/2025/04/671197886.jpg');">
            <div class="overlay"></div>
            <h3>Dwuosobowy</h3>
        </div>
        <div class="room-type-item" style="background-image: url('https://umarysi.pl/wp-content/uploads/2025/04/671197165.jpg');">
            <div class="overlay"></div>
            <h3>3-4 Osobowe</h3>
        </div>
    </div>
</section>

<section class="restaurant-section">
    <div class="container reverse-on-mobile">
        <div class="column content-column">
            <h2 class="section-subtitle">1 maja 2025</h2>
            <h2 class="section-title">Od 1 maja zapraszamy do Smażalni Ryb "Sandacz" oraz Wędzarni Ryb "Rybka"</h2>
            <p>Zapraszamy serdecznie do Smażalni Ryb „Sandacz” oraz Wędzarni Ryb „Rybka”! Już od 1 maja czeka na Was wyjątkowa uczta smaków prosto z serca natury. Świeże, aromatyczne ryby smażone na złoty kolor oraz delikatnie wędzone specjały zachwycą nawet najbardziej wymagające podniebienia. W naszej ofercie znajdziecie m.in. sandacza, pstrąga i wiele innych pyszności, które przyrządzamy z pasją i dbałością o każdy szczegół.</p>
            <div class="buttons-group">
                <a href="https://g.co/kgs/jwHrLts" target="_blank" class="btn">Smażalnia w Google</a>
                <a href="https://g.co/kgs/mcUcTkm" target="_blank" class="btn">Wędzarnia w Google</a>
            </div>
        </div>
        <div class="column image-column">
            <img src="https://umarysi.pl/wp-content/uploads/2025/01/2024-08-01.jpg" alt="Smażalnia Ryb" class="img-fluid">
        </div>
    </div>
</section>

<style>
/* General styles */
body {
    font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;
    margin: 0;
    line-height: 1.6;
    color: #333;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
}

.container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 20px;
}

section {
    padding: 80px 0;
    position: relative;
    overflow: hidden;
}

h1, h2, h3, h4, h5, h6 {
    margin-top: 0;
    margin-bottom: 20px;
    line-height: 1.2;
    color: #333;
}

.btn {
    display: inline-block;
    background-color: #007bff; /* Primary brand color */
    color: #fff;
    padding: 12px 25px;
    text-decoration: none;
    border-radius: 5px;
    transition: background-color 0.3s ease, transform 0.2s ease;
    font-weight: 600;
    text-align: center;
    border: none;
    cursor: pointer;
}

.btn:hover {
    background-color: #0056b3;
    transform: translateY(-2px);
}

.img-fluid {
    max-width: 100%;
    height: auto;
    display: block;
}

/* Screen reader only for accessibility */
.sr-only {
    position: absolute;
    width: 1px;
    height: 1px;
    padding: 0;
    margin: -1px;
    overflow: hidden;
    clip: rect(0, 0, 0, 0);
    white-space: nowrap;
    border: 0;
}

/* Header (if re-added to default.html) */
/* (Not included in this single file, assuming default.html handles it) */

/* Hero Slider */
.hero-slider {
    position: relative;
    height: 70vh; /* Responsive height */
    min-height: 450px;
    overflow: hidden;
    background-color: #eee; /* Fallback */
}

.hero-slider .swiper-slide {
    background-size: cover;
    background-position: center center;
    background-repeat: no-repeat;
    display: flex;
    align-items: center;
    justify-content: flex-start; /* Aligned left as per original */
    color: #fff;
    position: relative;
    /* animation: kenBurnsIn 15s infinite alternate; /* Simulate ken burns - controlled by Swiper's effect */
}

/* Swiper specific styles to fix visible multiple slides */
.swiper-container {
  width: 100%;
  height: 100%;
  position: relative; /* Ensure it contains the slides properly */
  overflow: hidden; /* Hide overflow from other slides */
}

.swiper-wrapper {
  display: flex; /* Ensure slides align correctly */
  position: relative;
  width: 100%;
  height: 100%;
}

.swiper-slide {
  flex-shrink: 0; /* Prevent shrinking */
  width: 100%;
  height: 100%;
  position: relative;
  transition-property: transform; /* Animate transform */
}


.hero-slider .swiper-slide::before {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-color: rgba(0, 0, 0, 0.5); /* Overlay */
    z-index: 0;
}

.hero-slider .slide-content {
    position: relative;
    z-index: 1;
    padding: 50px;
    max-width: 650px;
    text-align: left;
    /* Initial state for fadeInUp - controlled by JS animation */
    /* opacity: 0; */
    /* animation: fadeInUp 1s forwards cubic-bezier(0.2, 0.8, 0.2, 1); */
    /* animation-delay: 0.5s; */
}

.hero-slider .slide-content h2 {
    font-size: 45px;
    font-weight: 700;
    margin-bottom: 25px;
    color: #fff;
}

.hero-slider .slide-content p {
    font-size: 18px;
    line-height: 1.5;
    margin-bottom: 35px;
    color: #eee;
}

.hero-slider .btn {
    border: 2px solid #fff;
    color: #fff;
    background: transparent;
    padding: 10px 25px;
    font-size: 16px;
    font-weight: 500;
    border-radius: 30px;
}

.hero-slider .btn:hover {
    background-color: rgba(255, 255, 255, 0.2);
}

.swiper-button-prev, .swiper-button-next {
    color: #fff;
    width: 40px;
    height: 40px;
    background-color: rgba(0,0,0,0.3);
    border-radius: 50%;
    transition: background-color 0.3s ease;
    position: absolute; /* Swiper adds this by default, but good to be explicit */
    top: 50%;
    transform: translateY(-50%);
    z-index: 10; /* Ensure it's above slides */
    cursor: pointer;
}

.swiper-button-prev {
    left: 10px;
}

.swiper-button-next {
    right: 10px;
}

.swiper-button-prev:hover, .swiper-button-next:hover {
    background-color: rgba(0,0,0,0.6);
}

.swiper-button-prev::after, .swiper-button-next::after {
    font-size: 20px;
}

/* Booking Form */
.booking-form-section {
    background-color: #f7f7f7;
    padding: 50px 0;
    text-align: center;
    box-shadow: inset 0 5px 10px rgba(0,0,0,0.02);
}

.booking-form {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 20px;
    margin-bottom: 30px;
}

.booking-form .form-group {
    flex: 1 1 auto; /* Allow items to grow/shrink */
    min-width: 180px; /* Minimum width for responsiveness */
    max-width: 220px; /* Limit max width for smaller inputs */
}

.booking-form .form-control {
    width: 100%;
    padding: 12px 15px;
    border: 1px solid #ddd;
    border-radius: 8px;
    box-sizing: border-box;
    font-size: 16px;
    color: #333;
    background-color: #fff;
    transition: border-color 0.3s ease, box-shadow 0.3s ease;
}

.booking-form .form-control::placeholder {
    color: #aaa;
}

.booking-form .form-control:focus {
    border-color: #007bff;
    box-shadow: 0 0 0 3px rgba(0, 123, 255, 0.25);
    outline: none;
}

.booking-form .btn-primary {
    flex: 1 1 auto;
    min-width: 180px;
    max-width: 220px;
    padding: 14px 20px;
    font-size: 18px;
    font-weight: 700;
    background-color: #28a745; /* Green for action */
}

.booking-form .btn-primary:hover {
    background-color: #218838;
}

.discount-info {
    margin-top: 25px;
    font-style: italic;
    color: #666;
    font-size: 16px;
    max-width: 700px;
    margin-left: auto;
    margin-right: auto;
}

.form-heading {
    margin-top: 40px;
    font-size: 30px;
    font-weight: 700;
    color: #333;
}

/* About Section & similar content sections */
.about-section, .restaurant-section, .testimonials-section, .rooms-section {
    background: linear-gradient(135deg, #f0f8ff, #e0f2f7); /* Light blue gradient */
    padding: 80px 0;
    box-sizing: border-box;
}

.about-section .container, .restaurant-section .container, .testimonials-section .container, .rooms-section .container {
    display: flex;
    flex-wrap: wrap;
    align-items: center;
    gap: 40px;
}

.about-section .column, .restaurant-section .column, .testimonials-section .column, .rooms-section .column {
    flex: 1;
    min-width: 300px; /* Ensure content doesn't get too narrow */
}

.about-section .image-column {
    position: relative;
    min-height: 450px; /* Space for positioned images */
    display: flex; /* To manage inner image positioning */
    align-items: center;
    justify-content: center;
}

.about-section .image-column .image-1 {
    position: absolute;
    top: 0;
    left: 0;
    width: 85%; /* Slightly larger */
    height: auto;
    box-shadow: 0 15px 30px rgba(0,0,0,0.2);
    border-radius: 8px;
    transition: transform 0.5s ease;
    animation: slideInUp 1s ease-out forwards;
}

.about-section .image-column .image-2 {
    position: absolute;
    bottom: -30px; /* Slightly lower */
    right: 0;
    width: 55%; /* Slightly larger */
    height: auto;
    box-shadow: 0 15px 30px rgba(0,0,0,0.3);
    border-radius: 8px;
    transition: transform 0.5s ease;
}
/* Ensure z-index for overlapping */
.about-section .image-column .image-1 { z-index: 2; }
.about-section .image-column .image-2 { z-index: 3; }


.section-subtitle {
    font-size: 18px;
    color: #777;
    margin-bottom: 10px;
    text-transform: uppercase;
    letter-spacing: 1px;
}

.section-title {
    font-size: 40px;
    font-weight: 700;
    margin-bottom: 25px;
    color: #333;
}

p {
    font-size: 17px;
    line-height: 1.7;
    margin-bottom: 20px;
    color: #555;
}

.dropcap {
    font-size: 1.2em;
    line-height: 1.5;
}

.dropcap span {
    float: left;
    font-size: 4em;
    line-height: 0.8;
    margin-right: 10px;
    font-weight: bold;
    color: #007bff; /* Primary brand color */
}

.contact-info {
    display: flex;
    align-items: center;
    margin-top: 30px;
    gap: 15px;
}

.contact-info .icon {
    font-size: 35px;
    color: #007bff; /* Primary brand color */
}
/* Font Awesome icons - you need to include Font Awesome library in default.html */
.icon.icon-phone1:before { content: "\f095"; font-family: 'Font Awesome 5 Free'; font-weight: 900; }
.icon.icon-flower:before { content: "\f72b"; font-family: 'Font Awesome 5 Free'; font-weight: 900; }
.icon.icon-play-button:before { content: "\f144"; font-family: 'Font Awesome 5 Free'; font-weight: 900; }
.icon.icon-quote2:before { content: "\f10e"; font-family: 'Font Awesome 5 Free'; font-weight: 900; }

/* For dticon-like icons, assuming they are also Font Awesome or similar mapping */
.dticon {
    font-family: 'Font Awesome 5 Free';
    font-weight: 900;
    speak: none;
    font-style: normal;
    font-variant: normal;
    text-transform: none;
    line-height: 1;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
}
.dticon-car-outline:before { content: "\f5e1"; } /* Example: fa-car-alt */
.dticon-flower-outline:before { content: "\f72b"; } /* Example: fa-seedling, using flower as placeholder */
.dticon-water-outline:before { content: "\f043"; } /* Example: fa-tint */
.dticon-pricetag-outline:before { content: "\f02b"; } /* Example: fa-tag */


.contact-info .info-content {
    display: flex;
    flex-direction: column;
}

.contact-info .info-title {
    font-weight: 600;
    margin-bottom: 5px;
    color: #333;
    font-size: 16px;
}

.contact-info .info-description a {
    color: #007bff;
    text-decoration: none;
    font-size: 18px;
    font-weight: 500;
    transition: color 0.3s ease;
}

.contact-info .info-description a:hover {
    color: #0056b3;
}

/* Amenities Section */
.amenities-section {
    background-color: #f8f8f8;
    text-align: center;
    padding: 80px 0;
}

.amenities-description {
    max-width: 800px;
    margin: 0 auto 50px;
}

.divider {
    margin: 50px auto;
    width: 150px;
    height: 2px;
    background-color: #ddd;
    position: relative;
}

.divider .icon {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    background-color: #f8f8f8;
    padding: 0 15px;
    font-size: 28px;
    color: #007bff; /* Primary brand color */
}

.amenities-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    gap: 30px;
    margin-top: 40px;
}

.amenity-item {
    background-color: #fff;
    padding: 35px;
    border-radius: 10px;
    box-shadow: 0 8px 20px rgba(0,0,0,0.08);
    transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.amenity-item:hover {
    transform: translateY(-5px);
    box-shadow: 0 12px 25px rgba(0,0,0,0.15);
}

.amenity-icon {
    font-size: 50px;
    color: #007bff; /* Primary brand color */
    margin-bottom: 20px;
}

.amenity-title {
    font-size: 24px;
    font-weight: 600;
    margin-bottom: 15px;
    color: #333;
}

.amenity-text {
    font-size: 15px;
    color: #666;
}

/* Testimonials Section */
.testimonials-section {
    background-color: #f0f0f0;
    padding: 80px 0;
}

.testimonials-section .column.content-column {
    background-color: #fff;
    padding: 40px;
    border-radius: 10px;
    box-shadow: 0 10px 25px rgba(0,0,0,0.1);
    min-width: 350px;
}

.testimonial-carousel {
    margin-top: 30px;
}

.elementor-testimonial {
    padding: 20px;
    text-align: left;
}

.elementor-testimonial__text {
    font-size: 18px;
    line-height: 1.8;
    color: #444;
    margin-bottom: 20px;
}

.elementor-testimonial__cite {
    font-style: normal;
    font-weight: 600;
    color: #007bff;
    font-size: 16px;
}

/* Rooms Section */
.rooms-section {
    background-color: #e6f7ff; /* Lighter blue */
    padding-bottom: 0; /* No padding at bottom for room grid */
}

.rooms-section .column.content-column {
    flex: 1 1 45%; /* Adjust column width */
    max-width: 550px;
}

.rooms-section .column.image-column {
    flex: 1 1 45%;
    display: flex;
    justify-content: flex-end; /* Align images to the right */
    align-items: flex-end;
    min-height: 400px;
    position: relative;
}

.room-types-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 0; /* No gap between items for full width effect */
    margin-top: 80px; /* Push below content */
}

.room-type-item {
    position: relative;
    height: 400px;
    background-size: cover;
    background-position: center;
    display: flex;
    align-items: flex-end;
    justify-content: center;
    color: #fff;
    text-align: center;
    padding: 30px;
    box-sizing: border-box;
    transition: transform 0.3s ease;
}

.room-type-item:hover {
    transform: scale(1.03);
}

.room-type-item .overlay {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: linear-gradient(to top, rgba(0,0,0,0.7) 0%, rgba(0,0,0,0) 50%);
    z-index: 1;
}

.room-type-item h3 {
    position: relative;
    z-index: 2;
    font-size: 28px;
    font-weight: 700;
    color: #fff;
    margin: 0;
}

/* Restaurant Section */
.restaurant-section {
    background: linear-gradient(135deg, #fff7e6, #ffeacd); /* Warm, light orange gradient */
    padding: 80px 0;
}

.restaurant-section .column.image-column {
    display: flex;
    justify-content: center;
    align-items: center;
}

.restaurant-section .column.image-column img {
    border-radius: 10px;
    box-shadow: 0 15px 30px rgba(0,0,0,0.2);
    transition: transform 0.5s ease;
    animation: fadeInDown 1s ease-out forwards;
}

.buttons-group {
    display: flex;
    gap: 15px;
    margin-top: 30px;
    flex-wrap: wrap;
}

/* Footer (if re-added to default.html) */
/* (Not included in this single file, assuming default.html handles it) */

/* Responsive adjustments */
@media (max-width: 992px) {
    .container {
        padding: 0 15px;
    }

    section {
        padding: 60px 0;
    }

    .hero-slider {
        height: 50vh;
        min-height: 350px;
    }

    .hero-slider .slide-content {
        padding: 30px;
        max-width: 80%;
    }

    .hero-slider .slide-content h2 {
        font-size: 35px;
    }

    .hero-slider .slide-content p {
        font-size: 16px;
    }

    .booking-form {
        flex-direction: column;
        align-items: center;
    }

    .booking-form .form-group,
    .booking-form .btn-primary {
        max-width: 350px; /* Wider inputs for mobile */
        min-width: unset;
        width: 100%;
    }

    .about-section .container,
    .restaurant-section .container,
    .testimonials-section .container,
    .rooms-section .container {
        flex-direction: column;
    }

    .about-section .image-column {
        min-height: 300px;
    }
    .about-section .image-column .image-1,
    .about-section .image-column .image-2 {
        position: relative;
        width: 100%;
        left: unset;
        top: unset;
        right: unset;
        bottom: unset;
        margin-bottom: 20px;
        transform: none; /* Reset animation for stacking */
        animation: none;
    }
    .about-section .container.reverse-on-mobile {
        flex-direction: column-reverse; /* For reverse order on mobile */
    }

    .section-title {
        font-size: 32px;
    }

    .amenities-grid {
        grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
        gap: 20px;
    }

    .room-types-grid {
        grid-template-columns: 1fr; /* Stack rooms on mobile */
    }

    .buttons-group {
        flex-direction: column;
        align-items: center;
    }

    .buttons-group .btn {
        width: 100%;
        max-width: 300px;
    }
}

@media (max-width: 768px) {
    /* (Assuming header is in default.html) */

    .hero-slider {
        height: 40vh;
        min-height: 300px;
    }
    .hero-slider .slide-content h2 {
        font-size: 28px;
        margin-bottom: 15px;
    }
    .hero-slider .slide-content p {
        font-size: 14px;
        margin-bottom: 20px;
    }
    .hero-slider .btn {
        padding: 8px 18px;
        font-size: 14px;
    }

    .section-title {
        font-size: 28px;
    }

    .amenity-icon {
        font-size: 40px;
    }
    .amenity-title {
        font-size: 20px;
    }
    .amenity-text {
        font-size: 14px;
    }
}

/* Animations */
@keyframes fadeInUp {
    from {
        opacity: 0;
        transform: translateY(20px);
    }
    to {
        opacity: 1;
        transform: translateY(0);
    }
}

@keyframes slideInUp {
    from {
        opacity: 0;
        transform: translateY(50px);
    }
    to {
        opacity: 1;
        transform: translateY(0);
    }
}

@keyframes fadeInDown {
    from {
        opacity: 0;
        transform: translateY(-50px);
    }
    to {
        opacity: 1;
        transform: translateY(0);
    }
}

@keyframes zoomIn {
    from {
        opacity: 0;
        transform: scale(0.8);
    }
    to {
        opacity: 1;
        transform: scale(1);
    }
}

@keyframes bounceInRight {
    from,
    60%,
    75%,
    90%,
    to {
        animation-timing-function: cubic-bezier(0.215, 0.61, 0.355, 1);
    }
    0% {
        opacity: 0;
        transform: translate3d(3000px, 0, 0);
    }
    60% {
        opacity: 1;
        transform: translate3d(-25px, 0, 0);
    }
    75% {
        transform: translate3d(10px, 0, 0);
    }
    90% {
        transform: translate3d(-5px, 0, 0);
    }
    to {
        transform: none;
    }
}

/* Basic Ken Burns effect for slider */
/* This CSS animation can be combined with Swiper or replaced by Swiper's own effects */
@keyframes kenBurnsIn {
    0% {
        transform: scale(1);
        background-position: 50% 50%;
    }
    100% {
        transform: scale(1.1);
        background-position: 60% 40%;
    }
}
</style>