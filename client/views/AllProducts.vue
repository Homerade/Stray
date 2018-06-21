<template>
<div>
    <div>{{ getProducts }}</div>
    <p>something here</p>
</div>
</template>

<script>
    import Vue from 'vue';
    import { mapState, mapActions } from 'vuex';

    export default {

        // props: ['products'],

        
        
        computed: {
			getProducts() {
                return this.$store.state.products
                console.log('ok, computed w products:', this.$store.state.products);
            }
		},
        
        // mounted() {
        //             this.$store.dispatch('retrieveProducts');
        //             console.log('ok, mounted w products:', this.$store.state.products);
        //         }
    };        
</script>


