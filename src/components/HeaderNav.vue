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
<style lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;500;700;900&display=swap');

body {
  font-family: 'Roboto', sans-serif;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
* {
  margin: 0;
  padding: 0;
}
header {
  padding: 1em 10em;
  background: #2c3e50;
  font-size: 18px;

  nav {
    display: flex;
    align-items: center;
    justify-content: space-between;
    #logo {
      font-size: 24px;
      font-weight: 900;
      color: #42b983;
    }
    a {
      font-weight: bold;
      color: white;
      text-decoration: none;
    }
    a.router-link-exact-active {
      color: #42b983;
    }
    ul {
      list-style-type: none;
      display: flex;
      gap: 1em;
    }
  }

  .header-content {
    padding: 6em 0;
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 1em;

    .left {
      text-align: left;
      color: white;
      display: flex;
      flex-direction: column;
      gap: 10px;
      h1 {
        font-size: 48px;
      }
      button {
        width: 80px;
        height: 40px;
      }
    }
    .right {
      flex-shrink: 0;
      width: 50%;
      .image {
        height: 215px;
        background: white;
      }
    }
  }
}
</style>
