<template>
  <div>
      <h2>Merhaba single file template  </h2>
      <p> Sunucu Durumu : {{ status }}  </p>
      <lamp-component></lamp-component>

  </div>
</template>

<script>
export default {
 data: function() {
        return {
            status: "Pasif"
        };
    } 
}
</script>

 <!-- scoped sadece bu componentte islemesi icin -->
<style scoped>
  div{
    border: 2 px solid #fbbd08
  }
</style>
