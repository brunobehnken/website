<template>
  <div>
    <div class="section" style="">
      <div class="container text-center">
        <div class="row justify-content-md-end">
          <div class="col-12 section-text">
            <h1 class="title">
              Thanks for coming!<br>
              This page is still under construction!
            </h1>
          </div>
        </div>
        <div class="row justify-content-md-center">
          <div class="col-12">
            <img src="img/under_construction.jpg" alt="" style="max-width: 80%;">
          </div>
        </div>
        <div class="row justify-content-md-end">
          <div class="col-12 section-text">
            <n-button type="primary" simple style="margin: 50px 0; border-color: #f96332" v-on:click="go_back()">
              <span class="title" style="color: #FFFFFF; font-size: 20px">
                Take me back!
              </span>
            </n-button>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import {Button} from "@/components";
import router from "@/router";

export default {
  name: "Blog",
  bodyClass: 'blog-page',
  components: {
    [Button.name]: Button,
  },
  methods: {
    go_back() {
      router.go(-1)
    }
  }
}
</script>

<style scoped>

</style>