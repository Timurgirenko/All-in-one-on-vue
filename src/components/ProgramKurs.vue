<script setup>
import ProgCurseScript from "./ProgCurseScript.vue";
</script>

<template>
    <div class="container">
        <h2 class="title12">Программа курса</h2>
        <ProgCurseScript />
        <ProgCurseScript />
        <ProgCurseScript />
        <ProgCurseScript />
        <ProgCurseScript />
        <ProgCurseScript />
        <ProgCurseScript />
        <ProgCurseScript />
        <ProgCurseScript />
        

        <div class="of_course">
                <div class="bg_img"></div>
                    <h2 class="title16"><span class="spna_web3_gradient">Web3</span>Python-разработчик</h2>
                <div class="price">
                    <div class="about_course">
                        <div class="about_course_item"> <h5 class="about_course_item_fs16">Длительность</h5>  <h5 class="about_course_item_fs20">6 мес.</h5></div>
                            <hr class="about_course_hr47">
                        <div class="about_course_item"> <h5 class="about_course_item_fs16">Начало</h5>  <h5 class="about_course_item_fs20">06 Июля, 2024</h5> </div>
                            <hr class="about_course_hr47">
                        <div class="about_course_item"> <h5 class="about_course_item_fs16">Цена</h5>  <h5 class="about_course_item_fs20">500 USDT</h5> </div>
                    </div>
                    <button class="button_buy">Купить</button>
                </div>
        </div>
    </div>
</template>

<style>

.title12{
    font-family: Inter;
    font-size: 72px;
    font-weight: 600;
    line-height: 87.14px;
    margin: 0px;
    padding-bottom: 42px;
    color: #FFFFFF;
}




.of_course{
    width: 1440px;
    height: 231px;
    margin: 32px 0px 64px 0px;
    gap: 32px;
    border-radius: 32px;
    opacity: 0px;
    background: #FFFFFF0A url(../assets/bg/pyton_black.png) right no-repeat;

     
    z-index: 99;
/*     background-image: url(../bg/pyton_black.png) right no-repeat; */


}



.spna_web3_gradient{
    margin-right: 24px;
    color: transparent;    
    -webkit-background-clip: text;
    background-clip: text;
    background-image: linear-gradient(135deg, #2870DD 0%, #AA54B7 100%);
}

.title16{
    margin: 0px;
    padding: 32px 0px 0px 32px;
    font-family: Inter;
    font-size: 72px;
    font-weight: 600;
    line-height: 87.14px;
    text-align: left;
    color: #FFFFFF;
}

.price{
    display: grid;
    grid-template-columns: 457px 186px;
    width: 1376px;
    height: 48px;
    justify-content: space-between;
    padding-top: 32px;
    margin-left: 32px;
}

.about_course{
    display: flex;
    justify-content: space-between;
    text-align: left;
    width: 457px;
    height: 47px;
    gap: 10px;
    color: #FFFFFF;

}

.about_course_item{
    padding: 0px;
    margin: auto;
}

.about_course_hr47{
    width: 0px;
    height: 47px;
    border: 1px 0px 0px 0px;
    border: 1px solid #FFFFFF14;

}

.about_course_item_fs16{
    margin: 0px;
    font-family: Inter;
    font-size: 16px;
    font-weight: 500;
    line-height: 19.36px;
    text-align: left;
    color: #FFFFFF7A;

}

.about_course_item_fs20{
    margin: 4px 0px 0px 0px;
    font-family: Inter;
    font-size: 20px;
    font-weight: 600;
    line-height: 24.2px;
    text-align: left;    
}

.buy_button{    
    width: 186px;
    height: 48px;
    padding: 12px 32px 12px 32px;
    gap: 10px;
    border-radius: 12px;
    opacity: 0px;
    background: linear-gradient(135deg, #2870DD 0%, #AA54B7 100%);
    text-align: center;
    

    font-family: Inter;
    font-size: 20px;
    font-weight: 600;
    line-height: 24.2px;
    color: #FFFFFF;
}
</style>