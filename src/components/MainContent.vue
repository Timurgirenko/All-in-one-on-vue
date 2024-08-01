<template>
    <div class="container">
            <div class="main">
                
                <a class="hrf_back_to_kurs" href="#">
                    <div class="back_to_kurs">
                    <img class="left" src="../assets/icons/left.svg" alt="left">
                    <h3>Назад к курсам</h3>
                </div>
                </a>
                <h1 class="Web3">Web3</h1>
                <h2 class="title">Python-разработчик</h2>
                <div class="subtitle">На Python вы научитесь писать смарт-контракты, приложения <br> для взаимодействия с блокчейном и торговые боты</div>
                <div>
                    <h4 class="h4">Проекты написанные на Python</h4>
                    <div class="list_items">
                        <div class="list_item"><img class="img_list" src="../assets/icons/Ethereum.png" alt=""><h3 class="list_item_txt">Ethereum</h3></div>
                        <div class="list_item"><img class="img_list" src="../assets/icons/Uniswap.png" alt=""> <h3 class="list_item_txt">Uniswap</h3></div>
                        <div class="list_item"><img class="img_list" src="../assets/icons/CryptoKitties.png" alt=""><h3 class="list_item_txt">CryptoKitties</h3></div>
                        <div class="list_item"><img class="img_list" src="../assets/icons/Augur.png" alt=""><h3 class="list_item_txt">Augur</h3></div>
                    </div>
                </div>

                <div class="about_kurs">
                    <div class="about_kurs_item"> <h5 class="about_kurs_item_fs16">Длительность</h5>  <h5 class="about_kurs_item_fs20">6 мес.</h5></div>
                        <hr class="about_kurs_hr47">
                    <div class="about_kurs_item"> <h5 class="about_kurs_item_fs16">Начало</h5>  <h5 class="about_kurs_item_fs20">06 Июля, 2024</h5> </div>
                        <hr class="about_kurs_hr47">
                    <div class="about_kurs_item"> <h5 class="about_kurs_item_fs16">Цена</h5>  <h5 class="about_kurs_item_fs20">500 USDT</h5> </div>
                </div>
                
                <div class="buy_social">
                    <button class="button_buy">Купить</button>
                    <hr class="after_buttont_hr">
                        <a href="#" class="menu__link"><img class="menu__link_img" src="../assets/icons/Telegram.png" alt="telegram">Telegram</a>
                        <a href="#" class="menu__link"><img class="menu__link_img" src="../assets/icons/Telegram.png" alt="telegram">Telegram</a>
                        <a href="#" class="menu__link"><img class="menu__link_img" src="../assets/icons/Telegram.png" alt="telegram">Telegram</a>
                        <a href="#" class="menu__link"><img class="menu__link_img" src="../assets/icons/Telegram.png" alt="telegram">Telegram</a>
                </div>
            </div>
        </div>
</template>

<style>
.main{
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    width: 1440px;
    height: 876px;

}

.hrf_back_to_kurs{
    text-decoration: none
}

.back_to_kurs{
    display: flex;
    align-items: center;
    justify-content: center;
    width: 185px;
    height: 24px;
    gap: 10px;

    margin: 144px 0px 0px 0px;
}

h3{
    margin: 0px;
    font-family: Inter;
    font-size: 20px;
    font-weight: 600;
    line-height: 24.2px;
    text-align: left;
    color: #FFFFFF;
}

.Web3{
    margin: 16px 0px 0px 0px;
    font-family: Inter;
    font-size: 72px;
    font-weight: 600;
    line-height: 87.14px;
    color: transparent;    
	-webkit-background-clip: text;
	background-clip: text;
	background-image: linear-gradient(135deg, #2870DD 0%, #AA54B7 100%);;
}

.title{
    font-family: Inter;
    font-size: 72px;
    font-weight: 600;
    line-height: 87.14px;
    margin: 0px;
    color: #FFFFFF;
}

.subtitle{
    font-family: Inter;
    font-size: 24px;
    font-weight: 500;
    line-height: 29.05px;
    margin-top: 24px;
    color: #FFFFFFA3;
}

.h4{
    font-family: Inter;
    font-size: 16px;
    font-weight: 500;
    line-height: 19.36px;
    margin: 32px 0px 0px 0px;
    color: #FFFFFFA3;
}

.list_items{
    margin: 8px 0px 0px 0px;
    padding: 0px;
    width: 758px;
    height: 93px;
    gap: 12px;
    display: flex;
    justify-content: center;
    list-style: none;
    text-align: center;
    align-items: center;
    flex-flow:row nowrap;
align-items:center;
}

.img_list{
    width: 42px;
    height: 42px;
    margin-left: 0;
}

.list_item_txt{
    font-family: Inter;
    font-size: 20px;
    font-weight: 500;
    line-height: 24.2px;
    text-align: center;
    color: #FFFFFF;

}

.list_item{
    display: flex;
    align-items: center;
    padding: 0px;
    width: 100%;
    height: 66px;
    padding-left: 10px;
    padding-right: 12px;
    gap: 10px;
    border-radius: 12px;
    background: #FFFFFF0A;
    


}

.main_background{
    z-index: -99;
    margin: -30px 0px 0px 896px;
    width: 1024px;
    height: 767px;
}

.about_kurs{
    display: flex;
    justify-content: space-between;
    text-align: left;
    margin-top: 32px;
    width: 505px;
    height: 71px;
    padding: 12px 24px 12px 24px;
    gap: 10px;
    border-radius: 16px;
    background: #FFFFFF0A;
    color: #FFFFFF;

}

.about_kurs_item{
    padding: 0px;
    margin: auto;
}

.about_kurs_hr47{
    width: 0px;
    height: 47px;
    border: 1px 0px 0px 0px;
    border: 1px solid #FFFFFF14;

}

.about_kurs_item_fs16{
    margin: 0px;
    font-family: Inter;
    font-size: 16px;
    font-weight: 500;
    line-height: 19.36px;
    text-align: left;
    color: #FFFFFF7A;

}

.about_kurs_item_fs20{
    margin: 8px 0px 0px 0px;
    font-family: Inter;
    font-size: 20px;
    font-weight: 600;
    line-height: 24.2px;
    text-align: left;
}

.buy_social{
    display: flex;
    justify-content: space-between;
    margin-top: 32px;
    width: 758px;
    height: 48px;
    gap: 24px;

    text-align: center;
    align-items: center;


}

.button_buy{
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

.after_buttont_hr{
    margin: 0px;
    width: 0px;
    height: 48px;
    border: 1px 0px 0px 0px;
    border: 1px solid #FFFFFF14;

}

.menu__link{
    display: flex;
    align-items: center;
    font-family: Inter;
    font-size: 14px;
    font-weight: 600;
    line-height: 16.94px;
    text-align: center;
    color: #FFFFFF7A;
    text-decoration: none;

}

.menu__link_img{
    margin-right: 8px;
}
</style>