<template>
  <div class="about">
    <h1><i>Who is the man behind the camera?</i></h1>
    <hr/>
    <div class = "content-container">
    <div class= "column">
    <div class="item text">
    Aside from taking awesome photos, Eric is the loving father of a cute little two-year old girl, and is expecting another child very soon. He's been married to his supportive and energetic wife for several years now. Eric works as a Systems Administrator for Brigham Young University and knows anything and everything there is to know about computer and network systems!
    </div>
    <div class="item">
    <img src="../images/family3.jpg" height="200px">
    </div>
    </div>
    <div class="column">
    <div class="item">
    <img src="../images/image1.jpg" width = "448px" height="200px">
    </div>
    <div class="item text">
    "From a young age I was interested in photography. I noticed that if you get really close to something with a camera you can see details that you wouldn’t be able to see otherwise and a whole new world opens up. I would walk around a take close up pictures of anything I could find so I could find out what they looked like zoomed in. This is how my passion for photography started to grow and continues to grow as I find new angles to look at the world."
    </div>
    </div>
    <div class="column">
    <div class="item text">
    Eric loves to travel to new places and explore the world, you'll notice many of his sample shots are from different countries around the world!
    </div>
    <div class="item">
    <img src="../images/image3.jpg" width = "448px" height="200px">
    </div>
    </div>
    <div class="column">
    <div class="item">
    <img src="../images/image4.jpg" width = "450px" height="200px">
    </div>
    <div class="item">
    <img src="../images/image8.jpg" width = "450px" height="200px">
    </div>
    </div>



    </div>
  </div>
</template>

<script>
// @ is an alias to /src


export default {
  name: 'About',
  components: {

  }
}
</script>
<style>
.content-container{

width:900px;
justify-content:center;
align-items:center;
margin: 0 auto;

}

.column{
display:flex;
width:900px;

}
.item{
width:450px;
height:200px;
border:1px groove black;

}

</style>
