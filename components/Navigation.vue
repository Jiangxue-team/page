<template>
  <div style="margin-bottom: 44px;margin-top: 44px">
    <nav class="navbar ">
      <div class="navbar-brand">
        <a class="navbar-item">
          <logofull />
        </a>

        <div class="navbar-burger burger" data-target="navMenubd-example">
          <span></span>
          <span></span>
          <span></span>
        </div>
      </div>

      <div id="navMenubd-example" class="navbar-menu navbar-end">
        <div class="navbar-item">
          <div class="navbar-item has-dropdown is-hoverable">
            <a class="navbar-link  is-active"><p>首页</p><span>Home</span></a>
            <!--
            <div class="navbar-dropdown ">
              <a class="navbar-item">Components</a>
              <hr class="navbar-divider">
              <div class="navbar-item">
                <div>
                  <p class="is-size-6-desktop">
                    <strong class="has-text-info">0.5.1</strong>
                  </p>
                  <small>
                    <a class="bd-view-all-versions" href="/versions">View all versions</a>
                  </small>
                </div>
              </div>
            </div>
            -->
          </div>
          <!-- 工程计划 -->
          <div class="navbar-item has-dropdown is-hoverable">
            <a class="navbar-link" ><p>工程计划</p><span>Engineering plan</span></a>
            <!--
            <div class="navbar-dropdown ">
              <a class="navbar-item">Components</a>
              <hr class="navbar-divider">
              <div class="navbar-item">
                <div>
                  <p class="is-size-6-desktop">
                    <strong class="has-text-info">0.5.1</strong>
                  </p>
                  <small>
                    <a class="bd-view-all-versions" href="/versions">View all versions</a>
                  </small>
                </div>
              </div>
            </div>
            -->
          </div>
          <!-- 研究方向 -->
          <div class="navbar-item has-dropdown is-hoverable">
            <a class="navbar-link" ><p>研究方向</p><span>Research direction</span></a>
            <!--
            <div class="navbar-dropdown ">
              <a class="navbar-item">Components</a>
              <hr class="navbar-divider">
              <div class="navbar-item">
                <div>
                  <p class="is-size-6-desktop">
                    <strong class="has-text-info">0.5.1</strong>
                  </p>
                  <small>
                    <a class="bd-view-all-versions" href="/versions">View all versions</a>
                  </small>
                </div>
              </div>
            </div>
            -->
          </div>
          <!-- 学术论文 -->
          <div class="navbar-item has-dropdown is-hoverable">
            <a class="navbar-link" ><p>学术论文</p><span>Academic paper</span></a>
            <!--
            <div class="navbar-dropdown ">
              <a class="navbar-item">Components</a>
              <hr class="navbar-divider">
              <div class="navbar-item">
                <div>
                  <p class="is-size-6-desktop">
                    <strong class="has-text-info">0.5.1</strong>
                  </p>
                  <small>
                    <a class="bd-view-all-versions" href="/versions">View all versions</a>
                  </small>
                </div>
              </div>
            </div>
            -->
          </div>
          <!-- 关于我们 -->
          <div class="navbar-item has-dropdown is-hoverable">
            <a class="navbar-link" ><p>关于我们</p><span>About us</span></a>
            <!--
            <div class="navbar-dropdown ">
              <a class="navbar-item">Components</a>
              <hr class="navbar-divider">
              <div class="navbar-item">
                <div>
                  <p class="is-size-6-desktop">
                    <strong class="has-text-info">0.5.1</strong>
                  </p>
                  <small>
                    <a class="bd-view-all-versions" href="/versions">View all versions</a>
                  </small>
                </div>
              </div>
            </div>
            -->
          </div>
        </div>
      </div>
    </nav>
  </div>
</template>

<script>
import Logofull from "~/static/logo-full";
export default {
  name: "Navigation",
  components: {
    Logofull
  },
  mounted() {
    // Get all "navbar-burger" elements
    const $navbarBurgers = Array.prototype.slice.call(document.querySelectorAll('.navbar-burger'), 0);
     // Add a click event on each of them
    $navbarBurgers.forEach( el => {
      el.addEventListener('click', () => {
        // Get the target from the "data-target" attribute
        const target = el.dataset.target;
        const $target = document.getElementById(target);
        // Toggle the "is-active" class on both the "navbar-burger" and the "navbar-menu"
        el.classList.toggle('is-active');
        $target.classList.toggle('is-active');
      });
    });
  }
}
</script>

<style scoped>

</style>
