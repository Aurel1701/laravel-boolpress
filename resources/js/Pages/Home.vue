<template>
    <div>
        <div class="p-5 bg-light">
            <div class="container">
                <h1 class="display-3">Boolpress</h1>
                <p class="lead">welcome</p>
                <hr class="my-2">
                <p>More info</p>
                <p class="lead">
                    <a class="btn btn-lg" href="Jumbo action link" role="button">Jumbo action name</a>
                </p>
            </div>
        </div>
    </div>
</template>

<script>
import Axios from 'axios'

export default {
    name: "Home",

    /*  data() {
         return {
             posts: ''
         }
 
     },
     methods() {
 
     },
        mounted() {
           Axios.get('./api/posts')
               .then(response => {
                   const posts = response.data.posts
                   this.posts = posts.slice(),
               })
       }*/

}
</script>