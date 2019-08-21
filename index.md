# Hello World  
  
* foo 
  
- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media  


<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}   {{ post.date }}</a>
    </li>
  {% endfor %}
</ul>

