<template>
  <footer
    class="footer"
    :class="{ [`footer-${type}`]: type }"
    :data-background-color="backgroundColor"
  >
    <div class="container">
      <nav>
        <ul>
          <li>
            <a href="https://www.google.com">
              Behnken
            </a>
          </li>
          <li>
            <a href="https:///www.bing.com">
              Blog
            </a>
          </li>
          <li>
            <a href="https://github.com/brunobehnken/website">
              Source Code
            </a>
          </li>
        </ul>
      </nav>
      <div class="copyright">
        &copy; {{ year }}, Made with ❤ by Bruno Behnken.
      </div>
    </div>
  </footer>
</template>
<script>
export default {
  props: {
    backgroundColor: String,
    type: String
  },
  data() {
    return {
      year: new Date().getFullYear()
    };
  }
};
</script>
<style></style>
