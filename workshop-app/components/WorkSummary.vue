<template>
    <NuxtLink class="works-container" :to=" '/project/' + $props.works.slug">       
            <img :src="$props.works.previewImage">
            <div class="works-title"> {{ $prop.works.title }} </div> 
            <div class="works-artist">by {{ $props.works.artist }}</div>
            <div class="works-description"> {{ $props.works.description }}</div>

    </NuxtLink>
</template>

<script>

export default {

    props: ["works"]
}

</script>

<style scoped>
#works-container {
  display: grid;
  grid-template-columns: 1fr 1fr 1fr;
  width: 80vw;

}
div.works {
    display: flex;
    flex-direction: column;
    text-align: center;
    font-size: 1.5em;
    font-weight: bold;
    margin-bottom: 0.5em;
    align-items: center;
}

.works-title{

    margin-bottom: 0.8rem;
}
.works-artist {
    font-size: 0.8em;

}

.works-description {
    font-size: 1rem;
}

img {
  max-width: 90%;
  height: auto;
}

</style>
