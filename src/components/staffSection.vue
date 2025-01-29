<template>

<!-- EDIT HERE -->

<div class="container">
<section class="section staff text-center" id="staff">
<div class="tabs">
  <div class="spoon is-medium is-primary">Our Staff</div>
</div>
<div class="row d-flex justify-content-center">

<!-- one member -->
<div class="col-lg-4 col-md-4 col-6">
<img src="../assets/PFP.webp" class="lazy rounded-circle staff" alt="Mr_moon"/>
<p class="staff-name">Mr_moon</p>
<p class="staff-role">Owner</p>
</div>
<!-- one member -->

<!-- one member -->
<div class="col-lg-4 col-md-4 col-6">
<img src="../assets/Joucan.webp" class="lazy rounded-circle staff" alt="Joucan"/>
<p class="staff-name">Joucan</p>
<p class="staff-role">Head Admin</p>
</div>
<!-- one member -->

<!-- one member -->
<div class="col-lg-4 col-md-4 col-6">
<img src="../assets/Mac.png" class="lazy rounded-circle staff" alt="MACANDCHEESE"/>
<p class="staff-name">MACANDCHEESE</p>
<p class="staff-role">Admin</p>
</div>

<!-- one member -->
<div class="col-lg-4 col-md-4 col-6">
<img src="../assets/SolidStone.gif" class="lazy rounded-circle staff" alt="SolidStone"/>
<p class="staff-name">SolidStone</p>
<p class="staff-role">Moderator</p>
</div>

<!-- one member -->
</div><!-- row -->
</section>
</div>

<!-- EDIT HERE -->

</template>


<script>
export default {
  name: 'staffSection'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
img.rounded-circle.staff {
    max-width:150px;
    border: 2px solid var(--color-rust);
}
p.staff-name {
    padding-top:1rem;
    font-size:1.2rem;
    color: var(--color-highlight);
}
p.staff-role {
    margin-top:-1rem;
    font-size:.8rem;
    color:var(--color-rust);
}
</style>