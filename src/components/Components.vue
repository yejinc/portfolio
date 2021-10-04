<template>
  <!-- button components -->

  <div class="container">
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
