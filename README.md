<!DOCTYPE html>
<html lang="en">
    <head>
        <!-- Required meta tags -->
        <meta charset="utf-8" />
        <meta name="viewport" content="width=device-width, initial-scale=1" />

        <!-- Bootstrap CSS -->
        <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous" />

        <title>Hello, world!</title>
        <link rel="stylesheet" href="style.css" />
    </head>
    <body>
        <!-- heder-section -->
        <nav class="navbar navbar-expand-lg navbar-light bg-light p-3">
            <div class="container-fluid">
                <a class="navbar-brand text-danger" href="#">LFWF Academy</a>
                <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse" id="navbarSupportedContent">
                    <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                        <li class="nav-item">
                            <a class="nav-link active" aria-current="page" href="#">Home</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#">About</a>
                        </li>
                        <li class="nav-item dropdown">
                            <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                                Servics
                            </a>
                            <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
                                <li><a class="dropdown-item" href="#">Action</a></li>
                                <li><a class="dropdown-item" href="#">Another action</a></li>
                                <li><hr class="dropdown-divider" /></li>
                                <li><a class="dropdown-item" href="#">Something else here</a></li>
                            </ul>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#" tabindex="-1" aria-disabled="true">Blog</a>
                        </li>
                    </ul>
                    <form class="d-flex">
                        <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search" />
                        <button class="btn btn-outline-danger" type="submit">Search</button>
                    </form>
                </div>
            </div>
        </nav>

        <!-- slider-section -->

        <div id="carouselExampleCaptions" class="carousel slide" data-bs-ride="carousel">
            <div class="carousel-indicators">
                <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
                <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="1" aria-label="Slide 2"></button>
                <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="2" aria-label="Slide 3"></button>
            </div>
            <div class="carousel-inner">
                <div class="carousel-item active">
                    <img
                        src="https://jssors8.azureedge.net/demos/image-slider/img/px-fun-man-person-2361598-image.jpg
            "
                        class="d-block w-100"
                        alt="..."
                        style="height: 500px;"
                    />
                    <div class="carousel-caption d-none d-md-block slide">
                        <h5>First slide label</h5>
                        <p>Some representative placeholder content for the first slide.</p>
                    </div>
                </div>
                <div class="carousel-item">
                    <img
                        src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQC15VokGr5NPOWpWWkf6jOxeG6gdwn2nnCHA&usqp=CAU
            "
                        class="d-block w-100"
                        alt="..."
                        style="height: 500px;"
                    />
                    <div class="carousel-caption d-none d-md-block slide">
                        <h5>Second slide label</h5>
                        <p>Some representative placeholder content for the second slide.</p>
                    </div>
                </div>
                <div class="carousel-item">
                    <img
                        src="https://soliloquywp.com/wp-content/uploads/2013/05/action-backlit-beach-1046896-1200x450_c.jpg
            "
                        class="d-block w-100"
                        alt="..."
                        style="height: 500px;"
                    />
                    <div class="carousel-caption d-none d-md-block slide">
                        <h5>Third slide label</h5>
                        <p>Some representative placeholder content for the third slide.</p>
                    </div>
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

        <!-- image/blockquote -->

        <div class="container mt-5">
            <div class="row">
                <!-- image -->
                <div class="col-lg-4">
                    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSKeEeCUEMXFYalP5ZDqkzMyJWZB4RL2dxPs-4SJmHA38hr6Up9Z_v2Soi6-Ub8IX8y4yA&usqp=CAU" class="img-thumbnail" alt="..." />
                </div>
                <div class="col-lg-8">
                    <figure>
                        <blockquote class="blockquote">
                            <h4>Lorem ipsum dolor sit amet.</h4>
                            <small>
                                <p>
                                    Lorem ipsum, dolor sit amet consectetur adipisicing elit. Consequuntur sapiente corrupti praesentium molestiae sint, architecto, et earum excepturi dicta amet culpa accusantium alias, possimus repudiandae
                                    eligendi laboriosam veritatis voluptas labore.
                                </p>
                                <p>
                                    Lorem ipsum, dolor sit amet consectetur adipisicing elit. Consequuntur sapiente corrupti praesentium molestiae sint, architecto, et earum excepturi dicta amet culpa accusantium alias, possimus repudiandae
                                    elige voluptas labore.
                                </p>
                            </small>
                        </blockquote>
                        <figcaption class="blockquote-footer">LFWF <cite title="Source Title">Academy</cite></figcaption>
                    </figure>
                </div>
            </div>
        </div>

        <hr />

        <!-- table&form section -->

        <!-- table -->
        <section class="table mt-4 bg-light">
            <div class="container">
                <div class="row pt-5">
                    <div class="col-lg-7">
                        <h3 class="text-danger pb-3">Bootstrap5 Table</h3>
                        <table class="table table-bordered text-center">
                            <thead>
                                <tr class="table-dark">
                                    <th scope="col">No.</th>
                                    <th scope="col">Name</th>
                                    <th scope="col">Class</th>
                                    <th scope="col">Roll</th>
                                    <th scope="col">Section</th>
                                    <th scope="col">Address</th>
                                    <th scope="col">Contact</th>
                                </tr>
                                <tr class="table-primary">
                                    <td scope="col">1</td>
                                    <td scope="col">Sahid</td>
                                    <td scope="col">Ten</td>
                                    <td scope="col">15</td>
                                    <td scope="col">A</td>
                                    <td scope="col">Dhaka</td>
                                    <td scope="col">+8801723367747</td>
                                </tr>
                                <tr class="table-secondary">
                                    <td scope="col">1</td>
                                    <td scope="col">Arif</td>
                                    <td scope="col">Ten</td>
                                    <td scope="col">15</td>
                                    <td scope="col">A</td>
                                    <td scope="col">Dhaka</td>
                                    <td scope="col">+8801723367747</td>
                                </tr>
                                <tr class="table-success">
                                    <td scope="col">1</td>
                                    <td scope="col">Hasib</td>
                                    <td scope="col">Ten</td>
                                    <td scope="col">15</td>
                                    <td scope="col">A</td>
                                    <td scope="col">Dhaka</td>
                                    <td scope="col">+8801723367747</td>
                                </tr>
                                <tr class="table-danger">
                                    <td scope="col">1</td>
                                    <td scope="col">Akil</td>
                                    <td scope="col">Ten</td>
                                    <td scope="col">15</td>
                                    <td scope="col">A</td>
                                    <td scope="col">Dhaka</td>
                                    <td scope="col">+8801723367747</td>
                                </tr>
                                <tr class="table-warning">
                                    <td scope="col">1</td>
                                    <td scope="col">Jayed</td>
                                    <td scope="col">Ten</td>
                                    <td scope="col">15</td>
                                    <td scope="col">A</td>
                                    <td scope="col">Dhaka</td>
                                    <td scope="col">+8801723367747</td>
                                </tr>
                                <tr class="table-info">
                                    <td scope="col">1</td>
                                    <td scope="col">Mihir</td>
                                    <td scope="col">Ten</td>
                                    <td scope="col">15</td>
                                    <td scope="col">A</td>
                                    <td scope="col">Dhaka</td>
                                    <td scope="col">+8801723367747</td>
                                </tr>
                                <tr class="table-light">
                                    <td scope="col">1</td>
                                    <td scope="col">Sagor</td>
                                    <td scope="col">Ten</td>
                                    <td scope="col">15</td>
                                    <td scope="col">A</td>
                                    <td scope="col">Dhaka</td>
                                    <td scope="col">+8801723367747</td>
                                </tr>
                                <tr class="table-primary">
                                    <td scope="col">1</td>
                                    <td scope="col">Akil</td>
                                    <td scope="col">Ten</td>
                                    <td scope="col">15</td>
                                    <td scope="col">A</td>
                                    <td scope="col">Dhaka</td>
                                    <td scope="col">+8801723367747</td>
                                </tr>
                                <tr class="table-success">
                                    <td scope="col">1</td>
                                    <td scope="col">Mihir</td>
                                    <td scope="col">Ten</td>
                                    <td scope="col">15</td>
                                    <td scope="col">A</td>
                                    <td scope="col">Dhaka</td>
                                    <td scope="col">+8801723367747</td>
                                </tr>
                            </thead>
                        </table>
                    </div>

                    <!-- form -->
                    <div class="col-lg-5">
                        <h4 class="text-danger">Bootstrap5 Form</h4>
                        <div class="row mt-4">
                            <div class="col-lg-6">
                                <div class="mb-3">
                                    <label for="exampleFormControlInput1" class="form-label">First name</label>
                                    <input type="text" class="form-control" id="exampleFormControlInput1" placeholder="First name" />
                                </div>
                            </div>
                            <div class="col-lg-6">
                                <div class="mb-3">
                                    <label for="exampleFormControlInput2" class="form-label">Last name</label>
                                    <input type="text" class="form-control" id="exampleFormControlInput2" placeholder="Last name" />
                                </div>
                            </div>
                        </div>
                        <div class="mb-3">
                            <label for="exampleFormControlInput3" class="form-label">Email address</label>
                            <input type="email" class="form-control" id="exampleFormControlInput3" placeholder="name@example.com" />
                        </div>
                        <div class="mb-3">
                            <label for="exampleFormControlTextarea4" class="form-label">Massage</label>
                            <textarea class="form-control" id="exampleFormControlTextarea4" rows="3"></textarea>
                        </div>
                        <div class="mb-3">
                            <label for="formFile" class="form-label">Choose File</label>
                            <input class="form-control" type="file" id="formFile" />
                        </div>
                        <select class="form-select" aria-label="Default select example">
                            <option selected>select your country</option>
                            <option value="1">One</option>
                            <option value="2">Two</option>
                            <option value="3">Three</option>
                        </select>
                        <h5 class="mt-3">Choose your Course</h5>
                        <div class="form-check">
                            <input class="form-check-input" type="checkbox" value="" id="flexCheckDefault" />
                            <label class="form-check-label" for="flexCheckDefault">
                                Web Design
                            </label>
                        </div>

                        <div class="form-check">
                            <input class="form-check-input" type="checkbox" value="" id="flexCheckChecked" checked />
                            <label class="form-check-label" for="flexCheckChecked">
                                Graphic Design
                            </label>
                        </div>
                        <button type="button" class="btn btn-danger btn-sm px-4 mt-2">Submit</button>
                    </div>
                </div>
            </div>
            <hr />
        </section>

        <!-- card& progress section -->

        <section class="card-section bg-light">
            <h5 class="text-center pt-5">Bootstrap card and progressber</h5>
            <div class="container mt-5">
                <div class="row">
                    <div class="col-lg-4">
                        <div class="card">
                            <div class="card-header text-center">
                                This is Header
                            </div>
                            <div class="card-body">
                                <h5 class="card-title">Card title</h5>

                                <div class="card" style="width: 18.8rem;">
                                    <ul class="list-group list-group-flush">
                                        <li class="list-group-item">This card list</li>
                                        <li class="list-group-item">This card list</li>
                                        <li class="list-group-item">This card list</li>
                                        <li class="list-group-item">This card list</li>
                                    </ul>
                                </div>
                                <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Consequatur soluta praesentium voluptate recusandae cum minus placeat fugiat ad temporibus maxime!</p>

                                <a href="#" class="card-link">Card link</a>
                                <a href="#" class="card-link">Another link</a><br />
                                <a href="#" class="btn btn-danger mt-3">Read More</a>
                            </div>
                            <div class="card-footer text-center">
                                <bold>This is fotter</bold>
                            </div>
                        </div>
                    </div>
                    <div class="col-lg-4 mt-5">
                        <h5>HTML</h5>

                        <div class="progress ">
                            <div class="progress-bar bg-danger" role="progressbar" style="width: 90%;" aria-valuenow="90" aria-valuemin="0" aria-valuemax="100">90%</div>
                        </div>
                        <h5>CSS</h5>
                        <div class="progress">
                            <div class="progress-bar bg-danger" role="progressbar" style="width: 95%;" aria-valuenow="95" aria-valuemin="0" aria-valuemax="100">95%</div>
                        </div>
                        <h5>js</h5>
                        <div class="progress">
                            <div class="progress-bar bg-danger" role="progressbar" style="width: 80%;" aria-valuenow="80" aria-valuemin="0" aria-valuemax="100">80%</div>
                        </div>
                        <h5>Wordpress</h5>
                        <div class="progress">
                            <div class="progress-bar bg-danger" role="progressbar" style="width: 85%;" aria-valuenow="85" aria-valuemin="0" aria-valuemax="100">85%</div>
                        </div>
                        <h5 class="mt-5">text-transcate bootstrap class use kore 3 dot anben</h5>

                        <!-- Inline level -->
                        <span class="d-inline-block text-truncate mt-3" style="max-width: 100%;">
                            Lorem ipsum dolor sit amet consectetur adipisicing elit. Modi vitae veritatis asperiores atque ratione labore quasi maiores nobis consequatur quaerat!
                        </span>
                        <div class="alert alert-danger py-2 mt-5" role="alert">
                            A simple danger alert—check it out!
                        </div>
                    </div>

                    <div class="col-lg-4">
                        <div class="card-header text-center">
                            <h5>This is heder</h5>
                        </div>
                        <div class="card mt-3" style="width: 100%;">
                            <img src="https://post.healthline.com/wp-content/uploads/2020/09/man-measuring-height-thumb-1-732x549.jpg" class="card-img-top" style="height: 280px;" alt="..." />
                            <div class="card-body">
                                <p class="card-text mb-4">
                                    Some quick example text to build on the card title and make up the bulk of the card's content Some quick example text to build on the card title and make up the bulk of the card's content.
                                </p>
                            </div>
                            <div class="card-footer text-center">
                                <bold>This is fotter</bold>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <hr />
        </section>

        <!-- blog-section -->

        <section class="blog bg-light mt-3 pb-5">
            <div class="container pt-5">
                <h4 class="text-center text-danger">Lorem ipsum dolor sit amet consectetur adipisicing elit.</h4>
                <div class="row pt-4">
                    <div class="col-lg-4">
                        <div class="card shadow" style="width: 100%;">
                            <img src="https://www.elegantthemes.com/blog/wp-content/uploads/2020/10/shutterstock_1362337379.png" class="card-img-top" alt="..." />
                            <div class="card-body">
                                <h5 class="card-title">Card title</h5>
                                <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                            </div>

                            <div class="card-body">
                                <a href="#" class="btn btn-secondary">Go somewhere</a>
                            </div>
                        </div>
                    </div>
                    <div class="col-lg-4">
                        <div class="card shadow" style="width: 100%;">
                            <img src="https://www.elegantthemes.com/blog/wp-content/uploads/2020/10/shutterstock_1362337379.png" class="card-img-top" alt="..." />
                            <div class="card-body">
                                <h5 class="card-title">Card title</h5>
                                <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                            </div>

                            <div class="card-body">
                                <a href="#" class="btn btn-secondary">Go somewhere</a>
                            </div>
                        </div>
                    </div>
                    <div class="col-lg-4">
                        <div class="card shadow-lg" style="width: 100%;">
                            <img src="https://www.elegantthemes.com/blog/wp-content/uploads/2020/10/shutterstock_1362337379.png" class="card-img-top" alt="..." />
                            <div class="card-body">
                                <h5 class="card-title">Card title</h5>
                                <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                            </div>

                            <div class="card-body">
                                <a href="#" class="btn btn-secondary">Go somewhere</a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- pagination -->
        <section class="pagination py-2">
            <div class="container mt-3">
                <div class="row">
                    <div class="col-lg-4"></div>
                    <div class="col-lg-4">
                        <nav aria-label="Page navigation example" class="d-bl">
                            <ul class="pagination">
                                <li class="page-item "><a class="page-link text-danger" href="#">Previous</a></li>
                                <li class="page-item "><a class="page-link text-danger" href="#">1</a></li>
                                <li class="page-item "><a class="page-link text-danger" href="#">2</a></li>
                                <li class="page-item "><a class="page-link text-danger" href="#">3</a></li>
                                <li class="page-item "><a class="page-link text-danger" href="#">Next</a></li>
                            </ul>
                        </nav>
                    </div>
                    <div class="col-lg-4"></div>
                </div>
            </div>
        </section>

        <section class="fotter bg-danger text-center py-3 text-light">
            <h6>&copy; All Right Reserved By Tanvirul Islam</h6>
        </section>

        <!-- Optional JavaScript; choose one of the two! -->

        <!-- Option 1: Bootstrap Bundle with Popper -->
        <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM" crossorigin="anonymous"></script>

        <!-- Option 2: Separate Popper and Bootstrap JS -->
        <!--
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.2/dist/umd/popper.min.js" integrity="sha384-IQsoLXl5PILFhosVNubq5LC7Qb9DXgDA9i+tQ8Zj3iwWAwPtgFTxbJ8NT4GN1R8p" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.min.js" integrity="sha384-cVKIPhGWiC2Al4u+LWgxfKTRIcfu0JTxR+EQDz/bgldoEyl4H0zUF0QKbrJ0EcQF" crossorigin="anonymous"></script>
    --></body>
</html>
