<template>
    <div class="fast">
        <div class="fast__title">
            С нами быстрее
        </div>
        <div class="fast__text">
            С помощью наших инструментов поиск недвижимости станет еще проще
        </div>
        <div class="fast__flexRow">

            <div class="fast__textDiv">

                <div class="fast__card">
                    <div class="fast__card_imgWrap"> <img src="@/assets/fast1.png"> </div>
                    <div class="fast__card_title">Умный поиск</div>
                    <div class="fast__card_text">Подбирайте квартиру при помощи режима умной строки из более 50 возможных параметров</div>
                </div>

                <div class="fast__card">
                    <div class="fast__card_imgWrap"> <img src="@/assets/fast2.png"> </div>
                    <div class="fast__card_title">Работа вместе с клиентом</div>
                    <div class="fast__card_text">Удаленная работа с клиентом позволит вам показать потенциальному покупателю будущую квартиру</div>
                </div>

                <div class="fast__card">
                    <div class="fast__card_imgWrap"> <img src="@/assets/fast3.png"> </div>
                    <div class="fast__card_title">Поддержка на всех этапах</div>
                    <div class="fast__card_text">Наши специалисты проконсультируют, организуют показ и расскажут обо всех тонкостях</div>
                </div>
            </div>
            
            <div class="fast__imgDiv"> <img src="@/assets/fast.png"> </div>
            <div class="fast__textDiv">
                <div class="fast__card">
                    <div class="fast__card_imgWrap"> <img src="@/assets/fast4.png"> </div>
                    <div class="fast__card_title">Проведение сделки</div>
                    <div class="fast__card_text">Соберем все необходимые для сделки документы и организуем безопасную передачу денег</div>
                </div>

                <div class="fast__card">
                    <div class="fast__card_imgWrap"> <img src="@/assets/fast5.png"> </div>
                    <div class="fast__card_title">Гарантии по договору</div>
                    <div class="fast__card_text">Прописываем в договоре весь объем работ, размер нашей комиссии, а также сроки продажи объекта</div>
                </div>

                <div class="fast__card">
                    <div class="fast__card_imgWrap"> <img src="@/assets/fast6.png"> </div>
                    <div class="fast__card_title">Безопасная сделка</div>
                    <div class="fast__card_text">Наши юристы исключают риски утраты права собственности в будущем, объект проходит полную юридическую проверку</div>
                </div>
            </div>


        </div>
    </div>
</template>
<script>

export default{
    data(){
        return{
            path: "@/assets/fast1.png"
        }
    }
}
</script>

<style lang="scss" src="@/style/homeBottom.scss"></style>