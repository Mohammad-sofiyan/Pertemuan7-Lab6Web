# Pertemuan7-Lab6Web
## NIM  : 312010225 
## Kelas: TI.20.A2
## Matkul : Programan Web

# LAB6WEB 

## bentuk kode kerja CSS

**Syntax**
```html
<!doctype html>
<html lang="en">

<head>
  <!-- Required meta tags -->
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">

  <!-- Bootstrap CSS -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet"
    integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">

  <style>
    .container {
      width: 980px;
      margin: 0 auto;
      box-shadow: 0 0 8px #ccc;
      padding: 0;
    }

    .header h5 {
      color: #b5b5b5;
      margin: 20px 10px;
    }

    .divider {
      border: 0;
      border-top: 1px solid #eeeeee;
      margin: 40px 0;
    }

    .divider {
      border: 0;
      border-top: 1px solid #eeeeee;
      margin: 40px 0;
    }

    /* entry */
    .entry {
      margin: 15px 0;
    }

    .entry h2 {
      margin-bottom: 20px;
    }

    .entry p {
      line-height: 25px;
    }

    .entry img {
      float: left;
      border-radius: 5px;
      margin-right: 15px;
    }

    .entry .right-img {
      float: right;
    }

    footer {
      color: white;
    }
  </style>

  <title>Home</title>
</head>

<body>
  <div class="container">

    <!-- header -->
    <div class="card-body header">
      <h5 class="card-title display-6">Layout Sederhana</h5>
    </div>
    <!-- akhir header -->

    <!-- navbar -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
      <div class="container-fluid">
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav">
            <li class="nav-item">
              <a class="nav-link btn btn-primary fw-bold" href="#">Home</a>
            </li>
            <li class="nav-item">
              <a class="nav-link btn btn-primary fw-bold" href="#">Konten</a>
            </li>
            <li class="nav-item">
              <a class="nav-link btn btn-primary fw-bold" href="#">About</a>
            </li>
            <li class="nav-item">
              <a class="nav-link btn btn-primary fw-bold" href="#">Kontak</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>
    <!-- akhir navbar -->

    <!-- jumbotron -->
    <div class="card-body p-5 bg-secondary bg-opacity-25">
      <h5 class="card-title display-5 fw-bold">Hello world</h5>
      <p class="card-text text-sm-start">Lorem ipsum dolor sit amet consectetur adipisicing elit. Consectetur, libero
        exercitationem asperiores consequuntur ea fugiat ex? Molestiae unde, iusto expedita at asperiores distinctio
        ipsa est, sint explicabo voluptatibus, porro quae.</p>
      <a href="#" class="btn btn-primary">Loarn More...</a>
    </div>
    <!-- akhir jumbotron -->

    <!-- main -->
    <div class="card-body p-5">
      <div class="row">
        <div class="col-md-8">
          <div class="row m-2">
            <div class="col-md m-md-2">
              <img src="https://dummyimage.com/120/db7d25/fff.png" alt="" class="rounded-circle">
              <h3>Heading</h3>
              <p class="text-sm-start">Donec sed odio dui. Etiam porta sem malesuada magna mollis euismod.</p>
              <a href="#" class="btn btn-default">View detail</a>
            </div>
            <div class="col-md m-md-2">
              <img src="https://dummyimage.com/120/db7d25/fff.png" alt="" class="rounded-circle">
              <h3>Heading</h3>
              <p class="text-sm-start">Donec sed odio dui. Etiam porta sem malesuada magna mollis euismod.</p>
              <a href="#" class="btn btn-default">View detail</a>
            </div>
            <div class="col-md m-md-2">
              <img src="https://dummyimage.com/120/db7d25/fff.png" alt="" class="rounded-circle">
              <h3>Heading</h3>
              <p class="text-sm-start">Donec sed odio dui. Etiam porta sem malesuada magna mollis euismod.</p>
              <a href="#" class="btn btn-default">View detail</a>
            </div>
          </div>

          <!-- konten -->

          <hr class="divider" />
          <div class="row">
            <div class="col">
              <article class="entry">
                <h2>First featurette heading.</h2>
                <img src="https://dummyimage.com/150/7b8a70/fff.png" alt="">
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum lorem elit, iaculis in nisl
                  volutpat,
                  malesuada tincidunt arcu. Proin in leo fringilla, vestibulum mi porta, faucibus felis. Integer
                  pharetra est
                  nunc, nec pretium nunc pretium ac.</p>
              </article>
            </div>
          </div>
          <hr class="divider" />
          <div class="row">
            <div class="col">
              <article class="entry">
                <h2>First featurette heading.</h2>
                <img src="https://dummyimage.com/150/7b8a70/fff.png" alt="" style="float: right;">
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum lorem elit, iaculis in nisl
                  volutpat,
                  malesuada tincidunt arcu. Proin in leo fringilla, vestibulum mi porta, faucibus felis. Integer
                  pharetra est
                  nunc, nec pretium nunc pretium ac.</p>
              </article>
            </div>
          </div>

          <!-- akhir konten -->

        </div>
        <div class="col offset-1">
          <h3 class="bg-primary p-1">Widget Header</h3>
          <ul class="nav flex-column">
            <li class="nav-item">
              <a class="nav-link" aria-current="page" href="#">Widget Link</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Widget Link</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Widget Link</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Widget Link</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Widget Link</a>
            </li>
          </ul>

          <div>
            <h3 class="bg-primary">Widget Text</h3>
            <p class="text-sm-start">Vestibulum lorem elit, iaculis in nisl volutpat, malesuada tincidunt arcu. Proin in
              leo fringilla, vestibulum mi porta, faucibus felis. Integer pharetra est nunc, nec pretium nunc pretium
              ac.</p>
          </div>
        </div>
      </div>
    </div>
    <!-- akhir main -->

    <!-- footer -->
    <footer>
      <p class="p-1 bg-black">&copy; 2021 - Universitas Pelita Bangsa</p>
    </footer>
    <!-- akhir footer -->

  </div>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js"
    integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p" crossorigin="anonymous">
  </script>
</body>

</html>

```

## Maka Tampilan Browser
![tampilan](img/tampillan%20di%20browsernya.png)
