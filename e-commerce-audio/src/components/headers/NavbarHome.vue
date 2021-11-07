<template>
    <div class="navbar-home-container">
        <div class="navbar-home">
            <div class="navbar-home-logo">
                <img src="../../../public/assets/shared/desktop/logo.svg" alt="logo" />
            </div>

            <div class="navbar-home-menu">
                <div class="navbar-menu-title">Home</div>
                <div class="navbar-menu-title">Headphones</div>
                <div class="navbar-menu-title">Speakers</div>
                <div class="navbar-menu-title">Earphones</div>
            </div>

            <div class="navbar-home-icon">
                <img src="../../../public/assets/shared/desktop/icon-cart.svg" alt="icon" />
            </div>
        </div>

        <div class="header-home">
            <div class="header-home-left">
                <div class="header-home-subtitle">New Product</div>
                <div class="header-home-title">XX99 Mark II</div>
                <div class="header-home-title" style="margin-bottom: 1rem;">Headphones</div>
                <div class="header-home-description">Experience natural, lifelike audio and exceptionnal</div>
                <div class="header-home-description">build quality made for thepassionate music</div>
                <div class="header-home-description">enthusiast.</div>
                <div class="button-primary">
                    <div class="button-primary-text">
                        See product
                    </div>
                </div>
            </div>

            <div class="header-home-right">
                <img src="../../../public/assets/home/tablet/image-header.jpg" alt="headphones" class="navbar-home-img" />
            </div>
        </div>
    </div>
</template>

<script>
export default {
  name: 'NavbarHome',
  props: {
    msg: String
  }
}
</script>