<script>
import cardsbox from './cardsbox.vue';
import button1 from './button1.vue'

export default {
  name: 'App',
  components: {
    cardsbox,
    button1,
  },
};
</script>


<template>
    <div>
        <div class="box">
            <br/>
            <center><h1 class="txt1">ტოპ პროგრამირების კურსები</h1></center>
           <div class="mainBox">
                <div class="boxColaidor">
                    <p class="txt2">მოცემული პროგრამირების კურსებით მარტივად შეძლებ შენი
                    პირველი ნაბიჯების გადადგმას ვებ დეველოპმენტსა და პროგრამირებაში,
                    ქვემოთ მოცემულია საიტზე არსებული ტოპ 3 პროგრამირების კურსი,
                    რომელიც შენთვის გახდება გზამკვლევლი პრგრამისტის კარიერაში</p>
                </div>
                <cardsbox/>
                <center class="btn1"><button1 text="ყველა კურსი"/></center>
                
                
            </div>
        </div> 
        <br/><br/><br/>
    </div>
</template>




<style scoped>
.box{
    width: 100%;
    height: 750px;
    
}

.txt1{
    font-weight: 800;
    text-align: center;
    color: black;
}

.txt2{
    font-size: 20px;
    text-align: center;
}

.boxColaidor{
    width: 1200px;
    
}

.mainBox{
    width: 1200px;
    height: 750px;
    margin-left: 170px;
}


.btn1{
    margin-top: 17px;
}
</style>