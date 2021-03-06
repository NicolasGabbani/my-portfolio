<template>
  <div class="content">
    <div class="design-circle"></div>
    <h1>ma carrière</h1>
    <div class="sub-title">J'ai travaillé pour CareerBuilder pendant 6 ans.</div>
    <div class="separator small-separator" data-aos="zoom-in-up" data-aos-offset="100">
      <div class="bg-img" :style="{ backgroundImage: `url(${require(`@/images/lesjeudis.jpg`)})` }"></div>
      <div class="bg-white">
        <h2><a href="https://www.lesjeudis.com/" target="_blank">LesJeudis.com</a></h2>
        <div class="society">careerbuilder</div>
        <p>
          <span class="tag">RoR</span>
          <span class="tag">jQuery</span>
          <span class="tag">Responsive</span>
        </p>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Recusandae ratione nemo cum voluptas vitae, suscipit commodi dolorum hic maxime aperiam consectetur voluptate! Ut, ratione tenetur! Delectus deserunt alias ratione voluptatibus!</p>
        <h4>Missions :</h4>
        <ul>
          <li>Intégrateur et UI/UX designer</li>
          <li>Optimisation et simplification du code, maintenance des solutions et expertise design (UI et UX)</li>
        </ul>
      </div>
    </div>
    <div class="separator" data-aos="zoom-in-up" data-aos-offset="100">
      <div class="bg-img" :style="{ backgroundImage: `url(${require(`@/images/careerbuilder.png`)})` }"></div>
      <div class="bg-white">
        <h2><a href="https://www.careerbuilder.com/" target="_blank">careerbuilder.com</a></h2>
        <div class="society">careerbuilder</div>
        <p>
          <span class="tag">RoR</span>
          <span class="tag">jQuery</span>
          <span class="tag">Responsive</span>
        </p>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Recusandae ratione nemo cum voluptas vitae, suscipit commodi dolorum hic maxime aperiam consectetur voluptate! Ut, ratione tenetur! Delectus deserunt alias ratione voluptatibus!</p>
        <h4>Missions :</h4>
        <ul>
          <li>Intégrateur et UI/UX designer</li>
          <li>Optimisation et simplification du code, maintenance des solutions et expertise design (UI et UX)</li>
        </ul>
      </div>
    </div>
    <div class="separator" data-aos="zoom-in-up" data-aos-offset="100">
      <div class="bg-img" :style="{ backgroundImage: `url(${require(`@/images/jobmedic.jpg`)})` }"></div>
      <div class="bg-white">
        <h2><a href="https://www.jobmedic.co.uk/" target="_blank">jobmedic.co.uk</a></h2>
        <div class="society">careerbuilder</div>
        <p>
          <span class="tag">RoR</span>
          <span class="tag">jQuery</span>
          <span class="tag">Responsive</span>
        </p>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Recusandae ratione nemo cum voluptas vitae, suscipit commodi dolorum hic maxime aperiam consectetur voluptate! Ut, ratione tenetur! Delectus deserunt alias ratione voluptatibus!</p>
        <h4>Missions :</h4>
        <ul>
          <li>Intégrateur et UI/UX designer</li>
          <li>Optimisation et simplification du code, maintenance des solutions et expertise design (UI et UX)</li>
        </ul>
      </div>
    </div>
  </div>
</template>

<style lang="sass" scoped>
  .bg-img
    height: 350px
    width: 100%
    border-radius: 10px
    
    background-repeat: no-repeat
    background-size: cover
    background-position: center center
  .society
    color: grey
    text-transform: uppercase
    font-size: .8rem
    margin-bottom: 10px
  .bg-white
    background-color: var(--color-white)
    box-shadow: 0 0 25px 5px rgba(0,0,0,.4)

    width: 30vw
    margin: -300px auto 0 auto
    padding: 30px
    position: relative

    border-radius: 10px
    h4
      margin-bottom: 10px
    .tag
      margin-right: 4px 
      &:last-child
        margin-right: 0
</style>