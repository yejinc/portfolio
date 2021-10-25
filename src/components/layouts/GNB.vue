<template>
  <div class="container">
    <div class="row">
      <div class="col-sm-4">
        <div class="gnb">
          <div class="gnb-left">
            <a class="gnb-logo" href="#">
              <h1 class="logo-text sm-hidden">yejin cho</h1>
              <img
                class="logo"
                src="@/assets/images/logo.svg"
                alt="yejin cho"
              />
            </a>
          </div>

          <div class="gnb-right">
            <nav class="gnb-nav">
              <h2 class="visually-hidden">menu</h2>

              <ul class="gnb-nav-list">
                <li class="gnb-nav-item"><a href="#">works</a></li>
                <li class="gnb-nav-item"><a href="#">about</a></li>
                <li class="gnb-nav-item"><a href="#">blog</a></li>
              </ul>

              <button
                class="gnb-menu sm-only"
                type="button"
                aria-label="open the menu "
              >
                <i class="ic-menu"></i>
              </button>
            </nav>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'GNB'
}
</script>

<style lang="scss"></style>
