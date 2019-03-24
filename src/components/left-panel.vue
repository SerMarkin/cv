<template>
    <div id="left_panel">
        <h3>Маркин Сергей Андреевич</h3>
        <img src="../assets/myPhoto.jpg" class="photo">
        <person-info/>
        <social-media/>
    </div>
</template>

<script>
  import persInf from './sub-left-panels/person-info'
  import socMedia from './sub-left-panels/social-media'
  export default {
    name: 'left-panel',
    components: {
      'person-info': persInf,
      'social-media': socMedia
    }
  }
</script>

<style scoped>
    #left_panel{
        height: auto;
        width: 20%;
        position: absolute;
        top: 0;
        left:0;
        background: #666666;
        color:white;
        font-family: Times, "Times New Roman", serif;
    }
    .photo{
        width: 90%;
        height: auto;
        margin-top: 10px;
    }
    h3{
        background: #3e3e3e;
        padding: 10px 0;
    }
</style>
