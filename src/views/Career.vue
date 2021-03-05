<template>
  <div class="content">
    <div class="design-circle"></div>
    <h1>ma carrière</h1>
    <div class="separator small-separator">
      <img class="img" :src="require(`@/images/lesjeudis.jpg`)" alt="LesJeudis.com">
      <div class="bg-white">
        <h2>LesJeudis.com</h2>
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
    <div class="separator">
      <img class="img" :src="require(`@/images/careerbuilder.png`)" alt="careerbuilder.com">
      <div class="bg-white">
        <h2>careerbuilder.com</h2>
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
  .img
    display: block
    width: 50vw
    border-radius: 10px
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