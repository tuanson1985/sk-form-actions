<script>
	export let form;
</script>

<form method="post">
	<p>{form?.message || ''}</p>
	<input type="text" name="username" placeholder="Username" bind:value={username} />
	<input type="text" name="password" placeholder="Password" bind:value={password} />
	<button type="submit">Login</button>
</form>
