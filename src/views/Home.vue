<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <!--<HelloWorld msg="Welcome to Your Vue.js + TypeScript App"/>-->
    <ToDo />
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';
import ToDo from '@/components/ToDo.ts'; // @ is an alias to /src

@Component({
  components: {
    ToDo,
  },
})
export default class Home extends Vue {}
</script>
