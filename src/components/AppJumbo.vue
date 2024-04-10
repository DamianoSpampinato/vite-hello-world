<script>
import AppTitle from './AppTitle.vue';

    export default {
        name: 'AppJumbo',
    
		components: {
      AppTitle,
    
		}
       
    }
</script>

<template>
    <div>
        <AppTitle></AppTitle>
    </div>
</template>


<style>
    div{
        width: 600px;
        margin: 0 auto;
        height: 500px;
        background-image: url('../assets/Damiano.png');
        background-position: center;
        background-repeat: no-repeat;
        display: flex;
        justify-content: center;
        align-items: center;
        color: yellow;
    }
</style>