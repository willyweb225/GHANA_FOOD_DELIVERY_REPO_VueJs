<template>
    <header class="header black_nav clearfix element_to_stick">
        <div class="container">
            <div id="logo">
                <a href="index.html">
                    <img src="../../assets/img/logo-svg.png" width="162" height="35" alt="">
                </a>
            </div>
            <div class="layer"></div>
            <!-- Opacity Mask Menu Mobile -->
            <ul id="top_menu">
                <li><a href="#sign-in-dialog" id="sign-in" class="login">Sign In</a></li>
                <li><a href="wishlist.html" class="wishlist_bt_top" title="Your wishlist">Your wishlist</a></li>
            </ul>
            <!-- /top_menu -->
            <a href="#" class="open_close">
                <i class="icon_menu"></i><span>Menu</span>
            </a>
            <nav class="main-menu">
                <div id="header_menu">
                    <a href="#" class="open_close">
                        <i class="icon_close"></i><span>Menu</span>
                    </a>
                    <a href="/"><img src="../../assets/img/logo-svg.png" width="162" height="35" alt=""></a>
                </div>
                <ul>
                    <li class="submenu">
                        <a href="/" class="show-submenu">Home</a>
                    </li>
                    <li class="submenu">
                        <a href="/about" class="show-submenu">About Us</a>
                        <!-- <ul>
                            <li class="third-level"><a href="#">Who we are?</a></li>
                        </ul> -->
                    </li>
                    <li class="submenu">
                        <a href="#" class="show-submenu">Contact</a>
                    </li>
                    <li class="submenu">
                        <!-- <a href="#" class="show-submenu btn_kw">Register</a> -->
                        <a href="/register" class="btn_1 gradient kw_regis">Register</a>
                        <!-- <ul>
                            <li class="third-level">
                                <a href="#">Restaurant List</a>
                                <ul>
                                    <li><a href="detail-restaurant.html">Detail page 1</a></li>
                                    <li><a href="detail-restaurant-2.html">Detail page 2</a></li>
                                    <li><a href="detail-restaurant-3.html">Detail page 3</a></li>
                                </ul>
                            </li>
                        </ul> -->
                    </li>

                    <li class="submenu">
                        <a href="#" class="show-submenu">FAQ</a>

                    </li>

                </ul>
            </nav>
        </div>
    </header>
</template>