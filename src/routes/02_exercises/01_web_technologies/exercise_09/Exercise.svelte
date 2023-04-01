<script>
    function circumf(r) {
        return `The circumference of a circle with radius ${r}m is ${(2*Math.PI*r).toFixed(2)}m. `;
    }
</script>

<p>{circumf(2)} </p>
<p>{circumf(4)} </p>
<p>{circumf(10)} </p>
