<template>
  <header>
    <nav>
      <div class="left" id="logo">Header Logo</div>
      <div class="right">
        <ul>
          <li><router-link to="/">Home</router-link></li>
          <li><router-link to="/about">About</router-link></li>
        </ul>
      </div>
    </nav>
    <div class="header-content">
      <div class="left">
        <h1>This website is awesome</h1>
        <p>
          This website has some subtext that goes here under the main title.
          It's a smaller font and the color is lower contrast.
        </p>
        <button>sign up</button>
      </div>
      <div class="right">
        <div class="image">
          <img alt="Vue logo" src="../assets/logo.png" />
        </div>
      </div>
    </div>
  </header>
</template>
<script>
export default {};
</script>
