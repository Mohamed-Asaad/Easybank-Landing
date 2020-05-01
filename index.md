<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0"> <!-- displays site properly based on user's device -->

  <link rel="icon" type="image/png" sizes="32x32" href="./images/favicon-32x32.png">

  <title>Frontend Mentor | Easybank landing page</title>
  <!-- Google fonts -->

  <link href="https://fonts.google.com/specimen/Public+Sans" rel="stylesheet">

  <!-- CSS Stylesheets -->

  <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css" integrity="sha384-Vkoo8x4CGsO3+Hhxv8T/Q5PaXtkKtu6ug5TOeNV6gBiFeWPGFN9MuhOf23Q9Ifjh" crossorigin="anonymous">
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.min.js" integrity="sha384-wfSDF2E50Y2D1uUdj0O3uMBJnjuUD4Ih7YwaYd1iqfktj0Uod8GCExl3Og8ifwB6" crossorigin="anonymous"></script>
  <link rel="stylesheet" href="styles.css">

  <!-- Font Awesome -->

  <script src="https://kit.fontawesome.com/984efacfb4.js" crossorigin="anonymous"></script>
  <!-- Bootstrap scripts -->

  <script src="https://code.jquery.com/jquery-3.4.1.slim.min.js" integrity="sha384-J6qa4849blE2+poT4WnyKhv5vZF5SrPo0iEjwBvKU7imGFAV0wwj1yYfoRSJoZ+n" crossorigin="anonymous"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js" integrity="sha384-Q6E9RHvbIyZFJoft+2mJbHaEWldlvI9IOYy5n3zV9zzTtmI3UksdQRVvoxMfooAo" crossorigin="anonymous"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.min.js" integrity="sha384-wfSDF2E50Y2D1uUdj0O3uMBJnjuUD4Ih7YwaYd1iqfktj0Uod8GCExl3Og8ifwB6" crossorigin="anonymous"></script>

</head>

