---
title: Resources
tags: [color-logo]
---

<!-- Done for the new website! -->

<section class="breadcrumb-area">
         <div class="breadcrumb-shape"></div>
         <div class="container">
            <div class="row">
               <div class="col-lg-12">
                  <div class="breadcrumb-inn">
                     <div class="section-title wow fadeInUp" data-wow-duration="1s" data-wow-delay="0.3s" style="visibility: visible; animation-duration: 1s; animation-delay: 0.3s; animation-name: fadeInUp;">
                       <h2>Discover <span>Resources</span></h2>
                     </div>
                  </div>
               </div>
            </div>
         </div>
</section>


<section class="about-page-section section_100">
<div class="container">
<div class="row">
<div class="col-lg-12">

<h1> All recources </h1>
{% for page in site.pages %}{% if page.exclude != true %}
<ul class="list-inline">
<li><a href="{{ page.url }}">{{ page.title }}</a></li>
</ul>
{% endif %}{% endfor %}


</div>
</div>
</div>
</section>