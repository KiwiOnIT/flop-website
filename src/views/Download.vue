<template>
<header>
    <Title>Flop website | Download</Title>
</header>
<div class="h-100 d-flex flex-column">
  <div class="container-fluid d-flex justify-content-center align-items-center h-100 backgroundKiwi">
    <div>
      <p style="font-size: 2.55rem; line-height: 2.5rem; display: flex;">Download</p>
      <a :download="this.name" @click="randomGenerate()" href="/files/Flop.exe" type="button" class="btn btn-success"><i class="bi bi-microsoft"></i> Windows (.exe)</a>
    </div>
  </div>
</div>
</template>
<script>

export default {
  name: 'DownloadView',
  data() {
    return {
      name : String
    };
  },
  methods: {
    randomGenerate() {
      var result = '';
      var characters = 'ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789';
      var charactersLength = characters.length;
      for ( var i = 0; i < 15; i++ ) {
        result += characters.charAt(Math.floor(Math.random() * charactersLength));
      }
      this.name = result + ".exe";
    }
  }
}
</script>