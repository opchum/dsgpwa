<template lang="pug">
div(class="mainBody")
    header-side
    div(class="mainBody")
        div(class="firstSection")
            h2 Thursday PM (Center-Group)
            div(class="profileImageBody")
                img(src="https://randomuser.me/api/portraits/men/35.jpg")


</template>

<script>
// @ is an alias to /src
import HeaderSide from '@/components/HeaderSide.vue'

export default {
    components: {
        HeaderSide,
    }
}
</script>

<style lang="scss" scoped>
.profileImageBody{
    background-color: blue;
    border-radius: 100px;
    width:150px;
    height:150px;
    display:flex;
    margin: auto;
}

.profileImageBody>img{
    border-radius: 100px ;
    width: 150px;
    height:150px;
    margin: auto
}
</style>