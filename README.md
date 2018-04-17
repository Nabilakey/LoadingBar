<!DOCTYPE html>
<html>
<title>ITK</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel='stylesheet' href='https://fonts.googleapis.com/css?family=Roboto'>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>
html,body,h1,h2,h3,h4,h5,h6 {font-family: "Roboto", sans-serif}
}
#myProgress {
  width: 100%;
  background-color: #ddd;
}
#myBar {
  width: 1%;
  height: 30px;
  background-color: #4CAF50;
}
</style>
<body class="w3-light-grey">

<!-- Page Container -->
<div class="w3-content w3-margin-top" style="max-width:1400px;">

  <!-- The Grid -->
  <div class="w3-row-padding">

    <!-- Left Column -->
    <div class="w3-third">

      <div class="w3-white w3-text-grey w3-card-4">
        <div class="w3-display-container">
          <img src="itk.png" style="width:100%" alt="Avatar">
        </div>
        <div class="w3-container">
          <p><i class="fa fa-briefcase fa-fw w3-margin-right w3-large w3-text-teal"></i>College</p>
          <p><i class="fa fa-home fa-fw w3-margin-right w3-large w3-text-teal"></i>Balikpapan, Indonesia</p>
          <hr>

          <p class="w3-large"><b><i class="fa fa-asterisk fa-fw w3-margin-right w3-text-teal"></i>What we do ?</b></p>
          <p>Education</p>
          <div class="w3-light-grey w3-round-xlarge w3-small">
            <div class="w3-container w3-center w3-round-xlarge w3-teal" style="width:100%">100%</div>
          </div>
          <p>Research</p>
          <div class="w3-light-grey w3-round-xlarge w3-small">
            <div class="w3-container w3-center w3-round-xlarge w3-teal" style="width:80%">
              <div class="w3-center w3-text-white">80%</div>
            </div>
          </div>
          <p>Community Service</p>
          <div class="w3-light-grey w3-round-xlarge w3-small">
            <div class="w3-container w3-center w3-round-xlarge w3-teal" style="width:80%">80%</div>
          </div>
          <br>
        </div>
      </div><br>

    <!-- End Left Column -->
    </div>

    <!-- Right Column -->
    <div class="w3-twothird">

      <div class="w3-container w3-card w3-white w3-margin-bottom">
        <h2 class="w3-text-grey w3-padding-16"><i class="fa fa-certificate fa-fw w3-margin-right w3-xxlarge w3-text-teal"></i>Institut Teknologi Kalimantan</h2>
        <div class="w3-container">
          <h5 class="w3-opacity"><b>History</b></h5>
          <h6 class="w3-text-teal"><i class="fa fa-calendar fa-fw w3-margin-right"></i>2012 - <span class="w3-tag w3-teal w3-round">Now</span></h6>
          <p>Institut Teknologi Kalimantan telah ada sejak 2012, namun saat itu belum memiliki bangunan kampus. Sehingga mahasiswa kami berkuliah di ITS</p>
          <hr>
        </div>
        <div class="w3-container">
          <h5 class="w3-opacity"><b>The Buildings</b></h5>
          <h6 class="w3-text-teal"><i class="fa fa-calendar fa-fw w3-margin-right"></i>2015</h6>
          <p>Pada pendaftaran mahasiswa angkatan 2015 berdirilah gedung pertama ITK</p>
          <hr>
        </div>
        <div class="w3-container">
          <h5 class="w3-opacity"><b>Student</b></h5>
          <h6 class="w3-text-teal"><i class="fa fa-calendar fa-fw w3-margin-right"></i>2012-2017</h6>
          <p>Dari semenjak berdiri hingga sekarang, mahasiswa yang berkuliah di ITK mencapai hampir 2000 mahasiswa.</p><br>
        </div>
      </div>

      <div class="w3-container w3-card w3-white">
        <h2 class="w3-text-grey w3-padding-16"><i class="fa fa-certificate fa-fw w3-margin-right w3-xxlarge w3-text-teal"></i>Go to our website?</h2>
        <div class="w3-container">
          <h5 class="w3-opacity"><b></b></h5>
          <p><div id="myProgress">
            <div id="myBar"></div>
          </div>
          <br>
          <button onclick="move()">Click Me</button></p>
          <script>
          function move() {
            var elem = document.getElementById("myBar");
            var width = 1;
            var id = setInterval(frame, 10);
            function frame() {
              if (width >= 100) {
                clearInterval(id);
                window.location ="http://itk.ac.id/";
              } else {
                width++;
                elem.style.width = width + '%';
              }
            }
          }
          </script>
        </div>
      </div>
    </div>
  </div>
</div>

<footer class="w3-container w3-teal w3-center w3-margin-top">
</footer>

</body>
</html>
