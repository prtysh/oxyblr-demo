<script>
  export let name;
</script>

<main>
  <h1>Hello {name}!</h1>
  <iframe title="data-csv" class="iframe"
    src="https://docs.google.com/spreadsheets/d/e/2PACX-1vRop5pKt9b1rRf4dOe4fLmLrpM60PO2Q3HYns2Nho8sMcKMbWuUbMt4mRWY4SUQT97D4OfFDquLh61K/pubhtml?widget=true&amp;headers=false"
  />
  <a class="twitter-timeline" data-width="600" data-height="600" data-theme="dark" href="https://twitter.com/TwitterDev?ref_src=twsrc%5Etfw">Tweets by TwitterDev</a> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
</main>

<style>
	.iframe{
		width: 80%;
		height: 400px;
	}
  main {
    text-align: center;
    padding: 1em;
    max-width: 240px;
    margin: 0 auto;
  }

  h1 {
    color: #ff3e00;
    text-transform: uppercase;
    font-size: 4em;
    font-weight: 100;
  }

  @media (min-width: 640px) {
    main {
      max-width: none;
    }
  }
</style>
