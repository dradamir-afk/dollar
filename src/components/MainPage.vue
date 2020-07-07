<template>
    <div class="container">
        <Sidebar></Sidebar>
    </div>
</template>

<script>
import Sidebar from '../components/Sidebar.vue'
export default {
    components:{
        Sidebar
    }
}
</script>

<style scoped>
.container{
    width: 100%;
    height: 100vh;
    /* background-color: rgb(255, 255, 255); */
}
</style>