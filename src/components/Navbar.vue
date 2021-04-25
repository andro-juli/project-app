<template>
  <div class="">
    <nav>
      <div class="logo">
        <img src="../assets/logo1.svg" alt="" />
      </div>
      <div class="links">
        <a href="Home">Home</a>
        <a href="Blog">Blog</a>
        <a href="Features">Features</a>
        <a href="Pricing">Pricing</a>
        <a href="Documenttation">Documentation</a>
      </div>
      <div class="nav-social-icons">
        <div class="icon"><img src="../assets/f.svg" alt="" /></div>
        <div class="icon"><img src="../assets/kite.svg" alt="" /></div>
        <div class="icon"><img src="../assets/twitter.svg" alt="" /></div>
        <div class="icon"><img src="../assets/M.svg" alt="" /></div>
      </div>
      <button class="btn">Get Started</button>
    </nav>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
nav {
  display: flex;
  justify-content: space-around;
  padding: 1px;
  widows: 100%;
  height: 80px;
  margin-bottom: 19px;
  align-items: center;
}
.links {
  margin-right: 5rem;
}
.links a {
  font-family: Quicksand;
  font-style: normal;
  font-weight: 500;
  font-size: 12px;
  line-height: 15px;
  letter-spacing: 0.05em;
  color: #697ca6;
  text-shadow: 0px 0px 5px #e6e6e6;
  margin-right: 2.5rem;
  text-decoration: none;
}
.btn {
  font-family: Quicksand;
  font-style: normal;
  font-weight: bold;
  font-size: 13px;
  line-height: 16px;
  color: #3a79ff;
  width: 113px;
  height: 43px;
  background: #d2e1ff;
  border-radius: 2px;
}

.nav-social-icons {
  display: flex;
  align-items: center;
  margin-left: 10rem;
}

.icon {
  margin-right: 20px;
}
</style>
