<script>
import card from '../components/card.vue'
export default {
    
    // eslint-disable-next-line vue/multi-word-component-names
    name: "cardsbox",
    props: "text",
    components: {
        card,
    }

};
</script>



<template>
    <div>
        <br/>
        <div class="cardBox1">
            <card title="ჯავასკრიპტის (Javascript) უფასო კურსი დამწყებთათვის" 
            link="https://val-do.com/uploads/small/1717088248310.jpg" lessons="48"/>
            <card title="JavaScript-ის DOM-ის კურსი დამწყებთათვის" 
            link="https://val-do.com/uploads/small/1717090555213.jpg" lessons="6"/>
            <card title="TypeScript-ის კურსი დამწყებთათვის" 
            link="https://val-do.com/uploads/small/1717088375313.jpg" lessons="8"/>
        </div>
        <br/>
        <div class="cardBox2">
            <card title="HTML, CSS-ის კურსი დამწყებთათვის" 
            link="https://val-do.com/uploads/small/1717088862829.jpg" lessons="15"/>
            <card title="ალგორითმები" 
            link="https://val-do.com/uploads/small/1717089084893.jpg" lessons="2"/>
            <card title="Node.js-ის უფასო კურსი დამწყებთათვის"
             link="https://val-do.com/uploads/small/1709404617489.jpg" lessons="5"/>
        </div>

        
        
    </div>
</template>



<style scoped>
.cardBox1{
    display: flex;
}
.cardBox2{
    display: flex;
}
</style>