<template>
  <div class=home>
      <headerWowok/>
      <heroWowok/>
      <women/>
      <instawowok/>
      <logopartner/>
      <foter/>

    
   
      </div>
</template>

<script>
// @ is an alias to /src
import headerWowok from '@/components/headerWowok.vue'
import heroWowok from '@/components/heroWowok.vue'
import women from '@/components/women.vue'
import instawowok from '@/components/instawowok.vue'
import logopartner from '@/components/logopartner.vue'
import foter from '@/components/foter.vue'



export default {
  name: 'Home',
  components: {
    headerWowok,
     heroWowok,
     women,
     instawowok,
     logopartner,
     foter
  }
};
</script>
