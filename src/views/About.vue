<template>
  <div class="container">
    <div class='w-full'>
      <h1 class='pt-4 text-2xl font-bold'>About CoronaTracker</h1>
      <p class='pt-4'>CORONATRACKER.com is a community-based project powered by over 460 volunteers from across the globe, ranging from data scientists, medical professionals, UI/UX designers, fullstack developers, to the general public.</p>

      <p class='pt-4'>It acts as a portal for the public to keep track of the latest news development about the 2019-nCov, alongside collecting data for further analysis.

      All the contents are handpicked, filtered, and curated by volunteers to our best extent to ensure that sources are reliable with minimal hoaxes and fake news, in the best benefit of the public. Natural Language Processing (NLP) is used to analyze trending content and identify meaningful topics over various news sources and social media platforms prior to being verified by our team.
      </p>

<p class='pt-4'>CORONATRACKER.com also aims to gather data for in-depth analysis (e.g. time series to monitor the growth, spread of the virus) and localized news (e.g. news related to Malaysia, or KL only).The platform is vital for information consolidation, and all gathered information is open to use for the public.This is a 100% open source project, all information and publishable data are available on Github as well. Everyone is welcomed to contribute through our telegram channel.</p>

<p class='pt-4'>Our team of data scientists use OSEMN framework to collect, clean, explore, model, and run their own analysis. For ease of public understanding, it is presented using graphic visualizations and dashboards. Through the data obtained, we hope to build machine learning models very soon.</p>

<p class='pt-4'>We were inspired by the Coronavirus Outbreak Map by John Hopkins University that was very informative. We also recognised the difficulty to gather data for in-depth analysis through various other sources of scattered data on different news portals as well as in different languages.</p>

<p class='pt-4 pb-4'>Works started on the 25th of January, the first day of the Lunar New Year. Our team has been working relentlessly to make this a success, and launched officially on the 27th of January.</p> 

<em class='pt-4'>We aim to use technology and make information more accessible, gather talented people all around the world to win the fight!</em>
    </div>

    <div class='w-full'>
      <h2 class='pt-4 text-2xl font-bold mt-4 pb-2'>Heroes behind CoronaTracker</h2>
      <div class="flex flex-wrap -mb-4">
        <div class="w-full md:w-1/4 mb-4 hero">
          <img src="../assets/image/lau_cher_han.jpg" alt="Dr. Lau Cher Han" />
          <div class="mt-4 font-bold">Project lead</div>
          <div>Dr. Lau Cher Han</div>
          <div>(<a class='underline' href='https://www.linkedin.com/in/drhanlau/' target="_blank">LinkedIn</a>)</div>
        </div>
        <div class="w-full md:w-1/4 mb-4 hero">
          <img src="../assets/image/hafeez_nazri.jpg" alt="Hafeez Nazri" />
          <div class="mt-4 font-bold">Lead data scientist</div>
          <div class="">Hafeez Nazri</div>
          <div>(<a class='underline' href='https://www.linkedin.com/in/hafeeznazri/' target="_blank">LinkedIn</a>)</div>
        </div>
        <div class="w-full md:w-1/4 mb-4 hero">
          <img src="../assets/image/tan_wei_seng.png" alt="Tan Wei Seng" />
          <div class="mt-4 font-bold">Lead frontend engineer</div>
          <div>Tan Wei Seng</div>
          <div>(<a class='underline' href='https://www.linkedin.com/in/wei-seng-tan-304ba78a/' target="_blank">LinkedIn</a>)</div>
        </div>
        <div class="w-full md:w-1/4 mb-4 hero">
          <img src="../assets/image/shian.jpg" alt="Shian Poon" />
          <div class="mt-4 font-bold">Lead mobile developer</div>
          <div>Poon Chee Him/Shian</div>
          <div>(<a class='underline' href='https://www.linkedin.com/in/poon-cheehim/' target="_blank">LinkedIn</a>)</div>
        </div>
      </div>

      <a
          class="my-6 mx-auto text-center block text-2xl underline"
          href="https://docs.google.com/spreadsheets/d/1cG1UmEa-0IUetdKzYsMKXpypGFWoO88eTzadvN4NS5Y/edit#gid=0"
          target="_blank">
        And many more!!
      </a>
    </div>
  </div>
</template>
<script>
  export default {
  metaInfo: {
    title: 'About',
  },
}
</script>
<style scoped>
  .hero img {
    height: 200px;
    margin: 0 auto;
  }
  .hero > div {
    text-align: center;
  }
</style>