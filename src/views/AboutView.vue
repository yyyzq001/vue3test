<template>
  <div class="about">
    <h1>This is an about page</h1>
    <video width="640" height="360" controls>
      <source src="../assets/test.mp4" />
    </video>
    <audio controls>
      <!-- <source src="horse.ogg" /> -->
      <source src="../assets/test.mp3" />
      您的浏览器不支持 audio 元素。
    </audio>
  </div>
</template>

<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>
