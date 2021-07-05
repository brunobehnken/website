<template>
  <div>
    <div class="page-header clear-filter" filter-color="blue">
      <parallax
        class="page-header-image"
        style="background-color: #252733"
      >
      </parallax>
          <div class="container text-left">
            <div class="row justify-content-md-start">
              <div class="col-md-6 col-lg-6 section-text">
                <img class="img-behnken" src="img/behnken.png" alt="" />
              </div>
              <div class="col-md-6 col-lg-6 section-text">
                <div class="content-center brand">
                  <h1 class="h1-seo">Bruno Behnken</h1>
                  <h3>Software Engineer</h3>
              </div>
            </div>
          </div>
      </div>
    </div>
    <div class="section">
      <div class="container text-left">
        <div class="row justify-content-md-end">
          <div class="col-md-6 col-lg-6 section-text">
            <div class="col-12 section-text-col">
              <h3 class="title">
                Hello, I'm Bruno Behnken, a Software Engineer
                based in São Paulo City.
                <br><br>
                The language I mainly code with is Python,
                but I also like Javascript.<br>
                My focus is on the back-end.</h3>
            </div>
          </div>
          <div class="col-md-6 col-lg-6 section-image-div">
            <figure>
              <img src="img/setup.jpg" alt="" />
            </figure>
          </div>
        </div>
      </div>
    </div>

    <div class="section">
      <div class="container text-right">
        <div class="row justify-content-md-end">
          <div class="col-md-6 col-lg-6 section-image-div">
            <figure>
              <img src="img/python-code.jpg" alt="" />
            </figure>
          </div>
          <div class="col-md-6 col-lg-6 section-text">
            <div class="col-12 section-text-col">
              <h2 class="title">
                DevOps and Cloud-native
              </h2>
              <h4 class="section-description">
                I was born in the Cloud and have experience
                with AWS, specially with infrastructure as code
                and CI/CD.<br>
                I have also worked as a consultant for AWS.
              </h4>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class="section">
      <div class="container text-left">
        <div class="row justify-content-md-end">
          <div class="col-md-6 col-lg-6 section-text">
            <div class="col-12 section-text-col">
              <h2 class="title">
                Open-source
              </h2>
              <h4 class="section-description">
                I've been using Linux as my main OS for
                more than 10 years, my favorite distribution
                being Linux Mint.<br>
                I also try and find time to contribute
                to open-source projects on my GitHub.
              </h4>
            </div>
          </div>
          <div class="col-md-6 col-lg-6 section-image-div">
            <figure>
              <img src="img/git.jpg" alt=""/>
            </figure>
          </div>
        </div>
      </div>
    </div>

  </div>
</template>
<script>
import { Parallax } from '@/components';

export default {
  name: 'index',
  bodyClass: 'index-page',
  components: {
    Parallax,
  }
};
</script>
<style></style>
