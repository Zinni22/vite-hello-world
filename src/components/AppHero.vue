<script>
export default {
  data() {
    return {

        picture: 'https://miro.medium.com/max/1200/1*C8xdSMN_IkeXDsTLt6EACA.png',
    }
  }
}
</script>

<template>

    <div>
        <img :src="picture" alt="">

        <h2>
          Next Generation Frontend Tooling
        </h2>
    </div>
 
</template>

<style scoped>
div{
  position: relative;
}
h2{
  position: absolute;
  top:20px;
  left:50px;
  color: white;
}

</style>