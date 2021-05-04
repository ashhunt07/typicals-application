<template> 

<!-- <div class="container-fluid h-100">
    <div class="row h-100">
        <div class="col p-0 pt-3">
            <a href class="m-3 navbar-light" data-target="#sidebar" data-toggle="collapse">
                <span class="navbar-toggler-icon"></span>
            </a>

        </div>
        <div class="col-2 collapse fade bg-dark fixed-top p-3 h-100" id="sidebar">
            <ul class="nav flex-column">
                <li class="nav-item"><a class="nav-link text-white" href="#">Overview</a></li>
                <li class="nav-item"><a class="nav-link text-white" href="#">Analytics</a></li>
                <li class="nav-item"><a class="nav-link text-white" href="#">Export</a></li>
                <li class="nav-item"><a class="nav-link text-white" href="#">Link</a></li>
                <li class="nav-item"><a class="nav-link text-white" href="#">Link</a></li>
            </ul>
        </div>
    </div>
</div> -->


<nav class="navbar fixed-top navbar-dark bg-primary">
    <a class="navbar-brand" href="#">Navbar</a>
    <ul class="nav justify-content-end">
        <li class="nav-item">
          <a class="nav-link active"  style="color:#fff;" aria-current="page" href="#">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link"  style="color:#fff;" href="#">Features</a>
        </li>
        <li>
          <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#collapsingNavbar">
              <span><i class="fa fa-ellipsis-h" aria-hidden="true"></i>
              <br>
              <h6 class="tiny-text">MORE</h6>
              </span>
          </button>
        </li>
      </ul>

    <div class="navbar-collapse collapse" id="collapsingNavbar">
        <ul class="navbar-nav">
            <li class="nav-item active">
                <a class="nav-link" href="#">Home <span class="sr-only">Home</span></a>
            </li>
            <li class="nav-item">
                <a class="nav-link" href="//codeply.com">Codeply</a>
            </li>
            <li class="nav-item">
                <a class="nav-link" href="#myAlert" data-toggle="collapse">Wow</a>
            </li>
        </ul>
        <ul class="navbar-nav ml-auto">
            <li class="nav-item">
                <a class="nav-link" href="" data-target="#myModal" data-toggle="modal">About</a>
            </li>
        </ul>
    </div>
</nav>





</template>

<script>
    export default {
        name: 'Nav',
    }
</script>

<style scoped>
    @import '../styles/nav.css';
</style>

