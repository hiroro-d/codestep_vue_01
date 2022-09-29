<template>
  <div>
    <section id="about" class="MainContents mb_60">
      <li class="contents_wrapper"><h2 class="section_ttl">About</h2></li>
      <ul class="r_wrapper">
        <div>
        <li><img src="../assets/about.jpg" alt="" class="self_img"></li>
        </div>
        <div>
        <li class="text"><h3 class="content_ttl">KAKERU MIYAICHI</h3></li>
        <li class="text"><p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Sed pariatur id a alias consectetur in nobis sint accusamus at ex blanditiis aut autem, explicabo officiis dolores, nisi, tempora iure delectus!</p></li>
        </div>
      </ul>
    </section>
    <li class="contents_wrapper"><h2 class="section_ttl">Bicycle</h2></li>
    <section id="bicycle" class="MainContents mb_60">
      <div class="bicycle_content">
        <img src="../assets/bicycle1.jpg" alt="自転車1">
        <ul>
          <li><h3 class="content_ttl">自転車1</h3></li>
          <li class="text"><p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Sed pariatur id a alias consectetur in nobis sint accusamus at ex blanditiis aut autem, explicabo officiis dolores, nisi, tempora iure delectus!</p></li>
        </ul>
      </div>
      <div class="bicycle_content">
        <img src="../assets/bicycle2.jpg" alt="自転車2">
        <ul>
          <li><h3 class="content_ttl">自転車2</h3></li>
          <li class="text"><p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Sed pariatur id a alias consectetur in nobis sint accusamus at ex blanditiis aut autem, explicabo officiis dolores, nisi, tempora iure delectus!</p></li>
        </ul>
      </div>
      <div class="bicycle_content">
        <img src="../assets/bicycle3.jpg" alt="自転車3">
        <ul>
          <li><h3 class="content_ttl">自転車3</h3></li>
          <li class="text"><p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Sed pariatur id a alias consectetur in nobis sint accusamus at ex blanditiis aut autem, explicabo officiis dolores, nisi, tempora iure delectus!</p></li>
        </ul>
      </div>
    </section>
  </div>
</template>
<style scoped>

.MainContents {
  text-align: center;
}

#about .r_wrapper {
  padding: 0;
  margin: 0 30px;
}

#about img {
  width: 100px;
  border-radius: 50%;
}

.MainContents .text {
  text-align: left;
}

#bicycle {
  margin:0 30px;
}

.bicycle_content {
  margin-bottom: 30px;
}
</style>