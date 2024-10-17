<template>

<HelloWorld msg="Here we go again"></HelloWorld>
<Trial/> 
<Trial/>
<h1>
  {{ "     fw   ".trim() }}
  {{ "AYOOochiLL" }}
  {{movie}}


</h1>

</template>

<script>
import HelloWorld from './components/HelloWorld.vue';
import Trial from './components/Trial.vue';

export default{

  name:'App',
  components:{
    HelloWorld,
    Trial
  }
}
</script>

