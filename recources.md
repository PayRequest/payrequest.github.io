---
title: Recources
---

<section class="section section-lg section-shaped">
		<!-- Background circles -->
		<div class="shape shape-style-self shape-primary">
			<span class="span-150"></span>
			<span class="span-50"></span>
			<span class="span-50"></span>
			<span class="span-75"></span>
			<span class="span-100"></span>
			<span class="span-75"></span>
			<span class="span-50"></span>
			<span class="span-100"></span>
			<span class="span-50"></span>
			<span class="span-100"></span>
		</div>
		<div class="container shape-container d-flex align-items-center">
			<div class="col px-0">
				<div class="row align-items-center justify-content-center">
					<div class="col-lg-7 text-center">
<div class="icon icon-shape bg-gradient-white shadow rounded-circle mb-3"><i class="fa fa-hand-holding-heart text-info"></i></div>
						<h1 class="text-white">Recources
</h1>
						<p class="lead text-white">
						See here all our recources
						</p>
					

</div>
	</div>
			</div>
		</div>
	
</section>


<div class="main main-raised">
      <div class="container">
        <div class="row">
          <div class="col-lg-3 col-md-6">
            
</div>
          <div class="col-lg-6 col-md-6">
            <div class="card card-blog bg-default">
              
<div class="card-body">
                <h4 class="display-4 text-white text-center">
    <i class="fab fa-product-hunt" aria-hidden="true"></i> Featered on Product Hunt
</h4>
                <p class="lead text-white mt-0 text-center">
    
<a href="https://www.producthunt.com/posts/donation-pages-by-payrequest?utm_source=badge-featured&amp;utm_medium=badge&amp;utm_souce=badge-donation-pages-by-payrequest" target="_blank"><a href="https://www.producthunt.com/posts/donation-pages-by-payrequest?utm_source=badge-featured&amp;utm_medium=badge&amp;utm_souce=badge-donation-pages-by-payrequest" target="_blank"><img src="https://api.producthunt.com/widgets/embed-image/v1/featured.svg?post_id=195843&amp;theme=light" alt="Donation Pages by PayRequest - 0% Fee for your donation page to help during COVID-19! | Product Hunt Embed" style="width: 250px; height: 54px;" width="250px" height="54px"></a>

</a>

</p>
                
 </div>
            </div>
          </div>
          <div class="col-lg-3 col-md-6">
            
 </div>
        </div>
      </div>
     

 </div>

<div class="jumbotron" style="background-color: white;">
<div class="container text-center"> 

<h1> All recources </h1>
{% for page in site.pages %}{% if page.exclude != true %}
<ul class="list-inline">
<li><a href="{{ page.url }}">{{ page.title }}</a></li>
</ul>
{% endif %}{% endfor %}


</div>
</div>