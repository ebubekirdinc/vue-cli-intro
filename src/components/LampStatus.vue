<template>
  <div  > 
    <p> Lamba Durumu : {{ status }} </p>
    <button @click="OpenLamp">Lambayi Ac/Kapa</button>
  </div>
</template>

<script>
export default {
    data: function() {
        return {
            status: "Kapali"
        };
    },
    methods:{
        OpenLamp(){
            this.status="Acik...";
        }
    }
}
</script>

<style>
 
</style>
