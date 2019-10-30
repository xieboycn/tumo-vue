<template>
  <div class="page-container">
    <md-app md-waterfall md-mode="fixed">
      <md-app-toolbar class="md-primary">
        <div class="md-toolbar-row">
          <div class="md-toolbar-section-start">
            <a href="/">
              <md-avatar class="md-avatar-icon  md-primary">
                <md-icon>home</md-icon>
              </md-avatar>
            </a>
            <h3 class="md-title" style="flex: 1">Blog</h3>
          </div>
          <div class="md-toolbar-section-end">

            <a href="/about">
              <md-button class="md-icon-button">
                <md-icon>send</md-icon>
              </md-button>
            </a>
            <a href="/links">
              <md-button class="md-icon-button">
                <md-icon>link</md-icon>
              </md-button>
            </a>
            <a href="/archive">
              <md-button class="md-icon-button">
                <md-icon>archive</md-icon>
              </md-button>
            </a>
            <a href="/login">
              <md-button class="md-icon-button">
                <md-icon>account_circle</md-icon>
              </md-button>
            </a>
          </div>
        </div>
      </md-app-toolbar>
      <md-app-content>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Error quibusdam, non molestias et! Earum magnam,
          similique, quo recusandae placeat dicta asperiores modi sint ea repudiandae maxime? Quae non explicabo,
          neque.</p>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Error quibusdam, non molestias et! Earum magnam,
          similique, quo recusandae placeat dicta asperiores modi sint ea repudiandae maxime? Quae non explicabo,
          neque.</p>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Error quibusdam, non molestias et! Earum magnam,
          similique, quo recusandae placeat dicta asperiores modi sint ea repudiandae maxime? Quae non explicabo,
          neque.</p>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Error quibusdam, non molestias et! Earum magnam,
          similique, quo recusandae placeat dicta asperiores modi sint ea repudiandae maxime? Quae non explicabo,
          neque.</p>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Error quibusdam, non molestias et! Earum magnam,
          similique, quo recusandae placeat dicta asperiores modi sint ea repudiandae maxime? Quae non explicabo,
          neque.</p>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Error quibusdam, non molestias et! Earum magnam,
          similique, quo recusandae placeat dicta asperiores modi sint ea repudiandae maxime? Quae non explicabo,
          neque.</p>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Error quibusdam, non molestias et! Earum magnam,
          similique, quo recusandae placeat dicta asperiores modi sint ea repudiandae maxime? Quae non explicabo,
          neque.</p>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Error quibusdam, non molestias et! Earum magnam,
          similique, quo recusandae placeat dicta asperiores modi sint ea repudiandae maxime? Quae non explicabo,
          neque.</p>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Error quibusdam, non molestias et! Earum magnam,
          similique, quo recusandae placeat dicta asperiores modi sint ea repudiandae maxime? Quae non explicabo,
          neque.</p>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Error quibusdam, non molestias et! Earum magnam,
          similique, quo recusandae placeat dicta asperiores modi sint ea repudiandae maxime? Quae non explicabo,
          neque.</p>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Error quibusdam, non molestias et! Earum magnam,
          similique, quo recusandae placeat dicta asperiores modi sint ea repudiandae maxime? Quae non explicabo,
          neque.</p>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Error quibusdam, non molestias et! Earum magnam,
          similique, quo recusandae placeat dicta asperiores modi sint ea repudiandae maxime? Quae non explicabo,
          neque.</p>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Error quibusdam, non molestias et! Earum magnam,
          similique, quo recusandae placeat dicta asperiores modi sint ea repudiandae maxime? Quae non explicabo,
          neque.</p>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Error quibusdam, non molestias et! Earum magnam,
          similique, quo recusandae placeat dicta asperiores modi sint ea repudiandae maxime? Quae non explicabo,
          neque.</p>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Error quibusdam, non molestias et! Earum magnam,
          similique, quo recusandae placeat dicta asperiores modi sint ea repudiandae maxime? Quae non explicabo,
          neque.</p>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Error quibusdam, non molestias et! Earum magnam,
          similique, quo recusandae placeat dicta asperiores modi sint ea repudiandae maxime? Quae non explicabo,
          neque.</p>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Error quibusdam, non molestias et! Earum magnam,
          similique, quo recusandae placeat dicta asperiores modi sint ea repudiandae maxime? Quae non explicabo,
          neque.</p>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Error quibusdam, non molestias et! Earum magnam,
          similique, quo recusandae placeat dicta asperiores modi sint ea repudiandae maxime? Quae non explicabo,
          neque.</p>
        <footer class="md-primary main-footer">
          <div class="main-footer-container">
            <div class="main-footer-section">
              <a href="/about">About</a>
              <a href="/">Licence</a>
            </div>
            <div class="main-footer-section">
              <a href="https://github.com/xieboycn/tumo-vue">
                github
              </a>
            </div>
          </div>
        </footer>
      </md-app-content>
    </md-app>
  </div>
</template>

<script>
    export default {
        name: "frame",
    }
</script>

<style lang="scss" scoped>
  .main-footer {
    height: 96px;
    width: 100%;
    padding: 0 16px;
    position: relative;
    background-color: #eee;
  }

  .main-footer-container {
    max-width: 100%;
    height: 100%;
    display: flex;
    align-items: center;
    justify-content: space-between;
    transition: .3s cubic-bezier(.4, 0, .2, 1);
    transition-property: max-width;
  }

  .main-footer-section {
    position: relative;
  }

  .md-app {
    height: 100vh;
    border: 1px solid rgba(#000, .12);
  }
  .md-app-content{
    padding: 0;
  }
  // Demo purposes only
  .md-drawer {
    width: 230px;
    max-width: calc(100vw - 125px);
  }
</style>
