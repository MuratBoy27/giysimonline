<template>
    <nav class="navbar navbar-expand-lg navbar-light" style="background-color: white;">
        <div class="container">
            <!--<a href="#" class="navbar-brand">Navbar</a>-->
            <div class="row">
                <div class="col-2">
                    <a href="#" class="navbar-brand">
                        <img src="../static/logo2.jpg" alt="logo" width="150">
                    </a>

                    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                        <span class="navbar-toggler-icon"></span>
                    </button>
                </div>
            </div>
            <div class="col-8">
                <form class="form-inline my-12 my-lg-0">
                    <input class="form-control mr-sm-2" type="search" placeholder="Search" aria-label="Search">
                    <button class="btn btn-outline-success my-2 my-sm-0" type="submit">Ara</button>
                </form>
            </div>

            <div class="col-2">
                <div class="collapse navbar-collapse" id="navbarNav">
                    <ul class="navbar-nav">

                        <li class="nav-item">
                            <a href="#" class="nav-link ">Markalar</a>
                        </li>
                        <li class="nav-item">
                            <a href="#" class="nav-link ">Giriş Yap</a>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </nav>
</template>

<script>
export default {

}
</script>

<style></style>