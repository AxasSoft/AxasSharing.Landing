<template>
<div class="header">
    <div class="header__left">
        <img src="@/assets/logo.png" class="header__logo">
        <div 
            v-for="(link, idx) in links" 
            :key="idx" 
            class="header__link"
        >
            {{link.name}}
        </div>
    </div>
    <div class="header__right">
        <div class="header__link">
            Войти
        </div>
        <div class="header__link header__link_reg">
            Регистрация
        </div>
    </div>
    <div>

    </div>
</div>
</template>
<script>
export default{
    data(){
        return{
            links:[
                {name:"Жилая недвижимость", link:""},
                {name:"Коммерческая недвижимость", link:""},
                {name:"Земельные активы", link:""},
            ],
        }
    }
}
</script>
<style lang="scss" src="@/style/header.scss"></style>