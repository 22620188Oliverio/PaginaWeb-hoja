<template>
    <!-- Testimonios -->
    <section class="bg-light py-5">
        <div class="container">
            <h2 class="text-center mb-5">Playas escondidas de OAXACA</h2>
            <div id="testimonialCarousel" class="carousel slide" data-bs-ride="carousel">
                <div class="carousel-inner">
                    <div class="carousel-item active">
                        <blockquote class="blockquote text-center">
                            <img src="https://imgs.search.brave.com/bWhw3NlHYY5sK-8gYG_O_kr1pbIWyzgTpe8SIWWBE7I/rs:fit:860:0:0:0/g:ce/aHR0cHM6Ly9pbWcu/ZnJlZXBpay5jb20v/Zm90by1ncmF0aXMv/cGxheWFfMTA0OC01/MzU0LmpwZz9zZW10/PWFpc19oeWJyaWQ" alt="">
                            
                        </blockquote>
                    </div>
                    <div class="carousel-item">
                        <blockquote class="blockquote text-center">
                            <img src="https://imgs.search.brave.com/uGytikuxZt9s16B25fGduHGyiZPBsXgrpKtD2hGJkdk/rs:fit:860:0:0:0/g:ce/aHR0cHM6Ly9zdGF0/aWMuZ3J1cG9qb2x5/LmNvbS9jbGlwLzk2/ZDAyODJlLWUyZGUt/NGMwYi04YjU4LWI0/ZDM1MWVkNWM5Nl9z/b3VyY2UtYXNwZWN0/LXJhdGlvXzE2MDB3/XzBfeDExNzV5NzE4/LmpwZw" alt="">
                            
                        </blockquote>
                    </div>
                </div>
                <button class="carousel-control-prev" type="button" data-bs-target="#testimonialCarousel" data-bs-slide="prev">
                    <span class="carousel-control-prev-icon"></span>
                </button>
                <button class="carousel-control-next" type="button" data-bs-target="#testimonialCarousel" data-bs-slide="next">
                    <span class="carousel-control-next-icon" style="color:blue"></span>
                </button>
            </div>
        </div>
    </section>
</template>

<style>
img {
    width: 50%;
    height: 500%;
    object-fit: cover;
}

li::marker {
  color: red; /* Cambia el color de la viñeta */
}
</style>