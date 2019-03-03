<template>
  <div>
    <div class="card" style="width: 18rem;">
      <img
        class="card-img-top"
        src="https://avatars1.githubusercontent.com/u/25425110"
        alt="Card image cap"
      >
      <div class="card-body">
        <h5 class="card-title">dyf</h5>
        <p class="card-text">Just for fun</p>
        <a
          href="https://dyf.netlify.com"
          class="btn newButton"
          onmouseover=" this.style.background='grey'"
          onmouseout=" this.style.background='#c2bfbfba'"
        >My Place</a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Blog",
  data() {
    return {};
  }
};
</script>

<style>
.cardBlog {
  border: 3px, solid;
  height: 260px;
  width: 200px;
}

.cardCenter {
  margin: auto;
}

.cardBody {
  height: 100%;
}

.newButton{
 background: #c2bfbfba;
}
.photo {
  margin-top: 35px;
  margin-left: auto;
  margin-right: auto;
  left: 15px;
  width: 75px;
  height: 75px;
  bottom: 28px;
  border-radius: 50%;
}
</style>