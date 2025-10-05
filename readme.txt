Get PRO Here:
https://templatesjungle.gumroad.com/l/ultras-free-ecommerce-clothing-store-website-template

It is a free HTML CSS template by TemplatesJungle.com
You can use this template as a starter template and start building as you require.

The code is consistent and can be easily maintained as we have followed a good coding standards. We want everyone to easily understand it and modify it according to their requirement. As the main goal of providing these templates is to give you something to work on before even starting.


FREE FOR BOTH PERSONAL AND COMMERCIAL USE

This HTML Template is provided by TemplatesJungle.com and is free to use in both personal and commercial projects as long as you don't remove our credit link in the footer.

However, you can remove the credit link by paying for No Attribution version of the template.


RIGHTS

You are allowed to use it in your personal projects and commercial projects.

You can modify and sell it to your clients.


PROHIBITIONS

You cannot remove the credit link which links back to templatesjungle.com.

You are not permitted to resell or redistribute (paid or free) as it is. 

You cannot use it to build premium templates, themes or any other goods to be sold on marketplaces.

If you want to share the free resource in your blog, you must point it to original TemplatesJungle.com resource page. 

You cannot host the download file in your website.


SUPPORT

You can contact us to report any bugs and errors in the template. We will try and fix them immediately although it's a free resource.

Feel free to let us know about what you want to see in the future downloads. We will definitely give it a thought while creating our next freebie.


CREDITS & REFERENCES

https://getbootstrap.com/

Stock Photos
https://unsplash.com/
https://www.freepik.com/
https://www.pexels.com/

Fonts
Google fonts
https://fonts.google.com/

Icons
https://icomoon.io/

JQuery Plugins

Swiper Slider - https://swiperjs.com/
Slick Slider - https://kenwheeler.github.io/slick/
Chocolat.js – a Free Lightbox Plugin -http://chocolat.insipi.de/
Magnific Lightbox - https://github.com/dimsemenov/Magnific-Popup

Thanks for downloading from TemplatesJungle.com !


<nav class="navbar navbar-expand-lg fixed-top gold-glass-nav">
  <div class="container-fluid px-4 py-2">

    <!-- Left: Brand -->
    <a class="navbar-brand d-flex align-items-center gap-2" href="#">
      <span class="brand-mark"></span>
      <span class="brand-script">Follow Me</span>
    </a>

    <!-- Navbar Toggler -->
    <button class="navbar-toggler border-0 shadow-none" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
      aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>

    <!-- Center Nav Items -->
    <div class="collapse navbar-collapse justify-content-center" id="navbarNav">
      <ul class="navbar-nav gap-lg-1">
        <li class="nav-item"><a class="nav-link px-3 py-2 active" aria-current="page" href="#">Home</a></li>
        <li class="nav-item"><a class="nav-link px-3 py-2" href="catalogue.html">Shop</a></li>
        <li class="nav-item"><a class="nav-link px-3 py-2" href="#">About Us</a></li>
      </ul>
    </div>

    <!-- Right: Social Icons -->
    <div class="socialicon d-flex ms-auto align-items-center social-wrap">
      <a href="#" class="nav-link fs-5 mx-2 social-link"><i class="fab fa-instagram"></i></a>
      <a href="#" class="nav-link fs-5 mx-2 social-link"><i class="fab fa-facebook"></i></a>
      <a href="#" class="nav-link fs-5 mx-2 social-link"><i class="fab fa-twitter"></i></a>
    </div>

  </div>
</nav>

