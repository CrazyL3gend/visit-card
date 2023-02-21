<html>

<div class='main'>

    <span class='avatar'>
        <img class='avatar-png' src='{avatarUrl}' alt='' />
    </span>

	<span class='github'>
        <img class='github-png' src='{githubUrl}' alt='' />
    </span>
	<span class='telegram'>
        <img class='telegram-png' src='{telegramUrl}' alt='' />
    </span>
	<span class='vk'>
        <img class='vk-png' src='{vkUrl}' alt='' />
    </span>

</div>

</html>

<style>
    :global(body) {
        background-color: #2B1E2D;
    }

    .main {
        height: 40em;
        position: relative;
    }

    .avatar {
        height: 256px;
        width: 256px;
        border-radius: 50%;
        position: absolute;
        top: 50%;
        left: 50%;
        margin: 0 -50% 0 0;
        transform: translate(-50%, -50%);
        background: #D9D9D9;
        background-size: 100% auto;
    }

    .avatar-png {
        position: absolute;
        margin: 0 -50% 0 0;
        transform: translate(12%, 12%);
    }

    .github {
        height: 196px;
        width: 196px;
        border-radius: 50%;
        position: absolute;
        top: 100%;
        left: 50%;
        margin: 0 -50% 0 0;
        transform: translate(-250%, -50%);
        background: #D9D9D9;
        background-size: 100% auto;
    }

    .telegram {
        height: 196px;
        width: 196px;
        border-radius: 50%;
        position: absolute;
        top: 100%;
        left: 50%;
        margin: 0 -50% 0 0;
        transform: translate(-50%, -50%);
        background: #D9D9D9;
        background-size: 100% auto;
    }

    .vk {
        height: 196px;
        width: 196px;
        border-radius: 50%;
        position: absolute;
        top: 100%;
        left: 50%;
        margin: 0 -50% 0 0;
        transform: translate(150%, -50%);
        background: #D9D9D9;
        background-size: 100% auto;
    }

</style>

<script>

	// eslint-disable-next-line no-unused-vars
	function openInNewTab(url) {
		window.open(url, '_blank').focus();
	}
</script>