<script>
import { RouterLink, RouterView } from 'vue-router'
import HeaderView from "./components/Header.vue";
import HomeBody from "./components/HomeBody.vue"
export default {
    components: {
        HeaderView,
        HomeBody
    }
  }

</script>


<template>
    <div>
        <HeaderView />
        <div class="downView">
            <RouterView />
        </div>
    </div>
 
</template>


<style lang="scss" scoped>
    .downView{
        display: flex;
        justify-content: center;
        padding: 70px;
        background-color: #cfcece;
    }
</style>
