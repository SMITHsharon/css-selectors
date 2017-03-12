# NSS CSS Selectors Exercise

### Project Description 
This assignment gives opportunity to learn about `css` styling possibilities and node-traversal for accessing elements in the DOM. 
#### HTML Page Display
![CSS Selectors Output Screen](https:.png)

### Project Specs
1. The header element has a 1px border; color discretionary.
2. The `ul` navigation element is converted into a series of horizontal links, with `#` as the `href` value. Bullet characters have been removed, and the elements have some space between them horizontally.
3. The navigation is wrapped in the correct `HTML` tag.
4. Any text in an element with class `disabled` is colored `grey`, unless it is inside an anchor tag. 5. Any text that is inside an anchor tag is colored `purple`.
6. Any text inside an element with a class of `active` is colored `yellow`.
7. Section elements are contained within an `article` element.
8. The two missing closing tags were found and corrected.
9. The "I'm red" text is colored `red`. 
10. The "I'm blue" text is colored `blue`. 
11. The sibling `h4` of the `red` element should has a background color of `red`.
12. The sibling `h4` of the `blue` element should has a background color of `blue`.
13. Any `h4` that is a direct child of grandparent has a 1px border with rounded corners.
14. Elements with a class of `promo` have bold text that is also colored `gold`.
15. Without adding any other attributes to the input fields in the `footer`, write a CSS selector that makes any text input field have a height of 25px.

```
<-- input file -->
<header>
  <ul>
    <li>Home</li>
    <li>Profile</li>
    <li>Blog</li>
  </ul>
</header>

<section>
  <div class="month-list">
    <ul>
      <li>
        <a href="#">January</a>
        <span class="disabled">My favorite month</span>
      </li>
      <li>
        <a href="#">
          <span class="active">February</span>
        </a>
      </li>
      <li>
        <a href="#">
          <span class="disabled">March</span>
        </a>
      </li>
      <li>
        <a href="#">April</a>
      </li>
      <li>
        <a href="#">
          <div class="promo">
            <span class="disabled">May</span>
          </div>
        </a>
      </li>
      <li>
        <a href="#">June</a>
      </li>
      <li>
        <a href="#">July</a>
      </li>
      <li>
        <a href="#">August</a>
        <span class="disabled">My least favorite month</span>
      </li>
      <li>
        <a href="#" class="disabled">September</a>
      </li>
    </ul>
  </div>
</section>

<section>
  <div class="grandparent">
    <div class="parent">
      <h4>Child of parent</h4>
      <div>
        <div>I'm red!</div>
        <h4>I'm red's sister
        <div>I'm blue!</div>
        <h4>I'm blue's brother</h4>
      </div>
    </div>
    <h4>Child of grandparent</h4>
  </div>
</section>

<footer class="padded">

  <div class="disclaimer">
    Only one purchase per household. 
    <a href="#">
      <span class="footer-link">
        <span class="disabled">
          Privacy Policy
        </span>
      </span>
  </div>

  <div class="promo">
    Purchase a book today and receive the eBook for free!
  </div>

  <span>
      <input type="text" name="email" placeholder="Enter your email address">
      <input type="text" name="name" placeholder="Enter your name">
      <input type="tel" name="telephone" placeholder="Enter your telephone number">
  </span>

</footer>
```


### Technologies Used
- html
- css


### How To View The Screen 
#### (Node must be installed on your machine):
```
git clone git@github.com:SMITHsharon/css-selectors.git
cd css-selectors
npm install http-server -g
http-server -p 8080
```

This will show in your browser at: `http://localhost:8080`

### Contributor
[Sharon Smith](https://github.com/SMITHsharon)
