<template>
    <button @click="onClick()" :style="{backgroundColor: color}" class="btn">
        {{ title }}

    </button>
</template>

<script>

export default {
    name: 'Button',
    props: {
        title: String,
        color: String,

    }, 


    methods: {
        onClick() {
            console.log('clicked');
        }
    }
   
}



</script>




