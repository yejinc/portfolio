<template>
  <div class="container">
    <div class="row">
      <div class="col-sm-4">
        <div class="project-nav">
          <div class="project-nav-next">
            <div class="next-caption">
              <h3 class="next-caption-text">next</h3>
              <i class="ic-arrow-md" aria-hidden="true" />
            </div>
            <div class="next-project">
              <h1 class="next-project-text">golden</h1>
            </div>
          </div>
          <div class="project-nav-previous lg-only">
            <div class="previous-caption">
              <h3 class="previous-caption-text">previous</h3>
              <i class="ic-arrow-md" aria-hidden="true" />
            </div>
            <div class="previous-project">
              <h1 class="previous-project-text">tedxseoul</h1>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'ProjectNav'
}
</script>

<style lang="scss">
.project-nav {
  margin: 0 -#{$sm-margin};
  overflow: hidden;
  background-color: $black;

  &-next {
    @include column-flex;
    position: relative;
    z-index: $footer-index;
    height: 314px;

    &::after {
      content: '';
      @include pos-center-y;
      left: 40vw;
      width: 600px;
      height: 600px;
      z-index: $footer-circle-bg-index;
      border-radius: 50%;
      background-color: $icterine;
    }

    .next-caption {
      @include flex;
      margin-bottom: 30px;
      z-index: $footer-index;

      &-text {
        @include text-style(h3-sub, $main-coral);
        margin-right: 32px;
        text-transform: capitalize;
        mix-blend-mode: difference;
      }

      .ic-arrow-md {
        display: block;
        font-size: 30px;
        mix-blend-mode: difference;
        color: $main-cambridge-blue;
        transform: rotate(-90deg);
      }
    }

    .next-project {
      &-text {
        @include text-style(h1, $white);
        mix-blend-mode: difference;
      }
    }
  }

  @include responsive(T) {
    margin: 0 -#{$sm-margin + $md-margin * 2};

    &-next {
      &::after {
        left: 50vw;
      }
    }
  }
}
</style>
