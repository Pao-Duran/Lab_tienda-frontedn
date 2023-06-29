<script setup lang="ts"></script>

<template>
  <section class="hero-section" id="section_1">
    <div class="section-overlay"></div>

    <div class="container d-flex justify-content-center align-items-center">
      <div class="row">
        <div class="col-12 mt-auto mb-5 text-center">
        
          <h1 class="text-white mb-5">Rain Cosmetics</h1>

        </div>

        <div
          class="col-lg-12 col-12 mt-auto d-flex flex-column flex-lg-row text-center"
        >

          <div class="location-wrap mx-auto py-3 py-lg-0">
            <h5 class="text-white">
              <i class="custom-icon bi-geo-alt me-2"></i>
              hernando siles, Sucre
            </h5>
          </div>

          <div class="social-share">
            <ul
              class="social-icon d-flex align-items-center justify-content-center"
            >
              <span class="text-white me-3">Share:</span>

              <li class="social-icon-item">
                <a href="#" class="social-icon-link">
                  <span class="bi-facebook"></span>
                </a>
              </li>

              <li class="social-icon-item">
                <a href="#" class="social-icon-link">
                  <span class="bi-twitter"></span>
                </a>
              </li>

              <li class="social-icon-item">
                <a href="#" class="social-icon-link">
                  <span class="bi-instagram"></span>
                </a>
              </li>
            </ul>
          </div>
        </div>
      </div>
    </div>
    <!-- //sustituir video por un carrusel de fotos de los productos  -->
    <div class="video-wrap">
      <video autoplay="" loop="" muted="" class="custom-video" poster="">
        <source src="@/assets/video/lv_0_20230625181422.mp4" type="video/mp4" />

        Your browser does not support the video tag.
      </video>
    </div>
  </section>

  <section class="about-section section-padding" id="section_2">
    <div class="container">
      <div class="row">
        <div class="col-lg-6 col-12 mb-4 mb-lg-0 d-flex align-items-center">
          <div class="services-info">
            <h2 class="text-white mt-4">Rain Cosmetics</h2>

            <p class="text-white mt-4">
              Rain Cosmetics es una tienda online y contamos con una tienda
              fisica la cual ofrece variedad de productos 
              de belleza.
            </p>

            <h6 class="text-white mt-4">Productos de Belleza</h6>

            <p class="text-white mt-4">
            ofrecemos desde labiales, paletas de maquillajes, cremas de piel,
            aceites para el cuidado del cabello, en variedad de marcas y tonalidades.
            </p>
            
          </div>
        </div>

        <div class="col-lg-6 col-12">
          <div class="about-text-wrap">
            <img
              src="@/assets/images/pexels-alexander-suhorucov-6457579.jpg"
              class="about-image img-fluid"
            />

          </div>
        </div>
      </div>
    </div>
  </section>

  <section class="artists-section section-padding" id="section_3">
    <div class="container">
      <div class="row justify-content-center">
        <div class="col-12 text-center">
          <h2 class="mb-4">Productos </h2>
        </div>

        <div class="col-lg-5 col-12">
          <div class="artists-thumb">
            <div class="artists-image-wrap">
              <img
                src="@/assets/images/artists/joecalih-UmTZqmMvQcw-unsplash.jpg"
                class="artists-image img-fluid"
              />
            </div>

            <div class="artists-hover">
              <p>
                <strong>Precio:</strong>
                24 bs
              </p>

              <p>
                <strong>Marca:</strong>
                KYLIE
              </p>

              <p>
                <strong>forma del articulo:</strong>
                Liquido
              </p>

              <p>
                <strong>Tipo de acabado:</strong>
                Mate
              </p>

              <hr />

              <p class="mb-0">
                <strong> Descripcion:</strong>
                El lápiz labial líquido mate tiene pigmento de alta intensidad 
                para un labio mate atrevido instantáneo. 
                El lápiz labial extremadamente largo contiene ingredientes hidratantes 
                para una sensación cómoda, emoliente y sedosa que no seca tus labios.
              </p>
              <button type="button" class="btn btn-success" data-bs-toggle="modal" data-bs-target="#staticBackdrop">
              Comprar
            </button>
            <div class="form-row">
                  <button
                    class="btn  btn--primary"
                    type="submit"
                    name="add"
                    data-add-to-cart
                    >
                      <span data-add-to-cart-text>
                        
                          Agregar al carrito
                        
                      </span>
                  </button>
                  
            </div>
            <div class="form-row">                                                      
            </div>
            </div>
          </div>
          <div class="artists-thumb">
            <img
              src="@/assets/images/artists/brochas.jpg"
              class="artists-image img-fluid"
            />

            <div class="artists-hover">
              <p>
                <strong>Precio:</strong>
              27 bs
              </p>

              <p>
                <strong>Marca:</strong>
                JAF
              </p>

              <p>
                <strong>Usos :</strong>
                Maquillaje facial
              </p>

              <p>
                <strong>Material:</strong>
                Madera, fibra sintetica
              </p>

              <p>
                <strong>Tipo de piel:</strong>
                Todas
              </p>

              <hr />

              <p class="mb-0">
                <strong>Descripcion:</strong>
                Juego de brochas de maquillaje de alta calidad: 
                cerdas suaves y densas sin desprendimiento ni olor, 
                fácil de recoger y transportar el maquillaje.
              </p>
              <button type="button" class="btn btn-success" data-bs-toggle="modal" data-bs-target="#staticBackdrop">
              Comprar
            </button>
            <div class="form-row">
                  <button
                    class="btn  btn--primary"
                    type="submit"
                    name="add"
                    data-add-to-cart
                    >
                      <span data-add-to-cart-text>
                        
                          Agregar al carrito
                        
                      </span>
                  </button>
                  
            </div>
            <div class="form-row">                                                      
            </div>
            </div>
          </div>

        </div>

        <div class="col-lg-5 col-12">
          <div class="artists-thumb">
            <div class="artists-image-wrap">
              <img
                src="@/assets/images/artists/abstral-official-bdlMO9z5yco-unsplash.jpg"
                class="artists-image img-fluid"
              />
            </div>

            <div class="artists-hover">
              <p>
                <strong>Precio:</strong>
                14 bs
              </p>

              <p>
                <strong>Marca:</strong>
                MYUANGO
              </p>

              <p>
                <strong>Forma del articulo:</strong>
                Polvo
              </p>

              <p>
                <strong>Tipo de acabado:</strong>
                brillante
              </p>

              <hr />

              <p class="mb-0">
                <strong>Caracteristicas:</strong>
                Contiene 39 colores
                Tamaño de viaje, ingredientes naturales.
                No probado en animales
              </p>
              <button type="button" class="btn btn-success" data-bs-toggle="modal" data-bs-target="#staticBackdrop">
              Comprar
            </button>
            <div class="form-row">
                  <button
                    class="btn  btn--primary"
                    type="submit"
                    name="add"
                    data-add-to-cart
                    >
                      <span data-add-to-cart-text>
                        
                          Agregar al carrito
                        
                      </span>
                  </button>
                  
            </div>
            <div class="form-row">                                                      
            </div>
            </div>
          </div>

          <div class="artists-thumb">
            <img
              src="@/assets/images/artists/soundtrap-rAT6FJ6wltE-unsplash.jpg"
              class="artists-image img-fluid"
            />

            <div class="artists-hover">
              <p>
                <strong>Precio:</strong>
                34 bs
              </p>

              <p>
                <strong>Marca:</strong>
                Hair Chemist
              </p>

              <p>
                <strong>Forma del articulo:</strong>
                Suero, aceite
              </p>

              <p>
                <strong>Tipo de cabello:</strong>
                dry, normal
              </p>

              <p>
                <strong>Fragancia:</strong>
                Coco
              </p>

              <hr />

              <p class="mb-0">
                <strong>Descripcion:</strong>
                El suero de aceite de coco nutre el cuero cabelludo y promueve raíces
                y folículos saludables del cabello. Los nutrientes naturales del aceite 
                de coco ayudan a prevenir la rotura del cabello y mantienen tu cuero 
                cabelludo y raíz del cabello saludables. Tu cabello se sentirá revitalizado
              </p>
              <button type="button" class="btn btn-success" data-bs-toggle="modal" data-bs-target="#staticBackdrop">
              Comprar
            </button>
            <div class="form-row">
                  <button
                    class="btn  btn--primary"
                    type="submit"
                    name="add"
                    data-add-to-cart
                    >
                      <span data-add-to-cart-text>
                        
                          Agregar al carrito
                        
                      </span>
                  </button>
                  
            </div>
            <div class="form-row">                                                      
            </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <section class="schedule-section section-padding" id="section_4">
    <div class="container">
      <div class="row">
        <div class="col-12 text-center">
          <h2 class="text-white mb-4">Dias con descuento</h2>

          <div class="table-responsive">
            <table class="schedule-table table table-dark">
              <thead>
                <tr>
                  <th scope="col">Dia</th>

                  <th scope="col">Miercoles</th>

                  <th scope="col">Viernes</th>
                </tr>
              </thead>

              <tbody>
                <tr>
                  <th scope="row">Dia 1</th>

                  <td class="table-background-image-wrap pop-background-image">
                    <h3>Labiales</h3>

                    <p class="mb-2">3:00 - 5:00 PM</p>

                    <p>arriba de los 30 bs de compra, un 7% de descuento</p>

                    <div class="section-overlay"></div>
                  </td>

                  <td style="background-color: #f3dcd4"></td>

                
                </tr>


                <tr>
                  <th scope="row">Dia 2</th>

                  <td style="background-color: #d1cfc0"></td>
                  <td
                    class="table-background-image-wrap country-background-image"
                  >
                    <h3>Paleta de sombras </h3>

                    <p class="mb-2">5:30 - 7:30 PM</p>

                    <p>arriba de los 40 bs de compra un 10% de descuento </p>

                    <div class="section-overlay"></div>
                  </td>
                  
                </tr>
              </tbody>
            </table>
          </div>
        </div>
      </div>
    </div>
  </section>

  <section class="contact-section section-padding" id="section_6">
    <div class="container">
      <div class="row">
        <div class="col-lg-8 col-12 mx-auto">
          <h2 class="text-center mb-4">Interesada? contactanos</h2>

          <nav class="d-flex justify-content-center">
            <div
              class="nav nav-tabs align-items-baseline justify-content-center"
              id="nav-tab"
              role="tablist"
            >
              <button
                class="nav-link active"
                id="nav-ContactForm-tab"
                data-bs-toggle="tab"
                data-bs-target="#nav-ContactForm"
                type="button"
                role="tab"
                aria-controls="nav-ContactForm"
                aria-selected="false"
              >
                <h5>formulario</h5>
              </button>

              <button
                class="nav-link"
                id="nav-ContactMap-tab"
                data-bs-toggle="tab"
                data-bs-target="#nav-ContactMap"
                type="button"
                role="tab"
                aria-controls="nav-ContactMap"
                aria-selected="false"
              >
                <h5>Google Maps</h5>
              </button>
            </div>
          </nav>

          <div class="tab-content shadow-lg mt-5" id="nav-tabContent">
            <div
              class="tab-pane fade show active"
              id="nav-ContactForm"
              role="tabpanel"
              aria-labelledby="nav-ContactForm-tab"
            >
              <form
                class="custom-form contact-form mb-5 mb-lg-0"
                action="#"
                method="post"
                role="form"
              >
                <div class="contact-form-body">
                  <div class="row">
                    <div class="col-lg-6 col-md-6 col-12">
                      <input
                        type="text"
                        name="contact-name"
                        id="contact-name"
                        class="form-control"
                        placeholder="nombre"
                        required
                      />
                    </div>

                    <div class="col-lg-6 col-md-6 col-12">
                      <input
                        type="email"
                        name="contact-email"
                        id="contact-email"
                        pattern="[^ @]*@[^ @]*"
                        class="form-control"
                        placeholder="Email address"
                        required
                      />
                    </div>
                  </div>
                  <textarea
                    name="contact-message"
                    rows="3"
                    class="form-control"
                    id="contact-message"
                    placeholder="Message"
                  ></textarea>

                  <div class="col-lg-4 col-md-10 col-8 mx-auto">
                    <button type="submit" class="form-control">
                      enviar
                    </button>
                  </div>
                </div>
              </form>
            </div>

            <div
              class="tab-pane fade"
              id="nav-ContactMap"
              role="tabpanel"
              aria-labelledby="nav-ContactMap-tab"
            >
              <iframe
                class="google-map"
                src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d29974.469402870927!2d120.94861466021855!3d14.106066818082482!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x33bd777b1ab54c8f%3A0x6ecc514451ce2be8!2sTagaytay%2C%20Cavite%2C%20Philippines!5e1!3m2!1sen!2smy!4v1670344209509!5m2!1sen!2smy"
                width="100%"
                height="450"
                style="border: 0"
                allowfullscreen= ""
                loading="lazy"
                referrerpolicy="no-referrer-when-downgrade"
              ></iframe>
              <!-- You can easily copy the embed code from Google Maps -> Share -> Embed a map // -->
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
  <!-- Modal -->
  <div class="modal fade" id="staticBackdrop" data-bs-backdrop="static" data-bs-keyboard="false" tabindex="-1" aria-labelledby="staticBackdropLabel" aria-hidden="true">
    <div class="modal-dialog">
      <div class="modal-content">
        <div class="modal-header">
          <h1 class="modal-title fs-5" id="staticBackdropLabel">Comprar</h1>
          <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
        </div>
        <div class="modal-body">
          <form class="row g-3 needs-validation" novalidate>
            <div class="col-md-4">
              <label for="validationCustom01" class="form-label">Nombre</label>
              <input type="text" class="form-control" id="validationCustom01" value="Mark" required>
              <div class="valid-feedback">
                Looks good!
              </div>
            </div>
            <div class="col-md-4">
              <label for="validationCustom02" class="form-label">Apellido</label>
              <input type="text" class="form-control" id="validationCustom02" value="Otto" required>
              <div class="valid-feedback">
                Looks good!
              </div>
            </div>
            <div class="col-md-4">
              <label for="validationCustomUsername" class="form-label">Usuario</label>
              <div class="input-group has-validation">
                <span class="input-group-text" id="inputGroupPrepend">@</span>
                <input type="text" class="form-control" id="validationCustomUsername" aria-describedby="inputGroupPrepend" required>
                <div class="invalid-feedback">
                  Please choose a username.
                </div>
              </div>
            </div>
            <div class="col-md-6">
              <label for="validationCustom03" class="form-label">Direccion</label>
              <input type="text" class="form-control" id="validationCustom03" required>
              <div class="invalid-feedback">
                Please provide a valid city.
              </div>
            </div>
            <div class="col-12">
              <div class="form-check">
                <input class="form-check-input" type="checkbox" value="" id="invalidCheck" required>
                <label class="form-check-label" for="invalidCheck">
                  Agree to terms and conditions
                </label>
                <div class="invalid-feedback">
                  You must agree before submitting.
                </div>
              </div>
            </div>
          </form>
        </div>
        <div class="modal-footer">
          <button type="button" class="btn btn-danger" data-bs-dismiss="modal">Cerrar</button>
          <button type="button" class="btn btn-primary" 
            data-bs-toggle="tooltip" data-bs-placement="top" data-bs-title="Guardar Reserva">
            Guardar
          </button>
        </div>
      </div>
    </div>
  </div>
</template>

