
  
<style>
$card-header-bg-color: #000;
$card-header-txt-color: var(--white);
$link-color: var(--indigo);

body {
  font-family: var(--font-family-monospace);
  background: url('https://images.unsplash.com/photo-1518837695005-2083093ee35b?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1920&q=80') no-repeat center;
  background-attachment: fixed;
  background-size: cover;
  &:after {
    content: '';
    position: fixed;
    top: 0;
    right: 0;
    bottom: 0;
    left: 0;
    background-color: rgba(0,0,0,.3);
    z-index: -1;
  }
}
.card {
  .card-header {
    background-color: $card-header-bg-color;
    color: $card-header-txt-color;
  }
  .list-group-item {
    a {
      min-height: 50px;
      color: $link-color;
    }
    img {
      position: absolute;
      top: 50%;
      transform: translatey(-50%);
      width: 50px;
      height: 50px;
      object-fit: cover;
    }
    span { padding: 0 60px; }
  }
}



/*
 * Luis Badiali
 * badiali.es
 * Please leave your like | Por favor deja tu like
 */
.love {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: row;
  position: fixed;
  z-index: 1;
  bottom: 1rem;
  left: 1rem;
  padding: 1em;
  font-family: monospace, sans-serif;
  font-size: .875rem;
  line-height: 1em;
  color: #fff;
  background-color: rgba(0,0,0,.3);
  -webkit-backdrop-filter: blur(5px);
  backdrop-filter: blur(5px);
  border-radius: 5px;
  &::after {
    content: '❤️';
    margin-left: 10px;
    animation: beat .5s alternate infinite ease-in;
  }
}
@keyframes beat {
  0%   { transform: scale(1); }
  100% { transform: scale(1.2); }
}
</style>
<title>KodveBlog Github Page</title>
<div class="container">
  <div class="row justify-content-center">
    <div class="col-lg-8 d-flex flex-column align-items-center">
      <img class="rounded-circle mt-4" src="https://es.gravatar.com/userimage/3890878/26e5ee1b5d2703e9580d47bab83c0723.png?size=200" width="100">
      <p class="text-center text-white mb-0 mt-3">@badiali</p>
      <div class="card w-100 border-0 shadow mt-4">
        <ul class="list-group list-group-flush border-0">
          <li class="list-group-item border-0 text-center p-4">
            <p>Merhaba Ben Ömer <strong>Faruk</strong></p>
            <p class="mb-0">Full Stack Geliştiriciyim ve Siber Güvenlik Geliştiricisiyim</p>
          </li>
        </ul>
      </div>
      <div class="card w-100 border-0 shadow mt-3">
        <div class="card-header border-0 text-center font-weight-bold">
          Artículos
        </div>
        <ul class="list-group list-group-flush border-0">
          <li class="list-group-item p-1">
            </a>
          </li>
          <li class="list-group-item p-1">
            </a>
          </li>
        </ul>
      </div>
      <div class="card w-100 border-0 shadow mt-3">
        <div class="card-header border-0 text-center font-weight-bold">
          Contacto
        </div>
        <ul class="list-group list-group-flush border-0">
          <li class="list-group-item border-0 p-1">
            <a class="stretched-link d-flex align-items-center text-center" href="mailto:dijitaltekno2@gmail.com">
              <span class="flex-grow-1">Email</span>
            </a>
          </li>
        </ul>
      </div>
      <ul class="list-unstyled list-inline my-4">
          </a>
        </li>
        <li class="list-inline-item mx-2">
          <a class="text-white" href="https://instagram.com/kodveblog/" target="_blank">
            <i class="fab fa-instagram fa-2x"></i>
          </a>
        </li>
        <li class="list-inline-item mx-2">
          <a class="text-white" href="https://github.com/kodveblog/" target="_blank">
            <i class="fab fa-github fa-2x"></i>
          </a>
        </li>
        <li class="list-inline-item mx-2">
          <a class="text-white" href="https://codepen.io/kodveblog/" target="_blank">
            <i class="fab fa-codepen fa-2x"></i>
          </a>
        </li>
          </a>
        </li>
      </ul>
    </div>
  </div>
</div>


<!-- Please leave your like | Por favor deja tu like -->
<div class="love">Leave your</div>
<center>
<h3>🛠  Tech Stack</h3>
<div style="display: inline_block"><br>
    <img align="center" alt="kodveblog" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg">
 <img align="center" alt="kodveblog" height="30" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/php/php-original.svg"/>
  <img align="center" alt="kodveblog" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg">
  <img align="center" alt="kodveblog" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg">
  <img align="center" alt="kodveblog" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg">
  <img align="center" alt="kodveblog" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/csharp/csharp-original.svg">
  <img align="center" alt="kodveblogr" height="30" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/perl/perl-original.svg" />
    <img align="center" alt="kodveblog" height="30" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/c/c-original.svg" />
      <img align="center" alt="kodveblog" height="30" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/go/go-original.svg" />
      <img align="center" alt="kodveblog" height="30" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/bash/bash-original.svg" />
        <img align="center" alt="kodveblog" height="30" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" />