<body>

  <!-- Title Section -->

  <section id="title">
    <div class="row title-container">

      <div class="col-lg-4 nav-item">
        <img src="logo.svg" alt="brand-logo">
      </div>
      <div class="col-lg-4 nav-item">
        <div class="row">
          <div class="col">
            <a style="color: #dae1e7" href="#">Home</a>
          </div>
          <div class="col">
            <a style="color: #dae1e7" href="#">About</a>
          </div>
          <div class="col">
            <a style="color: #dae1e7" href="#">Contact</a>
          </div>
          <div class="col">
            <a style="color: #dae1e7" href="#">Blog</a>
          </div>
          <div class="col">
            <a style="color: #dae1e7" href="#">Careers</a>
          </div>

        </div>

      </div>
      <div class="col-lg-4 nav-item">
        <button type="button" class="btn btn-dark btn-mystyle">Request Invite</button>

      </div>

    </div>

  </section>

  <!-- Description Section -->

  <section id="description-style">
    <div class="row">
      <div class="col-lg-6" style="padding: 12%;">
        <h1 style="padding-bottom:10px;">Next generation digital banking</h1>
        <p style="padding-bottom:10px;">Take your financial life online. Your Easybank account will be a one-stop-shop
          for spending, saving, budgeting, investing, and much more.</p>
        <button type="button" class="btn btn-dark btn-mystyle">Request Invite</button>
      </div>
      <div class="col-lg-6" style="padding: 0;">
        <img src="bg-intro-desktop.svg" class="under-image" alt="intro-image">
        <img src="image-mockups.png" class="top-image" alt="mockups-image">
      </div>
    </div>

  </section>

  <!-- Feature Section -->

  <section id="feature-style">
    <div class="">
      <h1>Why choose Easybank?</h1>
      <p>We leverage Open Banking to turn your bank account into your financial hub. Control
        your finances like never before.</p>
    </div>
    <div class="row">
      <div class="col-lg-3" style="padding-top: 5%;">
        <img src="icon-online.svg" style="padding-bottom: 10%;" alt="online-image">
        <h4 style="padding-bottom: 10%;">Online Banking</h4>
        <p>Our modern web and mobile applications allow you to keep track of your finances
          wherever you are in the world.</p>
      </div>
      <div class="col-lg-3" style="padding-top: 5%;">
        <img src="icon-budgeting.svg" style="padding-bottom: 10%;" alt="budgeting-image">
        <h4 style="padding-bottom: 10%;">Simple Budgeting</h4>
        <p>See exactly where your money goes each month. Receive notifications when you’re
          close to hitting your limits.</p>
      </div>
      <div class="col-lg-3" style="padding-top: 5%;">
        <img src="icon-onboarding.svg" style="padding-bottom: 10%;" alt="onboarding-image">
        <h4 style="padding-bottom: 10%;">Fast Onboarding</h4>
        <p>We don’t do branches. Open your account in minutes online and start taking control
          of your finances right away.</p>
      </div>
      <div class="col-lg-3" style="padding-top: 5%;">
        <img src="icon-api.svg" style="padding-bottom: 10%;" alt="api-image">
        <h4 style="padding-bottom: 10%;">Open API</h4>
        <p>Manage your savings, investments, pension, and much more from one account. Tracking
          your money has never been easier.</p>
      </div>

    </div>

  </section>

  <!-- Latest Articles -->

  <section id="articles-style">
    <div class="">
      <h1 style="margin-bottom: 3%;">Latest Articles</h1>
      <div class="row">
        <div class="col-lg-3">
          <img src="image-currency.jpg" class="latest-image" alt="currency-image">
          <h6>By Claire Robinson</h6>
          <h4>Receive money in any currency with no fees</h4>
          <p>The world is getting smaller and we’re becoming more mobile. So why should you be
            forced to only receive money in a single …</p>
        </div>
        <div class="col-lg-3">
          <img src="image-restaurant.jpg" class="latest-image" alt="restaurant-image">
          <h6>By Wilson Hutton</h6>
          <h4>Treat yourself without worrying about money</h4>
          <p>Our simple budgeting feature allows you to separate out your spending and set
            realistic limits each month. That means you …</p>
        </div>
        <div class="col-lg-3">
          <img src="image-plane.jpg" class="latest-image" alt="plane-image">
          <h6>By Wilson Hutton</h6>
          <h4>Take your Easybank card wherever you go</h4>
          <p>We want you to enjoy your travels. This is why we don’t charge any fees on purchases
            while you’re abroad. We’ll even show you …</p>
        </div>
        <div class="col-lg-3">
          <img src="image-confetti.jpg" class="latest-image" alt="confetti-image">
          <h6>By Claire Robinson</h6>
          <h4>Our invite-only Beta accounts are now live!</h4>
          <p>After a lot of hard work by the whole team, we’re excited to launch our closed beta.
            It’s easy to request an invite through the site ...</p>
        </div>

      </div>

    </div>

  </section>

  <!-- Footer -->

  <section id="footer-style">
    <div class="row">
      <div class="col-lg-3">
        <img src="logo.svg" style="padding-bottom: 10%;" alt="brand-logo">
        <div class="row">
          <div class="col-lg-2">
            <img src="icon-facebook.svg" alt="facebook-image">
          </div>
          <div class="col-lg-2">
            <img src="icon-youtube.svg" alt="youtube-image">
          </div>
          <div class="col-lg-2">
            <img src="icon-twitter.svg" alt="twitter-image">
          </div>
          <div class="col-lg-2">
            <img src="icon-pinterest.svg" alt="pinterest-image">
          </div>
          <div class="col-lg-2">
            <img src="icon-instagram.svg" alt="instagram-image">
          </div>

        </div>

      </div>
      <div class="col-lg-3"style="padding-left: 6%;">
        <div class="row">
          <a href="#" style="color:#dae1e7;">About Us</a>
        </div>
        <div class="row">
          <a href="#" style="color:#dae1e7;">Contact</a>
        </div>
        <div class="row">
          <a href="#" style="color:#dae1e7;">Blog</a>
        </div>

      </div>
      <div class="col-lg-3">
        <div class="row">
          <a href="#" style="color:#dae1e7;">Careers</a>
        </div>
        <div class="row">
          <a href="#" style="color:#dae1e7;">Support</a>
        </div>
        <div class="row">
          <a href="#" style="color:#dae1e7;">Privacy Policy</a>
        </div>

      </div>
      <div class="col-lg-3" style="text-align: right;">
        <button type="button" class="btn btn-dark btn-mystyle">Request Invite</button>
        <h6 style="color: #dae1e7; padding-top: 20px;">© Easybank. All Rights Reserved</h6>

      </div>

    </div>

  </section>

</body>

</html>
