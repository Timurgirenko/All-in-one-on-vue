<template>
    <div class="container">
            <div class="about">
                <h2 class="title4">Что вы изучите</h2>
                <div class="learn_li">
                    <div class="learn_items">
                        <h5 class="learn_item_fs42">Основы Python</h5>
                        <hr class="learn_hr">
                        <h5 class="learn_item_fs24">Необходимые знания в python чтобы комфортно работать в web3 пространстве</h5>
                    </div>
                    <div class="learn_items">
                        <h5 class="learn_item_fs42">Web3</h5>
                        <hr class="learn_hr">
                        <h5 class="learn_item_fs24">Вы получите необходимые знания в python чтобы комфортно работать с web3</h5>
                    </div>
                    <div class="learn_items">
                        <h5 class="learn_item_fs42">Web3 <span class="gradient">PRO</span></h5>
                        <hr class="learn_hr">
                        <h5 class="learn_item_fs24">Вы получите необходимые знания в python чтобы комфортно работать с web3</h5>
                    </div>
                </div>
            </div>
        </div>
</template>

<style>

.about{
    width: 1440px;
    height: 422px;

}

.title4{
    
    padding-top: 64px;
    font-family: Inter;
    font-size: 72px;
    font-weight: 600;
    line-height: 87.14px;
    margin: 0px;
    color: #FFFFFF;
}

.learn_li{
    display: flex;
    justify-content: space-between;
    align-items: flex-start;
    margin-top: 42px;
    width: 1440px;
    height: 158px;
    gap: 42px;

}

.learn_item_fs42{
    margin: 0px 0px 10px 0px ;
    font-family: Inter;
    font-size: 42px;
    font-weight: 600;
    line-height: 50.83px;
    text-align: left;
    color: #FFFFFF;
}

.gradient{
    margin: 0 auto;
     color: transparent;    
    -webkit-background-clip: text;
    background-clip: text;
    background-image: linear-gradient(135deg, #2870DD 0%, #AA54B7 100%);

}

.learn_hr{
    margin: 0px;
    width: 124px;
    height: 4px;
    border: 1px solid;
    background: linear-gradient(90deg, #3A1862 0%, #4C04CB 50%, #9C4AB0 100%);

}

.learn_item_fs24{
    padding-bottom: 64px;
    margin: 10px 0px 0px 0px;
    font-family: Inter;
    font-size: 24px;
    font-weight: 500;
    line-height: 29.05px;
    text-align: left;
    color: #FFFFFFA3;

}

</style>