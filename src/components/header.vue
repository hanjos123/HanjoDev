<template>
  <header>
    <router-link to="/" class="site-logo">
      <svg viewBox="0 0 317.8 46.8" class="js-logo">
        <path
          d="M188.3 29V0h-5.9v29c0 9.6 7.8 17.3 17.3 17.3v-5.9c-6.3 0-11.4-5.1-11.4-11.4zm26.4 0V0h-5.9v29c0 9.6 7.8 17.3 17.3 17.3v-5.9c-6.3 0-11.4-5.1-11.4-11.4zM17.3.2C7.8.2 0 7.9 0 17.5v28.7h5.9c0-6.3 5.2-11.4 11.4-11.4 9.5 0 17.3-7.8 17.3-17.3C34.6 7.9 26.9.2 17.3.2zm0 28.6c-4.3 0-8.3 1.7-11.4 4.3V17.5c0-6.3 5.1-11.4 11.4-11.4 6.3 0 11.4 5.1 11.4 11.4 0 6.2-5.1 11.3-11.4 11.3zM61.4.2C51.8.2 44 8 44 17.5v29h6v-.2C50 40.1 55.1 35 61.4 35s11.4 5.1 11.4 11.4v.2h5.9v-29C78.7 8 70.9.2 61.4.2zm0 28.8C57 29 53 30.7 50 33.3V17.5c0-6.3 5.1-11.4 11.4-11.4s11.4 5.1 11.4 11.4v15.8c-3.1-2.6-7.1-4.3-11.4-4.3zM153.1.2c-9.5 0-17.3 7.8-17.3 17.3v29h5.9v-.2c0-6.3 5.1-11.4 11.4-11.4 6.3 0 11.4 5.1 11.4 11.4v.2h5.9v-29C170.4 8 162.6.2 153.1.2zm0 28.8c-4.4 0-8.3 1.6-11.4 4.3V17.5c0-6.3 5.1-11.4 11.4-11.4 6.3 0 11.4 5.1 11.4 11.4v15.8c-3.1-2.6-7.1-4.3-11.4-4.3zM254 .2c-9.5 0-17.3 7.8-17.3 17.3v29h5.9v-.2c0-6.3 5.1-11.4 11.4-11.4 6.3 0 11.4 5.1 11.4 11.4v.2h5.9v-29C271.4 8 263.6.2 254 .2zm0 28.8c-4.4 0-8.3 1.6-11.4 4.3V17.5c0-6.3 5.1-11.4 11.4-11.4 6.3 0 11.4 5.1 11.4 11.4v15.8c-3-2.6-7-4.3-11.4-4.3zm63.8-19.7V.6h-5.9v8.7c0 6.3-5.1 11.4-11.4 11.4-6.3 0-11.4-5.1-11.4-11.4V.6h-5.9v8.7c0 6 3 11.2 7.6 14.4-4.6 3.1-7.6 8.4-7.6 14.4v8.8h5.9V38c0-6.3 5.1-11.4 11.4-11.4 6.3 0 11.4 5.1 11.4 11.4v8.8h5.9V38c0-6-3-11.2-7.6-14.4 4.6-3.1 7.6-8.4 7.6-14.3zM117.2 32.2c4.6-3.2 7.6-8.5 7.6-14.5C124.8 8 117 .2 107.4.2 97.9.2 90.1 8 90.1 17.5v29h6c0-6.3 5.1-11.4 11.4-11.4h.2c6.2.1 11.2 5.1 11.2 11.4h5.9c0-5.9-3-11.2-7.6-14.3zm-21.1 1.4V17.5c0-6.3 5.1-11.4 11.4-11.4 6.3 0 11.4 5.2 11.4 11.6 0 6.3-5.1 11.5-11.4 11.5v.1c-4.4-.1-8.4 1.6-11.4 4.3z"
          fill="#fff"
        ></path>
      </svg>
    </router-link>
    <nav class="site-nav">
      <div class="site-nav__item">
        <router-link to="/#"><span>Work</span></router-link>
      </div>
      <div class="site-nav__item">
        <router-link to="/about"><span>Expertise</span></router-link>
      </div>
      <div class="site-nav__item">
        <router-link to="/3"><span>About</span></router-link>
      </div>
      <div class="site-nav__item">
        <router-link to="/4"><span>Blog</span></router-link>
      </div>
      <div class="site-nav__item">
        <router-link to="/4"><span>Careers</span></router-link>
      </div>
    </nav>

    <a
      href="mailto:dangthevinh12@gmail.com"
      class="flip-btn flip-btn--auto js-site-email site-header__email"
      ><span>dangthevinh12@gmail.com</span></a
    >

    <div class="header-social">
      <router-link to="#">
        <i class="fa-brands fa-facebook-f"></i>
        <svg
          width="60px"
          height="60px"
          viewBox="0 0 100 100"
          preserveAspectRatio="none"
        >
          <circle
            class="js-circle circle"
            cx="50"
            cy="50"
            r="30"
            stroke-width="2"
            fill="none"
          />
        </svg>
      </router-link>

      <router-link to="#">
        <i class="fa-brands fa-github"></i>
        <svg
          width="60px"
          height="60px"
          viewBox="0 0 100 100"
          preserveAspectRatio="none"
        >
          <circle
            class="js-circle circle"
            cx="50"
            cy="50"
            r="30"
            stroke-width="2"
            fill="none"
          />
        </svg>
      </router-link>

      <router-link to="#">
        <i class="fa-brands fa-instagram"></i>
        <svg
          width="60px"
          height="60px"
          viewBox="0 0 100 100"
          preserveAspectRatio="none"
        >
          <circle
            class="js-circle circle"
            cx="50"
            cy="50"
            r="30"
            stroke-width="2"
            fill="none"
          />
        </svg>
      </router-link>

      <router-link to="#">
        <i class="fa-brands fa-dribbble"></i>
        <svg
          width="60px"
          height="60px"
          viewBox="0 0 100 100"
          preserveAspectRatio="none"
        >
          <circle
            class="js-circle circle"
            cx="50"
            cy="50"
            r="30"
            stroke-width="2"
            fill="none"
          />
        </svg>
      </router-link>
    </div>
  </header>
