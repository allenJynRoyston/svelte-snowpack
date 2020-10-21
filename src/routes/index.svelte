<script>
	

	
</script>

<div style="background-color:#212529; padding: 1rem 1.2rem 1rem 1rem;width:calc(100% + 8px)">
  <label for="dark_select" style="color:#fff">nes-select.is-dark</label>
  <div class="nes-select is-dark">
    <select required id="dark_select">
      <option value="" disabled selected hidden>Select...</option>
      <option value="0">To be</option>
      <option value="1">Not to be</option>
    </select>
  </div>
</div>

<style lang='scss'>
	.test{
		h1{
			color: black
		}
	}
	h1 {
		color: #ff3e00;
		text-transform: uppercase;
		font-size: 4rem;
		font-weight: 100;
		line-height: 1.1;
		margin: 4rem auto;
		max-width: 14rem;
	}

	p {
		max-width: 14rem;
		margin: 2rem auto;
		line-height: 1.35;
	}

	@media (min-width: 480px) {
		h1 {
			max-width: none;
		}

		p {
			max-width: none;
		}
	}
</style>