<template>
  <div class="Contact">
    <h1>Don't be a stranger, we'd love to hear from you!</h1> <hr/>
    <div class= "content-container2">

    <div class="column">
    <div class="object">
    <h3>Phone: (801) 663-4890</h3>
    <h3>Email: Eric@tingeyphoto.com</h3>
    <h3>Or look us up on Facebook or Instagram!</h3>
    </div>
    <div class="object">
    <img src="../images/family1.jpg" width ="400px">
    </div>
    <div class="object">
    <h3>Send us your thoughts!</h3>
    <form v-on:submit.prevent="addComment">
      <input v-model="addedName" placeholder="Name">
      <textarea v-model="addedComment"></textarea>
      <br/>
      <button type="submit">Send</button>
    </form>
    </div>
    </div>
    </div>
  </div>
</template>
<script>
// @ is an alias to /src


export default {
  name: 'Contact',
  components: {

  }
}
</script>
<style>
.content-container2{
width:900px;
margin:auto;
height:400px;
}
.object{
height:297px;
}
</style>
