<script>
import cardsbox2 from './cardsbox2.vue';
import button1 from './button1.vue';

export default {
  name: 'App',
  components: {
    cardsbox2,
    button1,
  },
};
</script>


<template>
        <div>
                <div class="box">
                    <br/>
                    <center><h1 class="txt1">ბოლოს დაწერილი ბლოგები, პროგრამირების შესახებ</h1></center>
                <div class="mainBox">
                        <div class="boxColaidor">
                            <p class="txt2">ქვემოთ მოცემულია ტოპ 3 უახლესი ბლოგი პროგრამირების
                                 შესახებ, რომელიც ეხება ვებ-დეველოპმენტს</p>
                        </div>
                        <cardsbox2/>
                        <center><button1 text="ყველა ბლოგი"/></center>
                        <br/><br/><br/>
                        
                    </div>
                </div> 
                <br/><br/><br/><br/><br/><br/><br/><br/>
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
    margin-top: 10px;
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