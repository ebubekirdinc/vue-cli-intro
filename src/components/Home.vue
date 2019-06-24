<template>
    <div>  
        <Lamp-Status v-for="lamp in 5"></Lamp-Status>
    </div>
</template>

<script>
    //home icerisinde lampStatusu kullanabilmek icin
    import LampStatus from "./LampStatus"
    export default {
        components: {
            "Lamp-Status": LampStatus
        }
    }
</script>

 <!-- scoped sadece bu componentte islemesi icin -->
<style scoped>
  div{
    border: 2 px solid red
  }
</style>
