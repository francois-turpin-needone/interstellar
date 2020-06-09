<template>
    <div class="mb-3">
        <img :src="require(`../../../assets/img/${iconName}`)" alt="icon of fact"/>
        <p>{{txt}}</p>
    </div>
</template>
<script>
export default {
    name: "Fact",
    props: {
        txt: {
            type: String,
            required: true,
        },
        iconName: {
            type: String,
            required: true,
        }
    }
}
</script>
<style scoped>
div {
    max-width: 375px;
    display: flex;
    align-items: center;
}
p {
    color:#fff;
    font-weight: bold;
}
img {
    margin-right: 25px;
    width: 50px;
}
</style>