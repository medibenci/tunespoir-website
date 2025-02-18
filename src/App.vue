<template>
  <div id="app">
    <!-- Header Section with Serene Animated Background -->
     <!-- Navbar (Menu Button) -->
<nav class="navbar navbar-expand-lg navbar-light bg-light fixed-top">
  <div class="container">
    <a class="navbar-brand" href="#">Fondation Tunespoir</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
      aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav ms-auto">
        <li class="nav-item">
          <a class="nav-link" href="#about">À propos</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#donate">Faire un don</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#contact">Contact</a>
        </li>
      </ul>
    </div>
  </div>
</nav>

    <header class="bg-header text-white text-center p-5">
      <h1 class="display-3">Fondation Tunespoir</h1>
      <p class="lead">Améliorer les conditions de vie à travers l'éducation et la solidarité.</p>
      <a href="#about" class="btn btn-light btn-lg">En savoir plus</a>
    </header>

    <!-- About Us Section -->
    <section id="about" class="container py-5">
      <h2 class="display-4 text-center mb-4">À propos de nous</h2>
      <p class="lead text-center">
        Fondée en décembre 2013, la Fondation Tunespoir œuvre pour la réhabilitation des écoles et l'accès à l'éducation
        dans les régions défavorisées de la Tunisie. Nous intervenons dans des zones rurales où l'accès aux soins, à
        l'éducation et aux services de base est extrêmement limité. Nous visons à améliorer les conditions de vie des
        jeunes générations en leur offrant un environnement propice à l'apprentissage et au développement personnel.
      </p>

      <h3 class="text-center my-5">Nos projets</h3>
      <div class="row">
        <!-- Project 1 -->
        <div class="col-md-4">
          <div class="card shadow-sm">
            <img src="https://images.pexels.com/photos/15847204/pexels-photo-15847204/free-photo-of-yellow-building-with-grass-courtyard.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" class="card-img-top" alt="Project 1">
            <div class="card-body">
              <h5 class="card-title">Rénovation des écoles</h5>
              <p class="card-text">Nous avons rénové plusieurs écoles dans les zones rurales, en collaboration avec la
                Direction Régionale de l'Éducation (DRE) et des architectes locaux.</p>
            </div>
          </div>
        </div>
        <!-- Project 2 -->
        <div class="col-md-4">
          <div class="card shadow-sm">
            <img src="https://images.pexels.com/photos/159711/books-bookstore-book-reading-159711.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" class="card-img-top" alt="Project 2">
            <div class="card-body">
              <h5 class="card-title">Création de bibliothèques</h5>
              <p class="card-text">Nous avons également mis en place des bibliothèques et des espaces de jeu pour favoriser
                l'épanouissement des jeunes enfants.</p>
            </div>
          </div>
        </div>
        <!-- Project 3 -->
        <div class="col-md-4">
          <div class="card shadow-sm">
            <img src="https://images.pexels.com/photos/8540279/pexels-photo-8540279.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" class="card-img-top" alt="Project 3">
            <div class="card-body">
              <h5 class="card-title">Accessibilité et équipement</h5>
              <p class="card-text">Nos projets comprennent également l'équipement des salles de classe avec des meubles, du matériel informatique et des fournitures scolaires.</p>
            </div>
          </div>
        </div>
      </div>
    </section>
    <section id="video" class="container py-5">
      <h2 class="text-center">Vision de la Fondation</h2>
<p class="text-center">Regardez cette vidéo pour en savoir plus sur notre mission et nos projets.</p>
  <div class="text-center">
    <iframe width="560" height="315" src="https://www.youtube.com/embed/E1xkXZs0cAQ" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
  </div>
</section>

    <!-- Donation Section -->
    <section id="donate" class="bg-light py-5">
      <div class="container text-center">
        <h2 class="display-4 mb-4">Soutenez notre cause</h2>
        <p class="lead">Vos dons contribuent à la rénovation d'écoles et à l'équipement nécessaire pour offrir un avenir meilleur aux enfants des régions démunies.</p>
        <!-- PayPal Donate Button -->
        <a href="https://www.paypal.com/donate?hosted_button_id=YOUR_PAYPAL_ID" target="_blank">
          <button class="btn btn-success btn-lg">Faire un don</button>
        </a>
      </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="container py-5">
      <h2 class="display-4 text-center mb-4">Contactez-nous</h2>
      <form>
        <div class="form-row">
          <div class="col-md-6 mb-3">
            <label for="name">Nom complet</label>
            <input type="text" class="form-control" id="name" placeholder="Votre nom" required>
          </div>
          <div class="col-md-6 mb-3">
            <label for="email">Email</label>
            <input type="email" class="form-control" id="email" placeholder="Votre email" required>
          </div>
        </div>
        <div class="form-group">
          <label for="message">Message</label>
          <textarea class="form-control" id="message" rows="4" placeholder="Votre message" required></textarea>
        </div>
        <button type="submit" class="btn btn-primary btn-lg">Envoyer le message</button>
      </form>
    </section>

    <!-- Footer -->
    <footer class="bg-dark text-white text-center py-4">
      <p>&copy; 2025 Fondation Tunespoir. Tous droits réservés.</p>
      <a href="https://www.facebook.com" class="text-white mx-2">Facebook</a>
      <a href="https://www.twitter.com" class="text-white mx-2">Twitter</a>
      <a href="https://www.instagram.com" class="text-white mx-2">Instagram</a>
    </footer>
  </div>
</template>

<script>
export default {
  name: 'App',
};
</script>

<style scoped>
/* Header Section with Serene Animated Background */
.bg-header {
  background: linear-gradient(45deg, #d4e5f7, #ffb6b9, #d1cfe2, #f7e1d7);
  background-size: 400% 400%;
  animation: gradientAnimation 15s ease infinite;
}

@keyframes gradientAnimation {
  0% { background-position: 0% 50%; }
  50% { background-position: 100% 50%; }
  100% { background-position: 0% 50%; }
}

/* Optional custom styles */
.card-img-top {
  height: 200px;
  object-fit: cover;
}

footer a {
  text-decoration: none;
}

/* Customize button styles */
.btn-lg {
  font-size: 1.25rem;
  padding: 1rem 2rem;
}

/* Contact form adjustments */
form .form-row .col-md-6 {
  padding-right: 15px;
  padding-left: 15px;
}

form .form-group {
  margin-top: 20px;
}
</style>
html {
  scroll-behavior: smooth;
}
