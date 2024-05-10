<template>
    <nav class="navbar">
        <button class="toggle" @click="$store.commit('toggleButton')"><font-awesome-icon class="icon" :icon="['fas', 'bars-staggered']"></font-awesome-icon></button>
    </nav>
</template>

<script>

</script>

<style lang="scss" scoped>
 .navbar {
    background: #fff;
    width:100%;
    padding: 20px;
    display:flex;
    justify-content: end;
 }

 button {
    border:none;
    background: transparent;
    cursor: pointer;
 }

 .icon {
    color: #333;
    font-size:24px;
 }
</style>