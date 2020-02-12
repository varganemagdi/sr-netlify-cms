---
templateKey: about-page
title: Sr kedvezmények
---
<style>
.content_wrapper table td.createdate {
display: none;
}
.contentpaneopenkedvezmenyek{
width: 100%;
background: #f7f7f7;
}
.discount-wrapper {
padding-bottom: 4rem;
}
.discount-section1 {
text-align: center;
padding: 16rem 0  15rem 0;
color: white;
background: url("https://www.shoprenter.hu/images//discount-bg.jpg") top left no-repeat;
}
.discount-section1 h1 {
font-size: 5rem;
font-weight: 800;
}
.discount-section1 h1 {
font-size: 4rem;
}
}
.discount-section1 p {
font-size: 18px;
font-weight: 600;
margin: 0;
color: white;
}
.discount-section2  .ds-inner {
display: flex;
justify-content: center;
max-width: 1170px;
margin: auto;
border-bottom: 1px solid #ccc;
padding: 0 10%;
}
}
.discount-section2 a,
.discount-section2 a:focus,
.discount-section2 a:hover,
.discount-section2 .active {
width: 25%;
text-align: center;
display: block;
padding: 1.7rem;
position: relative;
color: rgba(40, 40, 40, 0.5);
transition: transform .4s ease-in-out;
}
.discount-section2 a:hover,
.discount-section2 .active {
text-decoration: none;
color: grey;
font-weight: 800;
}
.discount-section2 a:after,
.discount-section2 .active:after,
.discount-section2 a:hover:after{
content: "";
height: 1px;
background-color: grey;
display: block;
transition: transform .4s ease-in-out;
bottom: -1px;
position: absolute;
width: 100%;
left: 0;
}
.discount-section2 a:after {
background-color: transparent;
}
.discount-section3 .ds-inner {
display: flex;
justify-items: center;
align-items: center;
flex-flow: row wrap;
max-width: 1254px;
margin: 3rem auto;
}

}
.discount-item {
max-width: 360px;
width: 100%;
min-height: 440px;
margin: 3rem auto;
border-radius: 4px;
box-shadow: 0px 35px 50px 0 rgba(10, 47, 68, 0.15);
background-color: white;
transition: all .4s ease-in-out;
}
.discount-item:hover {
box-shadow: 0px 35px 50px 0 rgba(1, 7, 10, 0.3);
}
.discount-item a,
.discount-item a:focus,
.discount-item a:hover {
text-decoration: none;
}
.discount-img {
min-height: 143px;
height: 300px;
display: flex;
justify-content: center;
align-content: center;
align-items: center;
}
.discount-item img {
max-width: 100%!important;
height: auto!important;
min-height: 143px;
max-height: 300px;
margin: auto;
border-top-left-radius: 4px;
border-top-right-radius: 4px;
}
.discount-item h2 {
padding: 0 3rem;
font-size: 25px;
font-weight: 800;
line-height: 1.4;
letter-spacing: 0.5px;
text-align: left;
color: grey;
}
.discount-item p {
font-size: 14px;
line-height: 1.64;
letter-spacing: 0.28px;
text-align: left;
color: green;
padding: 0 3rem;
font-weight: 500;
}
</style>
<script>
function changeDiscountItems(e){
$(".ds-inner a").removeClass("active");
$(".discount-item").each(function () {
if ( jQuery(this).data("item") && ($(this).data("item")).search(e) > -1) {
$(this).show();
}
else  {
$(this).hide();
}
})
}
$(document).ready(function () {
$('.content-wrapper').removeClass('container');
$('.content-box').removeClass('container');
$('.content-box div').removeClass('content_wrapper');
$('div').removeClass('content-box');
$("#all").click(function () {
$(".discount-item").show();
$(".ds-inner a").removeClass("active");
$("#all").addClass("active");
});
$("#start").click(function () {
changeDiscountItems("start");
$("#start").addClass("active");
});
$("#500customers").click(function () {
changeDiscountItems("500customers");
$("#500customers").addClass("active");
});
$("#5000visitors").click(function () {
changeDiscountItems("5000visitors");
$("#5000visitors").addClass("active");
});
});
</script>
<div class="discount-wrapper">
<section class="discount-section discount-section1">
<h1>ShopRenter kedvezmények</h1>
<p>
Indulástól kezdve támogatjuk
</p>
</section>
<section class="discount-section discount-section2">
<div class="ds-inner">
<a id="all" class="active">Összes ajánlat</a>
<a id="start">Ajánlatok induláshoz</a>
<a id="5000visitors">5000 látogató felett</a>
<a id="500customers">500 vásárló felett</a>
</div>
</section>
<section class="discount-section discount-section3">
<div class="ds-inner">
<div class="discount-item" data-item="start">
<a href="http://bigfish.hu/" target="_blank">
<span class="discount-img">
<img src="https://www.shoprenter.hu/images/kedvezmenyek/bigfish.jpg" alt="Bigfish">
</span>
<h2>Bigfish</h2>
<p>
20.000 Ft az egyszeri integrációs díjból
</p>
</a>
</div>
<div class="discount-item" data-item="500customers">
<a href="http://www.minicrm.hu/" target="_blank">
<span class="discount-img">
<img src="https://www.shoprenter.hu/images/kedvezmenyek/minicrm.jpg" alt="MiniCRM">
</span>
<h2>MiniCRM</h2>
<p>
Első havi befizetés után plusz egy hónap ingyen
</p>
</a>
</div>
<div class="discount-item" data-item="500customers,5000visitors">
<a href="https://www.conversific.hu/startup-csomag/?utm_campaign=shoprenter_elofizetok&amp;utm_medium=kedvezmenyek-oldal&amp;utm_source=shoprenter.hu" target="_blank">
<span class="discount-img">
<img src="https://www.shoprenter.hu/images/kedvezmenyek/img-conv.jpg" alt="Conversific">
</span>
<h2>Conversific</h2>
<p>
50% kedvezmény a Business csomagra
</p>
</a>
</div>
<div class="discount-item" data-item="start,500customers,5000visitors">
<a href="https://landing.optimonk.hu/shoprenter/?utm_campaign=shoprenter_elofizetok&amp;utm_medium=kedvezmenyek-oldal&amp;utm_source=shoprenter.hu" target="_blank">
<span class="discount-img">
<img src="https://www.shoprenter.hu/images/kedvezmenyek/img-om.jpg" alt="OptiMonk">
</span>
<h2>OptiMonk</h2>
<p>
33% kedvezmény az összes csomagra
</p>
</a>
</div>
<div class="discount-item" data-item="start">
<a href="https://www.shoprenter.hu/furgefutar" target="_blank">
<span class="discount-img">
<img src="https://www.shoprenter.hu/images/kedvezmenyek/furgefutar-2017.jpg" alt="Fürgefutár">
</span>
<h2>Fürgefutár</h2>
<p>
Akár 35% kedvezmény (rendelés mennyiségtől függően)
</p>
</a>
</div>
<div class="discount-item" data-item="5000visitors">
<a href="http://www.symboltech.hu/" target="_blank">
<span class="discount-img">
<img src="https://www.shoprenter.hu/images/kedvezmenyek/symbol.jpg" alt="Symbol">
</span>
<h2>Symbol</h2>
<p>
40.000 Ft kedvezmény a webshop integrációs modulból
</p>
</a>
</div>
<div class="discount-item" data-item="start">
<a href="https://www.webshopkonyveles.hu/shoprenter" target="_blank">
<span class="discount-img">
<img src="https://www.shoprenter.hu/images/kedvezmenyek/webshopkonyveles.png" alt="Webshop Könyvelés">
</span>
<h2>Webshop Könyvelés</h2>
<p>
3 hónapig 33% kedvezmény kezdő csomagjainkra
</p>
</a>
</div>
<div class="discount-item" data-item="start">
<a href="https://www.zentrada.hu" target="_blank">
<span class="discount-img">
<img src="https://www.shoprenter.hu/images/kedvezmenyek/zentrada.png" alt="Zentrada">
</span>
<h2>Zentrada</h2>
<p>
15.000 Ft kedvezmény az első rendelésből. Kuponkód: ZEN-SR-2020
</p>
</a>
</div>
<div class="discount-item" data-item="500customers">
<a href="https://webshippy.com/?ref=shoprenter" target="_blank">
<span class="discount-img">
<img src="https://www.shoprenter.hu/images/kedvezmenyek/webshippy.png" alt="Webshippy">
</span>
<h2>Webshippy</h2>
<p>
Az első hónapban féláron csomagoljuk termékeit
</p>
</a>
</div>
<div class="discount-item" data-item="start">
<a href="https://keresoreklam.hu/" target="_blank">
<span class="discount-img">
<img src="https://www.shoprenter.hu/images/kedvezmenyek/keresoreklam.jpg" alt="Keresőreklám">
</span>
<h2>Keresőreklám</h2>
<p>
20% kedvezmény a listaárainkból
</p>
</a>
</div>
<div class="discount-item" data-item="start">
<a href="https://www.glami.hu/info/uzlet-hozzaadasa/?reg=yllewgvvayo6xr4yludl" target="_blank">
<span class="discount-img">
<img src="https://www.shoprenter.hu/images/kedvezmenyek/glami.jpg" alt="Glami">
</span>
<h2>Glami</h2>
<p>
20.000 Ft értékű kezdőkredit
</p>
</a>
</div>
<div class="discount-item" data-item="500customers">
<a href="https://okosugyvitel.hu/shoprenter-szinkron/" target="_blank">
<span class="discount-img">
<img src="https://www.shoprenter.hu/images/kedvezmenyek/okosugyvitel-2color-ugyvitel_sr.png" alt="Okos-Ügyvitel">
</span>
<h2>Okos-Ügyvitel</h2>
<p>
1 óra ingyenes online oktatás 15 000 Ft értékben
</p>
</a>
</div>
<div class="discount-item" data-item="start,500customers">
<a href="https://emanager.hu/" target="_blank">
<span class="discount-img">
<img src="https://www.shoprenter.hu/images/kedvezmenyek/emanager348.png" alt="Emanager">
</span>
<h2>Emanager</h2>
<p>
50% kedvezmény az első 3 hónap előfizetésből, PRO előfizetés esetén
</p>
</a>
</div>
<div class="discount-item" data-item="start,500customers,5000visitors">
<a href="https://maximumbusiness.hu/" target="_blank">
<span class="discount-img">
<img src="https://www.shoprenter.hu/images/kedvezmenyek/maximumbusiness.png" alt="MaximumBusiness">
</span>
<h2>MaximumBusiness</h2>
<p>
INGYENES Online marketing elemzés egy órás ingyenes konzultációval.
</p>
</a>
</div>
<div class="discount-item" data-item="start,500customers,5000visitors">
<a href="https://arukereso.hu/" target="_blank">
<span class="discount-img">
<img src="https://www.shoprenter.hu/images/kedvezmenyek/arukereso_logo.png" alt="Árukereső">
</span>
<h2>Árukereső</h2>
<p>
Egyszeri 5.000 Ft - os bónusz jóváírás az első feltöltésre és 6 hónapon keresztül 5% bónuszjóváírás minden egyes egyenlegfeltöltésre.
</p>
</a>
</div>
<div class="discount-item" data-item="start,500customers">
<a href="https://ebex.hu/shoprenter-webaruhaz-elkeszitesi-kedvezmeny//" target="_blank">
<span class="discount-img">
<img src="https://www.shoprenter.hu/images/kedvezmenyek/shoprenter_ebex.png" alt="Ebex">
</span>
<h2>Ebex</h2>
<p>
ShopRenteres webáruházak elkészítési díjából 10%-os kedvezmény.
</p>
</a>
</div>
<div class="discount-item" data-item="start,500customers,5000visitors">
<a href="http://help.billingo.hu/support/solutions/articles/22000244775-shoprenteres-%C3%BCgyfeleknek-6-h%C3%B3nap-billingo-premium-el%C5%91fizet%C3%A9s-ingyen" target="_blank">
<span class="discount-img">
<img src="https://www.shoprenter.hu/images/kedvezmenyek/billingo_logo_2015_vert.png" alt="Billingo">
</span>
<h2>Billingo</h2>
<p>
Számlázz automatán és stílusosan Shoprenter ügyfélként 6 hónapig ingyen!
</p>
</a>
</div>
<div class="discount-item" data-item="start,500customers,5000visitors">
<a href="https://boostx.eu/szolgaltatasaink?utm_source=shoprenter" target="_blank">
<span class="discount-img">
<img src="https://www.shoprenter.hu/images/boostx.jpg" alt="BoostX ">
</span>
<h2>BoostX EU</h2>
<p>
Akár 60.000 Ft kedvezmény (igényelt szolgáltatás típusától függően)
</p>
</a>
</div>
</div>
</section>
</div>
