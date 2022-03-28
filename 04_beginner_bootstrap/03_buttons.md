# Buttons
We notice that Warehouse’s navbar has a logout button: 
![navbar button original](https://user-images.githubusercontent.com/18662979/155177208-bfc96a3d-c2e2-4f8d-a77c-94d32696ffca.png)
<br/>
Take a cruise in [Bootstrap’s button documentation](https://getbootstrap.com/docs/5.0/components/buttons/) and explore their different options. 
<br/>
You’ll notice the `btn-outline-secondary` is the most similar to what we want. Add the button after the search button and make sure to add `text-uppercase`.
```html
<header>
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <div class="container-fluid">
            ...
            <form class="d-flex">
                <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
                <button class="btn btn-outline-success" type="submit">Search</button>
            </form>
            <button class="btn btn-outline-secondary text-uppercase">log out</button>
            ...
        </div>
    </nav>
</header>
```
![navbar button edited](https://user-images.githubusercontent.com/18662979/155175838-a7d75afc-1a8c-4384-99af-9bd8c5a6b53b.png)

