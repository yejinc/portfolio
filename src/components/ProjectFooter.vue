<template>
  <div class="container">
    <div class="row">
      <div class="col-sm-4">
        <div class="project-footer">
          <div class="project-footer-links">
            <ul class="links-list">
              <li class="list-title">
                <h6>social links</h6>
              </li>
              <li class="list-item">
                <a href="#"> EMAIL </a>
              </li>
              <li class="list-item">
                <a href="#">INSTAGRAM </a>
              </li>
              <li class="list-item">
                <a href="#">DRIBBBLE </a>
              </li>
              <li class="list-item">
                <a href="#">MEDIUM </a>
              </li>
              <li class="list-item">
                <a href="#">LINKEDIN </a>
              </li>
            </ul>
          </div>

          <div class="project-footer-wave">
            <img
              src="@/assets/images/wave.svg"
              alt="Project footer wavy divider"
              aria-hidden="true"
            />
          </div>

          <div class="project-footer-captions">
            <ul class="captions-list">
              <li class="made-with">
                Made with lots of Kombucha🍹 and Love 💜
              </li>
              <li class="copyright">@2020 Yejin Cho ・ Self Coded</li>
            </ul>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'ProjectFooter'
}
</script>

<style lang="scss">
.project-footer {
  @include column-flex;
  margin: 0 -#{$sm-margin};
  height: 520px;
  overflow: hidden;
  text-align: center;
  background-color: $dutch-white;

  &-links {
    .links-list {
      margin-bottom: 30px;

      .list-title {
        margin-bottom: 24px;

        h6 {
          @include text-style(link, $grey-3);
        }
      }

      .list-item {
        margin-bottom: 24px;

        a {
          @include text-style(link, $dutch-white);
          mix-blend-mode: difference;
        }
      }
    }
  }

  &-wave {
    @include flex;
    width: 162px;
    height: 10px;
    margin-bottom: 30px;
    overflow: hidden;
    text-align: center;

    img {
      display: block;
      height: 100%;
      overflow: hidden;
      object-fit: cover;
    }
  }

  &-captions {
    .captions-list {
      .made-with,
      .copyright {
        @include text-style(caption, $grey-1);
      }
    }
  }
}
</style>
