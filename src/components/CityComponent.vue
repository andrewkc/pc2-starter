
<script>
export default {
    name: "CityComponent",
}
</script>

<template>
    <h1>Ciudad</h1>
    <div class="city">
        <img
        src = "./../assets/city.jpg"
        width="400"
        height="400"
        />
    </div>
</template>

<style scoped>
    .city {
    padding: 2px;
    white-space: nowrap;
    width: 350px;
    height: 350px;
    border-style: solid;
    border-radius: 5px;
    border-color: grey;
    }
    h1 {
    overflow: hidden;
    text-overflow: ellipsis;
}
</style>