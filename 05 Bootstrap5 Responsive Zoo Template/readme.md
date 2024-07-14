# installation de bootstrap cdn

allez sur le lien :

```text
    <https://getbootstrap.com/>
```

Descendre dans la page d'accueil, jusqu'a Include via CDN.
copier le lien: "css only" et le coller dans la balise head.

```html
        <!-- Bootstrap CSS only -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
```

Ensuite.
Copier le lien "Javascript Bundle with Popper". et le coller en bas de la balise body.

```html
    <!-- JavaScript Bundle with Popper -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>
```

Allez sur <https://icons.getbootstrap.com/>.
copier coller le lien dans le head.

```html
    <!-- link cdn icons bootstrap -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css">
```

Allez dans "Docs de bootstrap", <https://getbootstrap.com/docs/5.3/getting-started/introduction/>.
sélectionner "Navbar" dans 'Compenents'.
copier coller le premier template, supprimer les éléments suivants.

```html
    <!-- à supprimer -->
     <li class="nav-item dropdown">
        <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
        Dropdown
        </a>
        <ul class="dropdown-menu">
        <li><a class="dropdown-item" href="#">Action</a></li>
        <li><a class="dropdown-item" href="#">Another action</a></li>
        <li><hr class="dropdown-divider"></li>
        <li><a class="dropdown-item" href="#">Something else here</a></li>
        </ul>
    </li>
    <li class="nav-item">
        <a class="nav-link disabled" aria-disabled="true">Disabled</a>
    </li>
    <form class="d-flex" role="search">
        <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
        <button class="btn btn-outline-success" type="submit">Search</button>
    </form>
```

descendre dans la page et sur 'image' copier coller.

```html
    <a class="navbar-brand" href="#">
      <img src="/docs/5.3/assets/brand/bootstrap-logo.svg" alt="Bootstrap" width="30" height="24">
    </a>

    <!--coller le lien sous 'container-fluid'-->
    <div class="container-fluid">
            <a class="navbar-brand" href="#">
                <img src="/docs/5.3/assets/brand/bootstrap-logo.svg" alt="Bootstrap" width="30" height="24">
            </a>

    <!-- changer le src -->
    <a class="navbar-brand" href="#">
        <img src="img/logo.svg" alt="Logo" width="30" height="24">
    </a>

    <!-- Ajout d'une div -->
        <div class="logo-s">
            <a class="navbar-brand" href="#">Wildlife</a>
            <p>Awesome zoo</p>
        </div>
```
