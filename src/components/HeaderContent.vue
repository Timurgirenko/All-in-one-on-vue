<template>
    <div class="container">
        <div class="menu">
        <div class="logo">
            <h1 class="kinetika_logo">All-in-one</h1>
            <h2 class="inter_logo">Study</h2> 
        </div>

        <div class="btns">
            <ul class="list_items_buttons">
                <li class="list_item_button">
                    <button class="referal"> Referal % </button>
                </li>
                <li class="list_item_button">
                    <button class="wallet">
                        <img src="../assets/icons/fox.png" alt="fox">
                        0x831...B49F
                        <img src="../assets/icons/Copy.svg" alt="copy">
                    </button>
                </li>
                <li class="list_item_button">
                    <button class="theme">
                        <img src="../assets/icons/Switcher_theme.svg" alt="Switcher_theme">
                    </button>
                </li>
                <li class="list_item_button">
                    <button class="question">
                        <img src="../assets/icons/cloud.svg" alt="cloud">
                    </button>
                </li>
                <li class="list_item_button">
                    <button class="FAQ">
                        ? FAQ
                    </button>
                </li>
                <li class="list_item_button">
                    <button class="Language">
                        <img src="../assets/icons/Flag Russia.png" alt="flag_russia">
                        RU
                    </button>
                </li>
            </ul>
        </div>
    </div>
    </div>
</template>

<style>
.menu{
    position: fixed;
    display: flex;
    align-items: center;
    justify-content: space-between;
    width: 100% ;
    height: 80px;
    z-index: 99;
    background: #0F0F0C;
}

.logo{
    
    width: 286px;
    height: 37px;
    margin: 21px 0px 21px 16px;

}

.kinetika_logo{
    display: inline;

    margin: 0px;
    color: #FFFFFF;
    font-family: Kinetica;
    font-size: 19px;
    font-weight: 700;
    line-height: 34.68px;
    text-align: left;

}

.inter_logo{
    display: inline;

    margin: 0px;
    color: #FFFFFF52;
    font-family: Kinetica;
    font-size: 20px;
    font-weight: 300;
    line-height: 36.5px;
    text-align: left;

}

.btns{
    display: flex;
    width: 1592px;
    height: 48px;
    align-items: center;
    justify-content: flex-end;
}

.list_items_buttons{
    display: flex;
    justify-content: space-between;
    list-style: none;
    text-align: center;
    align-items: center;
    justify-content: center;
    
}

.list_item_button{
    margin-right: 8px;
}

.referal{
    display: flex;
    align-items: center;
    justify-content: center;

    width: minmax(125px, auto);
    height: 45px;
    padding: 12px 20px 12px 20px;
    gap: 4px;
    border-radius: 8px;
    border: 1px;
    opacity: 0px;
    background: linear-gradient(185.36deg, #BDFF00 0%, #EDFF7B 100%);

    font-family: Inter;
    font-size: 14px;
    font-weight: 700;
    line-height: 17px;  
}

.wallet{
    display: flex;
    text-align: center;
    align-items: center;
    justify-content: center;
    width: 202px;
    height: 48px;
    padding: 8px 4px 8px 12px;
    gap: 12px;
    border-radius: 14px;
    border: 1px;
    opacity: 0px;
    background-color: rgba(15, 15, 12, 1);
    border: 1px solid #FFFFFF29;

    font-family: Inter;
    font-size: 14px;
    font-weight: 500;
    line-height: 16.94px;
    text-align: left;
    color: #FFFFFF;
}

.theme{
    display: flex;
    width: Hug (79px)px;
    height: Fill (48px)px;
    padding: 8px 12px 8px 12px;
    gap: 4px;
    border-radius: 14px;
    border: 1px ;
    opacity: 0px;
    background-color: rgba(15, 15, 12, 1);
    border: 1px solid #FFFFFF29;
}

.question{
    display: flex;
    width: 48px;
    height: 48px;
    padding: 8px 12px 8px 12px;
    gap: 4px;
    border-radius: 14px;
    border: 1px;
    opacity: 0px;
    background-color: rgba(15, 15, 12, 1);
    border: 1px solid #FFFFFF29;
}

.FAQ{
    display: flex;
    text-align: center;
    align-items: center;
    justify-content: center;
    width: 84px;
    height: 48px;
    padding: 8px 12px 8px 12px;
    gap: 4px;
    border-radius: 14px;
    border: 1px;
    opacity: 0px;
    background-color: rgba(15, 15, 12, 1);
    border: 1px solid #FFFFFF29;

    font-family: Inter;
    font-size: 16px;
    font-weight: 700;
    line-height: 19.36px;
    text-align: left;
    color: #FFFFFFA3;
}

.Language{
    display: flex;
    text-align: center;
    align-items: center;
    justify-content: center;
    width: 75px;
    height: 48px;
    padding: 8px 12px 8px 12px;
    gap: 4px;
    border-radius: 14px;
    border: 1px;
    opacity: 0px;
    background-color: rgba(15, 15, 12, 1);
    border: 1px solid #FFFFFF29;

    font-family: Inter;
    font-size: 16px;
    font-weight: 700;
    line-height: 19.36px;
    text-align: left;
    color: #FFFFFFA3;

}

.bg_main
{
    width: 1,440px;
    height: 797px;
    
    top: 80px;
    background: url(../assets/bg/Group\ 1.png) right no-repeat;
    background-position: left 896px top -150px ;
    
}

</style>