<template>
  <div class="background">
    <div class="app-header">
      <a class="nav-logo" href="/">
        <span class="nav-logo-icon">
          <svg viewBox="0 0 100 100" width="30" height="30">
            <defs>
              <linearGradient
                id="a"
                x1="82.85"
                y1="30.41"
                x2="51.26"
                y2="105.9"
                gradientTransform="matrix(1, 0, 0, -1, -22.41, 110.97)"
                gradientUnits="userSpaceOnUse"
              >
                <stop offset="0" stop-color="#6c56cc"></stop>
                <stop offset="1" stop-color="#9785e5"></stop>
              </linearGradient>
            </defs>
            <polygon
              points="44.61 0 12.91 17.52 0 45.45 19.57 90.47 47.35 100 52.44 89.8 63 26.39 44.61 0"
              fill="#34208c"
            ></polygon>
            <polygon
              points="63 26.39 43.44 14.41 16.43 35.7 47.35 100 52.44 89.8 63 26.39"
              fill="url(#a)"
            ></polygon>
            <polygon
              points="63 26.39 63 26.39 44.61 0 43.44 14.41 63 26.39"
              fill="#af9ff4"
            ></polygon>
            <polygon
              points="43.44 14.41 44.61 0 12.91 17.52 16.43 35.7 43.44 14.41"
              fill="#4a37a0"
            ></polygon>
            <polygon
              points="16.43 35.7 19.57 90.47 47.35 100 16.43 35.7"
              fill="#4a37a0"
            ></polygon>
          </svg>
        </span>
        <span class="nav-logo-text">Obsidian</span>
      </a>
      <div class="app-header-links">
        <a href="" class="app-header-link mod-twitter">
          <svg fill="#555" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 50 50" width="34px" height="24px">
  				<path d="M 50.0625 10.4375 C 48.214844 11.257813 46.234375 11.808594 44.152344 12.058594 C 46.277344 10.785156 47.910156 8.769531 48.675781 6.371094 C 46.691406 7.546875 44.484375 8.402344 42.144531 8.863281 C 40.269531 6.863281 37.597656 5.617188 34.640625 5.617188 C 28.960938 5.617188 24.355469 10.21875 24.355469 15.898438 C 24.355469 16.703125 24.449219 17.488281 24.625 18.242188 C 16.078125 17.8125 8.503906 13.71875 3.429688 7.496094 C 2.542969 9.019531 2.039063 10.785156 2.039063 12.667969 C 2.039063 16.234375 3.851563 19.382813 6.613281 21.230469 C 4.925781 21.175781 3.339844 20.710938 1.953125 19.941406 C 1.953125 19.984375 1.953125 20.027344 1.953125 20.070313 C 1.953125 25.054688 5.5 29.207031 10.199219 30.15625 C 9.339844 30.390625 8.429688 30.515625 7.492188 30.515625 C 6.828125 30.515625 6.183594 30.453125 5.554688 30.328125 C 6.867188 34.410156 10.664063 37.390625 15.160156 37.472656 C 11.644531 40.230469 7.210938 41.871094 2.390625 41.871094 C 1.558594 41.871094 0.742188 41.824219 -0.0585938 41.726563 C 4.488281 44.648438 9.894531 46.347656 15.703125 46.347656 C 34.617188 46.347656 44.960938 30.679688 44.960938 17.09375 C 44.960938 16.648438 44.949219 16.199219 44.933594 15.761719 C 46.941406 14.3125 48.683594 12.5 50.0625 10.4375 Z"></path>
  			</svg>
        </a>
        <a href="" class="app-header-link">Pricing</a>
        <a href="" class="app-header-link">Featuers</a>
        <a href="" class="app-header-link">Community</a>
        <a href="" class="app-header-link">Account</a>
      </div>
    </div>
    <div class="body">
      <h1 class="header">This is Background</h1>
    </div>
  </div>
</template>

<script>
export default {
  name: "ObsidianNavbar",
};
</script>

<style lang="css">
.header {
  font-size: 64px;
  color: white;
  margin: 0;
}

.app-header {
  height: 66px;
  width: 100%;
  position: fixed;
  background-color: rgba(22, 22, 22, 0.7);
  backdrop-filter: blur(5px);
  border-bottom: 1px solid rgba(255, 255, 255, 0.1);
  display: flex;
  justify-content: space-between;
  padding: 0 50px 0 100px;
  z-index: 10;
}

a {
  color: (--text-accent);
  outline: none;
}

.nav-logo {
  text-align: center;
  text-decoration: none;
}

.app-header-links {
  display: flex;
  align-items: center;
}


.nav-logo-icon {
  position: relative;
}

.nav-logo-text {
  font-size: 13px;
  font-family: 'Avenir Next', sans-serif;
  text-transform: uppercase;
  letter-spacing: 2px;
  margin: 0;
  -webkit-user-select: none;
  color: var(--text-muted);
  font-size: 20px;
}

.app-header-link {
  margin-left: 30px;
  text-decoration: none;
  color: var(--text-muted);
  display: flex;
}

.background {
  background-color: var(--background-secondary);
  height: 400px;
}
</style>