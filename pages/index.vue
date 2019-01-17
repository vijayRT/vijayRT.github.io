<template>
  <div>
    <div class="left">
      <img 
        src="/photo.jpg" 
        class="photo"
      >
    </div>
    <div class="right">
      <div class="name">
        VIJAY RAJASEKAR
        <div 
          class="subtitle" 
          title="and chatbots written in Python">
          I think I like Python. And chatbots.
        </div>
        <a
          href="https://github.com/vijayRT"
        >
          <img
            class="logos"
            src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png"
            height="50px"
          >
        </a>
        <a
          href="https://www.linkedin.com/in/vijayrajasekar96/"
        >
          <img
            class="logos"
            src="https://image.freepik.com/free-icon/linkedin-logo_318-50465.jpg"
            height="40px"
          >
        </a>
        <a
          href="https://twitter.com/CrowNoseFear"
        >
          <img
            class="logos"
            src="https://img.icons8.com/metro/50/000000/twitter.png"
            height="40px"
          >
        </a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  head: {
    title: 'Vijay Rajasekar'
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css?family=Barlow+Condensed');
.container {
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #383838;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}

.photo {
  margin-left: -10%;
  float: left;
  height: 100vh;
  filter: grayscale(100%);
}

.right {
  float: right;
}

.name {
  font-family: 'Barlow Condensed', sans-serif;
  font-size: 5em;
  position: absolute;
  top: 40%;
  left: 70%;
  transform: translate(-50%, -50%);
  text-align: center;
}
.logos {
  vertical-align: middle;
  margin-left: 5px;
}

a {
  text-decoration: none;
}

@media (max-width: 1000px) {
  .photo {
    margin-left: -40%;
  }

  .name {
    left: 80%;
  }
}
</style>
