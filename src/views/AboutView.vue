<template>
  <div class="about">
    <h2>Some random information.</h2>
    <div class="content">
      <div class="card">
        <div class="square"></div>
        <p>
          Some random information.Some random information.Some random
          information.
        </p>
      </div>
      <div class="card">
        <div class="square"></div>
        <p>
          Some random information.Some random information.Some random
          information.
        </p>
      </div>
      <div class="card">
        <div class="square"></div>
        <p>
          Some random information.Some random information.Some random
          information.
        </p>
      </div>
      <div class="card">
        <div class="square"></div>
        <p>
          Some random information.Some random information.Some random
          information.
        </p>
      </div>
    </div>
  </div>
</template>
<style lang="scss">
.about {
  padding: 3em 13em;
  display: flex;
  flex-direction: column;
  align-items: center;
  .content {
    display: flex;
    .card {
      padding: 2em;
      .square {
        border: 4px solid blue;
        border-radius: 20px;
        width: 160px;
        height: 160px;
      }
    }
  }
}
</style>
