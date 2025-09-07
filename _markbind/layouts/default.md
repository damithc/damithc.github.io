<head-bottom>
  <link rel="stylesheet" href="{{baseUrl}}/stylesheets/main.css">
</head-bottom>

<header sticky>
  <navbar type="dark">
    <a slot="brand" href="{{baseUrl}}/index.html" title="Home" class="navbar-brand">Home</a>
    <li><a href="{{baseUrl}}/index.html#awards" class="nav-link">Awards</a></li>
    <li><a href="{{baseUrl}}/index.html#projets" class="nav-link">Projects</a></li>
    <li><a href="{{baseUrl}}/index.html#books" class="nav-link">Books</a></li>
    <li><a href="{{baseUrl}}/index.html#teaching" class="nav-link">Teaching</a></li>
    <li><a href="{{baseUrl}}/index.html#research" class="nav-link">Research</a></li>
  </navbar>
</header>

<div id="flex-body">
  <div id="content-wrapper">
    {{ content }}
  </div>
  <scroll-top-button></scroll-top-button>
</div>

<footer>
<div class="text-center">
<small>[<md>**Powered by**</md> <img src="https://markbind.org/favicon.ico" width="30"> {{MarkBind}}, generated on {{timestamp}}]</small>
</div>
</footer>

