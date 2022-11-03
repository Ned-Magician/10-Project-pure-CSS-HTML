### 10 Project only with pure CSS and HTML

- There are ten projects of Different Navbar and Slider and Menus with fabulous animation just pure CSS and HTML
- They work without any language like jQuery or JavaScript only with
<img align="right" width="200" src="https://user-images.githubusercontent.com/94977052/199727552-35b3039f-ffb4-41f3-ab4d-7f078f1b4f0c.JPG">
 HTML elements like Inputs for changing the slides or the pages like this 

```
// Some part of codes
    <ul id="menu">
      <a href="https://github.com/Ned-Magician">
        <li>Different frame for your website</li>
      </a>
      <a href="https://github.com/Ned-Magician">
        <li>Shopstore, Teaching, sintec,Marketing,...</li>
      </a>
      <a href="https://github.com/Ned-Magician">
        <li>Support your website for six month</li>
      </a>
      <a href="https://github.com/Ned-Magician">
        <li>About US</li>
      </a>
    </ul>
```
and the CSS is so simple and easy to make for change the slides even whiteout JavaScript or jQuery codes 

```
   input#burger-menu:checked ~ #menu {
  opacity: 1;
  transition: all 0.8s cubic-bezier(0.17, 0.88, 0.32, 1.25);
}
input#burger-menu:checked ~ #main {
  opacity: 0;
}
input#burger-menu:checked ~ #menu a li {
  margin-top: 0px;
  transition: all 0.8s cubic-bezier(0.17, 0.88, 0.32, 1.25);
}

```
OR
with Target attribute
```
#t2:target #p2 .bi,
#t3:target #p3 .bi {
  transform: translateX(0) !important;
  transition-delay: 1s;
}
```

and the beautiful project appeared that i named **Diamond** you can check in this repository here and the 9 other projects like Menus or slides here.
