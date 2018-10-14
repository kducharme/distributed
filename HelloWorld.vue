<template>
  <div class="content">
    <h1>I'm Kyle, a UX designer & developer that focuses on <span>b2b software, startups, and remote work.</span> I've helped ship products used by more than 30,000 businesses, and I'm currently working at TaxJar => a fully remote company building software that makes eCommerce easier for merchants and developers.</h1>
    <a href="https://dribbble.com/kducharme" target="blank">View my portfolio</a>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
h1, h2, h3, h4, p, a {
  font-family: 'Lato';
  // color: #13293D;
}

.content {
  width: 100vw;
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  text-align: center;

  h1 {
    padding: 0 15%;
    font-weight: 600;
    font-size: 20px;
    margin-bottom: 16px;
    line-height: 1.6;
    color: #6C7A86;
    margin-bottom: 100px;
  }

  span {
    color: #13293D;
    font-weight: 40px;
    opacity: 1!important;
    font-weight: 900;
  }

  a {
    color: #003bde;
    text-decoration: none;
    padding: 6px 12px;
    font-weight: 700;
  }

  a:hover {
      color: rgb(60, 110, 248);
  }

  a:active {
    background-color: #F0F0F0;
    border-radius: 5px;
  }
}

</style>
