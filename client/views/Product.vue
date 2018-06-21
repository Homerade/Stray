<template>
    <ul>
        <li class='list-group-item list-group-item-action'>{{products.name}}</li>
        <li class='list-group-item list-group-item-action'>{{products.price}}</li>
    </ul>    
    
</template>

<script>
    export default {
        props: ['product'],
    }
</script>