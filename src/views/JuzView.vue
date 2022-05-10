<template>
  <section class="semua">
    <section class="page-section" id="team">
      <div class="container">
        <div class="text-center">
        <h3 class="find">You can find me on </h3>
        </div>
        <div class="row">
          <div class="col-lg-3">
            <div class="team-member">
              <a class="btn btn-primary btn-lg text-white fw-bold" href="https://www.facebook.com/dila.nuradila.5">Facebook</a>

            </div>
          </div>
          <div class="col-lg-3">
            <div class="team-member">
              <a class="btn btn-dark btn-lg text-white fw-bold" href="https://github.com/Nuradilaagustina">Github</a>

            </div>
          </div>
          <div class="col-lg-3">
            <div class="team-member">
              <a class="btn btn-danger btn-lg text-white fw-bold" href="https://www.instagram.com/nuradilaagtna/?hl=id=">Intagram</a>
            </div>
          </div>
        </div>
      </div>
    </section>
  </section>
</template>

<script>
import { onMounted } from "vue";

onMounted(() => {
  document.getElementsByTagName("body")[0].style.backgroundColor = "#E1BA9D";
  document.getElementsByTagName("body")[0].style.backgroundSize ="cover";
});

</script>

<style scoped>
.team-member {
  margin-left: 16rem;

}
.team-member img {
  width: 14rem;
  height: 14rem;
  border: 0.5rem solid rgba(0, 0, 0, 0.1);

}
.team-member h4, .team-member {
  margin-top: 10rem;
  margin-bottom: 0;
}

.page-section {
  background-size: cover;
  background-repeat: no-repeat;

}
.find{
  font-family: "Segoe UI";
  font-size: 40px;
  color: #727667;
  font-weight: bold;
  padding-bottom: 40px;
  margin-top: 90px;
}

.btn-social {
  height: 2.5rem;
  width: 2.5rem;
  display: inline-flex;
  align-items: center;
  justify-content: center;
  padding: 0;
  background-size: contain;
  background-repeat: no-repeat;
}
</style>