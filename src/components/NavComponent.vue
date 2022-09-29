<template>
  <div>
    <header id="header" class="wrapper">
      <a href="index.html"><img src="../assets/logo.svg" alt="Profile"></a>
      <ul>
        <a href="#about"><li>About</li></a>
        <a href="#bicycle"><li>Bicycle</li></a>
      </ul>
    </header>
  </div>
</template>

<style scoped>
  #header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin: 0 20px;
    padding: 7px;
  }

  #header a {
    text-decoration: none;
  }

  #header img {
    width: 120px;
    height: auto;
  }

  #header ul {
    display: flex;
    gap: 30px;
  }

  #header li {
    font-size: 0.9rem;
    color: #24292e;
    cursor: pointer;
  }

  #header li:hover {
    opacity: .7;
  }
</style>