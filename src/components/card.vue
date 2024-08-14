<template>
    <div>
        <div class="card">
            <div v-if="lessons === undefined" class="info2">HI</div>
            <div v-else class="info">{{ lessons }} გაკვეთილი</div>
            <img :src="link" alt="error" class="image"/>
        </div>
        <h3>{{ title }}</h3>
    </div>
</template>


<script>
export default {
    props: {
        lessons: {
            type: String,
            required: true,
        },
        title: {
            type: String,
            required: true,
        },
        link: {
            required: true,
        }
    }
};
</script>


<style scoped>
.card{
    width: 370px;
    height: 210px;
    background-color: rgb(19, 228, 179);
    cursor: pointer;
    margin-right: 20px;

}
.info{
    height: 35px;
    width: 150px;
    background-color: white;
    margin-left: 10px;
    transform: translateY(10px);
    font-size: 18px;
    text-align: center;
}
h3{
    font-weight: 900;
    font-size: 16px;
    margin-top: 10px;
}

.image{
    height: 210px;
    width: 370px;
    margin-top: -35px;
}
.info2{
    font-size: 22px;
}

</style>