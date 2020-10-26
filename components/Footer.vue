<template>
<div class="lg:flex bg-gray-800 md:block">
  <div class="flex-1 text-white text-center bg-gray-800 px-8 py-2 m-4">Servicios
      <li>
          <ul>Consultas</ul>
          <ul>Planes</ul>
      </li>
  </div>
  <div class="social-media flex-1 text-white text-center bg-gray-800 px-8 py-2 m-4">Siguenos en redes
        <div class="rounded-social-buttons mt-8">
            <a class="social-button facebook" href="https://www.facebook.com/" target="_blank"><i class="fab fa-facebook-f"></i></a>
            <a class="social-button twitter" href="https://www.twitter.com/" target="_blank"><i class="fab fa-twitter"></i></a>
            <a class="social-button linkedin" href="https://www.linkedin.com/" target="_blank"><i class="fab fa-linkedin"></i></a>
            <a class="social-button youtube" href="https://www.youtube.com/" target="_blank"><i class="fab fa-youtube"></i></a>
            <a class="social-button instagram" href="https://www.instagram.com/" target="_blank"><i class="fab fa-instagram"></i></a>
        </div>
  </div>
  <div class="flex-1 text-white text-center bg-gray-800 px-8 py-2 m-4">Contacto</div>
</div>
</template>

<script>
export default {

}
</script>

<style>
textarea {
    resize: none;
}

.text {
  color: white;
  font-size: 20px;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  -ms-transform: translate(-50%, -50%);
  white-space: nowrap;
}
.svg-inline--fa {
  vertical-align: -0.200em;
}

.rounded-social-buttons {
  text-align: center;
}

.rounded-social-buttons .social-button {
  display: inline-block;
  position: relative;
  cursor: pointer;
  width: 3.125rem;
  height: 3.125rem;
  border: 0.125rem solid transparent;
  padding: 0;
  text-decoration: none;
  text-align: center;
  color: #fefefe;
  font-size: 1.5625rem;
  font-weight: normal;
  line-height: 2em;
  border-radius: 1.6875rem;
  transition: all 0.5s ease;
  margin-right: 0.25rem;
  margin-bottom: 0.25rem;
}

.rounded-social-buttons .social-button:hover, .rounded-social-buttons .social-button:focus {
  -webkit-transform: rotate(360deg);
      -ms-transform: rotate(360deg);
          transform: rotate(360deg);
}

.rounded-social-buttons .fa-twitter, .fa-facebook-f, .fa-linkedin, .fa-youtube, .fa-instagram {
  font-size: 25px;
}

.rounded-social-buttons .social-button.facebook {
  background: #3b5998;
}

.rounded-social-buttons .social-button.facebook:hover, .rounded-social-buttons .social-button.facebook:focus {
  color: #3b5998;
  background: #fefefe;
  border-color: #3b5998;
}

.rounded-social-buttons .social-button.twitter {
  background: #55acee;
}

.rounded-social-buttons .social-button.twitter:hover, .rounded-social-buttons .social-button.twitter:focus {
  color: #55acee;
  background: #fefefe;
  border-color: #55acee;
}

.rounded-social-buttons .social-button.linkedin {
  background: #007bb5;
}

.rounded-social-buttons .social-button.linkedin:hover, .rounded-social-buttons .social-button.linkedin:focus {
  color: #007bb5;
  background: #fefefe;
  border-color: #007bb5;
}

.rounded-social-buttons .social-button.youtube {
  background: #bb0000;
}

.rounded-social-buttons .social-button.youtube:hover, .rounded-social-buttons .social-button.youtube:focus {
  color: #bb0000;
  background: #fefefe;
  border-color: #bb0000;
}

.rounded-social-buttons .social-button.instagram {
  background: #125688;
}

.rounded-social-buttons .social-button.instagram:hover, .rounded-social-buttons .social-button.instagram:focus {
  color: #125688;
  background: #fefefe;
  border-color: #125688;
}
</style>