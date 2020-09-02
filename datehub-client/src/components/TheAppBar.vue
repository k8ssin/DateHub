<template>
    <v-app-bar
        app
        dense
        color="rgb(0,0,0,0.8)"
    >
        <v-icon
            class="mx-4"
            color="red"
        >
            mdi-heart-broken
        </v-icon>

        <span class="title white--text align-self-center">
            DateHub
        </span>

        <v-tabs
            background-color="rgb(0,0,0,0)"
            class="mx-8"
            dark
            centered
        >
            <v-tab>
                데이트
            </v-tab>

            <v-tab>
                광장
            </v-tab>
        </v-tabs>

        <v-spacer/>

        <v-text-field
            dense
            solo-inverted
            hide-details
            prepend-inner-icon="mdi-magnify"
            label="검색"
            dark
        >
        </v-text-field>

        <v-btn 
            class="ml-2"
            color="rgb(0,0,0,0)" 
            depressed
        >
            <span class="white--text">
                로그인
            </span>
        </v-btn>
    </v-app-bar>
</template>

<script>
export default {
    data: () => {
        //
    }
}
</script>