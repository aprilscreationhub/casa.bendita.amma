<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Casa Bendita Amma – Oceanfront Property</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background: #f4f4f4;
      color: #333;
    }
    header {
      background: #0a4d68;
      color: white;
      padding: 20px;
      text-align: center;
    }
    .container {
      padding: 20px;
      max-width: 1000px;
      margin: auto;
      background: white;
    }
  
    .gallery {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 15px;
}

.gallery img {
  width: 100%;
  border-radius: 10px;
}
    .price {
      font-size: 28px;
      color: #0a4d68;
      font-weight: bold;
    }
    .features {
      display: flex;
      gap: 15px;
      flex-wrap: wrap;
      margin: 15px 0;
    }
    .feature-box {
      background: #e8f1f5;
      padding: 10px;
      border-radius: 8px;
    }
    footer {
      text-align: center;
      padding: 20px;
      background: #0a4d68;
      color: white;
      margin-top: 20px;
    }
    /* Gallery images */
.gallery {
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
  justify-content: center;
}

.gallery img {
  width: 200px;
  border-radius: 5px;
  cursor: pointer;
  transition: 0.3s;
}

.gallery img:hover {
  transform: scale(1.03);
}

/* Lightbox (zoom view) */
.lightbox {
  display: none;
  position: fixed;
  z-index: 999;
  left: 0;
  top: 0;
  width: 100%;
  height: 100%;
  background: rgba(0,0,0,0.8);
  justify-content: center;
  align-items: center;
}

.lightbox img {
  max-width: 90%;
  max-height: 90%;
  border-radius: 10px;
}
  </style>
</head>

<body>

<header>
  <h1>Casa Bendita Amma</h1>
  <p>Oceanfront Luxury – Isla Mujeres, Mexico</p>
</header>

<div class="container">

  <div class="price">$1,500,000 USD</div>

  <div class="features">
    <div class="feature-box">3 Bedrooms</div>
    <div class="feature-box">2 Bathrooms</div>
    <div class="feature-box">3,000 Sq Ft</div>
    <div class="feature-box">3 Levels</div>
  </div>

<div class="gallery">
  
  <img src="Frnt View 1" alt="Frnt View 1">
  <img src="side view 2" alt="side view 2">
  <img src="Frnt Patio 3" alt="Frnt Patio 3">
  <img src="kitchen 4" alt="kitchen 4">
  <img src="prmy rm 5.1" alt="prmy rm 5.1">
  <img src="prmy rm 5.2" alt="prmy rm 5.2">
  <img src="lvng rm 6" alt="lvng rm 6">
  <img src="prmy bthrm 7" alt="prmy bthrm 7">
  <img src="dwn strs 8" alt="dwn strs 8">
  <img src="Btm Flr rm 9" alt="Btm Flr rm 9">
  <img src="btm flr bthrm 10.1" alt="btm flr bthrm 10.1">
  <img src="btm flr bthrm 10.2" alt="btm flr bthrm 10.2">
  <img src="top flr 11.1" alt="top flr 11.1">
  <img src="top flr 11.2" alt="top flr 11.2">
  <img src="top view 12" alt="top view 12">
  <img src="bk house view 13" alt="bk house view 13">
  <img src="back balcony 14" alt="back balcony 14">
  <img src="bck balcony 14.1" alt="bck balcony 14.1">
  <img src="bk platform 15" alt="bk platform 15">
  <img src="bk view 16" alt="bk view 16">
  <img src="bk view 2 17" alt="bk view 2 17">
  <img src="beach view 18" alt="beach view 18">
  <img src="coast line 19" alt="coast line 19">
  
  </div>

  <h2>Property Highlights</h2>
  <p>
    Experience breathtaking oceanfront living on the Caribbean side of Isla Mujeres.
    This rare property offers unobstructed views that will never be blocked — one of the last homes of its kind.
  </p>

  <ul>
    <li>Oceanfront with a sandy beach close by</li>
    <li>Elevated 30 ft above sea level</li>
    <li>Sparkling heated & cooling tile pool</li>
    <li>Third-level deck with spectacular panoramic views</li>
    <li>New glass patio doors</li>
    <li>New split AC units</li>
    <li>Fully furnished (owners taking only personal items)</li>
    <li>Newly remodeled kitchen</li>
    <li>Beautiful tile bathrooms throughout</li>
    <li>Pergola-covered parking</li>
    <li>Workshop included</li>
    <li>Completely fenced with electric front gate</li>
  </ul>

  <h2>Description</h2>
  <p>
    Casa Bendita Amma is a stunning three-level oceanfront home designed for comfort,
    privacy, and unforgettable views. Enjoy the sound of waves, direct beach access,
    and luxury features throughout. Whether you're looking for a dream home,
    vacation property, or investment opportunity, this property delivers unmatched value.
  </p>

  <h2>Contact</h2>
  <p>
    📧 Email: casabenditaamma@gmail.com<br>
    📞 Phone: 1-409-381-1974
  </p>

</div>

<footer>
  <p>Schedule your showing today – This opportunity won’t last!</p>
</footer>

<div class="lightbox" id="lightbox" onclick="closeLightbox()">
  <img id="lightbox-img">
</div>

<script>
  const images = document.querySelectorAll(".gallery img");
  const lightbox = document.getElementById("lightbox");
  const lightboxImg = document.getElementById("lightbox-img");

  images.forEach(img => {
    img.addEventListener("click", () => {
      lightbox.style.display = "flex";
      lightboxImg.src = img.src;
    });
  });

  function closeLightbox() {
    lightbox.style.display = "none";
  }
</script>

</body>
</html>
