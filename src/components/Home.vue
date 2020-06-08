<template>
    <div class="home">
        <v-container fluid fill-height>
            <v-row align="center">
                <v-col>
                    <h1 class="title">Junior Frontend<br />разработчик</h1>
                </v-col>
            </v-row>
        </v-container>
        
    </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';

@Component
export default class Home extends Vue {
    
}
</script>

<style lang="scss" scoped>
    .home {
        height: calc(100vh - 118px);
        max-height: 970px;
        background: #ffffff url('../assets/home.png') bottom right no-repeat;
        background-size: 60%;
        position: relative;
    
        .title {
            text-transform: uppercase;
            font-size: 44px !important;
            line-height: 1;
            color: #e93f7d;
            padding-left: 10%;
        }
    }
</style>