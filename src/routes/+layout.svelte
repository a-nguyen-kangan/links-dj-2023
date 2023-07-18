<script>

</script>

<nav>
<ul>
    <li><a href="#">Home</a></li>
    <li><a href="/Text_Tutorials">Text Tutorials</a></li>
    <li><a href="/Component_Libraries">Component Libraries</a></li>
</ul>
</nav>

<div>
    <slot />
</div>

<style>
    nav {
  background-color: #333;
  color: #fff;
}

nav ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
}

nav ul li {
  display: inline-block;
}

nav ul li a {
  display: block;
  padding: 10px 20px;
  color: #fff;
  text-decoration: none;
}

nav ul li a:hover {
  background-color: #555;
}
</style>