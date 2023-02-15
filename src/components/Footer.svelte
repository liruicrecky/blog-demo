<script lang="ts">
    import Social from "./Social.svelte";
</script>

<footer>
    <div>
        <p>This is a test blog webside, it will be complish in the future.</p>
    </div>
    <Social platform="twitter" username="akka" />
    <Social platform="github" username="akka" />
    <Social platform="youtube" username="akka" />
</footer>

<style>
    footer {
        display: flex;
        gap: 1rem;
        margin-top: 2rem;
    }
    p {
        font-size: medium;
    }
</style>
