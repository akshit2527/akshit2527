<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <title>Bootstrap demo</title>
  </head>
  <body>
    
    <!-- NAVBAR CODE Starts here-->
    <nav class="navbar navbar-expand-lg bg-body-tertiary">
  <div class="container-fluid">
    <a class="navbar-brand" href="#">Apparel Store</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav">
        <li class="nav-item">
          <a class="nav-link active" aria-current="page" href="#">Shirts</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Pants</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#shoes">Shoes</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#" aria-disabled="true">Contact Us</a>
        </li>
      </ul>
    </div>
  </div>
</nav>
    
    <!--NAVBAR CODE Ends here-->
    <div class = "container mt-4">
    <!-- SHIRTS SECTION STARTS-->
    <h2 id="shirts">Shirts</h2>
    <div class = "row">
      <div class="col-md-4">
        <div class="card">
          <img src="https://media.istockphoto.com/id/1270438087/photo/looks-from-the-80s-are-making-a-comeback-in-fashion.jpg?s=2048x2048&w=is&k=20&c=ALP3alqbPonvqU6NsEeJb44vDD1VUit0FcsUluC1Yxs="
            <div class="card-body">
            <h5 class="card-title">Shirt 1</h5>
            <p class="card-text">Price: Rs 5000</p>
            <a href="#" class="btn btn-primary">Buy Now</a>
            <a href="#" class="btn btn-primary">Add to Cart</a>
            </div>
        </div>
      </div>
      
      <div class="col-md-4">
        <div class="card">
          <img src="https://media.istockphoto.com/id/694184272/photo/handsome-young-man-wearing-a-formal-dress.jpg?s=2048x2048&w=is&k=20&c=iSDalIUPECAlY48GV_sDD66uVeBPNb4ubaaoI2Tw-3k="
            <div class="card-body">
            <h5 class="card-title">Shirt 2</h5>
            <p class="card-text">Price: Rs 7000</p>
            <a href="#" class="btn btn-primary">Buy Now</a>
            <a href="#" class="btn btn-primary">Add to Cart</a>
            </div>
        </div>
      </div>
      
      <div class="col-md-4">
        <div class="card">
          <img src="https://images.unsplash.com/photo-1602810320073-1230c46d89d4?q=80&w=1887&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D">
            <div class="card-body">
            <h5 class="card-title">Shirt 3</h5>
            <p class="card-text">Price: Rs 10000</p>
            <a href="#" class="btn btn-primary">Buy Now</a>
            <a href="#" class="btn btn-primary">Add to Cart</a>
            </div>
        </div>
      </div>
      
    </div> <!-- THis div is the closing div for Row of Shirts-->
     
    
    <!--Shirts section Ends Here-->
    
    <!-- PANTS SECTION STARTS-->
    <p>
    <h2 id="pants">Pants</h2>
    
    <div class = "row">
      <div class="col-md-4">
        <div class="card">
          <img src="https://media.istockphoto.com/id/173239968/photo/skinny-tight-blue-jeans-on-white-background.jpg?s=2048x2048&w=is&k=20&c=p1taiRab1WZm98e03PrzFWHEkDl7_packPvFQBQAVWc=">
            <div class="card-body">
            <h5 class="card-title">Pant 1</h5>
            <p class="card-text">Price: Rs 5000</p>
            <a href="#" class="btn btn-primary">Buy Now</a>
            <a href="#" class="btn btn-primary">Add to Cart</a>
            </div>
        </div>
      </div>
      
      <div class="col-md-4">
        <div class="card">
          <img src="https://images.unsplash.com/photo-1602573991155-21f0143bb45c?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3wzMjM4NDZ8MHwxfHJhbmRvbXx8fHx8fHx8fDE3MjU2MjkzOTh8&ixlib=rb-4.0.3&q=80&w=400" class="card-img-top" alt="...">
            <div class="card-body">
            <h5 class="card-title">Pant 2</h5>
            <p class="card-text">Price: Rs 7000</p>
            <a href="#" class="btn btn-primary">Buy Now</a>
            <a href="#" class="btn btn-primary">Add to Cart</a>
            </div>
        </div>
      </div>
      
      <div class="col-md-4">
        <div class="card">
          <img src="https://images.unsplash.com/photo-1624378442362-d3247e8126ec?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3wzMjM4NDZ8MHwxfHJhbmRvbXx8fHx8fHx8fDE3MjU2Mjk0NDJ8&ixlib=rb-4.0.3&q=80&w=400" class="card-img-top" alt="...">
            <div class="card-body">
            <h5 class="card-title">Pant 3</h5>
            <p class="card-text">Price: Rs 1000</p>
            <a href="#" class="btn btn-primary">Buy Now</a>
            <a href="#" class="btn btn-primary">Add to Cart</a>
            </div>
        </div>
      </div>
      
    </div>
     <!-- Pants Section ENDS here-->
    
    <!--Shoes Section starts-->
    <p>
    <h2 id="shoes">Shoes</h2>
    
    <div class = "row">
      <div class="col-md-4">
        <div class="card">
          <img src="https://media.istockphoto.com/id/187310279/photo/brown-leather-shoe.jpg?s=2048x2048&w=is&k=20&c=Ka42FXZx1DbcaTZDP_5522DtcHbtP635XGaMkfuob3g="/"https://media.istockphoto.com/id/ 187310279/photo/brown-leather-shoe.jpg?s=2048x2048&w=is&k=20&c=Ka42FXZx1DbcaTZDP_5522DtcHbtP635XGaMkfuob3g=">
            <div class="card-body">
            <h5 class="card-title">Shoe 1</h5>
            <p class="card-text">Price: Rs 5000</p>
            <a href="#" class="btn btn-primary">Buy Now</a>
            <a href="#" class="btn btn-primary">Add to Cart</a>
            </div>
        </div>
      </div>
      
      <div class="col-md-4">
        <div class="card">
          <img src="https://images.unsplash.com/photo-1525753609950-724d3715874d?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3wzMjM4NDZ8MHwxfHJhbmRvbXx8fHx8fHx8fDE3MjU2Mjk1OTl8&ixlib=rb-4.0.3&q=80&w=400" class="card-img-top" alt="...">
            <div class="card-body">
            <h5 class="card-title" style="{border-top: 20px;}">Shoe 2</h5>
            <p class="card-text">Price: Rs 7000</p>
            <a href="#" class="btn btn-primary">Buy Now</a>
            <a href="#" class="btn btn-primary">Add to Cart</a>
            </div>
        </div>
      </div>
      
      <div class="col-md-4">
        <div class="card">
          <img src="https://images.unsplash.com/photo-1605812860427-4024433a70fd?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3wzMjM4NDZ8MHwxfHJhbmRvbXx8fHx8fHx8fDE3MjU2Mjk1OTl8&ixlib=rb-4.0.3&q=80&w=400" class="card-img-top" alt="...">
            <div class="card-body">
            <h5 class="card-title">Shoe 3</h5>
            <p class="card-text">Price: Rs 10000</p>
            <a href="#" class="btn btn-primary">Buy Now</a>
            <a href="#" class="btn btn-primary">Add to Cart</a>
            </div>
        </div>
      </div>
      
    </div>
    
    <!--Shoes section ends here-->
    
 
    </div>
   <!--Contact us-->
  <p>
    <div class = "container mt-4">
  <h2 id="contact-us"> Contact Us</h2>
  <form>
  <div class="mb-3">
    <label for="exampleInputEmail1" class="form-label">Email Address</label>
    <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp">
    <div id="emailHelp" class="form-text">We'll never share your email with anyone else.</div>
  </div>
  <div class="mb-3">
    <label for="exampleInputPassword1" class="form-label">Name</label>
    <input type="Text" class="form-control" id="exampleInputPassword1">
  </div>
  
  <div class="input-group">
  <span class="input-group-text">Your Message</span>
  <textarea class="form-control" aria-label="With textarea"></textarea>
</div>  
    <p><br>
  <button type="submit" class="btn btn-primary">Submit</button>
</form>
  
    </div>
    
    <footer class="bg-dark text-white text-center">
      <p>&copy; 2024 - Akshit Apparel Store  </p>
    </footer>
  
  
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>
  </body>
</html>
