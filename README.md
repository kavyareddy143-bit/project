# Project Responsive Web Design using Bootstrap
# Date:
# AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.

# DESIGN STEPS:
## Step 1:
Clone the repository from GitHub.

## Step 2:
Create Django Admin project.

## Step 3:
Create a New App under the Django Admin project.

## Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

## Step 5:
Create a HTML file and include the needed Bootstrap components.

## Step 6:
Publish the website in the LocalHost.

# PROGRAM:
```
index.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Dribble clone - Nithin</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet" />
  <link href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.10.5/font/bootstrap-icons.css" rel="stylesheet" />
  <link rel="stylesheet" href="css/style.css" />
</head>
<body>

  <nav class="navbar navbar-dark bg-dark py-2">
    <div class="container-fluid d-flex justify-content-between align-items-center px-3">
      <div class="d-flex gap-3 align-items-center">
        <a class="navbar-brand fw-bold text-info" href="#">DRIBBLE</a>
        <a href="#" class="nav-link text-white">Shots</a>
        <a href="#" class="nav-link text-white">Designers</a>
        <a href="#" class="nav-link text-white">Teams</a>
        <a href="#" class="nav-link text-white">Community</a>
        <a href="#" class="nav-link text-white">Jobs</a>
        <i class="bi bi-three-dots text-white fs-5" style="cursor:pointer;"></i>
      </div>
      <div class="d-flex align-items-center gap-2">
        <a href="#" class="btn btn-outline-light btn-sm">Sign in</a>
        <a href="#" class="btn btn-pink btn-sm text-white">Sign up</a>
        <input type="text" class="form-control form-control-sm" placeholder="Search" />
      </div>
    </div>
  </nav>


  <div class="header-section text-center py-4">
    <h5>What are you working on? <span class="text-muted">Dribbble is show and tell for designers.</span></h5>
    <button class="btn btn-sm btn-dark mt-2">Learn more</button>
    <button class="btn btn-sm btn-pink text-white mt-2">Sign up</button>
  </div>

  
  <div class="container">
    <div class="d-flex justify-content-between align-items-center py-3 border-bottom">
      <div>
        <strong>Popular</strong> |
        <a href="#" class="text-muted text-decoration-none">Shots</a> |
        <a href="#" class="text-muted text-decoration-none">Now</a>
      </div>
      <div>
        <i class="bi bi-grid-3x3-gap me-2"></i>
        <i class="bi bi-list"></i>
      </div>
    </div>
  </div>


  <div class="container py-4">
    <div class="row row-cols-1 row-cols-sm-2 row-cols-md-3 row-cols-lg-4 g-4">

   
      <div class="col">
        <div class="card h-100">
          <img src="https://picsum.photos/400/300?random=1" class="card-img-top" alt="Preview">
          <div class="card-body d-flex justify-content-between">
            <a href="#" class="fw-bold text-dark text-decoration-none">@Famous</a>
            <small class="text-muted">
              <i class="bi bi-eye"></i> 4.9k 
              <i class="bi bi-heart ms-2 like-icon" style="cursor:pointer;"></i> 290
            </small>
          </div>
        </div>
      </div>

  
      <div class="col">
        <div class="card h-100">
          <img src="https://picsum.photos/400/300?random=2" class="card-img-top" alt="Preview">
          <div class="card-body d-flex justify-content-between">
            <a href="#" class="fw-bold text-dark text-decoration-none">@BalkanBrothers</a>
            <small class="text-muted">
              <i class="bi bi-eye"></i> 2.4k 
              <i class="bi bi-heart ms-2 like-icon" style="cursor:pointer;"></i> 195
            </small>
          </div>
        </div>
      </div>


<div class="col">
  <div class="card h-100">
    <img src="https://picsum.photos/400/300?random=1" class="card-img-top" alt="Preview">
    <div class="card-body d-flex justify-content-between">
      <a href="#" class="fw-bold text-dark text-decoration-none">@Geex Arts</a>
      <small class="text-muted">
        <i class="bi bi-eye"></i> 4.9k 
        <i class="bi bi-heart ms-2 like-icon" style="cursor:pointer;"></i> 290
      </small>
    </div>
  </div>
</div>


<div class="col">
  <div class="card h-100">
    <img src="https://picsum.photos/400/300?random=2" class="card-img-top" alt="Preview">
    <div class="card-body d-flex justify-content-between">
      <a href="#" class="fw-bold text-dark text-decoration-none">@Rafiz Studio</a>
      <small class="text-muted">
        <i class="bi bi-eye"></i> 2.4k 
        <i class="bi bi-heart ms-2 like-icon" style="cursor:pointer;"></i> 195
      </small>
    </div>
  </div>
</div>


<div class="col">
  <div class="card h-100">
    <img src="https://picsum.photos/400/300?random=3" class="card-img-top" alt="Preview">
    <div class="card-body d-flex justify-content-between">
      <a href="#" class="fw-bold text-dark text-decoration-none">@JanLosert</a>
      <small class="text-muted">
        <i class="bi bi-eye"></i> 3.3k 
        <i class="bi bi-heart ms-2 like-icon" style="cursor:pointer;"></i> 234
      </small>
    </div>
  </div>
</div>


<div class="col">
  <div class="card h-100">
    <img src="https://picsum.photos/400/300?random=4" class="card-img-top" alt="Preview">
    <div class="card-body d-flex justify-content-between">
      <a href="#" class="fw-bold text-dark text-decoration-none">@MattiasJ</a>
      <small class="text-muted">
        <i class="bi bi-eye"></i> 2.1k 
        <i class="bi bi-heart ms-2 like-icon" style="cursor:pointer;"></i> 180
      </small>
    </div>
  </div>
</div>

<div class="col">
  <div class="card h-100">
    <img src="https://picsum.photos/400/300?random=5" class="card-img-top" alt="Preview">
    <div class="card-body d-flex justify-content-between">
      <a href="#" class="fw-bold text-dark text-decoration-none">@RuslanSliz</a>
      <small class="text-muted">
        <i class="bi bi-eye"></i> 2.8k 
        <i class="bi bi-heart ms-2 like-icon" style="cursor:pointer;"></i> 176
      </small>
    </div>
  </div>
</div>


<div class="col">
  <div class="card h-100">
    <img src="https://picsum.photos/400/300?random=6" class="card-img-top" alt="Preview">
    <div class="card-body d-flex justify-content-between">
      <a href="#" class="fw-bold text-dark text-decoration-none">@Paperpillar</a>
      <small class="text-muted">
        <i class="bi bi-eye"></i> 2.2k 
        <i class="bi bi-heart ms-2 like-icon" style="cursor:pointer;"></i> 150
      </small>
    </div>
  </div>
</div>


<div class="col">
  <div class="card h-100">
    <img src="https://picsum.photos/400/300?random=7" class="card-img-top" alt="Preview">
    <div class="card-body d-flex justify-content-between">
      <a href="#" class="fw-bold text-dark text-decoration-none">@Ivanetila</a>
      <small class="text-muted">
        <i class="bi bi-eye"></i> 3.1k 
        <i class="bi bi-heart ms-2 like-icon" style="cursor:pointer;"></i> 198
      </small>
    </div>
  </div>
</div>


<div class="col">
  <div class="card h-100">
    <img src="https://picsum.photos/400/300?random=8" class="card-img-top" alt="Preview">
    <div class="card-body d-flex justify-content-between">
      <a href="#" class="fw-bold text-dark text-decoration-none">@StudioJQ</a>
      <small class="text-muted">
        <i class="bi bi-eye"></i> 2.7k 
        <i class="bi bi-heart ms-2 like-icon" style="cursor:pointer;"></i> 140
      </small>
    </div>
  </div>
</div>


<div class="col">
  <div class="card h-100">
    <img src="https://picsum.photos/400/300?random=9" class="card-img-top" alt="Preview">
    <div class="card-body d-flex justify-content-between">
      <a href="#" class="fw-bold text-dark text-decoration-none">@RomanT</a>
      <small class="text-muted">
        <i class="bi bi-eye"></i> 1.8k 
        <i class="bi bi-heart ms-2 like-icon" style="cursor:pointer;"></i> 175
      </small>
    </div>
  </div>
</div>


<div class="col">
  <div class="card h-100">
    <img src="https://picsum.photos/400/300?random=10" class="card-img-top" alt="Preview">
    <div class="card-body d-flex justify-content-between">
      <a href="#" class="fw-bold text-dark text-decoration-none">@InFullMobile</a>
      <small class="text-muted">
        <i class="bi bi-eye"></i> 2.6k 
        <i class="bi bi-heart ms-2 like-icon" style="cursor:pointer;"></i> 160
      </small>
    </div>
  </div>
</div>


<div class="col">
  <div class="card h-100">
    <img src="https://picsum.photos/400/300?random=11" class="card-img-top" alt="Preview">
    <div class="card-body d-flex justify-content-between">
      <a href="#" class="fw-bold text-dark text-decoration-none">@UXLovers</a>
      <small class="text-muted">
        <i class="bi bi-eye"></i> 2.9k 
        <i class="bi bi-heart ms-2 like-icon" style="cursor:pointer;"></i> 205
      </small>
    </div>
  </div>
</div>

<div class="col">
  <div class="card h-100">
    <img src="https://picsum.photos/400/300?random=13" class="card-img-top" alt="Preview">
    <div class="card-body d-flex justify-content-between">
      <a href="#" class="fw-bold text-dark text-decoration-none">@TubikStudio</a>
      <small class="text-muted">
        <i class="bi bi-eye"></i> 3.0k 
        <i class="bi bi-heart ms-2 like-icon" style="cursor:pointer;"></i> 198
      </small>
    </div>
  </div>
</div>

<div class="col">
  <div class="card h-100">
    <img src="https://picsum.photos/400/300?random=12" class="card-img-top" alt="Preview">
    <div class="card-body d-flex justify-content-between">
      <a href="#" class="fw-bold text-dark text-decoration-none">@ZajnoCrew</a>
      <small class="text-muted">
        <i class="bi bi-eye"></i> 2.3k 
        <i class="bi bi-heart ms-2 like-icon" style="cursor:pointer;"></i> 170
      </small>
    </div>
  </div>
</div>
 
<div class="col">
  <div class="card h-100">
    <img src="https://picsum.photos/400/300?random=13" class="card-img-top" alt="Preview">
    <div class="card-body d-flex justify-content-between">
      <a href="#" class="fw-bold text-dark text-decoration-none">@ThreeDee</a>
      <small class="text-muted">
        <i class="bi bi-eye"></i> 3.0k 
        <i class="bi bi-heart ms-2 like-icon" style="cursor:pointer;"></i> 198
      </small>
    </div>
  </div>
</div>

<footer class="text-center py-3 mt-4">
  <small class="text-muted"> © 2025 Dribbble
Terms
Privacy
Cookies</small>
</footer>"

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>

  <script>
    document.querySelectorAll('.like-icon').forEach(function(icon) {
      icon.addEventListener('click', function () {
        const liked = this.classList.toggle('bi-heart-fill');
        this.classList.toggle('text-danger', liked); 
        this.classList.toggle('bi-heart', !liked);

        
        const parent = this.parentElement;
        const match = parent.innerText.match(/(\d+)$/);
        if (match) {
          let count = parseInt(match[1]);
          count = liked ? count + 1 : count - 1;
        
          parent.innerHTML = parent.innerHTML.replace(/\d+$/, count);
         
          this.classList.forEach(cls => this.classList.contains('bi-heart-fill') || this.classList.add('bi-heart'));
        }
      });
    });
  </script>

</body>
</html>


style.css

.btn-pink {
  background-color: #ff6eff;
  border-color: #ff6eff;
}

.card-img-top {
  height: 200px;
  object-fit: cover;
}


.header-section {
  background-color: #78efff;
}

.card:hover {
  transform: translateY(-5px);
  transition: 0.3s ease;
  box-shadow: 0 8px 16px rgba(250, 249, 249, 0.938);
}
```
# OUTPUT:
<img width="1013" height="514" alt="image" src="https://github.com/user-attachments/assets/2a756b31-afeb-4265-b76d-228406fc479c" />

# RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
