<template>
    <div>
        <h1>Hallo Dunia</h1>
        <p>Nama : {{ nama }}</p>
        <p>Umur : {{ umur }}</p>
    </div>
</template>
<script>
export default {
    props: ['nama', 'umur']
}
</script>