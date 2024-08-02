<script setup>
import { ref } from "vue";
const active = ref(null);
</script>

<template>
    <div class="Wraper" :class=" active === index ? 'WraperActive' : 'Wraperlock'">
            <header class="program_kurs"
                @click="active = active === index ? null : index"
                :class=" active === index ? 'program_kursActive' : 'program_kurslock'">
                <div 
                :class=" active === index ? 'Active' : 'lock'">
                    <div class="program_list">
                            <div class="program_item">
                                <h6 class="program_item_txt"><span class="program_item_gradient">1.</span>Основы Python</h6>
                            </div>
                            <button class="button_plus">
                                <h6 :class=" active === index ? 'plusActive' : 'pluslock'">+</h6>
                            </button>
                </div>
                <div v-if="active === index"
                    :class="
                        active === index ? 'discriptionblockActive' : 'discriptionBlock'
                    "
                    :id="'b' + el">
                        <h6 class="descr">Изучите один из самых востребованных и простых в освоении языков программирования. Сможете описывать алгоритмы для решения повседневных задач и работы с данными.</h6>
                </div>
                </div>
            </header>
        </div>
</template>

<style>
.Wraper{
    display: flex;
    width: 1440px;
}

.WraperActive{
    margin-bottom: 108px;
}

.Wraperlock{
    margin-bottom: 0px;
}


.program_kurs{
    :hover{
        background: #303030;
    }
    cursor: pointer;
}

.program_kursActive{
    width: 1440px;
    height: 80px;

}

.program_kurslock{
    width: 1440px;
    height: 138px;
}


.program_list{
    display: flex;
    width: 1400px;
    height: 80px;
    margin-bottom: 8px;
    padding: 0px 20px ;
    gap: 0px;
    border-radius: 24px;
    justify-content: space-between;
    align-items: center;
}

.program_item_txt{
    width: 213px;
    height: 29px;
    margin: 0px;
    font-family: Inter;
    font-size: 24px;
    font-weight: 600;
    line-height: 29.05px;
    text-align: left;
    color: #FFFFFF;

}

.program_item_gradient{
    margin-right: 12px;
    color: transparent;    
    -webkit-background-clip: text;
    background-clip: text;
    background-image: linear-gradient(135deg, #2870DD 0%, #AA54B7 100%);
}

.button_plus{
    display: inline-block;
    width: 40px;
    height: 40px;
    padding: 8px ;
    border-radius: 12px;
    border: 0px;
    background: #FFFFFF0A;
    border-radius: 12px;
    border: none;
    cursor: pointer;
    
}

.pluslock{
    margin: 2px;
    font-family: Inter-light;
    font-size: 36px;
    font-weight: 100;
    line-height: 0px;
    text-align: left;
    color: #FFFFFF;
    width: 18px;
}

.plusActive{
    margin: 2px;
    font-family: Inter-light;
    font-size: 36px;
    font-weight: 100;
    line-height: 0px;
    text-align: left;
    color: #FFFFFF;
    width: 18px;
    transform: rotate(45deg);
}

.descr{
    width: 1400px;
    height: 38px;
    margin: 0px;

    font-family: Inter;
    font-weight: 500;
    font-size: 16px;
    color: rgba(255, 255, 255, 0.64);
    padding: 10px 20px 10px 20px;
}

.discriptionBlock {
    pointer-events: none;
    transition: 500ms;
}

.discriptionBlockActive {
    pointer-events: none;
    transition: 500ms;
    transform: height 500ms ease-in-out;
}

.Active{
    width: 1440px;
    height: 138px;
    padding: 20px;
    gap: 20px;
    border-radius: 24px ;
    background: #161613;
    margin-bottom: 20px;

}

.lock{
    width: 1440px;
    height: 80px;
    padding: 20px ;
    border-radius: 24px ;
    justify-content: space-between;
    background: #161613;


}
</style>