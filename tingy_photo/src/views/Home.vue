<template>
  <div class="home">
  <div class = "header"><h2>"Capturing life's greatest moments..."</h2>
  </div>
    <img alt="Tingey Fam" src="../images/family2.jpg" height = "450px">

    <hr/>
    <h3>Welcome to Tingey Photography!<br/> We're seasoned, prepared, and excited to help with all of your photography needs!
    </h3>
    <div class= "offering">
    Let us help you with...
    <ul>
    <li>Wedding Receptions</li>
     <li>Sporting Events</li>
     <li>Announcements</li>
     <li>Family Photos</li>
     <li>Graduations</li>
     <li>You name it!</li>
     </ul>
</div>
  </div>
</template>

<script>
// @ is an alias to /src


export default {
  name: 'Home',
  components: {

  }
}
</script>

<style>
.header{
  font-style: italic;
  border: 2px grooved;
  font-size: 30px;
  margin-bottom: -25px;
  margin-top:-25px;
}

.offering{
text-align:center;
padding:10px;
align-items:center;
display:flex;
justify-content:center;
margin: auto 0;
}
</style>
