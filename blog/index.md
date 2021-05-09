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
<div class="col-lg-4 col-md-6">
                  <div class="blog-item wow fadeInLeft" data-wow-duration="1s" data-wow-delay="0.3s" style="visibility: visible; animation-duration: 1s; animation-delay: 0.3s; animation-name: fadeInLeft;">
                     <div class="blog-image">
                        <a href="#">
                        <img src="https://media.payrequest.nl/images/stripe-partner-news.webp" alt="Stripe Partner">
                        </a>
                     </div>
                     <div class="blog-desc">
                        <div class="meta-image">
                           <div class="author-round">
<img src="https://media.payrequest.nl/images/payrequest-news-icon.webp" alt="payrequest news icon">
                           </div>
                           <div class="tags">

<h4><span class="label label-primary" style="
display: inline;
padding: .2em .6em .3em;
font-size: 75%;
font-weight: 700;
line-height: 1;
background-color: #03acca;
color: white;
text-align: center;
white-space: nowrap;
vertical-align: baseline;
border-radius: .25em;
">Blog Post</span>
</h4>
<h5>5 August 2020</h5>
</div></div>

<div class="blog-text">
<a href="https://medium.com/payrequest/payrequest-joins-stripe-partner-program-765eb3de62b3">
<h3>PayRequest joins Stripe Partner program</h3> </a>
                        </div>
                     </div>
                  </div>
               </div>
 <!-- News Article End -->

 <!-- News Article Start -->
<div class="col-lg-4 col-md-6">
<div class="blog-item wow fadeInLeft" data-wow-duration="1s" data-wow-delay="0.4s" style="visibility: visible; animation-duration: 1s; animation-delay: 0.4s; animation-name: fadeInLeft;">
<div class="blog-image">
<a href="https://payrequest.io/payment-providers/multisafepay">
<img src="https://media.payrequest.nl/images/multisafepay-news.webp" alt="multisafepay news"></a>
</div>

<div class="blog-desc">
<div class="meta-image">
<div class="author-round">
<img src="https://media.payrequest.nl/images/payrequest-news-icon.webp" alt="payrequest news icon">
</div>
<div class="tags">

<h4><span class="label label-primary" style="display: inline; padding: .2em .6em .3em; font-size: 75%;
font-weight: 700; line-height: 1; background-color: #03acca; color: white; text-align: center;
white-space: nowrap; vertical-align: baseline; border-radius: .25em;
">Blog Post</span>
</h4>

<h5>5 August 2020</h5>
</div>
</div>

<div class="blog-text"><a href="https://payrequest.io/payment-providers/multisafepay">
<h3>New Payment Provider: MultiSafePay</h3></a>
</div>

</div>
</div>
</div>
 <!-- News Article End -->

 <!-- News Article Start -->
<div class="col-lg-4 col-md-6">
<div class="blog-item wow fadeInLeft" data-wow-duration="1s" data-wow-delay="0.5s" style="visibility: visible; animation-duration: 1s; animation-delay: 0.5s; animation-name: fadeInLeft;">
<div class="blog-image">
<a href="https://payrequest.io/api">
<img src="https://media.payrequest.nl/images/payrequest-api.webp" alt="PayRequest API">
</a>
</div>

<div class="blog-desc">
<div class="meta-image">
<div class="author-round">
<img src="https://media.payrequest.nl/images/payrequest-news-icon.webp" alt="payrequest news icon">
 </div>
<div class="tags">

<h4><span class="label label-primary" style="display: inline;
padding: .2em .6em .3em; font-size: 75%; font-weight: 700;
line-height: 1; background-color: #03acca; color: white;
text-align: center; white-space: nowrap; vertical-align: baseline; border-radius: .25em;
">Web Page</span>
</h4>
<h5>5 August 2020</h5>
</div>
</div>
<div class="blog-text">
<a href="https://payrequest.io/api"><h3>PayRequest API is now available for everyone</h3> </a>
</div>
</div>

</div>
</div>
 <!-- News Article End -->


</div>
</div>
</section>


<div class="posts">
<a href="{{ site.baseurl }}/posts.by.category">View Posts by Category</a>
{% for post in site.posts %}
<article class="post">
<h1><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h1>

<div class="entry">{{ post.excerpt }}</div>
<a href="{{ site.baseurl }}{{ post.url }}" class="read-more">Read More</a>
</article>
{% endfor %}
</div>