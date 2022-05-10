<script setup>
import { onMounted } from "vue";

onMounted(() => {
  document.getElementsByTagName("body")[0].style.backgroundImage ="Url('src/assets/Kareem.png')"
  document.getElementsByTagName("body")[0].style.backgroundSize ="cover";
});

</script>

<template>
  <main>

    <div class="card bg-dark text-white">

      <div class="card-img-overlay">
        <h5 class="atas">Welcome to my web</h5>
        <p class="card-text">"Bacalah Al-quran, karna Al-quran akan datang pada hari kiamat nanti sebagai syafi' (pemberi syafa'at) bagi yang membacanya"</p>
        <p class="text1">(HR.Muslim)</p>
        <p class="lead">Ini adalah website yang berisikan beberapa ayat alquran dengan API dari Quran.com untuk pemenuhan tugas UTS Pemrogaman Web</p>
        <p class="akses"></p>
        <p>Pelajari lebih lanjut tentang API Quran.com</p>
        <a class="btn btn-dark btn-lg" href="#" role="button"> <a href="https://quran.api-docs.io/v4/getting-started/introduction" class="text-white fw-bold">Quran.Api</a></a>
      </div>
    </div>
  </main>
</template>

<style>
.card-img-overlay{
  margin-top: 90px;
  text-align: center;
  color: #0a0909;
}

.card-text{
  margin-top: 40px;
  font-size: 18px;
  font-weight: bold;

}
.atas{
  font-size: 55px;
  font-family: "Blackadder ITC";
  font-weight: bold;
}
.akses{
  margin-top: 20px;
}
.lead{
  margin-top: 50px;
  font-weight: bold;
  background-color: #c8946b;
}
.text1{
  font-size: 18px;
  font-weight: bold;
}
</style>
