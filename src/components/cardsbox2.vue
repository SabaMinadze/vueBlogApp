<script>
import card from './card.vue'
export default {
    
    // eslint-disable-next-line vue/multi-word-component-names
    name: "cardsbox2",
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
            <card title="Nginx-ის ინსტალაცია Macintosh-ზე" 
            link="https://val-do.com/uploads/small/1715273489642.jpg"/>
            <card title="ინგლისური ენის მნიშვნელობა პროგრამირების სამყაროში" 
            link="https://val-do.com/uploads/small/1709192660192.jpg"/>
            <card title="როგორ ავაჩქაროთ საიტი, loading ატრიბუტის დახმარებით" 
            link="https://val-do.com/uploads/small/1707840523531.jpg"/>
        </div>
        <br/><br/>
        <center><h1 class="txt1">ბლოგები უფასო პროგრამირების გაკვეთილების შესახებ</h1></center>
        <p class="txt2">val-do.com-ზე ასევე შეგიძლიათ იხილოთ სტატიები და უფასო პროგრამირების
             გაკვეთილების ან ბლოგების სახით</p>
        <br/>
        <div class="cardBox2">
            <card title="ფავორიტი ედითორის ბრძანებები (VS CODE)" 
            link="https://val-do.com/uploads/small/1670172634319.jpg"/>
            <card title="mongodb-ს ხშირად გამოყენებული ბრძანებების ცნობარი" 
            link="https://val-do.com/uploads/small/1655825594881.jpg"/>
            <card title="git-ის ბრძანებები (ხშირად გამოყენებული)"
             link="https://val-do.com/uploads/small/1669795062311.jpg"/>
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

.txt1{
    font-weight: 800;
    text-align: center;
    color: black;
}

.txt2{
    font-size: 20px;
    text-align: center;
    margin-top: 10px;
}
</style>