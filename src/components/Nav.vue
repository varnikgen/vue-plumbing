<template>
    <div id="page" class="page"><!-- mian-content -->
        <!-- header -->
        <header>
            <div class="container">
                <nav class="py-4">
                    <div id="logo">
                        <h1><a href="#" class="editContent">Сантехника</a>
                        </h1>
                    </div>

                    <label for="drop" class="toggle">Menu</label>
                    <input type="checkbox" id="drop">
                    <ul class="menu mt-3">
                        <li><a href="#">Корзина</a></li>
                        <li><a href="#">Вход</a></li>
                    </ul>
                </nav>
            </div>
        </header>
        <div style="background-color: #cbc9c9">
            <div class="container py-md-3">
                <div class="row">
                    <div class="side-bar col-lg-3">
                        <div class="left-side drop-down">
                            <div class="d-flex">
                                <a href="#" class="btn1 dropdown-toggle" id="menu_btn">Каталог товаров</a>
                            </div>
                            <ul class="drop-down-child drop__shadow menu_side" style="opacity: 1; top: auto;">
                                <li class="menu__list"><img class="icon-menu" src="../assets/images/icon8.svg"><a
                                        href="#">Ванны</a>
                                    <ul class="menu__drop drop__shadow">
                                        <li><a href="#">Чугунные</a></li>
                                        <li><a href="#">Акриловые</a></li>
                                        <li><a href="#">Стальные</a></li>
                                    </ul>
                                </li>
                                <li><img class="icon-menu" src="../assets/images/icon18.svg"><a
                                        href="#">Водонагреватели</a>
                                </li>
                                <li class="menu__list"><img class="icon-menu" src="../assets/images/icon018.svg"><a
                                        href="#">Инструменты</a>
                                    <ul class="menu__drop drop__shadow">
                                        <li><a href="#">Электроинструменты</a></li>
                                        <li><a href="#">Ручные инструменты</a></li>
                                    </ul>
                                </li>
                                <li><img class="icon-menu" src="../assets/images/icon3.svg"><a href="#">Мойки и
                                    Раковины</a>
                                </li>
                                <li><img class="icon-menu" src="../assets/images/icon2.svg"><a href="#">Унитазы</a></li>
                            </ul>
                        </div>
                    </div>
                    <div class="left-ads-display col-lg-9">
                        <div class="search-bar">
                            <div class="w3layouts-newsletter">
                                <form action="#" method="post" class="d-flex editContent">
                                    <input type="search" placeholder="Введите название..." name="search"
                                           class="form-control" required="">
                                    <button class="btn1 btn"><span class="fa fa-search" aria-hidden="true"></span>
                                    </button>
                                </form>
                            </div>
                        </div>
                    </div>

                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: "nav"
}
</script>

<style scoped>

</style>