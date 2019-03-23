<template>
    <b-container class="top-seperator">
        <b-row class="text-center">
            <b-col>
                <b-list-group>
                    <b-list-group-item>Cras justo odio</b-list-group-item>
                    <b-list-group-item active>Dapibus ac facilisis in</b-list-group-item>
                    <b-list-group-item>Morbi leo risus</b-list-group-item>
                    <b-list-group-item>Porta ac consectetur ac</b-list-group-item>
                    <b-list-group-item>Vestibulum at eros</b-list-group-item>
               </b-list-group>
            </b-col>
            <b-col cols="6">2 of 3 user list here</b-col>
            <b-col>
                <b-card
                    title="Card Title"
                    img-src="https://picsum.photos/600/300/?image=25"
                    img-alt="Image"
                    img-top
                    tag="article"
                    style="max-width: 20rem;"
                    class="mb-2">

                    <b-card-text>Some quick example text to build on the card title and make up the bulk of the card's content.</b-card-text>

                    <b-button href="#" variant="primary">Go somewhere</b-button>
                </b-card>
            </b-col>
        </b-row>
    </b-container>
</template>

<script>
// @ is an alias to /src
//import HelloWorld from '@/components/HelloWorld.vue'

export default {
    name: 'home',
    components: {
        //HelloWorld
    }
}
</script>
