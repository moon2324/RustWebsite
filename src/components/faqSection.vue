<template>

<!-- EDIT HERE -->

<div class="container">
<section class="section rules text-center" id="faq">
<div class="tabs">
  <div class="spoon is-medium is-primary">FAQ</div>
</div>
<!-- SINGLE QUESTION & ANSWER -->
<h3 class="faq-question">Who are we</h3>
<p class="text-start">We are a small team of rust players who wanted to create some more relaxed rust servers with the hope of building a community of people for the sake of having fun.</p>
<!-- SINGLE QUESTION & ANSWER /END -->
<!-- SINGLE QUESTION & ANSWER -->
<h3 class="faq-question">Server Uptime/Reliability</h3>
<p class="text-start">The servers are being hosted locally by me running on my own hardware. i pride myself on having >95% with the only exceptions being power outages or my isp doing mantinence.</p>
<!-- SINGLE QUESTION & ANSWER /END -->
<!-- SINGLE QUESTION & ANSWER -->
<h3 class="faq-question">Future goals</h3>
<p class="text-start">Our goals are to create a large tight knit community with multiple servers down the line!</p>
<!-- SINGLE QUESTION & ANSWER /END -->
</section>
</div>

<!-- EDIT HERE -->

</template>


<script>
export default {
  name: 'faqSection'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3.faq-question {
	text-align: left;
  border-bottom: 1px solid var(--color-rust);
  padding-bottom: 5px;
  margin-bottom: 10px;
}
p.text-start {
	color: var(--color-mute);
}
p.text-start > a {
	color: var(--color-mute);
	text-decoration: underline;
}
p.text-start > a:hover {
	color: var(--color-white);
	text-decoration: none;
}
</style>