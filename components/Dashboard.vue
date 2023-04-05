<template>
  <div>
    <nav class="navbar fixed-top navbar-expand-lg">
      <div class="container">
        <a class="navbar-brand" href="#">Spondise</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="d-flex justify-content-center">

        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <div class="input-group">
            <input type="text" class="filter" placeholder="Filter">
            <div class="input-group-append">
              <!-- <span class="input-group-text"><i class="bi bi-person"></i></span> -->
            </div>
          </div>

          <div class="input-group">
            <input type="password" class="smart-search" placeholder="Smart Search">
              <span class="f-search d-flex justify-content-right"></span>
          </div>
        </div>

        </div>
        <form class="d-flex" role="search">
          <div class="row">
            <div class="col-md-6">
              <span class="group-user">
                <i class="fal fa-file-alt"></i>
                <i class="far fa-bell"></i>
                <i class="far fa-envelope"></i>
              </span>
            </div>
            <div class="col-md-3">
              <div class="input-group">
                <input type="text" class="dropdown" placeholder="Sponsor">
                <!-- <div class="input-group-append"> -->
                  <!-- <span class="input-group-text"><i class="bi bi-person"></i></span> -->
                <!-- </div> -->
              </div>
            </div>
          </div>
        </form>
      </div>
    </nav>
    <div class="border-bottom">
      <div class="row">
        <div class="col-md-4 d-flex justify-content-center">
          <span class="route" >Dashboard > Sponsor profile > Verification</span>
        </div>
        <div class="d-flex justify-content-center col-md-4">
          <span class="form-check-label-sponsor">Sponsor</span>
          <div class="form-check form-switch form-switch-creator">
            <input class="form-check-input" type="checkbox" role="switch" id="flexSwitchCheckDefault">
            <label class="form-check-label" for="flexSwitchCheckDefault">Creator</label>
          </div>
        </div>
        <div class="col-md-4">
          <div class="prog-bar">
            <span class="profile-completeness">Profile completeness</span><span class="percent">90%</span>
            <div class="progress" role="progressbar" aria-label="Danger example" aria-valuenow="90" aria-valuemin="0" aria-valuemax="100">
              <div class="progress-bar" style="width: 90%"></div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="body container">
      <div class="row">
        <div class="col-md-4">
          <div class="card">
            <div class="d-flex justify-content-center">
              <img src="../assets/images/Vector.png" class="image-prof"/>
            </div>
            <label class="text-center">Jhonny_Official</label>
            <div class="prof-details">
              <hr />
              <small>Sponsor Level</small>
              <hr />
              <small>Sponsor Plan</small>
              <hr />
              <small>Verified</small>
              <hr />
              <small>Ratings</small>
              <hr />
              <small>Completed Contracts</small>
            </div>

          </div>
        </div>
        <div class="col-md-8">
          <div class="row1">
              <div class="form-label-header">
                <small>Verify phone number</small>
                <span class="form-check form-switch switch-f">
                  <input class="form-check-input" type="checkbox" role="switch" id="flexSwitchCheckDefault">
                </span> 
              </div>
              <div class="row">
                <div class="col-md-6">
                  <input class="form-control" placeholder="Select country code"/>
                </div>
                <div class="col-md-6">
                  <input class="form-control" placeholder="Phone number"/>
                </div>
              </div>
          </div>
          <div class="row2">
              <div class="form-label-header">
                <small>Verify Email</small>
                <span class="form-check form-switch switch-f">
                  <input class="form-check-input" type="checkbox" role="switch" id="flexSwitchCheckDefault">
                </span> 
              </div>
              <div class="row">
                <div class="col-md-12">
                  <input class="form-control" placeholder="Email"/>
                </div>
              </div>
          </div>
          <div class="row3">
              <div class="form-label-header">
                <small>Verify Identity</small>
                <span class="form-check form-switch switch-f">
                  <input class="form-check-input" type="checkbox" role="switch" id="flexSwitchCheckDefault">
                </span> 
              </div>
              <small class="choose-id">Choose an ID type to add </small>
              <div class="row">
                <div class="col-md-6">
                  <select class="form-control select-f" >
                    <option>Issuing country/region</option>
                  </select>
                </div>
                <div class="col-md-6">
                  <select class="form-control select-f">
                    <option>Choose Identification</option>
                  </select>                
                </div>
              </div>
          </div>
          <div class="row4">
              <div class="form-label-header">
                <small>Upload images of your ID</small>
                <span class="form-check form-switch switch-f">
                  <input class="form-check-input" type="checkbox" role="switch" id="flexSwitchCheckDefault">
                </span> 
              </div>
              <div class="row">
                <div class="col-md-6 card">
                    <div class="d-flex justify-content-center">
                      <img src="../assets/images/front.png" class="front-img"/>
                    </div>
                    <p class="text-center">Upload front</p>
                    <small class="text-center require-ext">JPEG or PNG only</small>
                    <div class="d-flex justify-content-center upload-button">
                      <button class="btn-select">Select Files</button>
                    </div>
                </div>
                <div class="col-md-6 card">
                  <div class="d-flex justify-content-center">
                      <img src="../assets/images/back.png" class="back-img"/>
                    </div>
                    <p class="text-center">Upload back</p>
                    <small class="text-center require-ext">JPEG or PNG only</small>
                    <div class="d-flex justify-content-center upload-button">
                      <button class="btn-select">Select Files</button>
                    </div>
                </div>
              </div>
          </div>
        </div>
      </div>
    </div>
  </div>

