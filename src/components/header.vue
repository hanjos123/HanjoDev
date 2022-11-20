<template>
  <header class="header" ref="header" @scroll="demo">
    <router-link to="/" class="site-logo">
      <svg
        width="40"
        height="34"
        viewBox="0 0 459 399"
        fill="none"
        xmlns="http://www.w3.org/2000/svg"
      >
        <path
          d="M55 1H1L230 397L256.5 350.5L159 181.5H185.5L269.5 327L296.5 280.5L135 1H81L159 135H132L55 1Z"
          fill="white"
        />
        <path d="M293 1H161.5L228 114.5L293 1Z" fill="white" />
        <path
          d="M323 84H269.5L239 136L309.5 258L458 1H404L309.5 165L292.5 136L323 84Z"
          fill="white"
        />
        <path
          d="M55 1H1L230 397L256.5 350.5L159 181.5H185.5L269.5 327L296.5 280.5L135 1H81L159 135H132L55 1Z"
          stroke="white"
        />
        <path d="M293 1H161.5L228 114.5L293 1Z" stroke="white" />
        <path
          d="M323 84H269.5L239 136L309.5 258L458 1H404L309.5 165L292.5 136L323 84Z"
          stroke="white"
        />
      </svg>
    </router-link>

    <nav class="site-nav">
      <div class="site-nav__item">
        <router-link to="/work" active-class="active" exact
          ><span>Work</span></router-link
        >
      </div>
      <div class="site-nav__item">
        <router-link to="/experience" active-class="active" exact
          ><span>Expertise</span></router-link
        >
      </div>
      <div class="site-nav__item">
        <router-link to="/about" active-class="active" exact
          ><span>About</span></router-link
        >
      </div>
      <div class="site-nav__item">
        <router-link to="/blog" active-class="active" exact
          ><span>Blog</span></router-link
        >
      </div>
      <div class="site-nav__item">
        <router-link to="/career" active-class="active" exact
          ><span>Careers</span></router-link
        >
      </div>
    </nav>

    <div class="site-nav__item">
      <router-link to="/contact" active-class="active" exact
        ><span>Contact</span></router-link
      >
    </div>

    <!-- <a
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
    </div> -->
  </header>
</template>

<script setup lang="ts">
import { onMounted, ref } from "vue";

onMounted(() => {
  window.addEventListener("scroll", demo);
});

const header = ref({});
const demo = () => {
  const ele = header.value as HTMLElement;
  console.log(header.value);
  if (window.pageYOffset > 40) {
    ele.classList.add("red");
  } else {
    ele.classList.remove("red");
  }
};
</script>

<style lang="scss" scoped>
header {
  position: fixed;
  top: 0;
  display: flex;
  justify-content: space-between;
  align-items: center;
  width: 100%;
  padding: 20px 40px;
  box-sizing: border-box;
  z-index: 100;
  background: transparent;
  transition: 0.3s all linear;

  &.red {
    padding: 10px 40px;
    background: $primary;

    .site-nav {
      &__item {
        span {
          &::after {
            border-color: $white;
          }
        }
      }
    }
  }

  .site-logo {
    z-index: 100;
    svg {
      z-index: 99;
    }
  }

  .site-nav {
    display: flex;
    width: 100%;
    justify-content: center;
    font-family: "GT-Pressura-Mono", Courier, monospace;
    align-items: center;

    &__item {
      padding: 0 25px;

      span {
        color: $white;
        font-size: 0.88889rem;

        &::after {
          display: block;
          content: "";
          border-bottom: solid 3px $primary;
          transform: scaleX(0);
          transition: all 250ms ease-in-out;
          margin-top: 5px;
        }
      }

      &:hover,
      .active {
        span {
          &::after {
            transform: scaleX(1);
          }
        }
      }
    }
  }

  .contact {
    font-family: "GT-Pressura-Mono", Courier, monospace;
    color: $white;
    font-size: 0.88889rem;
    padding: 22px 0;
    border: 2px solid #333;
    width: 158px;
    // box-sizing: content-box;
    text-align: center;
    background-color: transparent;
    background-size: 100% 200%;
    background-repeat: no-repeat;
    background-position: 0 0;
    transition: color 0.3s, background-position 0.3s, box-shadow 0.3s,
      opacity 0.4s;
    background-image: linear-gradient(
      to bottom,
      transparent 0%,
      transparent 50%,
      #333 50%,
      #333 100%
    );

    &:hover {
      background-position: 0 100%;
      color: $white;
    }
  }
}
</style>
