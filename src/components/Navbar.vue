<template>
    <div id="page" class="page"><!-- mian-content -->
        <!-- header -->
        <header>
            <div class="header-logo">
                <div class="container">
                    <div class="header-top">
                        <a href="#" class="logo">
                            <h1>Санехника<span class="fa fa-faucet" aria-hidden="true"></span></h1>
                        </a>
                        <div class="header-nav">
                            <ul>
                                <li><a href="#" class="header-nav-item"><span class="fa fa-shopping-cart"></span></a></li>
                                <li><a href="#" class="header-nav-item">Вход<span class="fa fa-sign-in-alt pl-2"></span></a></li>
                            </ul>
                        </div>
                    </div>
                </div>
            </div>
        </header>
        <div class="header-bottom">
            <div class="container">
                <div class="header-bottom-content">
                    <div>
                        <b-dropdown id="dropdown-1" text="Каталог товаров" class="mr-2 borderrad btn1 header-button dropmenu">
                            <b-dropdown-item><a href="#"><span class="fa fa-bath pr-2" aria-hidden="true"></span>Ванны</a></b-dropdown-item>
                            <b-dropdown-item><a href="#"><span class="fa fa-toilet pr-2" aria-hidden="true"></span>Унитазы</a></b-dropdown-item>
                        </b-dropdown>
                    </div>
<!--                    <div class="pr-3 dropdown">-->
<!--                        <button href="#" class="btn1 btn btn-secondary header-button dropdown-toggle"  type="button" id="dropdownMenuButton" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false" data-offset>-->
<!--                            Каталог товаров-->
<!--                        </button>-->
<!--                        <ul class="dropdown-menu dropmenu" aria-labelledby="dropdownMenuButton">-->
<!--                            <li class="dropdown-item"><a href="#"><span class="fa fa-bath pr-2" aria-hidden="true"></span>Ванны</a></li>-->
<!--                            <li class="dropdown-item"><a href="#"><span class="fa fa-toilet pr-2" aria-hidden="true"></span>Унитазы</a></li>-->
<!--                            <li class="dropdown-item">-->
<!--                                <a href=# class="submenu"><span class="fa fa-tools pr-2" aria-hidden="true"></span>Инструменты</a>-->
<!--                                <ul class="dropdown-menu dropmenu" aria-labelledby="dropdownMenuButton">-->
<!--                                    <li class="dropdown-item"><a href="#">wsfgG</a></li>-->
<!--                                    <li class="dropdown-item"><a href="#">wsfgG</a></li>-->
<!--                                    <li class="dropdown-item"><a href="#">wsfgG</a>-->
<!--                                    </li>-->
<!--                                    <li class="dropdown-item"><a href="#">wsfgG</a></li>-->
<!--                                    <li class="dropdown-item"><a href="#">wsfgG</a></li>-->
<!--                                </ul>-->
<!--                            </li>-->
<!--                            <li class="dropdown-item"><a href="#"><span class="fa fa-sink pr-2" aria-hidden="true"></span>Мойки раковины</a></li>-->
<!--                            <li class="dropdown-item"><a href="#"><span class="fa fa-faucet pr-2" aria-hidden="true"></span>Смесители</a></li>-->
<!--                        </ul>-->
<!--                    </div>-->
                    <div class="search-bar">
                        <input type="search" class="form-control search-input" placeholder="Введите название товара..." name="search" required="">
                        <button class="btn1 btn search-button"><span class="fa fa-search"></span></button>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: "navbar"
}
</script>

<style scoped>

</style>