</template>
<style scoped>
@import 'https://pro.fontawesome.com/releases/v5.10.0/css/all.css';
  ::placeholder {
    font-size: 10px;
    padding: 5px;
  }
  .upload-button {
    margin-top: 10px;
    margin-bottom: 30px;
  }
  .btn-select {
    width: 123px;
    height: 34px;
    color: #fff;
    background-color: #F29820;
    border-radius: 20px;
    border: 1px #F29820;
  }
  .require-ext {
    margin-top: -20px;
  }

  .front-img, .back-img {
    width: 50px;
    margin-top: 30px;
  }
  .select-f {
    font-size: 10px;
  }
  hr {
    margin: 0;
  }
  .choose-id {
    margin-bottom: 5px;
  }
  .row2, .row3, .row4 {
    margin-top: 20px;
  }
  .form-label-header {
    margin-bottom: 10px;
  }
  .switch-f {
    float: right;
  }
  .prof-details {
    padding: 15px;
  }
  small {
    font-size: 10px;
  }
  .image-prof {
    padding: 10px;
    width: 130px;
  }
  .card {
    width: 280px;
    margin-left: 40px;
  }
  .body {
    margin-top: 20px;
    margin-left: 210px;
  }
  .prog-bar {
    width: 380px;
    margin-bottom: 5px;
  }
  .progress {
    height: 5px;
  }
  .progress-bar {
    background-color: #F29820;
  }
  .profile-completeness {
    font-size: 10px;
  }
  .percent {
    font-size: 10px;
    float: right;
    margin-top: 7px;
  }
  .form-switch-creator {
    margin-right: 70px;
  }
  .form-check-input {
    margin-top: 7px;
  }
  .form-check-label-sponsor {
    margin-right: 10px;
    margin-top: 7px;
    font-size: 10px;
  }
  .form-check-label {
    font-size: 10px;
  }

  .route {
    font-size: 10px;
    color: #F29820;
    margin-left: 190px;
    margin-top: 7px;
  }
  .border-bottom {
    border: 0.05px solid #E8E8F3;
    margin-top: 50px;
    width: 100%;
  }
  .group-user {
    margin-top: 3px;
  }
  .fa-bell {
    margin-left: 10px;
  }
  .fa-envelope {
    margin-left: 10px;
  }
  .f-search {
    position: absolute;
  }
  .dropdown {
    border: 1px solid #999999;
    width: 136px;
    border-radius: 20px;
  }
  .filter {
    border: 1px solid #999999;
    width: 150px;
    border-radius: 5px;
  }
  .smart-search {
    border: 1px solid #999999;
    border-left-width: 0;
    width: 162px;
    border-top-right-radius: 5px !important;
    border-bottom-right-radius: 5px !important;
  }
  .nav-item .nav-link {
    margin-left: 30px;
    padding: 20px;
    }
    .navbar-brand {
    margin-left: 70px;
    }
    .calltoAction {
    margin-right: 70px;
    }
</style>
