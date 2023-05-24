<template>
  <q-layout>
    <q-header id="header" class="bg-transparent text-black q-py-sm">
      <q-toolbar>
        <q-avatar>
        <img src="https://cdn.quasar.dev/logo-v2/svg/logo-mono-black.svg" style="width: 30px;">
      </q-avatar>
      <q-toolbar-title>Job Portal</q-toolbar-title>
      <q-space/>
      <q-tabs no-caps>
        <q-route-tab label="About" />
        <q-route-tab label="Blog" />
      </q-tabs>
      <q-btn rounded flat class="bg-grey-4" label="Contact Us"/>
    </q-toolbar>
    </q-header>
    <q-page-container>
      <q-page>
    <div id="hero-section" class="row q-py-md">
      <div class="col flex content-center items-center q-px-xl q-gutter-md">
        <div class="row">
          <div class="text-h2">Someone needs you in their team</div>
        </div>
        <div class="row text-grey-6 text-justify">
          Lorem ipsum, dolor sit amet consectetur adipisicing elit. Cupiditate sed, eaque culpa sunt autem facere, accusantium totam, ut debitis architecto quo in cum. Officiis, quas repellat, ullam eligendi non rerum hic provident laudantium perferendis animi exercitationem enim culpa veritatis officia blanditiis nemo quam odio sapiente laboriosam asperiores ipsam fugit velit
        </div>
        <div class="row q-gutter-md">
          <q-btn unelevated size="17px" class="bg-primary text-white" label="Post A Job"/>
          <q-btn flat size="17px" class="text-primary" label="Find a Job"/>
        </div>
      </div>
      <div class="col">
        <q-img id="hero-image" src="https://images.unsplash.com/photo-1522202176988-66273c2fd55f?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1171&q=80"/>
      </div>
    </div>
    <div id="cards">

    </div>
  </q-page>
    </q-page-container>
  </q-layout>
</template>
<script setup>
</script>
<style>
#header{
  margin: 10px 50px;
}
#hero-image{
  border-radius: 50px 0 0 50px;
  height: 650px;
}
</style>
<!-- /* eslint-disable */ -->
