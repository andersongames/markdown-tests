<style>
.red {
color: red;
}
</style>

<p class="red"> Vermelho</p>

<a href="google.com" target="_blank">Google</a>

<span class="toggle">Toggle</span>

<script>
span = document.querySelector(".toggle");
p = document.querySelector(".red");

span.addEventListener("click", () =>
p.classList.remove("red"));
</script>
