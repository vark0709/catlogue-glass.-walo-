
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>VARK ENTERPRISES | Wholesale Product Catalogue</title>
<meta name="description" content="Importer & distributor of trending products, gadgets, bottles, tumblers, household items and corporate gifts across India.">
<style>
:root{--ink:#111;--mute:#5f5f5f;--line:#e8e8e8;--bg:#fff;--soft:#f5f5f4;--wa:#128c4a}
*{box-sizing:border-box;margin:0;padding:0}
html{scroll-behavior:smooth;scroll-padding-top:70px}
body{font-family:system-ui,-apple-system,"Segoe UI",Roboto,Arial,sans-serif;color:var(--ink);background:var(--bg);line-height:1.5;overflow-x:hidden;padding-bottom:110px}
img{max-width:100%;display:block}
a{color:inherit}
.wrap{max-width:1100px;margin:0 auto;padding:0 20px}
section{padding:48px 0}
h1{font-size:clamp(2.2rem,9vw,4rem);line-height:1.05;letter-spacing:-.03em}
h2{font-size:clamp(1.5rem,5vw,2.1rem);letter-spacing:-.02em;margin-bottom:8px}
.sub{color:var(--mute);margin-bottom:24px}
header{position:sticky;top:0;background:rgba(255,255,255,.95);backdrop-filter:blur(8px);border-bottom:1px solid var(--line);z-index:50}
.bar{display:flex;flex-wrap:wrap;align-items:center;justify-content:space-between;gap:4px 16px;padding:10px 20px;max-width:1100px;margin:0 auto}
.brand{font-weight:800;letter-spacing:.08em;text-decoration:none;font-size:1rem}
nav.top{display:flex;gap:16px;font-size:.9rem}
nav.top a{text-decoration:none;color:var(--mute);padding:4px 0}
nav.top a:hover{color:var(--ink)}
.btn{display:inline-block;border:1.5px solid var(--ink);background:var(--ink);color:#fff;padding:13px 22px;border-radius:999px;font-weight:600;font-size:.95rem;text-decoration:none;cursor:pointer;transition:transform .15s,box-shadow .15s;font-family:inherit}
.btn:hover{transform:translateY(-2px);box-shadow:0 8px 20px rgba(0,0,0,.15)}
.btn.out{background:#fff;color:var(--ink)}
.btn.wa{background:var(--wa);border-color:var(--wa)}
.btn.sm{padding:10px 14px;font-size:.85rem;width:100%;text-align:center}
.row{display:flex;flex-wrap:wrap;gap:12px;margin-top:24px}
.hero{padding:56px 0 24px}
.hero p{max-width:540px;color:var(--mute);margin-top:16px;font-size:1.05rem}
.cats{display:grid;grid-template-columns:repeat(2,1fr);gap:14px}
.cat{background:var(--soft);border-radius:24px;padding:22px 16px;text-align:left;border:1px solid transparent;cursor:pointer;font-family:inherit;color:inherit;transition:transform .2s,border-color .2s;min-height:130px}
.cat:hover{transform:translateY(-3px);border-color:var(--ink)}
.cat span{font-size:2rem;display:block;margin-bottom:10px}
.cat b{font-size:.95rem}
.tools{display:grid;gap:10px;margin-bottom:20px}
.tools input,.tools select{width:100%;padding:13px 16px;border:1.5px solid var(--line);border-radius:999px;font-size:1rem;font-family:inherit;background:#fff;color:var(--ink)}
.tools input:focus,.tools select:focus{outline:2px solid var(--ink);border-color:var(--ink)}
.chip{display:inline-block;background:var(--ink);color:#fff;padding:4px 12px;border-radius:999px;font-size:.8rem;margin-bottom:12px}
.grid{display:grid;grid-template-columns:repeat(2,1fr);gap:14px}
.card{border:1px solid var(--line);border-radius:22px;overflow:hidden;background:#fff;display:flex;flex-direction:column;transition:transform .2s,box-shadow .2s}
.card:hover{transform:translateY(-4px);box-shadow:0 12px 28px rgba(0,0,0,.08)}
.imgbox{position:relative;aspect-ratio:1/1;background:var(--soft)}
.imgbox img{width:100%;height:100%;object-fit:cover}
.fav{position:absolute;top:8px;right:8px;width:38px;height:38px;border-radius:50%;border:0;background:#fff;font-size:1.2rem;cursor:pointer;box-shadow:0 2px 8px rgba(0,0,0,.12)}
.info{padding:12px;display:flex;flex-direction:column;gap:4px;flex:1}
.info small{color:var(--mute);font-size:.75rem}
.info h3{font-size:.95rem;line-height:1.3}
.info .d{font-size:.8rem;color:var(--mute)}
.price{font-weight:700;margin-top:4px}
.moq{font-size:.78rem;color:var(--mute);margin-bottom:8px}
.info .btn{margin-top:auto}
.empty{text-align:center;padding:40px 16px;background:var(--soft);border-radius:24px;display:none}
.empty p{color:var(--mute);margin:8px 0 16px}
.dark{background:var(--ink);color:#fff;border-radius:28px;padding:36px 24px}
.dark p{color:#ccc;margin:8px 0 4px}
.dark .btn{background:#fff;color:#111;border-color:#fff}
.why{display:grid;gap:14px;grid-template-columns:1fr}
.why div{border:1px solid var(--line);border-radius:22px;padding:20px}
.why b{display:block;margin-bottom:4px}
.why p{color:var(--mute);font-size:.92rem}
footer{border-top:1px solid var(--line);padding:32px 0;color:var(--mute);font-size:.88rem}
footer .links{display:flex;flex-wrap:wrap;gap:6px 16px;margin:12px 0}
footer button{background:none;border:0;font:inherit;color:var(--ink);text-decoration:underline;cursor:pointer;padding:4px 0}
#policy{display:none;background:var(--soft);border-radius:18px;padding:16px;margin-top:10px;color:var(--ink)}
.bottom{position:fixed;left:50%;transform:translateX(-50%);bottom:14px;width:min(94%,440px);background:#111;border-radius:999px;display:flex;justify-content:space-around;padding:8px 6px;z-index:60;box-shadow:0 8px 24px rgba(0,0,0,.3)}
.bottom a{color:#fff;text-decoration:none;display:flex;flex-direction:column;align-items:center;font-size:.66rem;gap:2px;padding:4px 8px;border-radius:999px;min-width:56px}
.bottom a span{font-size:1.2rem;line-height:1}
.bottom a:hover,.bottom a:focus{background:#2b2b2b}
@media(min-width:700px){
.grid{grid-template-columns:repeat(3,1fr)}.cats{grid-template-columns:repeat(4,1fr)}
.tools{grid-template-columns:2fr 1.2fr 1.2fr auto}.why{grid-template-columns:repeat(4,1fr)}
.tools .btn{padding:12px 20px}}
@media(min-width:1000px){.grid{grid-template-columns:repeat(4,1fr)}.bottom{display:none}body{padding-bottom:0}}
</style>
</head>
<body>

<header>
  <div class="bar">
    <a class="brand" href="#home">VARK ENTERPRISES</a>
    <nav class="top" aria-label="Main">
      <a href="#home">Home</a><a href="#products">Products</a><a href="#about">About</a><a href="#contact">Contact</a>
    </nav>
  </div>
</header>

<main>
<section class="hero" id="home"><div class="wrap">
  <h1>Discover.<br>Source.<br>Save.</h1>
  <p>Trending products, everyday essentials and gifting solutions for retailers, resellers and bulk buyers.</p>
  <div class="row">
    <a class="btn" href="#products">Explore Catalogue</a>
    <a class="btn wa" data-wa="general" href="#">Enquire on WhatsApp</a>
  </div>
</div></section>

<section id="categories" style="padding-top:24px"><div class="wrap">
  <h2>Shop by category</h2><p class="sub">Tap a category to see its products.</p>
  <div class="cats" id="catCards"></div>
</div></section>

<section id="products"><div class="wrap">
  <h2>Featured Products</h2><p class="sub">Indicative prices. Ask us for the latest wholesale rates.</p>
  <div class="tools">
    <input id="q" type="search" placeholder="Search products by name" aria-label="Search products">
    <select id="cat" aria-label="Filter by category"></select>
    <select id="sort" aria-label="Sort products">
      <option value="">Sort: Featured</option>
      <option value="asc">Price: Low to High</option>
      <option value="desc">Price: High to Low</option>
    </select>
    <button class="btn out" id="clear" type="button">Clear filters</button>
  </div>
  <div id="savedChip" class="chip" style="display:none">Showing saved items only</div>
  <div class="grid" id="grid"></div>
  <div class="empty" id="empty">
    <h3>No products found</h3>
    <p>Try a different name or category, or ask us if we can source it for you.</p>
    <button class="btn" id="clear2" type="button">Clear filters</button>
  </div>
</div></section>

<section id="bulk"><div class="wrap"><div class="dark">
  <h2>Bulk Orders &amp; Corporate Gifting</h2>
  <p>Planning a festive campaign, employee gifting or a large reseller order? Tell us your quantity, budget and timeline and we will suggest suitable products.</p>
  <div class="row"><a class="btn" data-wa="bulk" href="#">Request a Bulk Quote</a></div>
</div></div></section>

<section id="about"><div class="wrap">
  <h2>Why choose VARK</h2><p class="sub">An importer and distributor serving retailers, resellers and businesses across India.</p>
  <div class="why">
    <div><b>Direct sourcing</b><p>We work close to the source so you get genuine products.</p></div>
    <div><b>Competitive wholesale pricing</b><p>Fair rates that leave room for your margin.</p></div>
    <div><b>Diverse product range</b><p>Gadgets, bottles, home items, gifts and festive stock in one place.</p></div>
    <div><b>Enquiry support</b><p>Message us for pricing, MOQ and availability, answered personally.</p></div>
  </div>
</div></section>

<section id="contact"><div class="wrap">
  <h2>Contact us</h2><p class="sub">Message us on WhatsApp for prices, MOQ and availability.</p>
  <div class="row" style="margin-top:0">
    <a class="btn wa" data-wa="general" href="#">Chat on WhatsApp</a>
    <a class="btn out" id="insta" href="#" target="_blank" rel="noopener">Instagram</a>
  </div>
</div></section>
</main>

<footer><div class="wrap">
  <b style="color:#111">VARK ENTERPRISES</b><br>
  Importer &amp; Distributor | India<br>
  Prices are indicative and may change. Enquiry only, no online checkout.
  <div class="links">
    <button type="button" data-policy="privacy">Privacy Policy</button>
    <button type="button" data-policy="terms">Terms</button>
    <button type="button" data-policy="shipping">Shipping &amp; Returns</button>
  </div>
  <div id="policy"></div>
  <p style="margin-top:12px">&copy; <span id="yr"></span> VARK ENTERPRISES. All rights reserved.</p>
</div></footer>

<nav class="bottom" aria-label="Mobile navigation">
  <a href="#home"><span>🏠</span>Home</a>
  <a href="#categories"><span>▦</span>Categories</a>
  <a href="#" data-wa="general"><span>💬</span>Enquiry</a>
  <a href="#products" id="navSaved"><span>♥</span>Saved</a>
  <a href="#contact"><span>☎</span>Contact</a>
</nav>

<script>
/* =====================================================
   1) YOUR SETTINGS - EDIT THESE TWO LINES
   ===================================================== */
// Country code + number, digits only. Example: 919876543210
const WHATSAPP_NUMBER = "91XXXXXXXXXX";   // <-- REPLACE 91XXXXXXXXXX WITH YOUR NUMBER
const INSTAGRAM_URL   = "https://www.instagram.com/"; // <-- paste your Instagram page link

/* =====================================================
   2) PRODUCT LIST - EDIT YOUR PRODUCTS HERE
   For each product:
   name, category (must match a name in CATEGORIES),
   price (a number like 249, or null for "Contact for Price"),
   moq (text like "12 pcs", or "" to hide),
   description, image (full photo link, or "" to use a placeholder),
   emoji (shown in the placeholder).
   Keep the commas and quote marks exactly as they are.
   ===================================================== */
const CATEGORIES = ["Gadgets & Electronics","Bottles & Tumblers","Home & Lifestyle","Corporate & Festive Gifts"];
const CAT_EMOJI  = ["🎧","🥤","🏠","🎁"];

const PRODUCTS = [
 {name:"Wireless Earbuds",category:"Gadgets & Electronics",price:399,moq:"10 pcs",description:"Bluetooth 5.0 with charging case.",image:"",emoji:"🎧"},
 {name:"20W Fast Charger",category:"Gadgets & Electronics",price:179,moq:"20 pcs",description:"Type-C fast charging adapter.",image:"",emoji:"🔌"},
 {name:"Mini Bluetooth Speaker",category:"Gadgets & Electronics",price:349,moq:"10 pcs",description:"Portable speaker with clear sound.",image:"",emoji:"🔊"},
 {name:"Smart Fitness Band",category:"Gadgets & Electronics",price:null,moq:"10 pcs",description:"Step, heart rate and sleep tracking.",image:"",emoji:"⌚"},
 {name:"Steel Water Bottle 750ml",category:"Bottles & Tumblers",price:149,moq:"24 pcs",description:"Single-wall stainless steel bottle.",image:"",emoji:"🍶"},
 {name:"Insulated Tumbler 500ml",category:"Bottles & Tumblers",price:299,moq:"12 pcs",description:"Keeps drinks hot or cold for hours.",image:"",
 
<!DOCTYPE html>
