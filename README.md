<!DOCTYPE html>
<html>

<head>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z" crossorigin="anonymous">
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js" integrity="sha384-B4gt1jrGC7Jh4AgTPSdUtOBvfO8shuf57BaghqFfPlYxofvL8/KUEfYiJOMMV+rV" crossorigin="anonymous"></script>
</head>

<body>
    <div id="sectionHome">
        <div class="bg-container d-flex flex-column justify-content-end">
            <div class="tourism-card">
                <h1 class="main-heading">Big Cats Week at Maasai Mara</h1>
                <p class="paragraph">Diwali 2023 special.</p>
                <button class="button" onclick="display('sectionFavouritePlaces')">Get Started</button>

            </div>
        </div>
    </div>

    <div id="sectionFavouritePlaces">
        <div class="favourite-places-bg-container">
            <h1 class="favourite-places-heading">Places</h1>
            <div class="favourite-place-card-container d-flex flex-row" onclick="display('sectionTajMahalDetailedView')">
                <div>
                    <h1 class="favourite-place-card-heading">Nairobi
                        national park</h1>
                    <p class="favourite-place-card-description">
                        The World's only Wildlife Capital. it is one of only a few parks where visitors can be certain of seeing a black rhinoceros in its natural habitat.
                    </p>
                </div>
                <img src="https://netstorage-tuko.akamaized.net/images/0a85becc7c67bd3d.jpg?&imwidth=1200" class="favourite-place-card-image" />
            </div>
            <div class="favourite-place-card-container d-flex flex-row" onclick="display('sectionGoldenTempleDetailedView')">
                <div>
                    <h1 class="favourite-place-card-heading">The Great Rift Valley</h1>
                    <p class="favourite-place-card-description">
                        The most well-known rift valley on Earth
                        is probably the so-called "Great Rift Valley System"
                    </p>
                </div>
                <img src="https://study.com/cimages/videopreview/african-rift-valley-formation-and-overview_115720.jpg" class="favourite-place-card-image" />
            </div>
            <div class="favourite-place-card-container d-flex flex-row">
                <div>
                    <h1 class="favourite-place-card-heading">Sand river</h1>
                    <p class="favourite-place-card-description">

                        The largest and most well-known river is the Mara River.
                        It flows straight through the Masai Mara and into the Serengeti.
                    </p>
                </div>
                <img src="https://www.masaimara.travel/images/sand-river-gate-masai-mara-kenya-mobile.jpg" class="favourite-place-card-image" />
            </div>
        </div>
    </div>

    <div id="sectionTajMahalDetailedView">
        <div class="detailed-view-bg-container">
            <h1 class="detailed-view-heading">Detailed View</h1>
            <div class="detailed-view-card-container">
                <div id="carouselExampleIndicators1" class="carousel slide" data-ride="carousel">
                    <ol class="carousel-indicators">
                        <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
                        <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
                        <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
                    </ol>
                    <div class="carousel-inner">
                        <div class="carousel-item active">
                            <img src="https://media.tacdn.com/media/attractions-splice-spp-674x446/07/90/bd/9e.jpg" class="d-block w-100" alt="..." />
                        </div>
                        <div class="carousel-item">
                            <img src="https://www.kids365.org/wp-content/uploads/2021/02/Nairobi-National-Park-lion-1400x744.jpg" class="d-block w-100" alt="..." />
                        </div>
                        <div class="carousel-item">
                            <img src="https://nationalparks-15bc7.kxcdn.com/images/parks/nairobi/Nairobi%20National%20Park%20herd%20of%20elephant.jpg" class="d-block w-100" alt="..." />
                        </div>
                    </div>
                    <a class="carousel-control-prev" href="#carouselExampleIndicators1" role="button" data-slide="prev">
                        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                        <span class="sr-only">Previous</span>
                    </a>
                    <a class="carousel-control-next" href="#carouselExampleIndicators1" role="button" data-slide="next">
                        <span class="carousel-control-next-icon" aria-hidden="true"></span>
                        <span class="sr-only">Next</span>
                    </a>
                </div>
                <div class="detailed-view-card-text-container">
                    <h1 class="detailed-view-card-heading">Nairobi national park</h1>
                    <p class="detailed-view-card-description">
                        “The World's only Wildlife Capital”

                        Wide open grass plains and backdrop of the city scrapers,
                        scattered acacia bush play host to a wide variety of wildlife
                        including the endangered black rhino, lions, leopards, cheetahs, hyenas, buffaloes,
                        giraffes and diverse birdlife with over 400 species recorded.

                    </p>
                </div>
            </div>
            <button class="btn btn-dark" onclick="display('sectionFavouritePlaces')">
                back
            </button>
        </div>
    </div>
    <div id="sectionGoldenTempleDetailedView">
        <div class="detailed-view-bg-container">
            <h1 class="detailed-view-heading">Detailed View</h1>
            <div class="detailed-view-card-container">
                <div id="goldenTempleCarousel" class="carousel slide" data-ride="carousel">
                    <ol class="carousel-indicators">
                        <li data-target="#goldenTempleCarousel" data-slide-to="0" class="active"></li>
                        <li data-target="#goldenTempleCarousel" data-slide-to="1"></li>
                        <li data-target="#goldenTempleCarousel" data-slide-to="2"></li>
                    </ol>
                    <div class="carousel-inner">
                        <div class="carousel-item active">
                            <img src="https://www.safarisrwandasafari.com/wp-content/uploads/2022/10/31224_c0-41-990-701_r1050x700-1.jpg" class="d-block w-100" alt="..." />
                        </div>
                        <div class="carousel-item">
                            <img src="https://www.thoughtco.com/thmb/b6o-DRRF_0ah7TZR97zgIWOk0NQ=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc()/ethiopia-rift-valley-aerial-view-sb10068596hq-001-5878cd753df78c17b65b7898.jpg" class="d-block w-100" alt="..." />
                        </div>
                        <div class="carousel-item">
                            <img src="https://study.com/cimages/videopreview/african-rift-valley-formation-and-overview_115720.jpg" class="d-block w-100" alt="..." />
                        </div>
                    </div>
                    <a class="carousel-control-prev" href="#goldenTempleCarousel" role="button" data-slide="prev">
                        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                        <span class="sr-only">Previous</span>
                    </a>
                    <a class="carousel-control-next" href="#goldenTempleCarousel" role="button" data-slide="next">
                        <span class="carousel-control-next-icon" aria-hidden="true"></span>
                        <span class="sr-only">Next</span>
                    </a>
                </div>
                <div class="detailed-view-card-text-container">
                    <h1 class="detailed-view-card-heading">The Great Rift Valley.</h1>
                    <p class="detailed-view-card-description">
                        The most well-known rift valley on Earth is probably the so-called "Great Rift Valley System"
                        which stretches from the Middle East in the north to Mozambique in the south.
                        The area is geologically active, and features volcanoes, hot springs, geysers, and frequent earthquakes.
                    </p>

                </div>
            </div>
            <button class="btn btn-dark" onclick="display('sectionFavouritePlaces')">
                back
            </button>
            <div id="sectionGoldenTempleDetailedView">
                <div class="detailed-view-bg-container">
                    <h1 class="detailed-view-heading">Detailed View</h1>
                    <div class="detailed-view-card-container">
                        <div id="goldenTempleCarousel" class="carousel slide" data-ride="carousel">
                            <ol class="carousel-indicators">
                                <li data-target="#goldenTempleCarousel" data-slide-to="0" class="active"></li>
                                <li data-target="#goldenTempleCarousel" data-slide-to="1"></li>
                                <li data-target="#goldenTempleCarousel" data-slide-to="2"></li>
                            </ol>
                            <div class="carousel-inner">
                                <div class="carousel-item active">
                                    <img src="https://www.masaimara.travel/images/sand-river-gate-masai-mara-kenya-mobile.jpg" class="d-block w-100" alt="..." />
                                </div>
                                <div class="carousel-item">
                                    <img src="https://c8.alamy.com/comp/E2G88X/kenya-masai-mara-game-reserve-sand-river-E2G88X.jpg" class="d-block w-100" alt="..." />
                                </div>
                                <div class="carousel-item">
                                    <img src="https://upload.wikimedia.org/wikipedia/commons/a/a4/Mara_River_Massai_Mara.jpg" class="d-block w-100" alt="..." />
                                </div>
                            </div>
                            <a class="carousel-control-prev" href="#goldenTempleCarousel" role="button" data-slide="prev">
                                <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                                <span class="sr-only">Previous</span>
                            </a>
                            <a class="carousel-control-next" href="#goldenTempleCarousel" role="button" data-slide="next">
                                <span class="carousel-control-next-icon" aria-hidden="true"></span>
                                <span class="sr-only">Next</span>
                            </a>
                        </div>
                        <div class="detailed-view-card-text-container">
                            <h1 class="detailed-view-card-heading">Sand river</h1>
                            <p class="detailed-view-card-description">
                                The largest and most well-known river is the Mara River.
                                It flows straight through the Masai Mara and into the Serengeti.
                                The Mara River basin covers a surface of approximately 13,504 square kilometres and has a length of 395 kilometres.

                            </p>


                        </div>

                    </div>
                    <button class="btn btn-dark" onclick="display('sectionFavouritePlaces')">
                        back
                    </button>
                </div>
            </div>


            <script type="text/javascript" src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/js/ccbp-ui-kit.js"></script>


</body>

</html>
