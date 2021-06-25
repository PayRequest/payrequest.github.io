---
title: PayRequest Blog
tags:
- color-logo
---

<section class="breadcrumb-area">
         <div class="breadcrumb-shape"></div>
         <div class="container">
            <div class="row">
               <div class="col-lg-12">
                  <div class="breadcrumb-inn">
                     <div class="section-title wow fadeInUp" data-wow-duration="1s" data-wow-delay="0.3s">
                       <h2>PayRequest <span>Blog</span></h2>
                     </div>
                  </div>
               </div>
            </div>
         </div>
      </section>

<section class="choose-section section_100">
         <div class="container">
            <div class="row align-items-center">
               <div class="col-lg-5 col-md-12">
                  <div class="section-title wow fadeInLeft" data-wow-duration="1s" data-wow-delay="0.3s" style="visibility: visible; animation-duration: 1s; animation-delay: 0.3s; animation-name: fadeInLeft;">
                     <h2><span>New</span> Articles</h2>
                  </div>
               </div>
               <div class="col-lg-7 col-md-12">
                  <div class="section-para wow fadeInRight" data-wow-duration="1s" data-wow-delay="0.4s" style="visibility: visible; animation-duration: 1s; animation-delay: 0.4s; animation-name: fadeInRight;">
                     <p>Read helpful articles written by us, to get paid faster!</p>
                  </div>
               </div>
            </div>
            <div class="row">

 <!-- News Article Start -->
{% for post in site.posts %}

<div class="col-lg-4 col-md-6">
<div class="blog-item wow fadeInLeft" data-wow-duration="1s" data-wow-delay="0.3s" style="visibility: visible; animation-duration: 1s; animation-delay: 0.3s; animation-name: fadeInLeft;">
<div class="blog-image">
<a href="{{ site.baseurl }}{{ post.url }}">
<img src="{{ post.image | escape }}" alt="{{ post.title }}" title="{{ post.title }}">
</a>
</div>

<div class="blog-desc" style="padding-top: 10px;">
<div class="other_info" style="margin: 10px;padding: 5px 0 0 0;">
<div class="blog-meta">
<figure><img src="https://media.payrequest.nl/images/payrequest-news-icon.webp" alt="blog image"></figure>
</div>
<label><i class="fad fa-calendar" aria-hidden="true"></i>

<time class="dt-published"
datetime="{{ page.date | date_to_xmlschema }}"
itemprop="datePublished">
{{ post.date | date: site.date_format }}
</time>

</label>
 <label><i class="fad fa-tag" aria-hidden="true"></i>
 {%- if post.categories -%}
     {% for category in post.categories %}
     {{ post.categories }}
     {%- if forloop.last == false %}, {% endif -%}
     {% endfor %}
     {%- endif -%}
</label>
</div>

<div class="blog-text">
<a href="{{ site.baseurl }}{{ post.url }}">  <h3> {{ post.title }}</h3> </a> 
<h4>{{ post.excerpt }} </h4>
</div>
</div>
</div>
</div>
{% endfor %}
<!-- News Article End -->


</div>
</div>
</section>

{% include footer-promo.html %}