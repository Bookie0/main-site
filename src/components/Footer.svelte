<style>
	footer {
		display: flex;
		flex-direction: column;
		margin-top: 10vh;
	}
	div {
		display: flex;
		flex-direction: row;
		justify-content: center;
		flex-wrap: wrap;
	}
	div a {
		margin: 6px;
		padding: 6px;
  	transition: 150ms ease-out;
		border-radius: 50%;
		opacity: 0.5;
	}
	div a:hover {
  	transform: scale(1.1);
		opacity: 1;
	}
	div img {
		width: 60px;
		height: 60px;
		border-radius: 50%;
	}
	p {
		color: #999999;
		padding: 8px 0;
		text-align: center;
	}
</style>

<footer class="footer" id="footer">
	<div>
		<a target="_blank" href="https://anchor.fm/responsive"><img src="/social/anchor.png" alt=""></a>
		<a target="_blank" href="https://discord.gg/semsxbP"><img src="/social/discord.png" alt=""></a>
		<a target="_blank" href="mailto:responsivedev@pm.me"><img src="/social/email.png" alt=""></a>
		<a target="_blank" href="https://github.com/ResponsiveDev"><img src="/social/github.png" alt="" style="background-color: white"></a>
		<a target="_blank" href="https://twitch.tv/vandesm14"><img src="/social/twitch.png" alt=""></a>
		<a target="_blank" href="https://twitter.com/RespDev"><img src="/social/twitter.png" alt=""></a>
	</div>
	<p>© Copyright {@html new Date().getFullYear()} Responsive</p>
</footer>