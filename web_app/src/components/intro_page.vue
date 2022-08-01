<template>
  <div class="Container">
    <img class="Doctor3D" src="@/assets/14.png" />
    <div class="Container-text-left">
      <h1>VOIS Security Systems</h1>
      <p>
        VOIS system we built, is depended on three main concepts. These are Face
        Recognition, Speech Analysis and Posture Detection. The data processed
        in Cloud system, determines the behaviour of security system. Risk map
        will be refreshed, Doors will be locked, necessary notifications will be
        sent.
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