</template>

<script setup lang="ts"></script>

<style lang="scss" scoped>
.site-logo {
  transform: rotate(-90deg);
  position: fixed;
  top: 220px;
  left: 85px;
  width: 135px;
  height: 20px;
  display: block;
  z-index: 100;
  transform-origin: top left;
}

.site-nav {
  display: flex;
  padding-top: 70px;
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  justify-content: center;
  font-family: "GT-Pressura-Mono", Courier, monospace;

  &__item {
    padding: 0 25px;

    span {
      color: $white;
      font-size: 0.88889rem;
    }
  }
}

.site-header__email {
  display: inline-block;
  position: fixed;
  bottom: 160px;
  right: 30px;
  -ms-transform: translateY(-50%) rotate(90deg);
  transform: translateY(-50%) rotate(90deg);
  font-size: 0.88889rem;
  transition: opacity 0.6s 2.2s;
  color: $white;
}

.header-social {
  position: fixed;
  display: flex;
  flex-direction: column;
  z-index: 100;
  left: 68px;
  bottom: 79px;

  a {
    display: flex;
    align-items: center;
    justify-content: center;
    margin-top: 25px;
    width: 40px;
    height: 40px;
    border-radius: 50%;
    box-sizing: border-box;
    border: 2px solid transparent;
    transition: 0.2s all linear;
    position: relative;

    i {
      color: $white;
      font-size: 17px;
    }

    svg {
      position: absolute;
      top: -11.5px;
      left: -12px;
      transform: rotate(-90deg);
      opacity: 0.5;
    }

    .circle {
      stroke: $white;
      stroke-dasharray: 301.59px 301.59px;
      stroke-dashoffset: 301.59px;
      transition: all 0.8s;
      transition-timing-function: ease-out;
    }

    &:hover svg {
      scale: 1.1;
      opacity: 1;
    }

    &:hover .circle {
      stroke-dashoffset: 0;
    }
  }
}
</style>
