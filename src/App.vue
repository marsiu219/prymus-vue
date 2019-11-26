<template>
  <div>  
    <h1>Clicked {{ no0fclick}} times.</h1>
    <button @click="iAmClicked()">Click me!</button>
  </div>
</template>
 
<script>
    export default {
        data() {
            return {title: 'Not clicked yet',
					no0fclick: 0}
        },
        methods: {
            iAmClicked() {
                this.no0fclick++;
            }
        }
    };
</script>
