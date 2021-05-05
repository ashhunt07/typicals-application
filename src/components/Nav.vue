<template> 

    <ul class="nav">
        <li class="nav-item">
          <a class="nav-link" aria-current="page" href="#">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Features</a>
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






</template>

<script>
    export default {
        name: 'Nav',
    }
</script>

<style scoped>
    @import '../styles/nav.css';
</style>

