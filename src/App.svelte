<!-- <script>
    let name = 'Svelte'
    let src = 'https://media.dev.to/cdn-cgi/image/width=1000,height=420,fit=cover,gravity=auto,format=auto/https%3A%2F%2Fdev-to-uploads.s3.amazonaws.com%2Fuploads%2Farticles%2Fynt5bho2y1xl32q2vkku.png';
    let string = 'Some <strong>string</strong> with html';
</script>

<img {src} alt="Monkey beats {name}" />
<h1>Hello {name.toLowerCase()}!</h1>
<p>{@html string}</p>

<style>
    h1 {
        color: red
    }
</style> -->

<script>
    import Counter from './lib/Counter.svelte';
</script>

<Counter />