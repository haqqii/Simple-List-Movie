<template>
   <footer>
      <p>Created by Mohammad Ibadul Haqqi
      </p>
   </footer>
</template>

<style scoped>
footer {
   background: transparent;
   position: fixed;
   height: 80px;
   bottom: 0;
   width: 100%;
}

footer p {
   color: white;
   justify-content: center;
   text-align: center;
   margin-top: 2%;
   display: flex;
}

footer p a {
   text-decoration: none;
   color: white;
}

@media(max-width: 767px) {
   footer p {
      margin-top: 8%;
      font-size: 14px;
   }
}
</style>

<script>
export default {
   mounted() {
      const currentYear = new Date().getFullYear();
      document.getElementById("currentYear").innerHTML = currentYear;
   },
};
</script>