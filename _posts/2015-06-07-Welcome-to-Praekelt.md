---
published: true
---

<ul class="posts">  
	{% for post in site.posts limit:20 %}  
	   <li>  
		   <span>{{ post.date | date_to_string }}</span> &raquo;  
		   <a href="{{ BASE_PATH }}{{ post.url }}">  
		   {{ post.title }}</a>  
	   </li>  
	{% endfor %}  
</ul>


- [item](http://praekelt.github.io/handbook/2015/06/07/Handbook.html)
- item
- item



## A New Post
