<template>
    <div class="home">
        <div class="home__wrapText">
            <div class="home__axasHome">
                <img src="@/assets/star.png" style="position: absolute; top: -3px;left: -30px;">
                AxasHome
            </div>
            <div class="home__title">
                Технологичный сервис для поиска недвижимости по всей России
            </div>
            <div class="home__text">
                Загрузи приложение и воспользуйся поиском объявлений об аренде и продаже жилой и коммерческой недвижимости
            </div>
            <div class="home__searchCont">
                
                <div class="home__searchDiv">
                    <div class="home__selectText">
                        Город
                    </div>
                    <select class="home__select">
                        
                        <option value="dfs">Москва</option>
                        <option value="dfs">Краснодар</option>
                        <option value="dfs">Санк-Петербург</option>
                        <option value="dfs">Екатеринбург</option>
                        <option value="dfs">Новосибирск</option>
                    </select>
                    <img src="@/assets/Vector.png" class="home__searchDiv_arrow"/>
                    <div class="home__searchBut">
                        Поиск
                    </div>
                    
                </div>
            </div>
        </div>
        <div class="home__wrapImg">

            <img src="@/assets/present.png">
        </div>
    </div>
</template>
<script>

</script>
<style lang="scss" src="@/style/home.scss"></style>