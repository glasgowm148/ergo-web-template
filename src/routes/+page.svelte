<script lang="ts">
	import WalletBalanceExample from "$lib/basic/WalletBalanceExample.svelte";
	import NotificationsExample from "$lib/basic/NotificationsExample.svelte";
	import TransactionExample from "$lib/basic/TransactionExample.svelte";
	import MintNftExample from "$lib/basic/MintNftExample.svelte";
	import WalletBoxesExample from "$lib/basic/WalletBoxesExample.svelte";
	import FetchOracleBoxExample from "$lib/basic/FetchOracleBoxExample.svelte";
</script>

<div class="flex flex-col grow p-4 main-page" style="padding-top:77px;">
	<h1 class="text-5xl font-bold mb-10 mt-5">Welcome to SampleApp!</h1>

	<div class="flex flex-wrap gap-4 w-full">
		<WalletBalanceExample></WalletBalanceExample>
		<NotificationsExample></NotificationsExample>
		<TransactionExample></TransactionExample>
		<MintNftExample></MintNftExample>
		<FetchOracleBoxExample></FetchOracleBoxExample>
		<WalletBoxesExample></WalletBoxesExample>
	</div>
</div>

<style lang="postcss">
	:global(html) {
		background-color: #8bc6ec;
		background-image: linear-gradient(135deg, #8bc6ec 0%, #9599e2 100%);
		min-height: 100vh;
	}
	:global(body) {
		min-height: 100vh;
		display: flex;
		flex-direction: column;
		color: #251e43;
	}
	.main-page{
		background-image: url("https://bitmasks.io/landing/sushimobile.png");
		background-position: center;
    	background-repeat: no-repeat;
	}
</style>
