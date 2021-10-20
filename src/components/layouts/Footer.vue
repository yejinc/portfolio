<template>
  <div class="container">
    <div class="row">
      <div class="col-sm-4">
        <div class="footer">
          <div class="footer-wave">
            <img
              src="@/assets/images/landing-footer-wave-bg.svg"
              alt="Wave graphic"
              aria-hidden="true"
            />
          </div>

          <div class="footer-contents">
            <div class="contents-header">
              <h3>Let’s chat</h3>
            </div>

            <div class="contents-footer">
              <ul class="contents-footer-links">
                <li class="links-item">
                  <a href="#">Email</a>
                </li>
                <li class="links-item">
                  <a href="#">LinkedIn</a>
                </li>
                <li class="links-item">
                  <a href="#">Medium</a>
                </li>
                <li class="links-item">
                  <a href="#">Dribbble</a>
                </li>
                <li class="links-item">
                  <a href="#">Twitter</a>
                </li>
              </ul>

              <ul class="contents-footer-captions">
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
  </div>
</template>

<script>
export default {
  name: 'Footer'
}
</script>

<style lang="scss">
.footer {
  margin: 0 -#{$sm-margin};
  overflow: hidden;
  background-color: $old-lavender;

  &-wave {
    position: relative;
    left: -30px;
    height: 60px;
    margin-top: 30px;

    img {
      display: block;
      height: 100%;
      object-fit: cover;
    }
  }

  &-contents {
    @include column-flex;
    background-color: $main-dark-purple;

    .contents-header {
      margin-top: 15px;

      h3 {
        @include text-style(h3, $ghost-white);
        mix-blend-mode: difference;
      }
    }

    .contents-footer {
      position: relative;
      z-index: $footer-index;
      margin-top: 40px;

      &::after {
        content: '';
        @include pos-center-x;
        top: 0;
        width: 760px;
        height: 760px;
        z-index: $footer-circle-bg-index;
        border-radius: 50%;
        background-color: $dutch-white;
      }

      &-links {
        margin-top: 40px;

        .links-item {
          margin-bottom: 12px;
          mix-blend-mode: difference;
          text-align: center;

          a {
            @include text-style(link, $ghost-white);
          }
        }
      }

      &-captions {
        text-align: center;
        padding: 12px 0 24px;

        .made-with {
          @include text-style(caption, $french-lilac);
        }

        .copyright {
          @include text-style(caption, $old-lavender);
        }
      }
    }
  }

  @include responsive(T) {
    margin: 0 -#{$sm-margin + $md-margin * 2};

    &-wave {
      margin-top: 50px;
    }

    &-contents {
      .contents-header {
        margin-top: 40px;

        h3 {
          @include text-style(desktop-h1);
        }
      }

      .contents-footer {
        margin-top: 60px;

        &::after {
          width: 1200px;
          height: 1200px;
        }

        &-links {
          margin-top: 52px;

          .links-item {
            margin-bottom: 18px;

            a {
              @include text-style(desktop-link);
            }
          }
        }

        &-captions {
          padding: 24px 0;

          .made-with,
          .copyright {
            @include text-style(desktop-caption);
          }

          .made-with {
            margin-bottom: 6px;
          }
        }
      }
    }
  }

  @include responsive(D) {
    margin: 0 -#{$sm-margin};
  }
}
</style>