<style>
  :root{
    --gold:#d4af37;
    --gold-deep:#b9931e;
    --gold-soft:#f6e7b4;
    --ink:#1f1f1f;
  }

  /* Glassy, gold navbar */
  .gold-glass-nav{
    background: rgba(255,255,255,0.58); /* must be translucent for blur to show */
    backdrop-filter: blur(10px);
    -webkit-backdrop-filter: blur(10px);
    border-bottom:1px solid rgba(212,175,55,0.35);
    box-shadow:0 10px 24px rgba(212,175,55,0.2);
  }

  /* Toggler styled for light glass background */
  .gold-glass-nav .navbar-toggler{
    border:1px solid rgba(212,175,55,.55)!important;
    border-radius:10px;
    background: linear-gradient(180deg,#fffef6,#fff8df);
    padding:.35rem .5rem;
  }
  .gold-glass-nav .navbar-toggler .navbar-toggler-icon{
    background-image:none;
    position:relative; width:1.4rem; height:1.2rem; display:inline-block;
  }
  .gold-glass-nav .navbar-toggler .navbar-toggler-icon::before,
  .gold-glass-nav .navbar-toggler .navbar-toggler-icon::after{
    content:""; position:absolute; left:0; right:0; height:2px; background:#2b2710; border-radius:2px;
  }
  .gold-glass-nav .navbar-toggler .navbar-toggler-icon::before{ top:3px; }
  .gold-glass-nav .navbar-toggler .navbar-toggler-icon::after{ bottom:3px; }
  .gold-glass-nav .navbar-toggler:focus{ box-shadow:0 0 0 4px rgba(212,175,55,.22)!important; }

  /* Brand */
  .gold-glass-nav .brand-mark{
    width:36px; height:36px; border-radius:8px; display:inline-block;
    border:1px solid rgba(212,175,55,0.6);
    background: radial-gradient(circle at 30% 30%, #fff 10%, #fef6d8 40%, #f3e2a2 70%);
    box-shadow:0 6px 14px rgba(212,175,55,.28);
  }
  .gold-glass-nav .brand-script{
    font-family:"Great Vibes",cursive;
    font-size:30px; color:var(--gold-deep);
    text-shadow:0 1px 8px rgba(212,175,55,.35);
    letter-spacing:.5px;
  }

  /* Links */
  .gold-glass-nav .nav-link{
    color:#2b2710 !important;
    font-weight:600;
    border:1px solid transparent;
    border-radius:10px;
    transition: color .15s ease, background .15s ease, border-color .15s ease, transform .12s ease;
  }
  .gold-glass-nav .nav-link:hover,
  .gold-glass-nav .nav-link:focus{
    color:#1e1a08 !important;
    background:linear-gradient(180deg,#fffef6,#fff9e3);
    border-color:rgba(212,175,55,.45);
    transform: translateY(-1px);
  }
  .gold-glass-nav .nav-link.active,
  .gold-glass-nav .nav-link[aria-current="page"]{
    background:linear-gradient(180deg, var(--gold) 0%, #f3d777 60%, var(--gold) 100%);
    color:#1e1a08 !important;
    border-color: var(--gold);
    box-shadow: inset 0 1px 0 rgba(255,255,255,.6), 0 8px 18px rgba(212,175,55,.28);
  }

  /* Social icons */
  .gold-glass-nav .social-link{
    color:#2b2710 !important;
    border-radius:10px;
    border:1px solid transparent;
  }
  .gold-glass-nav .social-link:hover{
    background:linear-gradient(180deg,#fffef6,#fff9e3);
    border-color:rgba(212,175,55,.45);
    transform: translateY(-1px);
  }

  /* Collapse panel styling on mobile */
  @media (max-width: 991.98px){

    .gold-glass-nav .navbar-collapse{
      background:#fff;
      border:1px solid rgba(212,175,55,.45);
      border-radius:14px;
      box-shadow:0 18px 38px rgba(212,175,55,.25);
      padding:10px;
      margin-top:10px;
    }
    .gold-glass-nav .navbar-nav .nav-link{
      padding:.65rem .8rem;
    }
  }
</style>


<!-- data-colors='{"purple":["./images/fboy2.jpg","./images/fboy1.jpg"],"black":["./images/fboy1.jpg","./images/fboy2.jpg"]}' -->


        data-description="100% cotton, 180 GSM, regular fit"
        data-sku="TEE-PURPLE-XS"
        data-material="Cotton"