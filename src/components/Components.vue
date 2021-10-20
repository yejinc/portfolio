<template>
  <div class="container">
    <ProjectFooter />

    <Footer />

    <!-- card components -->

    <!-- card component: link card -->

    <div class="row">
      <div class="col-sm-4 col-md-6">
        <div class="link-card">
          <a class="link-card-wrapper" href="#" aria-hidden="true">
            <div class="card-top">
              <div class="top-icon">
                <lottie-player
                  src="https://assets7.lottiefiles.com/packages/lf20_bpfzqkha.json"
                  background="transparent"
                  speed="1"
                  loop
                  autoplay
                ></lottie-player>
              </div>
              <h6 class="top-name">link name</h6>
            </div>
            <div class="card-contents">
              <p class="contents-text">
                Lorem ipsum dolor sit amet consectetur adipisicing elit.
                Officiis, tenetur.
              </p>
              <div class="contents-tags-sm sm-only">
                <strong class="links-tag tag-32">keyword</strong>
                <strong class="links-tag tag-32">keyword</strong>
              </div>

              <div class="contents-tags-md sm-hidden">
                <strong class="links-tag tag-40">keyword</strong>
                <strong class="links-tag tag-40">keyword</strong>
                <strong class="links-tag tag-40">keyword</strong>
              </div>
            </div>
          </a>
        </div>
      </div>
    </div>

    <!-- card component: user card -->

    <div class="row">
      <div class="col-sm-4">
        <div class="user-card-wrapper">
          <h4 class="user-card-name">Danielle, 21</h4>

          <div class="user-card">
            <div class="user-card-header">
              <div class="header-image">
                <img
                  src="@/assets/images/default/default-1.jpg"
                  alt="user image"
                />
              </div>

              <!-- keywords in mobile -->
              <div class="header-keywords-sm sm-only">
                <strong class="user-card-tag tag-32">#WorkinStudent</strong>
                <strong class="user-card-tag tag-32">#SelfAwareness</strong>
              </div>

              <!-- keywords in tablet & desktop -->

              <div class="header-keywords-md sm-hidden">
                <strong class="user-card-tag tag-40">#WorkinStudent</strong>
                <strong class="user-card-tag tag-40">#BurnOut</strong>
                <strong class="user-card-tag tag-40">#SelfAwareness</strong>
              </div>
            </div>

            <dl class="user-card-contents">
              <div class="contents-story">
                <dt class="contents-title">Story</dt>
                <dd class="contents-desc sm-hidden">
                  Danielle is a senior college student and also a freelancer.
                  She has been living with her hectic schedule for three years,
                  and one day she felt like she can’t do anything anymore. While
                  trying to figure out what is happening, Danielle started
                  researching physical/mental health-related information. She
                  then found it was burnout she was experiencing, and it was
                  because she didn’t much care about time management. So, she
                  decided to know when is her best time to work and rest by
                  measuring her energy level for a while.
                </dd>
                <dd class="contents-quote">
                  “With my busy schedule, I easily get exhausted, yet I have to
                  work to support my life and tuition. To figure out how my
                  energy level fluctuates, I want to start recording and see if
                  it has patterns. I heard that every person has their own
                  biological prime time, and I want to figure out what is mine.”
                </dd>
              </div>

              <div class="contents-case">
                <dt class="contents-title">case</dt>
                <dd class="contents-desc">
                  Widget centre ⟶ Setting presets ⟶ Check in ⟶ Start recording ⟶
                  Check out ⟶ Check today’s status
                </dd>
              </div>

              <div class="contents-flow">
                <dt class="contents-title">Flow</dt>
                <dd class="contents-desc">
                  Widget ⟶ Check in ⟶ Notification ⟶ Record ⟶ Check out ⟶
                  Home(status)
                </dd>
              </div>
            </dl>
          </div>
        </div>
      </div>
    </div>

    <!-- card component: project card -->

    <div class="row">
      <div class="col-sm-4 col-md-6 col-lg-7">
        <div class="project-card-image">
          <img src="@/assets/images/default/default-7.jpg" alt="Card image" />
        </div>
      </div>
      <div class="col-sm-4 col-md-6 col-lg-5">
        <div class="project-card-text-group">
          <h3 class="card-title">design ideas worth spreading</h3>
          <h3 class="card-subtitle">
            TEDxSeoul is a program of local, self-organized events that bring
            people to share a TED-like experience.
          </h3>
          <button
            type="button"
            class="card-button btn-outlined-ic-right btn-24 sm-only"
          >
            <span class="button-content">
              discover more
              <i class="ic-arrow-sm"></i>
            </span>
          </button>
          <button
            type="button"
            class="card-button btn-outlined-ic-right btn-32 md-only"
          >
            <span class="button-content">
              discover more
              <i class="ic-arrow-sm"></i>
            </span>
          </button>
          <button
            type="button"
            class="card-button btn-outlined-ic-right btn-40 lg-only"
          >
            <span class="button-content">
              discover more
              <i class="ic-arrow-sm"></i>
            </span>
          </button>
        </div>
      </div>
    </div>

    <!-- feature -->

    <div class="row">
      <div class="col-sm-4 col-md-3 col-lg-7">
        <div class="feature-prototype" aria-label="prototype of a feature">
          <iframe
            src="https://player.vimeo.com/video/152153054?h=fd9ee2ac5&autoplay=1&loop=1&autopause=0&muted=1&background=1"
            frameborder="0"
            allow="autoplay; fullscreen; picture-in-picture"
            allowfullscreen
            muted
            loop
          ></iframe>
        </div>
      </div>
      <div class="col-sm-4 col-md-3 col-lg-5">
        <div class="feature-texts">
          <h4 class="feature-texts-title">
            🏷 <br />Personalised content suggestion
          </h4>
          <p class="feature-texts-desc">
            Empower the users to take control over their preferences to get
            suitable movie relevant suggestions effortlessly.
          </p>
        </div>
      </div>
    </div>

    <!-- feature-reversed -->

    <div class="row">
      <div class="col-sm-4 col-md-3 col-lg-5">
        <div class="feature-reversed-texts">
          <h4 class="feature-reversed-texts-title">
            🏷 <br />Personalised content suggestion
          </h4>
          <p class="feature-reversed-texts-desc">
            Empower the users to take control over their preferences to get
            suitable movie relevant suggestions effortlessly.
          </p>
        </div>
      </div>
      <div class="col-sm-4 col-md-3 col-lg-7">
        <div class="feature-reversed-prototype">
          <iframe
            src="https://player.vimeo.com/video/152153054?h=fd9ee2ac5a&autoplay=1&loop=1&autopause=0&muted=1"
            frameborder="0"
            allow="autoplay; fullscreen; picture-in-picture"
            allowfullscreen
            allowautoplay
            muted
            loop
          ></iframe>
        </div>
      </div>
    </div>

    <!-- tag modules -->

    <div class="row">
      <div class="tags">
        <div class="tag-group-32">
          <strong class="user-card-tag tag-32">#WorkinStudent</strong>
          <strong class="links-tag tag-32">keyword</strong>
        </div>
        <div class="tag-group-40">
          <strong class="user-card-tag tag-40">#Developer</strong>
          <strong class="links-tag tag-40">keyword</strong>
        </div>
      </div>
    </div>

    <!-- button modules -->

    <div class="row">
      <div class="buttons">
        <div class="btn-group-24">
          <button type="button" class="btn-outlined-ic-right btn-24">
            <span class="button-content">
              button
              <i class="ic-arrow-sm"></i>
            </span>
          </button>
          <button type="button" class="btn-outlined btn-24">
            <span class="button-content">
              button
            </span>
          </button>
          <button type="button" class="btn-filled-ic-right btn-24">
            <span class="button-content">
              button 24 filled
              <i class="ic-arrow-sm"></i>
            </span>
          </button>
          <button type="button" class="btn-filled btn-24">
            <span class="button-content">
              button 24 filled
            </span>
          </button>
        </div>
        <div class="btn-group-32">
          <button type="button" class="btn-outlined-ic-right btn-32">
            <span class="button-content">
              button
              <i class="ic-arrow-sm"></i>
            </span>
          </button>
          <button type="button" class="btn-outlined btn-32">
            <span class="button-content">
              button
            </span>
          </button>
          <button type="button" class="btn-filled-ic-right btn-32">
            <span class="button-content">
              button 32 filled
              <i class="ic-arrow-sm"></i>
            </span>
          </button>
          <button type="button" class="btn-filled btn-32">
            <span class="button-content">
              button 32 filled
            </span>
          </button>
        </div>
        <div class="btn-group-40">
          <button type="button" class="btn-outlined-ic-right btn-40">
            <span class="button-content">
              button
              <i class="ic-arrow-sm"></i>
            </span>
          </button>
          <button type="button" class="btn-outlined btn-40">
            <span class="button-content">
              button
            </span>
          </button>
          <button type="button" class="btn-filled-ic-right btn-40">
            <span class="button-content">
              button 40 filled
              <i class="ic-arrow-sm"></i>
            </span>
          </button>
          <button type="button" class="btn-filled btn-40">
            <span class="button-content">
              button 40 filled
            </span>
          </button>
        </div>
      </div>
    </div>

    <!-- process components -->

    <!-- process component: basic-process -->

    <div class="row">
      <div class="col-sm-4 col-md-6 col-lg-4">
        <div class="basic-process-texts">
          <h2 class="basic-process-title">design system</h2>
          <p class="basic-process-desc">
            To speed up the design process and eliminate inconsistencies, I
            created a design system and actively used components to manage the
            project efficiently.
          </p>
        </div>
      </div>
      <div class="col-sm-4 col-md-6 col-lg-8">
        <div class="basic-process-image-group">
          <div class="basic-process-image">
            <img
              src="@/assets/images/default/default-6.jpg"
              alt="basic process image"
            />
          </div>
          <div class="basic-process-image">
            <img
              src="@/assets/images/default/default-3.jpg"
              alt="basic process image"
            />
          </div>
          <div class="basic-process-image">
            <img
              src="@/assets/images/default/default-2.jpg"
              alt="basic process image"
            />
          </div>
          <div class="basic-process-image">
            <img
              src="@/assets/images/default/default-1.jpg"
              alt="basic process image"
            />
          </div>
          <div class="basic-process-image">
            <img
              src="@/assets/images/default/default-5.jpg"
              alt="basic process image"
            />
          </div>
          <div class="basic-process-image">
            <img
              src="@/assets/images/default/default-8.jpg"
              alt="basic process image"
            />
          </div>
        </div>
      </div>
    </div>

    <!-- process component : sprint-process -->

    <!-- sprint-process component: mobile & tablet -->

    <div class="row lg-hidden">
      <div class="col-sm-4 col-md-2">
        <div class="sprint-process-titles">
          <h6 class="sprint-process-day">DAY 1 - DAY 2</h6>
          <h5 class="sprint-process-stage">
            Understand<br />
            —<br />
            Research
          </h5>
        </div>
      </div>
      <div class="col-sm-4 col-md-4">
        <div class="sprint-process-desc-wrapper">
          <p class="sprint-process-desc">
            Lorem ipsum, dolor sit amet consectetur adipisicing elit. Ducimus
            animi natus culpa et ullam nulla cum tempore enim voluptates
            recusandae, quasi, voluptas amet dignissimos ipsam expedita quis
            corrupti. Quod iste blanditiis, modi in soluta optio alias ea hic
            inventore eaque dolore dolorum, ipsum quas totam ullam neque
            laboriosam ipsam esse?
          </p>
        </div>
      </div>
      <div class="col-sm-4">
        <div class="sprint-process-image">
          <img src="@/assets/images/default/default-8.jpg" alt="" />
        </div>
        <div class="sprint-process-image">
          <img src="@/assets/images/default/default-2.jpg" alt="" />
        </div>
      </div>
    </div>

    <!-- sprint-process component: deesktop -->

    <div class="row lg-only">
      <div class="col-lg-4">
        <div class="sprint-process-titles">
          <h6 class="sprint-process-day">DAY 1 - DAY 2</h6>
          <h5 class="sprint-process-stage">
            Understand<br />
            —<br />
            Research
          </h5>
        </div>
        <div class="sprint-process-desc-wrapper">
          <p class="sprint-process-desc">
            Lorem ipsum, dolor sit amet consectetur adipisicing elit. Ducimus
            animi natus culpa et ullam nulla cum tempore enim voluptates
            recusandae, quasi, voluptas amet dignissimos ipsam expedita quis
            corrupti. Quod iste blanditiis, modi in soluta optio alias ea hic
            inventore eaque dolore dolorum, ipsum quas totam ullam neque
            laboriosam ipsam esse?
          </p>
        </div>
      </div>
      <div class="col-lg-8">
        <div class="sprint-process-image">
          <img src="@/assets/images/default/default-8.jpg" alt="" />
        </div>
        <div class="sprint-process-image">
          <img src="@/assets/images/default/default-2.jpg" alt="" />
        </div>
      </div>
    </div>

    <!-- text components -->

    <!-- text component: basic  -->

    <div class="row">
      <div class="col-sm-4 col-lg-4">
        <h2 class="text-basic-title">
          text title
        </h2>
      </div>
      <div class="col-sm-4 col-lg-8">
        <p class="text-basic-desc">
          Basic style text block description
        </p>
      </div>
    </div>

    <!-- text component: numbered list -->

    <div class="row">
      <div class="col-sm-4 col-lg-4">
        <h2 class="text-list-title">
          numberedlist title
        </h2>
      </div>
      <div class="col-sm-4 col-lg-8">
        <dl class="text-list-content">
          <div class="content-1">
            <dt class="content-1-title">
              <h4 class="title-number">01.</h4>
              <h4 class="title-text">title 1</h4>
            </dt>
            <dd class="content-1-desc">
              <p>
                St. agur blue cheese cheese and wine camembert de normandie.
                Hard cheese cheese triangles mozzarella cheese and biscuits
                airedale blue castello cauliflower cheese cheese and biscuits.
              </p>
            </dd>
          </div>
          <div class="content-2">
            <dt class="content-2-title">
              <h4 class="title-number">02.</h4>
              <h4 class="title-text">title 2</h4>
            </dt>
            <dd class="content-2-desc">
              <p>
                St. agur blue cheese cheese and wine camembert de normandie.
                Hard cheese cheese triangles mozzarella cheese and biscuits
                airedale blue castello cauliflower cheese cheese and biscuits.
              </p>
            </dd>
          </div>
          <div class="content-3">
            <dt class="content-3-title">
              <h4 class="title-number">03.</h4>
              <h4 class="title-text">title 3</h4>
            </dt>
            <dd class="content-3-desc">
              <p>
                St. agur blue cheese cheese and wine camembert de normandie.
                Hard cheese cheese triangles mozzarella cheese and biscuits
                airedale blue castello cauliflower cheese cheese and biscuits.
              </p>
            </dd>
          </div>
        </dl>
      </div>
    </div>

    <!-- text component: unordered list -->

    <div class="row">
      <div class="col-sm-4 col-lg-4">
        <h2 class="text-list-title">
          unordered list title
        </h2>
      </div>
      <div class="col-sm-4 col-lg-8">
        <dl class="text-list-content">
          <div class="content-1">
            <dt class="content-1-title">
              <h4 class="title-text">🌿 title 1</h4>
            </dt>
            <dd class="content-1-desc">
              <p>
                St. agur blue cheese cheese and wine camembert de normandie.
                Hard cheese cheese triangles mozzarella cheese and biscuits
                airedale blue castello cauliflower cheese cheese and biscuits.
              </p>
            </dd>
          </div>
          <div class="content-2">
            <dt class="content-2-title">
              <h4 class="title-text">💪 title 2</h4>
            </dt>
            <dd class="content-2-desc">
              <p>
                St. agur blue cheese cheese and wine camembert de normandie.
                Hard cheese cheese triangles mozzarella cheese and biscuits
                airedale blue castello cauliflower cheese cheese and biscuits.
              </p>
            </dd>
          </div>
          <div class="content-3">
            <dt class="content-3-title">
              <h4 class="title-text">👾 title 3</h4>
            </dt>
            <dd class="content-3-desc">
              <p>
                St. agur blue cheese cheese and wine camembert de normandie.
                Hard cheese cheese triangles mozzarella cheese and biscuits
                airedale blue castello cauliflower cheese cheese and biscuits.
              </p>
            </dd>
          </div>
        </dl>
      </div>
    </div>

    <!-- image list component -->

    <div class="row">
      <div class="col-sm-4 col-lg-8">
        <div class="image-list">
          <div class="list-image-bg">
            <div class="list-image">
              <img
                src="@/assets/images/default/default-5.jpg"
                alt="List image"
              />
            </div>
          </div>
          <div class="list-text">
            <h4 class="list-text-title">image list</h4>
            <p class="list-text-desc">
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Quasi
              vero tempora, aspernatur pariatur placeat laudantium, reiciendis
              minima nisi nam officia odit sapiente voluptas dolorem eligendi
              aperiam? Tempore voluptatum eligendi voluptas?
            </p>
          </div>
        </div>
      </div>
    </div>

    <!-- hmw component-->

    <div class="row">
      <div class="col-sm-4">
        <div class="hmw">
          <h4 class="hmw-text">
            How might we go to beach and diive into the water?
          </h4>
        </div>
      </div>
    </div>

    <!-- introduction component -->

    <div class="row">
      <div class="col-md-1 md-only" aria-hidden="true">
        <div class="blank-column"></div>
      </div>
      <div class="col-sm-4 col-md-4 col-lg-4">
        <div class="intro-logo">
          <img src="@/assets/images/default/default-3.jpg" alt="" />
        </div>
      </div>
      <div class="col-md-1 md-only" aria-hidden="true">
        <div class="blank-column"></div>
      </div>
      <div class="col-md-1 md-only" aria-hidden="true">
        <div class="blank-column"></div>
      </div>
      <div class="col-sm-4 col-md-4 col-lg-8">
        <h3 class="intro-text-title">
          BMW is a German multinational company that produces luxury vehicles
          and motorcycles.
        </h3>

        <dl class="intro-list">
          <div class="list-item">
            <dt>ROLE</dt>
            <dd>Brand Management Intern</dd>
          </div>
          <div class="list-item">
            <dt>DURATION</dt>
            <dd>July - December 2017</dd>
          </div>
          <div class="list-item">
            <dt>TAG</dt>
            <dd>Digital Product, Brand Management, Marketing</dd>
          </div>
          <div class="list-item">
            <dt>WEBSITE</dt>
            <dd><a href="http://www.bmw.co.kr">http://www.bmw.co.kr</a></dd>
          </div>
        </dl>
      </div>
      <div class="col-md-1 md-only" aria-hidden="true">
        <div class="blank-column"></div>
      </div>
    </div>
  </div>
</template>

<script>
import Footer from './Footer.vue'
import ProjectFooter from './ProjectFooter.vue'

export default {
  name: 'Components',

  components: {
    Footer,
    ProjectFooter
  }
}
</script>

<style lang="scss">
.container {
  background-color: $main-dark-purple;
}

.row {
  margin-bottom: 80px;
}

.buttons {
  @include column-flex(start);
  gap: 20px;
  width: 100%;
  background-color: $old-lavender;
  /* background-image: url('https://images.unsplash.com/photo-1546026423-cc4642628d2b?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxzZWFyY2h8NTl8fHVuZGVyd2F0ZXJ8ZW58MHx8MHx8&auto=format&fit=crop&w=800&q=60');
  background-size: cover;
  background-repeat: no-repeat; */
}
</style>
