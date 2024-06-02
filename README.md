# Página Fan de Taylor Swift

Bienvenido a la página fan no oficial de Taylor Swift. Este proyecto es una "fan page" desarrollada como parte de un proyecto de tecnología. La página incluye información sobre la biografía de Taylor Swift, sus álbumes más conocidos, fechas de gira, noticias recientes y enlaces a sus redes sociales.

## Características

- **Biografía**: Información sobre la vida y carrera de Taylor Swift.
- **Álbumes**: Lista de sus álbumes más conocidos.
- **Galería de Fotos**: Una colección de imágenes de Taylor Swift.
- **Fechas de la Gira**: Próximas fechas y ciudades de la gira.
- **Noticias Recientes**: Últimas noticias sobre Taylor Swift.
- **Redes Sociales**: Enlaces a las redes sociales oficiales de Taylor Swift.

## Autor

Este sitio web fue creado por [Alejandra Pulido](https://www.instagram.com/atsv___?igsh=OHE1ZjRvYWcyMDhy). Puedes contactarme en [askolmi1011@gmail.com](mailto:askolmi1011
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Página Fan de Taylor Swift</title>
    <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header class="bg-primary text-white text-center py-3">
        <div class="container">
            <h1>Página Fan de Taylor Swift</h1>
        </div>
    </header>
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <a class="navbar-brand" href="#">Inicio</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav">
                <li class="nav-item"><a class="nav-link" href="#biografia">Biografía</a></li>
                <li class="nav-item"><a class="nav-link" href="#albumes">Álbumes</a></li>
                <li class="nav-item"><a class="nav-link" href="#fotos">Fotos</a></li>
                <li class="nav-item"><a class="nav-link" href="#gira">Gira</a></li>
                <li class="nav-item"><a class="nav-link" href="#noticias">Noticias</a></li>
                <li class="nav-item"><a class="nav-link" href="#redes">Redes Sociales</a></li>
            </ul>
        </div>
    </nav>
    <div class="container my-4">
        <div class="row">
            <div class="col-lg-8">
                <section>
                    <h2 id="biografia">Biografía de Taylor Swift</h2>
                    <p>Taylor Swift es una cantante y compositora estadounidense conocida por sus canciones sobre experiencias personales. Nació el 13 de diciembre de 1989 en Reading, Pensilvania, y se mudó a Nashville, Tennessee, a los 14 años para seguir una carrera en la música country. Ha lanzado múltiples álbumes de éxito y ha ganado numerosos premios, incluyendo varios Grammy.</p>
                </section>
                <section id="albumes">
                    <h2>Álbumes Más Conocidos</h2>
                    <ul>
                        <li>Fearless (2008)</li>
                        <li>Speak Now (2010)</li>
                        <li>Red (2012)</li>
                        <li>1989 (2014)</li>
                        <li>Reputation (2017)</li>
                        <li>Lover (2019)</li>
                        <li>Folklore (2020)</li>
                        <li>Evermore (2020)</li>
                    </ul>
                </section>
                <section id="fotos">
                    <h2>Galería de Fotos</h2>
                    <div class="row">
                        <div class="col-md-4">
                            <img src="https://via.placeholder.com/150" class="img-fluid" alt="Foto de Taylor Swift">
                        </div>
                        <div class="col-md-4">
                            <img src="https://via.placeholder.com/150" class="img-fluid" alt="Foto de Taylor Swift">
                        </div>
                        <div class="col-md-4">
                            <img src="https://via.placeholder.com/150" class="img-fluid" alt="Foto de Taylor Swift">
                        </div>
                    </div>
                </section>
                <section id="gira">
                    <h2>Fechas de la Gira</h2>
                    <table class="table">
                        <thead>
                            <tr>
                                <th>Fecha</th>
                                <th>Ciudad</th>
                            </tr>
                        </thead>
                        <tbody>
                            <tr>
                                <td>1 de junio, 2024</td>
                                <td>Los Ángeles, CA</td>
                            </tr>
                            <tr>
                                <td>15 de junio, 2024</td>
                                <td>Nueva York, NY</td>
                            </tr>
                            <tr>
                                <td>30 de junio, 2024</td>
                                <td>Chicago, IL</td>
                            </tr>
                            <tr>
                                <td>15 de julio, 2024</td>
                                <td>Miami, FL</td>
                            </tr>
                        </tbody>
                    </table>
                </section>
                <section id="noticias">
                    <h2>Noticias Recientes</h2>
                    <p>¡Taylor Swift anuncia su nueva gira mundial para 2024! Los boletos saldrán a la venta pronto, así que mantente atento a las actualizaciones.</p>
                </section>
                <section id="redes">
                    <h2>Enlaces a Redes Sociales</h2>
                    <ul>
                        <li><a href="https://www.facebook.com/TaylorSwift" target="_blank">Facebook</a></li>
                        <li><a href="https://twitter.com/taylorswift13" target="_blank">Twitter</a></li>
                        <li><a href="https://www.instagram.com/taylorswift" target="_blank">Instagram</a></li>
                    </ul>
                </section>
            </div>
            <aside class="col-lg-4">
                <h3>Autor</h3>
                <p>Este sitio web fue creado por <a href="https://www.instagram.com/atsv___?igsh=OHE1ZjRvYWcyMDhy" target="_blank">Alejandra Pulido</a>, una amante de Taylor Swift. Puedes escribirme un correo a <a href="mailto:askolmi1011@gmail.com">askolmi1011@gmail.com</a>.</p>
                <img src="https://via.placeholder.com/150" class="img-fluid" alt="Foto del Autor">
            </aside>
        </div>
    </div>
    <footer class="bg-primary text-white text-center py-3">
        <div class="container">
            
# Página Fan de Taylor Swift

Bienvenido a la página fan no oficial de Taylor Swift. Este proyecto es una "fan page" desarrollada como parte de un proyecto de tecnología. La página incluye información sobre la biografía de Taylor Swift, sus álbumes más conocidos, fechas de gira, noticias recientes y enlaces a sus redes sociales.

## Características

- **Biografía**: Información sobre la vida y carrera de Taylor Swift.
- **Álbumes**: Lista de sus álbumes más conocidos.
- **Galería de Fotos**: Una colección de imágenes de Taylor Swift.
- **Fechas de la Gira**: Próximas fechas y ciudades de la gira.
- **Noticias Recientes**: Últimas noticias sobre Taylor Swift.
- **Redes Sociales**: Enlaces a las redes sociales oficiales de Taylor Swift.

## Autor

Este sitio web fue creado por [Alejandra Pulido](https://www.instagram.com/atsv___?igsh=OHE1ZjRvYWcyMDhy). Puedes contactarme en [askolmi1011@gmail.com](mailto:askolmi1011
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Página Fan de Taylor Swift</title>
    <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header class="bg-primary text-white text-center py-3">
        <div class="container">
            <h1>Página Fan de Taylor Swift</h1>
        </div>
    </header>
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <a class="navbar-brand" href="#">Inicio</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav">
                <li class="nav-item"><a class="nav-link" href="#biografia">Biografía</a></li>
                <li class="nav-item"><a class="nav-link" href="#albumes">Álbumes</a></li>
                <li class="nav-item"><a class="nav-link" href="#fotos">Fotos</a></li>
                <li class="nav-item"><a class="nav-link" href="#gira">Gira</a></li>
                <li class="nav-item"><a class="nav-link" href="#noticias">Noticias</a></li>
                <li class="nav-item"><a class="nav-link" href="#redes">Redes Sociales</a></li>
            </ul>
        </div>
    </nav>
    <div class="container my-4">
        <div class="row">
            <div class="col-lg-8">
                <section>
                    <h2 id="biografia">Biografía de Taylor Swift</h2>
                    <p>Taylor Swift es una cantante y compositora estadounidense conocida por sus canciones sobre experiencias personales. Nació el 13 de diciembre de 1989 en Reading, Pensilvania, y se mudó a Nashville, Tennessee, a los 14 años para seguir una carrera en la música country. Ha lanzado múltiples álbumes de éxito y ha ganado numerosos premios, incluyendo varios Grammy.</p>
                </section>
                <section id="albumes">
                    <h2>Álbumes Más Conocidos</h2>
                    <ul>
                        <li>Fearless (2008)</li>
                        <li>Speak Now (2010)</li>
                        <li>Red (2012)</li>
                        <li>1989 (2014)</li>
                        <li>Reputation (2017)</li>
                        <li>Lover (2019)</li>
                        <li>Folklore (2020)</li>
                        <li>Evermore (2020)</li>
                    </ul>
                </section>
                <section id="fotos">
                    <h2>Galería de Fotos</h2>
                    <div class="row">
                        <div class="col-md-4">
                            <img src="https://via.placeholder.com/150" class="img-fluid" alt="Foto de Taylor Swift">
                        </div>
                        <div class="col-md-4">
                            <img src="https://via.placeholder.com/150" class="img-fluid" alt="Foto de Taylor Swift">
                        </div>
                        <div class="col-md-4">
                            <img src="https://via.placeholder.com/150" class="img-fluid" alt="Foto de Taylor Swift">
                        </div>
                    </div>
                </section>
                <section id="gira">
                    <h2>Fechas de la Gira</h2>
                    <table class="table">
                        <thead>
                            <tr>
                                <th>Fecha</th>
                                <th>Ciudad</th>
                            </tr>
                        </thead>
                        <tbody>
                            <tr>
                                <td>1 de junio, 2024</td>
                                <td>Los Ángeles, CA</td>
                            </tr>
                            <tr>
                                <td>15 de junio, 2024</td>
                                <td>Nueva York, NY</td>
                            </tr>
                            <tr>
                                <td>30 de junio, 2024</td>
                                <td>Chicago, IL</td>
                            </tr>
                            <tr>
                                <td>15 de julio, 2024</td>
                                <td>Miami, FL</td>
                            </tr>
                        </tbody>
                    </table>
                </section>
                <section id="noticias">
                    <h2>Noticias Recientes</h2>
                    <p>¡Taylor Swift anuncia su nueva gira mundial para 2024! Los boletos saldrán a la venta pronto, así que mantente atento a las actualizaciones.</p>
                </section>
                <section id="redes">
                    <h2>Enlaces a Redes Sociales</h2>
                    <ul>
                        <li><a href="https://www.facebook.com/TaylorSwift" target="_blank">Facebook</a></li>
                        <li><a href="https://twitter.com/taylorswift13" target="_blank">Twitter</a></li>
                        <li><a href="https://www.instagram.com/taylorswift" target="_blank">Instagram</a></li>
                    </ul>
                </section>
            </div>
            <aside class="col-lg-4">
                <h3>Autor</h3>
                <p>Este sitio web fue creado por <a href="https://www.instagram.com/atsv___?igsh=OHE1ZjRvYWcyMDhy" target="_blank">Alejandra Pulido</a>, una amante de Taylor Swift. Puedes escribirme un correo a <a href="mailto:askolmi1011@gmail.com">askolmi1011@gmail.com</a>.</p>
                <img src="https://via.placeholder.com/150" class="img-fluid" alt="Foto del Autor">
            </aside>
        </div>
    </div>
    <footer class="bg-primary text-white text-center py-3">
        <div class="container">
            
