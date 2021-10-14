        <ul class="navbar">
            {% for page in site.pages %}
            <a href={{ page.filename }}>{{ page.title }}</a>
            {% endfor %}
            <li><a href="default.asp"><i id = "home" class="material-icons" >house</i></a></li>
            <li><a id = "projects" href="news.asp">Projects</a></li>
            <li><a id = "social" href="contact.asp">Social Media</a></li>
            <li><a id = "about" href="about.asp">About Me</a></li>
            <li><a id = "contact" href="contact.asp">Contact Me</a></li>
        </ul>
