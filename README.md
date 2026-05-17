<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Vermont Dining</title>
     <!-- FONT DYNAPUFF -->
    <link href="https://fonts.googleapis.com/css2?family=DynaPuff:wght@400..700&display=swap">
  <!-- Hubungkan ke file CSS -->
  <link rel="stylesheet" href="style.css">
</head>
<body>
       
    <header>
        <!-- LOGO -->
        <div class="logo-img">
         <h1 style="color: white;">VERMONT</h1>
        </div>



        <!-- NAVIGASI -->
        <nav>
          <a href="#menu">Menu</a>
          <a href="#about">About</a>
          <a href="#contact">Contact</a>
        </nav>

        <!-- TOMBOL -->
        <button class="btn-reserve">Reserve Table</button>
    </header>

 <!-- HERO SECTION -->
  <section class="hero">
    <div class="hero-overlay"></div>
    <div class="hero-content">
      <h1>Fine Dining Experience</h1>
      <h2>COOKED WITH CARE, SERVE WITH SOUL</h2>
    </div>
  </section>

 <!-- ===== MENU SECTION ===== -->
  <section class="menu-section" id="menu">
    <div class="menu-header">
      <h2>Our Menu</h2>
      <p>Crafted with the finest ingredients</p>
    </div>
    

    <!-- TOMBOL KATEGORI -->
    <div class="menu-categories">
      <button class="cat-btn active" data-category="all">All</button>
      <button class="cat-btn" data-category="salad">Salad & Soup</button>
      <button class="cat-btn" data-category="bites">Bites</button>
      <button class="cat-btn" data-category="maincourse">Main Course</button>
      <button class="cat-btn" data-category="dessert">Dessert</button>
      <button class="cat-btn" data-category="beverage">Beverage</button>
      
    </div>

    <!-- GRID MENU -->
    <div class="menu-grid">

      <!-- SALAD -->
      <div class="menu-card" data-category="salad">
        <div class="menu-img-wrapper">
          <img src="tuna tataki.png" alt="Tuna Tataki Salad">
        </div>
        <div class="menu-info">
          <div class="menu-title-row">
            <h3>TUNA TATAKI SALAD</h3>
            <span class="menu-price">Rp65,000</span>
          </div>
          <p class="menu-desc">Pan Seared Tuna, Mix Mesclun, Watercress, Tomato Cherry, Cashewnut, Edammame, Kyuri, Goma Yoghurt Dressing</p>
        </div>
      </div>

      <div class="menu-card" data-category="salad">
        <div class="menu-img-wrapper">
          <img src="caesar salad.png" alt="Caesar Salad">
        </div>
        <div class="menu-info">
          <div class="menu-title-row">
            <h3>CAESAR SALAD ★</h3>
            <span class="menu-price">Rp65,000</span>
          </div>
          <p class="menu-desc">Baby Romaine, Tomato Cherry, Pan Seared Chicken Breast, Crouton, Soft Boiled Egg, Beef Bacon Bits, Caesar Dressing</p>
        </div>
      </div>

      <div class="menu-card" data-category="salad">
        <div class="menu-img-wrapper">
          <img src="prawnwatermelon.png" alt="Prawn & Watermelon Salad">
        </div>
        <div class="menu-info">
          <div class="menu-title-row">
            <h3>PRAWN & WATERMELON SALAD ★</h3>
            <span class="menu-price">Rp65,000</span>
          </div>
          <p class="menu-desc">Poached Prawn, Mix Mesclun, Watermelon, Watercress, Tomato Cherry, Cashew Nut, Edamame, Kyuri, Red Onion Pickle, Chili Lime Dressing</p>
        </div>
      </div>

      <div class="menu-card" data-category="salad">
        <div class="menu-img-wrapper">
          <img src="CHICKEN KATSU SALAD.jpg" alt="chicken katsu salad">
        </div>
        <div class="menu-info">
          <div class="menu-title-row">
            <h3>CHICKEN KATSU SALAD</h3>
            <span class="menu-price">Rp65,000</span>
          </div>
          <p class="menu-desc">Crispy Chicken Katsu, Mix Mesclun, Watercress, Tomato Cherry,Carrot, Kyuri, Katsuobushi, Nori, Soy Onion Dressing</p>
        </div>
      </div>

      <div class="menu-card" data-category="salad">
        <div class="menu-img-wrapper">
          <img src="trufle cream soup.jpg" alt="TRUFFLE CREAM SOUP">
        </div>
        <div class="menu-info">
          <div class="menu-title-row">
            <h3>TRUFFLE CREAM SOUP</h3>
            <span class="menu-price">Rp50,000</span>
          </div>
          <p class="menu-desc">Creamy & Velvety Mushroom Soup, Truffle Oil, Crouton</p>
        </div>
      </div>

      <!-- BITES -->
      <div class="menu-card" data-category="bites">
        <div class="menu-img-wrapper">
          <img src="sate lilit.png" alt="sate lilit">
        </div>
        <div class="menu-info">
          <div class="menu-title-row">
            <h3>SATE LILIT BALI ★</h3>
            <span class="menu-price">Rp52,000</span>
          </div>
          <p class="menu-desc">Balinese Chicken Skewer, Sambal Matah</p>
        </div>
      </div>

      <div class="menu-card" data-category="bites">
        <div class="menu-img-wrapper">
          <img src="MAC CHICK BAO.png" alt="MAC’CHICKEN BAO">
        </div>
        <div class="menu-info">
          <div class="menu-title-row">
            <h3>MAC’CHICKEN BAO</h3>
            <span class="menu-price">Rp42,000</span>
          </div>
          <p class="menu-desc">Fried Bao, Chicken Patty, Nori Mayo,Pickle Kyuri, Tobiko</p>
        </div>
      </div>

      <div class="menu-card" data-category="bites">
        <div class="menu-img-wrapper">
          <img src="ESCARGOT JIMBARAN.png" alt="JIMBARAN ESCARGOT PIE TEE">
        </div>
        <div class="menu-info">
          <div class="menu-title-row">
            <h3>JIMBARAN ESCARGOT PIE TEE🌶️</h3>
            <span class="menu-price">Rp42,000</span>
          </div>
          <p class="menu-desc">Jimbaran Spices, Sambal Ijo Mayo, Tobiko,Pico De GalO</p>
        </div>
      </div>

      <div class="menu-card" data-category="bites">
        <div class="menu-img-wrapper">
          <img src="BETUTU SPRING ROLL.png" alt="BETUTU SPRING ROLL">
        </div>
        <div class="menu-info">
          <div class="menu-title-row">
            <h3>BETUTU SPRING ROLL🌶️</h3>
            <span class="menu-price">Rp38,000</span>
          </div>
          <p class="menu-desc">Pulled Betutu Duck, Mix Vegetables,Sambal Korek</p>
        </div>
      </div>

      <div class="menu-card" data-category="bites">
        <div class="menu-img-wrapper">
          <img src="salmon panipuri.png" alt="SALMON panipuri">
        </div>
        <div class="menu-info">
          <div class="menu-title-row">
            <h3>SALMON PANIPURI★🌶️</h3>
            <span class="menu-price">Rp42,000</span>
          </div>
          <p class="menu-desc">Pulled Betutu Duck, Mix Vegetables,Sambal Korek</p>
        </div>
      </div>
      
      <div class="menu-card" data-category="bites">
        <div class="menu-img-wrapper">
          <img src="CORN RIBS.png" alt="CORN RIBS">
        </div>
        <div class="menu-info">
          <div class="menu-title-row">
            <h3>CORN RIBS</h3>
            <span class="menu-price">Rp32,000</span>
          </div>
          <p class="menu-desc">Rujak Powder, Grana Padano Cheese</p>
        </div>
      </div>

      <div class="menu-card" data-category="bites">
        <div class="menu-img-wrapper">
          <img src="CHICKEN TACO .png" alt="CHICKEN TACO">
        </div>
        <div class="menu-info">
          <div class="menu-title-row">
            <h3>CHICKEN TACO</h3>
            <span class="menu-price">Rp32,000</span>
          </div>
          <p class="menu-desc">Grilled Chicken, Guacamole, Chipotle Mayo,Pico De Gallo, Pickle Green Chili</p>
        </div>
      </div>


      <!-- MAIN COURSE -->
      <div class="menu-card" data-category="maincourse">
        <div class="menu-img-wrapper">
          <img src="chicken katsu curry.png" alt="CHICKEN KATSU CURRY">
        </div>
        <div class="menu-info">
          <div class="menu-title-row">
            <h3>CHICKEN KATSU CURRY</h3>
            <span class="menu-price">Rp70,000</span>
          </div>
          <p class="menu-desc">Japanese Fried Chicken, Curry Sauce, Scrambled Egg, Asian Slaw , Furikake, Steamed Rice</p>
        </div>
      </div>

      <div class="menu-card" data-category="maincourse">
        <div class="menu-img-wrapper">
          <img src="nasi tutug oncom.png" alt="nasi tutug oncom">
        </div>
        <div class="menu-info">
          <div class="menu-title-row">
            <h3>NASI TUTUG ONCOM</h3>
            <span class="menu-price">Rp72,000</span>
          </div>
          <p class="menu-desc">Fried Ayam Kampung, Oncom, Serundeng Lengkoas,Telur Barendo, Rempeyek Kacang, Sambal Roa</p>
        </div>
      </div>

      <div class="menu-card" data-category="maincourse">
        <div class="menu-img-wrapper">
          <img src="IGA BETAWI.png" alt="IGA BETAWI">
        </div>
        <div class="menu-info">
          <div class="menu-title-row">
            <h3>IGA BETAWI★</h3>
            <span class="menu-price">Rp85,000</span>
          </div>
          <p class="menu-desc">Slow Cooked Beef Ribs, Beef Shank,White Curry Broth, Fried Potato, Tomato, Leek,Steam Rice, Sambal, Pickle, Emping</p>
        </div>
      </div>

      <div class="menu-card" data-category="maincourse">
        <div class="menu-img-wrapper">
          <img src="SPICY BEEF RAMDON.png" alt="SPICY BEEF RAMDON">
        </div>
        <div class="menu-info">
          <div class="menu-title-row">
            <h3>SPICY BEEF RAMDON🌶️★</h3>
            <span class="menu-price">Rp85,000</span>
          </div>
          <p class="menu-desc">Ramen Noodle, Beef Shortplate Tare,Spicy Black Bean Sauce, 63c Sousvide Egg,Furikake, Nori, Ito Kezuri</p>
        </div>
      </div>

      <div class="menu-card" data-category="maincourse">
        <div class="menu-img-wrapper">
          <img src="NASI CAMPUR BALI.png" alt="NASI CAMPUR BALI">
        </div>
        <div class="menu-info">
          <div class="menu-title-row">
            <h3>NASI CAMPUR BALI🌶️</h3>
            <span class="menu-price">Rp62,000</span>
          </div>
          <p class="menu-desc">Ayam Kampung Betutu, Lawar, Sate Lilit,Nasi Gurih Kecombrang,Sambal Matah,Sambal Mbe, Kerupuk Gendar</p>
        </div>
      </div>

      <div class="menu-card" data-category="maincourse">
        <div class="menu-img-wrapper">
          <img src="IRENG CRISPY DUCK.png" alt="IRENG CRISPY DUCK">
        </div>
        <div class="menu-info">
          <div class="menu-title-row">
            <h3>IRENG CRISPY DUCK★</h3>
            <span class="menu-price">Rp90,000</span>
          </div>
          <p class="menu-desc">Madura Crispy Half Duck, Bumbu Hitam, Assorted Sambal, Serundeng Lengkoas, Lawar , SteamedRice</p>
        </div>
      </div>

      <div class="menu-card" data-category="maincourse">
        <div class="menu-img-wrapper">
          <img src="SALMON CREAMY SPINACH.png" alt="SALMON CREAMY SPINACH">
        </div>
        <div class="menu-info">
          <div class="menu-title-row">
            <h3>SALMON CREAMY SPINACH★</h3>
            <span class="menu-price">Rp148,000</span>
          </div>
          <p class="menu-desc">Pan Seared Salmon, Hassleback Potato,Creamy Spinach Sauce, Glazed Carrot, Watercress</p>
        </div>
      </div>

      <div class="menu-card" data-category="maincourse">
        <div class="menu-img-wrapper">
          <img src="WAGYU BEEF CHEEK.png" alt="WAGYU BEEF CHEEK">
        </div>
        <div class="menu-info">
          <div class="menu-title-row">
            <h3>WAGYU BEEF CHEEK★</h3>
            <span class="menu-price">Rp165,000</span>
          </div>
          <p class="menu-desc">48 Hours Slow Cooked Beef Cheek, Soy Glazed,Mashed potato, Eggplant Roa, Watercress,Kalio Sauce</p>
        </div>
      </div>


      <!-- DESSERT -->
      <div class="menu-card" data-category="dessert">
        <div class="menu-img-wrapper">
          <img src="MOCHI BERRY CHEESECAKE.png" alt="MOCHI BERRY CHEESECAKE">
        </div>
        <div class="menu-info">
          <div class="menu-title-row">
            <h3>MOCHI BERRY CHEESECAKE★</h3>
            <span class="menu-price">Rp58,000</span>
          </div>
          <p class="menu-desc">Basque Cheesecake Brule, Strawberry Salsa,Mochi, Strawberry Sorbet</p>
        </div>
      </div>

      <div class="menu-card" data-category="dessert">
        <div class="menu-img-wrapper">
          <img src="TIRAMISU.png" alt="Tiramisu">
        </div>
        <div class="menu-info">
          <div class="menu-title-row">
            <h3>TIRAMISU★</h3>
            <span class="menu-price">Rp58,000</span>
          </div>
          <p class="menu-desc">Espresso Soaked Ladyfinger, Mascarpone Cream, Cocoa Powder</p>
        </div>
      </div>

      <div class="menu-card" data-category="dessert">
        <div class="menu-img-wrapper">
          <img src="HOJICHA CHOCOLATE PANNA COTTA.png" alt="HOJICHA CHOCOLATE PANNA COTTA">
        </div>
        <div class="menu-info">
          <div class="menu-title-row">
            <h3>THOJICHA CHOCOLATE PANNA COTTA</h3>
            <span class="menu-price">Rp48,000</span>
          </div>
          <p class="menu-desc">Hojicha Panna Cotta, Chocolate Malt, Chocolate Mousse</p>
        </div>
      </div>

      <div class="menu-card" data-category="dessert">
        <div class="menu-img-wrapper">
          <img src="PANDAN COCONUT.png" alt="PANDAN COCONUT">
        </div>
        <div class="menu-info">
          <div class="menu-title-row">
            <h3>PANDAN COCONUT</h3>
            <span class="menu-price">Rp48,000</span>
          </div>
          <p class="menu-desc">Pandan Butter Cake, Homemade Coconut Ice Cream,Ketan Hitam Crunch, Gula Melaka Drizzle</p>
        </div>
      </div>
      

      <!-- Beverage -->

      <div class="menu-card" data-category="beverage">
        <div class="menu-img-wrapper">
          <img src="espresso.png" alt="espresso">
        </div>
        <div class="menu-info">
          <div class="menu-title-row">
            <h3>ESPRESSO</h3>
            <span class="menu-price">Rp25,000</span>
          </div>
          <p class="menu-desc">
            <a>Espresso</a>
              <a>doppio</a>
          </div>
      </div>

      <div class="menu-card" data-category="beverage">
        <div class="menu-img-wrapper">
          <img src="OSMANTHUS AMERICANO.png" alt="OSMANTHUS AMERICANO">
        </div>
        <div class="menu-info">
          <div class="menu-title-row">
            <h3>OSMANTHUS AMERICANO★</h3>
            <span class="menu-price">Rp35,000</span>
          </div>
          <p class="menu-desc">Sea Salt Cream, Osmanthus, Espresso</p>
        </div>
      </div>

      <div class="menu-card" data-category="beverage">
        <div class="menu-img-wrapper">
          <img src="AVOCADO COFFEE.png" alt="AVOCADO COFFEE">
        </div>
        <div class="menu-info">
          <div class="menu-title-row">
            <h3>AVOCADO COFFEE★</h3>
            <span class="menu-price">Rp35,000</span>
          </div>
          <p class="menu-desc">Avocado, Fresh Milk, Chocolate Sauce, Espresso</p>
        </div>
      </div>

    </div>
  </section>


  <!-- JAVASCRIPT FILTER -->
  <script>
    const buttons = document.querySelectorAll('.cat-btn');
    const cards = document.querySelectorAll('.menu-card');

    buttons.forEach(btn => {
      btn.addEventListener('click', () => {
        buttons.forEach(b => b.classList.remove('active'));
        btn.classList.add('active');

        const selected = btn.dataset.category;

        cards.forEach(card => {
          if (selected === 'all' || card.dataset.category === selected) {
            card.classList.remove('hidden');
          } else {
            card.classList.add('hidden');
          }
        });
      });
    });
  </script>
  
  <!-- ===== ABOUT SECTION ===== -->
  <about class="about">
    <section class="about-section" id="about">




  
  
  
  
  
  
  
  
  <!-- FOOTER -->
  <footer class="footer" >
    <section class="footer-section" id="contact">

    <!-- LOGO TENGAH -->
    <div class="footer-brand">
      <div class="brand-inner">
        <div class="brand-ornament">
          <div class="brand-ornament">
    <img src="logo vrmnt.png" alt="Vermont Logo" class="brand-logo-img"></div>
        </div>
        <div class="brand-divider-v"></div>
        <div class="brand-text">
          <h2 class="brand-name">VERMONT</h2>
          <p class="brand-sub">Fine Dining & Experience</p>
        </div>
      </div>
    </div>

    <!-- SPACER -->
    <div class="footer-spacer"></div>

    <!-- 3 KOLOM -->
    <div class="footer-locations">

      <!-- KOLOM 1: CONTACT -->
      <div class="location-col">
        <h3 class="location-city">CONTACT US</h3>

        <div class="contact-list">

          <!-- WhatsApp -->
          <a href="https://wa.me/6285179976731" class="contact-item" target="_blank" aria-label="WhatsApp">
            <div class="contact-icon-wrap wa">
              <svg viewBox="0 0 24 24" width="20" height="20" fill="currentColor">
                <path d="M17.472 14.382c-.297-.149-1.758-.867-2.03-.967-.273-.099-.471-.148-.67.15-.197.297-.767.966-.94 1.164-.173.199-.347.223-.644.075-.297-.15-1.255-.463-2.39-1.475-.883-.788-1.48-1.761-1.653-2.059-.173-.297-.018-.458.13-.606.134-.133.298-.347.446-.52.149-.174.198-.298.298-.497.099-.198.05-.371-.025-.52-.075-.149-.669-1.612-.916-2.207-.242-.579-.487-.5-.669-.51-.173-.008-.371-.01-.57-.01-.198 0-.52.074-.792.372-.272.297-1.04 1.016-1.04 2.479 0 1.462 1.065 2.875 1.213 3.074.149.198 2.096 3.2 5.077 4.487.709.306 1.262.489 1.694.625.712.227 1.36.195 1.871.118.571-.085 1.758-.719 2.006-1.413.248-.694.248-1.289.173-1.413-.074-.124-.272-.198-.57-.347z"/>
                <path d="M12 0C5.373 0 0 5.373 0 12c0 2.123.553 4.116 1.523 5.845L.057 23.571a.5.5 0 0 0 .613.613l5.726-1.466A11.944 11.944 0 0 0 12 24c6.627 0 12-5.373 12-12S18.627 0 12 0zm0 22a9.944 9.944 0 0 1-5.073-1.386l-.363-.215-3.761.963.983-3.761-.234-.376A9.944 9.944 0 0 1 2 12C2 6.477 6.477 2 12 2s10 4.477 10 10-4.477 10-10 10z"/>
              </svg>
            </div>
            <div class="contact-info">
              <span class="contact-label">WhatsApp</span>
              <span class="contact-value">+62 811-7075-6865</span>
            </div>
          </a>

          <!-- Instagram -->
          <a href="https://www.instagram.com/vermont.dining?utm_source=ig_web_button_share_sheet&igsh=ZDNlZDc0MzIxNw==" class="contact-item" target="_blank" aria-label="Instagram">
            <div class="contact-icon-wrap ig">
              <svg viewBox="0 0 24 24" width="20" height="20" fill="none" stroke="currentColor" stroke-width="2">
                <rect x="2" y="2" width="20" height="20" rx="5"/>
                <circle cx="12" cy="12" r="4"/>
                <circle cx="17.5" cy="6.5" r="1.5" fill="currentColor" stroke="none"/>
              </svg>
            </div>
            <div class="contact-info">
              <span class="contact-label">Instagram</span>
              <span class="contact-value">@vermont.dining</span>
            </div>
          </a>

          <!-- Email -->
          <a href="vermontdining.pwt@gmail.com" class="contact-item" aria-label="Email">
            <div class="contact-icon-wrap email">
              <svg viewBox="0 0 24 24" width="20" height="20" fill="none" stroke="currentColor" stroke-width="2">
                <rect x="2" y="4" width="20" height="16" rx="3"/>
                <polyline points="2,4 12,13 22,4"/>
              </svg>
            </div>
            <div class="contact-info">
              <span class="contact-label">Email</span>
              <span class="contact-value">vermontdining.pwt@gmail.com</span>
            </div>
          </a>

        </div>
      </div>

      <!-- GARIS VERTIKAL -->
      <div class="vline"></div>

      <!-- KOLOM 2: LOKASI / ADDRESS -->
      <div class="location-col">
        <h3 class="location-city">OUR LOCATION</h3>
        <p class="location-address">
          Purwokerto<br>
          Jl. Jend. Gatot Subroto No. 34-36<br>
          Purwokerto Timur<br>
          Banyumas<br>
        </p>
        <p class="location-contact"></p>
        <p class="location-contact"></p>
        <div class="social-row">
          
          
          </a>
        </div>
      </div>

      <!-- GARIS VERTIKAL -->
      <div class="vline"></div>

      <!-- KOLOM 3: GOOGLE MAPS -->
      <div class="location-col">
        <h3 class="location-city">FIND US</h3>
        <div class="map-wrapper">
          
          <iframe
            src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3956.3797350890873!2d109.24094407605787!3d-7.423159673121598!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x2e655f20da76ce75%3A0xdeae13e510e7c9b2!2sVermont%20Dining!5e0!3m2!1sen!2sus!4v1779011007326!5m2!1sen!2sus"
            width="100%"
            height="100%"
            style="border:0;"
            allowfullscreen=""
            loading="lazy"
            referrerpolicy="no-referrer-when-downgrade">
          </iframe>
          <!-- Tombol buka di Google Maps -->
          <a
            href="https://maps.google.com/?q=Vermont+Dining+Purwokerto"
            target="_blank"
            class="map-open-btn">
            <svg viewBox="0 0 24 24" width="14" height="14" fill="currentColor">
              <path d="M12 2C8.13 2 5 5.13 5 9c0 5.25 7 13 7 13s7-7.75 7-13c0-3.87-3.13-7-7-7zm0 9.5c-1.38 0-2.5-1.12-2.5-2.5S10.62 6.5 12 6.5s2.5 1.12 2.5 2.5S13.38 11.5 12 11.5z"/>
            </svg>
            Buka di Google Maps
          </a>
        </div>
      </div>

    </div>

    <!-- BOTTOM BAR -->
    <div class="footer-bottom-bar">
      <div class="bottom-content">
        <p class="footer-copy">Copyright © 2026 <strong>Vermont Dining</strong>. All Right Reserved</p>
        <a href="#" class="footer-terms">TERMS</a>
      </div>
    </div>

  </footer>

  <!-- animasi type js -->
  <script src="https://unpkg.com/typed.js@3.0.0/dist/typed.umd.js">
    </script>
  <script>
    var typed = new Typed('#running-text', {
      strings:  ['hello', '&amp; a second sentence.'],
      typeSpeed: 50,
    });
  </script>
</body>
</html>>
