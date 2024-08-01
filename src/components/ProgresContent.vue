<template>
    <div class="container">
            <div class="progress">
                <h2 class="title8">Будущие достижения</h2>
                <div class="progress_grid_container">
                    <div class="progress_grid_elem"><h6 class="grid_elem_fs20">Первое взаимодействие с блокчейном</h6></div>
                    <div class="progress_grid_elem"><h6 class="grid_elem_fs20">Свап на Uniswap V3</h6></div>
                    <div class="progress_grid_elem"><h6 class="grid_elem_fs20">Свап на Uniswap V3</h6></div>
                    <div class="progress_grid_elem"><h6 class="grid_elem_fs20">Свап на Uniswap V3</h6></div>
                    <div class="progress_grid_elem"><h6 class="grid_elem_fs20">Свап на Uniswap V3</h6></div>
                    <div class="progress_grid_elem"><h6 class="grid_elem_fs20">Первое взаимодействие с блокчейном</h6></div>
                    <div class="progress_grid_elem"><h6 class="grid_elem_fs20">Свап на Uniswap V3</h6></div>
                    <div class="progress_grid_elem"><h6 class="grid_elem_fs20">Свап на Uniswap V3</h6></div>
                    <div class="progress_grid_elem"><h6 class="grid_elem_fs20">Свап на Uniswap V3</h6></div>
                    <div class="progress_grid_elem"><h6 class="grid_elem_fs20">Свап на Uniswap V3</h6></div>
                    <div class="progress_grid_elem"><h6 class="grid_elem_fs20">Первое взаимодействие с блокчейном</h6></div>
                    <div class="progress_grid_elem"><h6 class="grid_elem_fs20">Свап на Uniswap V3</h6></div>
                    <div class="progress_grid_elem"><h6 class="grid_elem_fs20">Свап на Uniswap V3</h6></div>
                    <div class="progress_grid_elem"><h6 class="grid_elem_fs20">Свап на Uniswap V3</h6></div>
                    <div class="progress_grid_elem"><h6 class="grid_elem_fs20">Свап на Uniswap V3</h6></div>
                </div>
            </div>
        </div>
</template>

<style>

.progress{
    width: 1440px;
    height: 697px;
    padding: 64px 0px 64px 0px;
}

.title8{
    font-family: Inter;
    font-size: 72px;
    font-weight: 600;
    line-height: 87.14px;
    margin: 0px;
    color: #FFFFFF;
}

.progress_grid_container{
    width: 1440px;
    height: 440px;
    margin-top: 42px;
    display: grid;
    grid-template-columns: repeat(5, 275px);
    grid-template-rows: repeat(3, 136px);
    row-gap: 16px;
    column-gap: 16px;
    text-align: center;
    align-items: center;
}

.progress_grid_elem{
    display: flex;
    align-items: center;
    width: 275.2px;
    height: 136px;
    gap: 32px;
    border-radius: 24px ;
    opacity: 0px;
    background: #161613;

}

.grid_elem_fs20{
    font-family: Inter;
    font-size: 20px;
    font-weight: 500;
    line-height: 24.2px;
    color: #FFFFFF;
    text-align: left;
    align-items: center;
    margin-left: 32px;
}

</style>