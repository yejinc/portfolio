<template>
  <div class="container">
    <div class="row">
      <div class="col-sm-4">
        <div class="project-nav">
          <button class="project-nav-previous lg-only">
            <div class="previous-caption">
              <i class="ic-arrow-md" aria-hidden="true" />
              <h3 class="previous-caption-text">previous</h3>
            </div>
            <div class="previous-project">
              <h1 class="previous-project-text">tedxseoul</h1>
            </div>
          </button>

          <button class="project-nav-next">
            <div class="next-caption">
              <h3 class="next-caption-text">next</h3>
              <i class="ic-arrow-md" aria-hidden="true" />
            </div>
            <div class="next-project">
              <h1 class="next-project-text">golden</h1>
            </div>
          </button>
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
  $next-bg-circle-color: $icterine;
  $previous-bg-circle-color: $dark-sky-blue;

  @include column-flex;
  margin: 0 -#{$sm-margin};
  overflow: hidden;
  background-color: $black;

  &-next {
    @include column-flex;
    position: relative;
    z-index: $footer-index;
    width: 100%;
    height: 314px;

    &::after {
      content: '';
      @include pos-center-y;
      left: 50vw;
      width: 600px;
      height: 600px;
      z-index: $footer-circle-bg-index;
      border-radius: 50%;
      background-color: rgba($next-bg-circle-color, 0.7);
      transition: all 450ms cubic-bezier(0.075, 0.82, 0.165, 1);
    }

    &:active {
      &::after {
        left: 40vw;
      }
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
      height: 300px;

      &::after {
        left: 55vw;
      }

      &:active {
        &::after {
          left: 45vw;
        }
      }
    }
  }

  @include responsive(D) {
    @include flex(between);
    flex-direction: row;
    margin: 0 -#{$sm-margin};
    padding: 0 $lg-unit + $gutter;

    &-previous {
      @include column-flex(center, start);
      position: relative;
      z-index: $footer-index;
      height: 300px;
      width: 100%;

      &::after {
        content: '';
        @include pos-center-y;
        right: 35vw;
        width: 600px;
        height: 600px;
        z-index: $footer-circle-bg-index;
        border-radius: 50%;
        background-color: rgba($previous-bg-circle-color, 0.7);
        transition: all 450ms cubic-bezier(0.075, 0.82, 0.165, 1);
      }

      &:hover {
        &::after {
          right: 25vw;
        }
      }

      .previous-caption {
        @include flex;
        margin-bottom: 30px;

        &-text {
          @include text-style(h3-sub, $main-coral);
          margin-left: 32px;
          text-transform: capitalize;
          mix-blend-mode: difference;
        }

        .ic-arrow-md {
          display: block;
          font-size: 30px;
          mix-blend-mode: difference;
          color: $main-cambridge-blue;
          transform: rotate(90deg);
        }
      }

      .previous-project {
        &-text {
          @include text-style(h1, $white);
          mix-blend-mode: difference;
        }
      }
    }

    &-next {
      @include column-flex(center, end);

      &::after {
        left: 35vw;
        transition: all 450ms cubic-bezier(0.075, 0.82, 0.165, 1);
      }

      &:hover {
        &::after {
          left: 25vw;
        }
      }
    }
  }
}
</style>
