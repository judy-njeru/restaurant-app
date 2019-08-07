<template>
    <div>
        <div id="nav">
            <router-link to="/">Home</router-link> |
            <router-link to="/Restaurant">Restaurant</router-link> |
            <router-link to="/Products">Products</router-link> |
            <router-link to="/NewsLetter">NewsLetter</router-link> |
            <router-link to="/Contact">Contact</router-link> 
        </div>
        <!-- <router-view/> -->
    </div>
</template>

<script>
    export default {
       name: 'NavBar' 
    }
</script>

