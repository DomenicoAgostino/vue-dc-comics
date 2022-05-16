<template>
  <footer class="d-flex justify-content-between">
    <div class="container-fluid">

      <div class="communication">

        <div class="container logo d-flex justify-content-between">

          <div class="communication-list d-flex">

            <div class="communication-dc-comics">

              <h4>dc comics</h4>

              <ul>
                <li><a href="#">Characters</a></li>
                <li><a href="#">Comics</a></li>
                <li><a href="#">Movies</a></li>
                <li><a href="#">Tv</a></li>
                <li><a href="#">Games</a></li>
                <li><a href="#">Videos</a></li>
                <li><a href="#">News</a></li>
              </ul>

              <h4>shop</h4>

              <ul>
                <li><a href="#">Shop DC</a></li>
                <li><a href="#">Shop DC Collectibles</a></li>
              </ul>

            </div>

            <div class="communication-dc">

              <h4>dc</h4>

              <ul>
                <li><a href="#">Terms of Use</a></li>
                <li><a href="#">Privacy Policy (new)</a></li>
                <li><a href="#">Ad Choices</a></li>
                <li><a href="#">Advertising</a></li>
                <li><a href="#">Jobs</a></li>
                <li><a href="#">Subscription</a></li>
                <li><a href="#">Talent Workshops</a></li>
                <li><a href="#">Cpsc Certificates</a></li>
                <li><a href="#">Ratings</a></li>
                <li><a href="#">Shop help</a></li>
                <li><a href="#">Contact us</a></li>
              </ul>

            </div>

            <div class="communication-sites">

              <h4>sites</h4>

              <ul>
                <li><a href="#">DC</a></li>
                <li><a href="#">MAD magazine</a></li>
                <li><a href="#">DC kids</a></li>
                <li><a href="#">DC universe</a></li>
                <li><a href="#">DC power visa</a></li>
              </ul>

            </div>

          </div>

          <div class="communication-logo">
            <img src="" alt="">
          </div>

        </div>

        <div class="communication-social">
          <div class="container d-flex justify-content-between">

            <button class="sign-up">sign-up now!</button>

            <div class="social-media d-flex align-items-center">

              <a class="follow" href="#">follow us</a>

              <a href="#">
                <img src="../assets/img/footer-facebook.png" alt="">
              </a>

              <a href="#">
                <img src="../assets/img/footer-twitter.png" alt="">
              </a>

              <a href="#">
                <img src="../assets/img/footer-youtube.png" alt="">
              </a>

              <a href="#">
                <img src="../assets/img/footer-pinterest.png" alt="">
              </a>

              <a href="#">
                <img src="../assets/img/footer-periscope.png" alt="">
              </a>

            </div>

          </div>
        </div>

      </div>

    </div>

  </footer>

</template>
<script>
export default {
  name: 'FooterComponent'
}
</script>

<style>

  footer {
    background-image: url(../assets/img/footer-bg.jpg);
    background-size: cover;
  }

  .container-fluid {
    padding: 0;
  }

  .logo{
    background-image: url(../assets/img/dc-logo-bg.png);
    background-repeat: no-repeat;
    background-position: right
  }

  h4 {
    color: white;
    text-transform: uppercase;
  }

  ul {
    padding: 0;
    
  }

  li {
    padding: 0px 0px ;

  }

  a {
    color: grey;
  }

  .communication-dc-comics, .communication-dc, .communication-sites {
    margin: 30px 15px 0px 0px;
  }

  .communication-social {
    background-color: #303030;
  }

  .sign-up {
    margin: 25px 0px;
    color: white;
    background-color: #303030;
    border: 2px solid #0282F9;
    font-size: 20px;
    padding: 10px 20px
  }

  .social-media a{
    margin-left: 18px;

  }

  .follow {
    font-size: 22px;
    color: #0282F9
  }


</style>