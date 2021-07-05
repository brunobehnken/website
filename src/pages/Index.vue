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
                  <!-- todo place this img on the left side of the same line as the text -->
                  <h1 class="h1-seo">Bruno Behnken</h1>
                  <h3>Software Engineer</h3>
              </div>
            </div>
          </div>
<!--        <div class="content-center brand">-->
<!--          &lt;!&ndash; todo place this img on the left side of the same line as the text &ndash;&gt;-->
<!--          <h1 class="h1-seo">Bruno Behnken</h1>-->
<!--          <h3>Software Engineer</h3>-->
<!--        </div>-->
<!--        </div>-->
<!--        <h6 class="category category-absolute">-->
<!--          Designed by-->
<!--          <a href="http://invisionapp.com/" target="_blank">-->
<!--            <img src="img/invision-white-slim.png" class="invision-logo" /> </a-->
<!--          >. Coded by-->
<!--          <a href="https://www.creative-tim.com" target="_blank">-->
<!--            <img-->
<!--              src="img/creative-tim-white-slim2.png"-->
<!--              class="creative-tim-logo"-->
<!--            /> </a-->
<!--          >.-->
<!--        </h6>-->
      </div>
    </div>
<!--    <div class="main">-->
<!--      <div class="section section-images">-->
<!--        <div class="container">-->
<!--          <div class="row">-->
<!--            <div class="col-md-12">-->
<!--              <div class="hero-images-container">-->
<!--                <img src="img/hero-image-1.png" alt="" />-->
<!--              </div>-->
<!--              <div class="hero-images-container-1">-->
<!--                <img src="img/hero-image-2.png" alt="" />-->
<!--              </div>-->
<!--              <div class="hero-images-container-2">-->
<!--                <img src="img/hero-image-3.png" alt="" />-->
<!--              </div>-->
<!--            </div>-->
<!--          </div>-->
<!--        </div>-->
<!--      </div>-->
<!--    </div>-->
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
import BasicElements from './components/BasicElementsSection';
import Navigation from './components/Navigation';
import TabsSection from './components/Tabs';
import ProgressPagination from './components/ProgressPagination';
import Notifications from './components/Notifications';
import Typography from './components/Typography';
import JavascriptComponents from './components/JavascriptComponents';
import CarouselSection from './components/CarouselSection';
import NucleoIconsSection from './components/NucleoIconsSection';
import SignupForm from './components/SignupForm';
import ExamplesSection from './components/ExamplesSection';
import DownloadSection from './components/DownloadSection';

export default {
  name: 'index',
  bodyClass: 'index-page',
  components: {
    Parallax,
  }
};
</script>
<style></style>
