<script>
	
</script>

<style>
	.tournament-bracket__number {
  display: inline-block;
  padding: 0.2em 0.4em 0.2em;
  border-bottom: 0.075em solid transparent;
  font-size: 0.95rem;
  background-color: #F5F5F5;
  border-color: #c22e2e;
}
.tournament-bracket__team--winner .tournament-bracket__number {
  background-color: #FFF176;
  border-color: #fad674;
}
	.tournament-bracket__list {
    margin-bottom: 0;
    padding-bottom: 0;
    border-right: 1px dashed #e5e5e5;
    border-bottom: 0;
  }
  .tournament-bracket__item {
  display: flex;
  flex: 0 1 auto;
  justify-content: center;
  flex-direction: column;
  align-items: flex-start;
  position: relative;
  padding: 2% 0;
  width: 48%;
  transition: padding 0.2s linear;
}
.tournament-bracket__list {
    padding-bottom: 1em;
    margin-bottom: 1em;
  }
.tournament-bracket__list {
  display: flex;
  flex-direction: column;
  flex-flow: row wrap;
  justify-content: center;
  height: 100%;
  min-height: 100%;
  border-bottom: 1px dashed #e5e5e5;
  padding-bottom: 2em;
  margin-bottom: 2em;
  transition: padding 0.2s ease-in-out, margin 0.2s ease-in-out;
}
</style>


<div class="vs-col vs-xs- vs-sm- vs-lg-" style="margin-left: 0%; width: 75%;">
	<h1> BallStar </h1>
	<div class="vs-con-items">
		<div class="vs-row" style="display: flex; width: 100%;">
		<div class="vs-col vs-xs- vs-sm- vs-lg-" style="margin-left: 0%; width: 8.33333%;">
		<span class="sm:inline-flex xl:hidden cursor-pointer p-2 feather-icon select-none relative">
		<svg xmlns="http://www.w3.org/2000/svg" width="24px" height="24px" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-menu ">
		<line x1="3" y1="12" x2="21" y2="12"></line><line x1="3" y1="6" x2="21" y2="6"></line>
		<line x1="3" y1="18" x2="21" y2="18"></line></svg></span></div><div class="vs-col vs-xs- vs-sm- vs-lg-" style="margin-left: 0%; width: 75%;">
		<div class="vx-logo cursor-pointer mr-auto flex items-center router-link-exact-active is-active-route">
		
		</div>
		</div>
		<div class="vs-col vs-xs- vs-sm- vs-lg-" style="margin-left: 3%; width: 8.33333%;">
		<!----></div>
		</div>
		<div class="vs-spacer"></div></div>

		<div class="container">
			<h1>BasketBall League</h1>
			
			<div class="tournament-bracket tournament-bracket--rounded">                                                     
			  <div class="tournament-bracket__round tournament-bracket__round--quarterfinals">
				<h3 class="tournament-bracket__round-title">Quarterfinals</h3>
				<ul class="tournament-bracket__list">
				  <li class="tournament-bracket__item">
					<div class="tournament-bracket__match" tabindex="0">
					  <table class="tournament-bracket__table">
						<caption class="tournament-bracket__caption">
						  <time datetime="Jun 02, 2021">Jun 02, 2021</time>
						</caption>
						<thead class="sr-only">
						  <tr>
							<th>Team</th>
							<th>Score</th>
						  </tr>
						</thead>  
						<tbody class="tournament-bracket__content">
						  <tr class="tournament-bracket__team tournament-bracket__team--winner">
							<td class="tournament-bracket__team">
							  <abbr class="tournament-bracket__code" title="Atlanta Hawks">Atlanta Hawks</abbr>
							  <span class="tournament-bracket__teamlogo" aria-label="Logo"></span>
							</td>
							<td class="tournament-bracket__score">
							  <span class="tournament-bracket__number">103</span>
							</td>
						  </tr>
						  <tr class="tournament-bracket__team">
							<td class="tournament-bracket__team">
							  <abbr class="tournament-bracket__code" title="New York Knicks">New York Knicks</abbr>
							  <span class="tournament-bracket__teamlogo" aria-label="Logo"></span>
							</td>
							<td class="tournament-bracket__score">
							  <span class="tournament-bracket__number">89</span>
							</td>
						  </tr>
						</tbody>
					  </table>
					</div>
				  </li>
		  
				 </div>
			</div>
			</div>
			</div>
