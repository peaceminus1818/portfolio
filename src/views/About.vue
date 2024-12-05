<template>
  <div style="margin-bottom: 80px;">
    <h1>Hello!</h1>

    <div class="paragraph">
      <div>
        I'm <strong>Chloe Ooi</strong>, currently a game development student pursuing a career as a game programmer.<br/>
        I'm excited to showcase some of the projects I've been working on.
      </div>

      <div style="margin-top: 20px;">I've worked on  <router-link to="/game-projects">games</router-link> using <strong>Unity</strong>
      , <router-link to="/other-projects">games</router-link> using <strong>Stencyl</strong>.
      </div>

      <div style="margin-top: 30px;">You can reach me at <a href="mailto:chloeooi1989@gmail.com">chloeooi1989@gmail.com</a> or <router-link to="/contact">through here</router-link>.</div>
    </div>

    <div class="photo">
      <img src="img/avatar.png" alt="Avatar of Me" /> 
    </div>

    <div style="clear:both"></div>

  </div>
</template>

<style scoped>
.paragraph {
  max-width: 700px;
  margin-bottom: 50px;
}

.photo {
  margin-top: -10px;
  text-align: center;
}

@media only screen and (min-width: 620px){
  .paragraph {
    float: left;
  }

  .photo {
    float: left;
    padding: 0px;
    padding-left: 100px;
  }
}

</style>