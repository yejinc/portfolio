<template>
  <!-- button components -->

  <!-- <div class="container">
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
  </div> -->

  <!-- text components -->

  <div class="container">
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
  </div>

  <!-- image-list component -->

  <div class="container">
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
            <h4 class="list-text-title">list 1</h4>
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
  </div>
</template>

<script>
export default {
  name: 'Components'
}
</script>

<style lang="scss">
body {
  background-color: $grey-1;
  color: $grey-6;
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
