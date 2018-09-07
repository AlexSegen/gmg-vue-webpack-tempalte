<template>
  <div id="app">

    <nav class="navbar navbar-default">
      <div class="container">
        <div class="navbar-header">
          <button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#bs-example-navbar-collapse-1">
            <span class="sr-only">Toggle navigation</span>
            <span class="icon-bar"></span>
            <span class="icon-bar"></span>
            <span class="icon-bar"></span>
          </button>
          <router-link class="navbar-brand" to="/"></router-link>
        </div>

        <div class="collapse navbar-collapse" id="bs-example-navbar-collapse-1">
          <ul class="nav navbar-nav">
            <li>
                <router-link to="/">Home</router-link>
            </li>
            <li>
                <router-link to="/elements">Web Elements</router-link>
            </li>
          </ul>
        </div>
      </div>
    </nav>

    <router-view/>

  </div>
</template>

<style lang="scss">
</style>
