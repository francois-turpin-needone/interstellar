<template>
    <div>
        <h4 class="mb-4">Interesting Fact</h4>
        <ul>
            <li v-for="(fact, index) in facts" :key="index">
                <Fact
                :txt="fact.txt"
                :iconName="fact.iconName"/>
            </li>
        </ul>
    </div>
</template>
<script>
import Fact from "./fact/Fact.vue";

export default {
    name: "Facts",
    components: {
        Fact,
    },
    data() {
        return {
            facts: [
                {
                    iconName: "black-hole.svg",
                    txt: "Dr. Kip Thorn Laid Out Two Rules For The Movie's Science"
                },
                {
                    iconName: "planets.svg",
                    txt: "Christopher Nolan Told Hans Zimmer To Throw Out The Rulebook"
                },
                {
                    iconName: "moon.svg",
                    txt: "New CGI Software Was Invented To Visualize Wormhole From T.E"
                },
                {
                    iconName: "astronomy.svg",
                    txt: "The Special Effects Are So Extensive, The Team Had To Develop New Technology"
                },
            ]
        }
    }
}
</script>
<style scoped>
h4 {
    margin-left: 75px;
    text-transform: uppercase;
    text-align: left;
    font-weight: bold;
    color: #fff;
    font-size: 1em;
}
ul {
    list-style: none;
    text-align: left;
    padding-left: 0;
}
</style>