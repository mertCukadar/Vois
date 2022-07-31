<template>
  <div class="Container">
    <img class="Doctor3D" src="@/assets/14.png" />
    <div class="Container-text-left">
      <h1>VOIS Security Systems</h1>
      <p>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Velit,
        consequuntur harum ipsum vitae assumenda nobis reiciendis similique
        deserunt, est magnam voluptatem! Nam eveniet quisquam officiis in rem
        dolore blanditiis consequuntur.Lorem ipsum dolor sit amet consectetur
        adipisicing elit. Velit, consequuntur harum ipsum vitae assumenda nobis
        reiciendis similique deserunt, est magnam voluptatem! Nam eveniet
        quisquam officiis in rem dolore blanditiis consequuntur.Lorem ipsum
        dolor sit amet consectetur adipisicing elit. Velit, consequuntur harum
        ipsum vitae assumenda nobis reiciendis similique deserunt, est magnam
        voluptatem! Nam eveniet quisquam officiis in rem dolore blanditiis
        consequuntur.
      </p>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
.Container {
  width: 100%;
}

.logo_inter {
  flex: auto;
  position: relative;
}

.Doctor3D {
  float: right;
  position: absolute;
  width: 40%;
  right: 10%;
  margin-right: 1rem;
  align-items: center;
}

.Container-text-left {
  margin-top: 9rem;
  width: 50%;
  position: absolute;
  animation: myFirst 3s;
  animation-direction: alternate;
}

@keyframes myFirst {
  0% {
    left: -1000px;
    right: 0px;
  }
  100% {
    left: 0px;
  }
}
</style>
