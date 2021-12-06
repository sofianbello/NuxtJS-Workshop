<template>
    <nav>
        <NuxtLink to='/'>Home</NuxtLink>
        <NuxtLink to='/Art'>Art</NuxtLink>
        <NuxtLink to='/about'>Über mich</NuxtLink>
        <NuxtLink to='/'>Kontakt</NuxtLink>
    </nav>
</template>

<script>
export default {

};
</script>

<style>

nav {
    display: flex;
    flex-direction: row;
    justify-content: center;
    gap: 20px;
    padding: 30px 0;
}

nav div {
    font-size: 1.5rem;
}

</style>
