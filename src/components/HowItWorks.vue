<template>
    <div class="HIW">
        <div class="HIW__wrap">
            <div class="HIW__title">
                AXAS HOUSE
            </div>
            <div class="HIW__bigTitle">
                Как это работает?
            </div>
            <div class="HIW__text">
                Several modules that can be used separately or together to adapt to your reality
            </div>

            <div v-if="rent" class="HIW__cardWrap">

                <div class="HIW__card">
                    <div class="HIW__card_iconDiv">
                        <img src="@/assets/cardIcon1.png" >
                    </div>
                    <div class="HIW__card_text">
                        Подбираете квартиру
                    </div>
                    <div class="HIW__card_number">
                        1
                    </div>
                </div>

                <div class="HIW__card">
                    <div class="HIW__card_iconDiv">
                        <img src="@/assets/cardIcon1.png" >
                    </div>
                    <div class="HIW__card_text">
                        Снимаете квартиру
                    </div>
                    <div class="HIW__card_number">
                        2
                    </div>
                </div>

                <div class="HIW__card">
                    <div class="HIW__card_iconDiv">
                        <img src="@/assets/cardIcon1.png" >
                    </div>
                    <div class="HIW__card_text">
                        Снимаете квартиру
                    </div>
                    <div class="HIW__card_number">
                        3
                    </div>
                </div>
            </div>
             <div v-else="" class="HIW__cardWrap">

                <div class="HIW__card">
                    <div class="HIW__card_iconDiv">
                        <img src="@/assets/cardIcon1.png" >
                    </div>
                    <div class="HIW__card_text">
                        Сдаю квартиру
                    </div>
                    <div class="HIW__card_number">
                        1
                    </div>
                </div>

                <div class="HIW__card">
                    <div class="HIW__card_iconDiv">
                        <img src="@/assets/cardIcon1.png" >
                    </div>
                    <div class="HIW__card_text">
                        Сдаю квартиру
                    </div>
                    <div class="HIW__card_number">
                        2
                    </div>
                </div>

                <div class="HIW__card">
                    <div class="HIW__card_iconDiv">
                        <img src="@/assets/cardIcon1.png" >
                    </div>
                    <div class="HIW__card_text">
                        Сдаю квартиру
                    </div>
                    <div class="HIW__card_number">
                        3
                    </div>
                </div>
            </div>
            <div  class="HIW__flexRow">
                <div @click="rent=true" :class="{HIW__active:rent}" class="HIW__button">Я хочу снять</div>
                <div @click="rent=false" :class="{HIW__active:!rent}" class="HIW__button">Я хочу сдать</div>
            </div>


        </div>
    </div>
</template>
<script>
export default{
    data(){
        return{
            rent: true,
        }
    }
}
</script>

