<template>
  <nav>
      <div class="nav-wrapper">
          <div class="left col s5">
              <!-- <ul>
                  <li>
                      <a href="#!" class="papis-menu">
                          <i class="material-icons">menu</i>
                      </a>
                  </li>
              </ul> -->
          </div>
          <div class="searchbar">
              <i class="material-icons">search</i>
              <input type="text" name="Search" class="searchtext z-depth-2" placeholder="Explore Papers" style="">
          </div>
          <div class="col l7">
              <ul class="right">
                  <li>
                      <a href="#!">
                          <i class="material-icons">more_vert</i>
                      </a>
                  </li>
              </ul>
          </div>
      </div>
    </nav>
</template>

<script>
export default {
  name: 'NavBar',
  data () {
    return {
      msg: 'Papis'
    }
  }
}
</script>


<style scoped>
</style>
