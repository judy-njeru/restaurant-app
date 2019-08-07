<template>
    <div>
        <div id="nav">
            <b-container>
                <b-row align-h="between">
                    <b-col cols="2">
                        <router-link to="/">Home</router-link> 
                    </b-col>
                    <b-col cols="2"> 
                        <router-link to="/Restaurant">Restaurant</router-link> 
                    </b-col>
                    <b-col cols="2"> 
                        <router-link to="/Products">Products</router-link> 
                    </b-col>
                    <b-col cols="2"> 
                        <router-link to="/NewsLetter">NewsLetter</router-link> 
                    </b-col>
                    <b-col cols="2"> 
                        <router-link to="/Contact">Contact</router-link> 
                    </b-col>
                </b-row>
            </b-container>
            <!-- <router-link to="/">Home</router-link> |
            <router-link to="/Restaurant">Restaurant</router-link> |
            <router-link to="/Products">Products</router-link> |
            <router-link to="/NewsLetter">NewsLetter</router-link> |
            <router-link to="/Contact">Contact</router-link>  -->
        </div>
        <!-- <router-view/> -->
    </div>
</template>

<script>
    export default {
       name: 'NavBar' 
    }
</script>

