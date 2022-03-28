# Containers
Containers are a utility class provided by Bootstrap to pad and align your content within a viewport.
We can choose from a responsive, fixed-width container (meaning its ***max-width changes*** at each breakpoint) or fluid-width (meaning it’s ***100% wide*** all the time).
Let's use `.container` on the div containing our categories list and cards. Let's remove the margins and paddings previously applied on the list and cards too.
```html
<main>
    <div class="container">
    ...
    </div>
</main>
```
Open your chrome developer tools by pressing F12 on Windows or CMD+SHFT+i on Mac. Notice how the container behaves as we change the viewport's width.
Now let's use `.container-fluid` on the div containing our categories list and cards.
Notice how the container behaves as we change the viewport's width.
```html
<main>
    <div class="container-fluid">
    ...
    </div>
</main>
```
## when to use container-fluid vs. container?
`.container` has a fixed width at each breakpoint in Bootstrap (xs, sm, md, lg, xl, xxl) which can feel choppy because it noticeably changes at each breakpoint. On the other hand, `.container-fluid` makes the width span to be ***100%*** of the available width and changes smoothly as the viewport width changes. You can use `.container` if you want the width to change at each breakpoint only, or `.container-fluid` if you want it to adjust to every change in the viewport's width. 