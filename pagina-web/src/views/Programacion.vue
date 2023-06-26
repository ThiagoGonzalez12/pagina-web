<template>
    <v-app>
    
            <nav class="navbar navbar-expand-lg bg-white shadow-lg">
    
                <div class="container">
    
                    <a href="#" class="navbar-brand">E.E.S.T N°5 <span class="text-danger">JFK</span></a>
    
                    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
    
                        <span class="navbar-toggler-icon"></span>
    
                    </button>
    
                    <div class="collapse navbar-collapse" id="navbarNav">
    
                        <ul class="navbar-nav ms-auto">
    
                            <li class="nav-item">
    
                                <a class="nav-link click-scroll" href="#section_1"> Inicio</a>
    
                            </li>
    
                            <li class="nav-item">
    
                                <a class="nav-link click-scroll" href="#section_2"> Historia</a>
    
                            </li>
    
                            <li class="nav-item">
    
                                <a class="nav-link click-scroll" href="#section_3"> Especialidades</a>
    
                            </li>
    
                            <li class="nav-item">
    
                                <a class="nav-link click-scroll" href="#section_4"> Informacion</a>
    
                            </li>
    
                            <li class="nav-item">
    
                                <a class="nav-link click-scroll" href="#section_5"> Contactos</a>
    
                            </li>
    
                            <a href=""><button type="submit" class="btn btn-primary btn-lg">Iniciar sesion</button></a>
    
                        </ul>
    
                        <div>
    
                        </div>
    
                    </div>
    
                </div>
    
            </nav>
    
            <section class="hero">
    
                <div class="container-fluid h-100">
    
                    <div class="row h-100">
    
                        <div id="carouselExampleCaptions" class="carousel carousel-fade hero-carousel slide" data-bs-ride="carousel">
    
                            <div class="carousel-inner">
    
                                <div class="carousel-item active">
    
                                    <div class="container position-relative h-100">
    
                                        <div class="carousel-caption d-flex flex-column justify-content-center">
    
                                            <small class="small-title">John Fitzgerald Kennedy <strong class="text-warning">31/03/1943</strong></small>
    
                                            <h1>Conoce el mejor futuro para vos</h1>
    
                                            <div class="d-flex align-items-center mt-4">
    
                                                <a href=""><button type="submit" class="custom-btn btn custom-link">Leer mas</button></a>
    
                                            </div>
    
                                        </div>
    
                                    </div>
    
                                    <div class="carousel-image-wrap">
    
                                        <img src="../assets/images/especialidades/programacion.jpg" class="img-fluid carousel-image" alt="">
    
                                    </div>
    
                                </div>
    
                                <div class="carousel-item">
    
                                    <div class="container position-relative h-100">
    
                                        <div class="carousel-caption d-flex flex-column justify-content-center">
    
                                            <small class="small-title">Apoyando tu futuro <strong class="text-warning">31/03/1943</strong></small>
    
                                            <h1>Conoce nuestra historia!!!</h1>
    
                                            <div class="d-flex align-items-center mt-4">
    
                                                <a href=""><button type="submit" class="custom-btn btn custom-link">Leer mas</button></a>
    
                                            </div>
    
                                        </div>
    
                                    </div>
    
                                    <div class="carousel-image-wrap">
    
                                        <img src="../assets/images/colegio.png" class="img-fluid carousel-image" alt="">
    
                                    </div>
    
                                </div>
    
                                <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="prev">
    
                                    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    
                                    <span class="visually-hidden">Previous</span>
    
                                </button>
    
                                <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="next">
    
                                    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    
                                    <span class="visually-hidden">Next</span>
    
                                </button>
    
                            </div>
    
                        </div>
    
                    </div>
    
                </div>
    
            </section>
            <div class="container mt-12">
                <div class="col-lg-10 col-12 text-center mx-auto mb-5">
    
                    <h2>Especialidades</h2>
    
                </div>
                <div class="row mt-12">
                    <div class="d-flex align-items-stretch">
                        <div class="col">
                            <div class="card h-100 especialidad-card">
                                <img src="../assets/images/programacion.png" style="width: 25%; height: auto; align-self: center;" class="card-img-top" alt="Programación">
                                <div class="card-body d-flex flex-column">
                                    <h5 class="card-title">Programación</h5>
                                    <p class="card-text">La programación es una disciplina que se basa en el pensamiento lógico. Comprender los algoritmos y conceptos principales e incluso los lenguajes.</p>
                                    <div class="mt-auto text-center">
                                        <a href="#"><button class="btn btn-primary">Más información</button></a>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="col">
                            <div class="card h-100 especialidad-card">
                                <img src="../assets/images/electromecanica.png" style="width: 25%; height: auto; align-self: center;" class="card-img-top" alt="Electromecánica">
                                <div class="card-body d-flex flex-column">
                                    <h5 class="card-title">Electromecánica</h5>
                                    <p class="card-text">La electromecánica es aquella rama de la ingeniería que combina conocimientos de electrónica, mecánica, etc. Centrándose en las labores técnicas de los sistemas electrónicos mecánicos.</p>
                                    <div class="mt-auto text-center">
                                        <a href="#"><button class="btn btn-primary">Más información</button></a>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="col">
                            <div class="card h-100 especialidad-card">
                                <img src="../assets/images/informatica.png" style="width: 25%; height: auto; align-self: center;" class="card-img-top" alt="Informática">
                                <div class="card-body d-flex flex-column">
                                    <h5 class="card-title">Informática</h5>
                                    <p class="card-text">La Informática es la rama de la Ingeniería que estudia el hardware, las redes de datos y el software necesarios para tratar información de forma automática.</p>
                                    <div class="mt-auto text-center">
                                        <a href="#"><button class="btn btn-primary">Más información</button></a>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <section class="about section-padding" id="section_2">
                <div class="container">
                    <div class="row">
    
                        <div class="col-lg-6 col-12 mb-2 mb-lg-2">
                            <div class="about-image-wrap h-100">
                                <img src="../assets/images/director.jpg" class="img-fluid about-image" alt="">
    
                                <div class="about-image-info">
                                    <h4 class="text-white">Director</h4>
    
                                    <p class="text-white mb-0">"Sólo cuando queremos las cosas, nos incentivamos. Aquel que realiza las obras siente por ellas más cariño que el que las encontró hechas."</p>
                                </div>
                            </div>
                        </div>
    
                        <div class="col-lg-6 col-12 d-flex flex-column">
                            <div class="about-thumb bg-white shadow-lg">
    
                                <div class="about-info">
                                    <small class="small-title">Historia</small>
    
                                    <h2 class="mb-3">Conoce nuestra historia</h2>
    
                                    <h5 class="mb-3">Educando desde 1943</h5>
    
                                    <p>La institucion fue fundada un 31 de marzo de 1943 por el diputado Fabián Onsari, los vecinos Vicente Damonte, Emérito González, Perfecto Facal, Ulises Spinelli, Luis Strático y Antonio Araneo.</p>
    
                                    <p>Y con apenas 70 alumnos fundadores comenzamos a hacer historia.</p>
                                    <p>Y con apenas 70 alumnos fundadores comenzamos a hacer historia.</p>
                                    <p>Y con apenas 70 alumnos fundadores comenzamos a hacer historia.</p>
                                    <p>Y con apenas 70 alumnos fundadores comenzamos a hacer historia.</p>
                                    <p>Y con apenas 70 alumnos fundadores comenzamos a hacer historia.</p>
                                    <p>Y con apenas 70 alumnos fundadores comenzamos a hacer historia.</p>
                                    <p>Y con apenas 70 alumnos fundadores comenzamos a hacer historia.</p>
                                    <p>Y con apenas 70 alumnos fundadores comenzamos a hacer historia.</p>
                                    <p>Y con apenas 70 alumnos fundadores comenzamos a hacer historia.</p>
                                    <p>Y con apenas 70 alumnos fundadores comenzamos a hacer historia.</p>
                                    <p>Y con apenas 70 alumnos fundadores comenzamos a hacer historia.</p>
                                    <p>Y con apenas 70 alumnos fundadores comenzamos a hacer historia.</p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </section>
    
            <div class="cards-wrapper">
                <div class="card carrousel-card">
                    <img src="../assets/images/18.jpeg" class="card-img-top" alt="...">
                    <div class="card-body">
                        <h5 class="card-title">Card title</h5>
                        <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                        <a href="#" class="btn btn-primary">Go somewhere</a>
                    </div>
                </div>
                <div class="card carrousel-card">
                    <img src="../assets/images/18.jpeg" class="card-img-top" alt="...">
                    <div class="card-body">
                        <h5 class="card-title">Card title</h5>
                        <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                        <a href="#" class="btn btn-primary">Go somewhere</a>
                    </div>
                </div>
                <div class="card carrousel-card">
                    <img src="../assets/images/18.jpeg" class="card-img-top" alt="...">
                    <div class="card-body">
                        <h5 class="card-title">Card title</h5>
                        <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                        <a href="#" class="btn btn-primary">Go somewhere</a>
                    </div>
                </div>
                <div class="card carrousel-card">
                    <img src="../assets/images/18.jpeg" class="card-img-top" alt="...">
                    <div class="card-body">
                        <h5 class="card-title">Card title</h5>
                        <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                        <a href="#" class="btn btn-primary">Go somewhere</a>
                    </div>
                </div>
            </div>
    
            <v-container fluid>
            </v-container>
        <footer class="site-footer">
            <div class="container">
                <div class="row">
    
                    <div class="col-lg-6 col-12">
                        <div class="site-footer-wrap d-flex align-items-center">
                            <p class="copyright-text mb-0 me-4">Copyright © 3090 John F. Kennedy</p>
                        </div>
                    </div>
    
                </div>
            </div>
        </footer>
    </v-app>
    </template>