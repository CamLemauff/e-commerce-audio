<template>
    <div class="container-home">
        <navbar-home></navbar-home>

        <div class="home-category-container">
            <div class="home-category-content">
                <div class="home-category">
                    <div class="home-category-img">
                        <img src="../../public/assets/shared/desktop/image-category-thumbnail-headphones.png" alt="headphones" class="category-img"/>
                    </div>
                    <div class="home-category-title">
                        Headphones
                    </div>
                    <div class="home-category-subtitle">
                        <div class="home-category-subtitle-text">Shop</div>
                        <img src="../../public/assets/shared/desktop/icon-arrow-right.svg" alt="arrow" class="arrow-icon" />
                    </div>
                </div>

                <div class="home-category">
                    <div class="home-category-img">
                        <img src="../../public/assets/shared/desktop/image-category-thumbnail-speakers.png" alt="speakers" class="category-img"/>
                    </div>
                    <div class="home-category-title">
                        Speakers
                    </div>
                    <div class="home-category-subtitle">
                        <div class="home-category-subtitle-text">Shop</div>
                        <img src="../../public/assets/shared/desktop/icon-arrow-right.svg" alt="arrow" class="arrow-icon" />
                    </div>
                </div>

                <div class="home-category">
                    <div class="home-category-img">
                        <img src="../../public/assets/shared/desktop/image-category-thumbnail-earphones.png" alt="earphones" class="category-img"/>
                    </div>
                    <div class="home-category-title">
                        Earphones
                    </div>
                    <div class="home-category-subtitle">
                        <div class="home-category-subtitle-text">Shop</div>
                        <img src="../../public/assets/shared/desktop/icon-arrow-right.svg" alt="arrow" class="arrow-icon" />
                    </div>
                </div>
            </div>
        </div>

        <div class="primary-product-container">
            <div class="primary-product-content">
                <div class="primary-content-left">
                    <img src="../../public/assets/home/desktop/image-speaker-zx9.png" alt="speaker" class="primary-content-img" />
                    <img src="../../public/assets/home/desktop/pattern-circles.svg" alt="pattern" class="primary-content-pattern" />
                </div>
                <div class="primary-content-right">
                    <div class="primary-content-right-title">Zx9</div>
                    <div class="primary-content-right-title">Speaker</div>
                    <div class="primary-content-right-description">Upgrade to premium speakers that are</div>
                    <div class="primary-content-right-description">phenomenally built to deliver truly remarkable</div>
                    <div class="primary-content-right-description">sound.</div>
                    <div class="button-black">
                        <div class="button-black-text">
                            See product
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
import NavbarHome from './headers/NavbarHome.vue';
export default {
  name: 'Index',
  components: {
      NavbarHome
  },
  props: {
    msg: String
  }
}
</script>