# What is OpenNav?

OpenNav is a HTML5 navbar solution aimed at those wanting to stop relying on frameworks such as Bootstrap. The idea behind it is to provide a good barebones navbar with all the essential features that is easy to customize and build on top of.

# Main Features

## Modern Code

Built with the latest CSS Grid and Flexbox for optimal performance and ease of use. (You can include a custom polyfill should you need to support older browsers)

## SCSS Powered

Built in SCSS with the uncomplied code included so that you can make changes to the style yourself without battling the existing code.

## No dependencies

Made with pure HTML5, CSS3 and JS using absolutely no frameworks or outside dependencies meaning you can use this in any project you like with your choice of framework.

# Types of Navbars

OpenNav ships with three different modifiers for your nav - those are a standard nav, a contained nav and a fixed nav.

You may use these interchangeably with eachother (e.g. If you wanted a contained fixed navbar)

## Standard Navbar

This code is for a standard full width navbar, it includes a brand and nav menu. You can customize how big the menu is in the CSS plus tweak the colors.

```html
<nav class="open-nav--wrap">
    <div class="open-nav">
        <div class="open-nav--brand">
            <span>OpenNav</span>
        </div>
        <ul class="open-nav--menu">
            <li class="open-nav--item">
                <a href="#">Home</a>
            </li>
            <li class="open-nav--item">
                <a href="#">About</a>
            </li>
            <li class="open-nav--item">
                <a href="#">Contact</a>
            </li>
        </ul>
        <ul class="open-nav--mobilemenu" id="mobileMenu">
            <li class="open-nav--item">
                <a href="#">Home</a>
            </li>
            <li class="open-nav--item">
                <a href="#">About</a>
            </li>
            <li class="open-nav--item">
                <a href="#">Contact</a>
            </li>
        </ul>
        <div class="nav-toggler" onclick="toggleNav();">
            <div class="nav-toggler-line"></div>
            <div class="nav-toggler-line"></div>
            <div class="nav-toggler-line"></div>
        </div>
    </div>
</nav>
```

## Contained Navbar

This code is for a contained navbar, it includes all the same features as the normal one except it has a max-width set for a contained website design.

```html
<nav class="open-nav--wrap">
    <div class="open-nav contained">
        <div class="open-nav--brand">
            <span>OpenNav</span>
        </div>
        <ul class="open-nav--menu">
            <li class="open-nav--item">
                <a href="#">Home</a>
            </li>
            <li class="open-nav--item">
                <a href="#">About</a>
            </li>
            <li class="open-nav--item">
                <a href="#">Contact</a>
            </li>
        </ul>
        <ul class="open-nav--mobilemenu" id="mobileMenu">
            <li class="open-nav--item">
                <a href="#">Home</a>
            </li>
            <li class="open-nav--item">
                <a href="#">About</a>
            </li>
            <li class="open-nav--item">
                <a href="#">Contact</a>
            </li>
        </ul>
        <div class="nav-toggler" onclick="toggleNav();">
            <div class="nav-toggler-line"></div>
            <div class="nav-toggler-line"></div>
            <div class="nav-toggler-line"></div>
        </div>
    </div>
</nav>
```

## Fixed Navbar

Perhaps you want your navbar to stay on screen at all times, that's why we added the option for a fixed navbar. This navbar will stay at the top of the screen, it can also be used with the contained design by adding the `.contained` class to `.open-nav` div.

```html
<nav class="open-nav--wrap nav-fixed">
    <div class="open-nav">
        <div class="open-nav--brand">
            <span>OpenNav</span>
        </div>
        <ul class="open-nav--menu">
            <li class="open-nav--item">
                <a href="#">Home</a>
            </li>
            <li class="open-nav--item">
                <a href="#">About</a>
            </li>
            <li class="open-nav--item">
                <a href="#">Contact</a>
            </li>
        </ul>
        <ul class="open-nav--mobilemenu" id="mobileMenu">
            <li class="open-nav--item">
                <a href="#">Home</a>
            </li>
            <li class="open-nav--item">
                <a href="#">About</a>
            </li>
            <li class="open-nav--item">
                <a href="#">Contact</a>
            </li>
        </ul>
        <div class="nav-toggler" onclick="toggleNav();">
            <div class="nav-toggler-line"></div>
            <div class="nav-toggler-line"></div>
            <div class="nav-toggler-line"></div>
        </div>
    </div>
</nav>
```