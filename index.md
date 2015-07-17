---
layout: bootstrap
---

<div class="post">

  <!-- <header class="post-header">
    <h1 class="post-title">{{ page.title }}</h1>
    <p class="post-meta">{{ page.date | date: "%b %-d, %Y" }}{% if page.author %} • {{ page.author }}{% endif %}{% if page.meta %} • {{ page.meta }}{% endif %}</p>
  </header> -->

  <article class="post-content">
  	<div class="container-fluid">
  		<div class="row">
    		<div class="col-lg-6 col-lg-offset-3">
      		{{site.posts[0].content}}
    		</div>
  	</div>

  </article>

  

</div>


<div class="container-fluid">
	<div class="row">
	  <hr>

	            <ul class="pager">
             
	                <li class="next">
	                    <a href="{{ site.posts[0].previous.url | prepend: site.baseurl | replace: '//', '/' }}" data-toggle="tooltip" data-placement="top" title="{{site.posts[0].previous.title}}">Next &rarr;</a>
	                </li>
	            </ul>
	</div>
</div>





