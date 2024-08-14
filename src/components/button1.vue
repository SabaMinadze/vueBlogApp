<script>
export default {
    props: {
        text: {
            type: String,
            required: true,
        }
    }

}
</script>


<template>
    <div>
        <br/>
        <button>{{ text }}</button>
        
    </div>
</template>


<style scoped>
button{
    height: 50px;
    width: 200px;
    background-color: rgb(253,231,103);
    font-size: 23px;
    border: none;
    cursor: pointer;
    font-weight: 400;
}
button:hover{
    background-color: cornflowerblue;
}
</style>