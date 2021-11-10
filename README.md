# bootstrap5.1
I am taking Dr Angela Yu (London App Brewery class at Udemy)
Angela(Dr Yu) is Mentoring with bootstrap3 ? or 4? for 2021 and it is now November 2021 and Bootstrap has gone through some changes. I did some research on stackOverflow and on Bootstrap. There are others with similar problems, so I came up with the easy solution for navBar Toggler. For example, I started with Bootstrap 4.6 with jquery.
It was the closest fit to bootstrap3.0 and my navBar Toggler did not work. I have noticed there are others which can not get Bootstrap to function because of the rapid technological advances in Boot strap. I have had similar problems with Python, packages and Python Mentors, so from the time any Mentor Python or Html, Bootstap and CSS . . . Creates their Mentoring video and the time I get to studying there is a time gap and the Python or Bootstap changes due to rapid technological advances. Besides, this kind of stuff is acceptable and normal, so stimulates everyone to SQ3R (Survey, question, read, recite and review) and do their research and experimentation to get the fix or caught up with the current now times and the way it works today.
Bootstrap has gone through some changes which may cause confusion? Bottstrap 5.1 is the easy and best fix just upgrade and make sure your page at Bootstrap is set to version 5.1. I set up the code according to the instructions at Bootstrap v5.1 and tested the code below with MS notepad and saved it as all files in Win 10 .html= NavBarTest.html and it works. Good Luck I hope this helps.
<!DOCTYPE html>
<html>

<head>
  <meta charset="utf-8">
  <title>TinDog</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">

  <link rel="stylesheet" href="css/styles.css">

</head>

<body>
<nav class="navbar navbar-expand-lg navbar-light bg-light">
  <div class="container-fluid">
    <a class="navbar-brand" href="#">Navbar</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav me-auto mb-2 mb-lg-0">
        <li class="nav-item">
          <a class="nav-link active" aria-current="page" href="#">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Link</a>
        </li>
        <li class="nav-item dropdown">
          <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
            Dropdown
          </a>
          <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
            <li><a class="dropdown-item" href="#">Action</a></li>
            <li><a class="dropdown-item" href="#">Another action</a></li>
            <li><hr class="dropdown-divider"></li>
            <li><a class="dropdown-item" href="#">Something else here</a></li>
          </ul>
        </li>
        <li class="nav-item">
          <a class="nav-link disabled">Disabled</a>
        </li>
      </ul>
      <form class="d-flex">
        <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
        <button class="btn btn-outline-success" type="submit">Search</button>
      </form>
    </div>
  </div>
</nav>
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p" crossorigin="anonymous"></script>

</body>
<html>
