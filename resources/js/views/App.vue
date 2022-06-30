<template>
  <div>
    <ul class="nav justify-content-center">
      <li class="nav-item">
        <router-link class="navbar-brand" :to="{ name: 'home' }">Boolpress</router-link>
      </li>
      <li class="nav-item">
        <router-link class="navbar-brand" :to="{ name: 'about' }">About</router-link>
      </li>
      <li class="nav-item">
        <router-link class="navbar-brand" :to="{ name: 'posts' }">Posts</router-link>
      </li>
    </ul>
    <router-view></router-view>
  </div>

</template>

<script>
export default {
  name: "App",
  data() {
    return {
      menu_items: [
        {
          route_name: 'home',
          route_text: 'Home'
        },
        {
          route_name: 'about',
          route_text: 'About'
        },
        {
          route_name: 'posts',
          route_text: 'Posts'
        },
      ]
    }
  }
}
</script>
