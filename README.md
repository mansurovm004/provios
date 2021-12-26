# provios
Explore view git
*,
*::after,
*::before {
    box-sizing: border-box;
}

body {
    font-family: 'Roboto', sans-serif;
    font-weight: 400;
    font-size: 18px;
    line-height: 140%;
    color: #1f1e1e;
    margin: 0;
}

a {
    text-decoration: none;
    color: inherit;
}

.title {
    text-align: center;
    font-weight: 500;
    font-size: 36px;
    line-height: 130%;
}

.container {
    max-width: 1140px;
    margin: 0 auto;
    padding: 0 10px;
}

.header {
    background-image: url(../provios/directions-12.jpg);
    background-repeat: no-repeat;
    background-position: top center;
    background-size: cover;
    min-height: 100vh;
}

.header__inner {
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    min-height: 100vh;
}

.header__top {
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-wrap: wrap;
    padding: 16px 0 49px;
}

.logo {
    font-size: 24px;
    color: #fff;
    font-family: 'Ribeye Marrow';
}

.logo:hover {
    color: rgb(236, 194, 53);
    transform: scale(1.04);
    box-shadow: 0 4px 9px rgba(255, 208, 78, 0.5);
}

.header__phone {
    font-size: 16px;
    line-height: 130%;
    color: #fff;
    font-weight: 700;
}

.header__phone-number {
    font-weight: 400;
    margin-left: 19px;
    padding: 12px 31px 13px;
    /* Permalink - use to edit and share this gradient: https://colorzilla.com/gradient-editor/#f85032+0,f16f5c+50,f6290c+51,f02f17+71,e73827+100;Red+Gloss+%231 */
background: #f85032; /* Old browsers */
background: -moz-linear-gradient(top,  #f85032 0%, #f16f5c 50%, #f6290c 51%, #f02f17 71%, #e73827 100%); /* FF3.6-15 */
background: -webkit-linear-gradient(top,  #f85032 0%,#f16f5c 50%,#f6290c 51%,#f02f17 71%,#e73827 100%); /* Chrome10-25,Safari5.1-6 */
background: linear-gradient(to bottom,  #f85032 0%,#f16f5c 50%,#f6290c 51%,#f02f17 71%,#e73827 100%); /* W3C, IE10+, FF16+, Chrome26+, Opera12+, Safari7+ */
filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#f85032', endColorstr='#e73827',GradientType=0 ); /* IE6-9 */

    border-radius: 22px;
    transition: all .1s ease-out;
    text-align: center;
}

.header__phone-number:hover {
    transform: scale(1.04);
    box-shadow: 0 4px 9px rgba(255, 127, 80, .5);
        /* Permalink - use to edit and share this gradient: https://colorzilla.com/gradient-editor/#f5f6f6+0,dbdce2+21,b8bac6+49,dddfe3+80,f5f6f6+100;Grey+Pipe */
background: #f5f6f6; /* Old browsers */
background: -moz-linear-gradient(top,  #f5f6f6 0%, #dbdce2 21%, #b8bac6 49%, #dddfe3 80%, #f5f6f6 100%); /* FF3.6-15 */
background: -webkit-linear-gradient(top,  #f5f6f6 0%,#dbdce2 21%,#b8bac6 49%,#dddfe3 80%,#f5f6f6 100%); /* Chrome10-25,Safari5.1-6 */
background: linear-gradient(to bottom,  #f5f6f6 0%,#dbdce2 21%,#b8bac6 49%,#dddfe3 80%,#f5f6f6 100%); /* W3C, IE10+, FF16+, Chrome26+, Opera12+, Safari7+ */
filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#f5f6f6', endColorstr='#f5f6f6',GradientType=0 ); /* IE6-9 */

}

.dws__menu {
    width: 100%;
    border-top: 1px solid #fff;
    border-bottom: 1px solid #fff;
    margin-top: 15px;
    padding: 27px 0 24px;
}

.menu__list {
    display: flex;
    justify-content: space-evenly;
    align-items: center;
    list-style-type: none;
    font-size: 16px;
    color: #fff;
    
}

.dws__menu .menu__list .menu__item .menu__link {
    display: block;
    /* Permalink - use to edit and share this gradient: https://colorzilla.com/gradient-editor/#f85032+0,f16f5c+50,f6290c+51,f02f17+71,e73827+100;Red+Gloss+%231 */
background: #f85032; /* Old browsers */
background: -moz-linear-gradient(top,  #f85032 0%, #f16f5c 50%, #f6290c 51%, #f02f17 71%, #e73827 100%); /* FF3.6-15 */
background: -webkit-linear-gradient(top,  #f85032 0%,#f16f5c 50%,#f6290c 51%,#f02f17 71%,#e73827 100%); /* Chrome10-25,Safari5.1-6 */
background: linear-gradient(to bottom,  #f85032 0%,#f16f5c 50%,#f6290c 51%,#f02f17 71%,#e73827 100%); /* W3C, IE10+, FF16+, Chrome26+, Opera12+, Safari7+ */
filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#f85032', endColorstr='#e73827',GradientType=0 ); /* IE6-9 */

    padding: 15px 30px 15px 40px;
    color: #fff;
    margin: 0 -5px;
}

.dws__menu .menu__list .menu__item {
    position: relative;
    border-right: 1px solid #000;
}

.dws__menu .menu__list .menu__item .menu__link i.fa {
    position: absolute;
    top: 19px;
    left: 12px;
    font-size: 18px;
}

.dws__menu .menu__item .menu__link:hover {
        /* Permalink - use to edit and share this gradient: https://colorzilla.com/gradient-editor/#f5f6f6+0,dbdce2+21,b8bac6+49,dddfe3+80,f5f6f6+100;Grey+Pipe */
background: #f5f6f6; /* Old browsers */
background: -moz-linear-gradient(top,  #f5f6f6 0%, #dbdce2 21%, #b8bac6 49%, #dddfe3 80%, #f5f6f6 100%); /* FF3.6-15 */
background: -webkit-linear-gradient(top,  #f5f6f6 0%,#dbdce2 21%,#b8bac6 49%,#dddfe3 80%,#f5f6f6 100%); /* Chrome10-25,Safari5.1-6 */
background: linear-gradient(to bottom,  #f5f6f6 0%,#dbdce2 21%,#b8bac6 49%,#dddfe3 80%,#f5f6f6 100%); /* W3C, IE10+, FF16+, Chrome26+, Opera12+, Safari7+ */
filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#f5f6f6', endColorstr='#f5f6f6',GradientType=0 ); /* IE6-9 */

    color: #000;
    box-shadow: 10px 5px 10px 5px black;
    transition: all .1s ease-in-out;
}

.dws__menu li ul {
    position: absolute;
    min-width: 150px;
}



.dws__menu li > ul li a{
    padding: 10px;
    list-style-type: none;
    text-transform: none;
}
.header__title {
    font-family: 'PT Serif', serif;
    font-weight: 700;
    font-size: 90px;
    line-height: 130%;
    text-align: center;
    margin-bottom: auto;
    color: #fff;
}

.header__descr {
    font-weight: 700;
    font-size: 20px;
    max-width: 420px;
    margin-bottom: 20px;
    color: #fff;
}

.header__btn {
    display: inline-block;
    font-size: 18px;
    color: #fff;
    padding: 19px 55px 20px;
    border-radius: 30px;
    /* Permalink - use to edit and share this gradient: https://colorzilla.com/gradient-editor/#f85032+0,f16f5c+50,f6290c+51,f02f17+71,e73827+100;Red+Gloss+%231 */
background: #f85032; /* Old browsers */
background: -moz-linear-gradient(top,  #f85032 0%, #f16f5c 50%, #f6290c 51%, #f02f17 71%, #e73827 100%); /* FF3.6-15 */
background: -webkit-linear-gradient(top,  #f85032 0%,#f16f5c 50%,#f6290c 51%,#f02f17 71%,#e73827 100%); /* Chrome10-25,Safari5.1-6 */
background: linear-gradient(to bottom,  #f85032 0%,#f16f5c 50%,#f6290c 51%,#f02f17 71%,#e73827 100%); /* W3C, IE10+, FF16+, Chrome26+, Opera12+, Safari7+ */
filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#f85032', endColorstr='#e73827',GradientType=0 ); /* IE6-9 */

    margin-bottom: 20px;
}

.header__btn:hover {
    background: #f5f6f6; /* Old browsers */
    background: -moz-linear-gradient(top,  #f5f6f6 0%, #dbdce2 21%, #b8bac6 49%, #dddfe3 80%, #f5f6f6 100%); /* FF3.6-15 */
    background: -webkit-linear-gradient(top,  #f5f6f6 0%,#dbdce2 21%,#b8bac6 49%,#dddfe3 80%,#f5f6f6 100%); /* Chrome10-25,Safari5.1-6 */
    background: linear-gradient(to bottom,  #f5f6f6 0%,#dbdce2 21%,#b8bac6 49%,#dddfe3 80%,#f5f6f6 100%); /* W3C, IE10+, FF16+, Chrome26+, Opera12+, Safari7+ */
    filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#f5f6f6', endColorstr='#f5f6f6',GradientType=0 ); /* IE6-9 */
}

.header__arrow {
    text-align: center;
    margin-bottom: 15px;
}

.direction {
    padding: 100px 0;
}

.direction__inner {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    grid-gap: 32px;
}

.direction__img {
    width: 260px;
    height: 100px;
    display: block;
}

.description__text {
    font-size: 16px;
    border: 1px solid #D9D9dE;
    padding: 10px 19px 14px;
    border-top: none;
    margin-top: -1px;
}

.travel-info {
    height: 110vh;
    background-image: url(../provios/directions-11.jpg);
    background-repeat: no-repeat;
    background-size: cover;
    background-position: top center;
    padding: -20px 0 50px;
}

.travel-info__title {
    margin-bottom: 20px;
    color: #fff;
}

.travel-info__items {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    grid-gap: 54px 67px;
}

.travel-info__img {
    margin-bottom: 15px;
}

.travel-info__text {
    width: 200px;
    font-size: 16px;
    color: #fff;
    line-height: 130%;
}

.popular {
    padding: 100px 0;
}

.popular__title {
    margin-bottom: 40px;
}

.popular__items {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    grid-template-rows: repeat(4, 1fr);
    grid-gap: 32px;
    padding-bottom: 80px;
    border-bottom: 1px solid #D9D9dE;
}

.popular__link {
    padding: 16px 24px 19px;
    color: #fff;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    background-repeat: no-repeat;
    background-size: cover;
    background-position: center;
    min-height: 256px;
    line-height: 130%;
}

.popular__link:nth-child(3),
.popular__link:nth-child(6) {
    grid-column: span 2;
    grid-row: span 2;
}

.popular__link-title {
    font-weight: 500;
    font-size: 24px;
    margin-bottom: 15px;
}

.popular__price {
    font-weight: 700;
    font-size: 16px;
}

.map {
    padding-bottom: 100px;
}

.map__title {
    margin-bottom: 46px;
    
}

.map__iframe {
    width: 100%;
    height: 80vh;
   
}

.dws__menu [type="checkbox"] {
    display: none;
}

.dws__menu label.toggleMenu {
    background-color: black;
    color: #fff;
    display: none;
    padding: 15px 40px;
    text-transform: uppercase;
    font-size: 18px;
    cursor: pointer;
    position: relative;
}

.dws__menu label.toggleMenu .fa {
    position: absolute;
    top: 18px;
    left: 12px;
    font-size: 18px;
}

@media all and (max-width: 800px) {
    .dws__menu {
        overflow: hidden;
    }
    .dws__menu ul {
        display: none;
    }

    .dws__menu .menu__item .menu__link:hover {
        background-color: #fff;
        color: #000;
    }
    .dws__menu label.toggleMenu {
         /* Permalink - use to edit and share this gradient: https://colorzilla.com/gradient-editor/#f85032+0,f16f5c+50,f6290c+51,f02f17+71,e73827+100;Red+Gloss+%231 */
background: #f85032; /* Old browsers */
background: -moz-linear-gradient(top,  #f85032 0%, #f16f5c 50%, #f6290c 51%, #f02f17 71%, #e73827 100%); /* FF3.6-15 */
background: -webkit-linear-gradient(top,  #f85032 0%,#f16f5c 50%,#f6290c 51%,#f02f17 71%,#e73827 100%); /* Chrome10-25,Safari5.1-6 */
background: linear-gradient(to bottom,  #f85032 0%,#f16f5c 50%,#f6290c 51%,#f02f17 71%,#e73827 100%); /* W3C, IE10+, FF16+, Chrome26+, Opera12+, Safari7+ */
filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#f85032', endColorstr='#e73827',GradientType=0 ); /* IE6-9 */
        display: none;
        padding: 15px 40px;
        text-transform: uppercase;
        font-size: 14px;
        cursor: pointer;
        position: relative;
    }
    .dws__menu .menu__list .menu__item:first-child {
        border-left: 1px solid #fff;
    }
    
    .dws__menu .menu__list .menu__item .menu__link:last-child {
        border-right: 1px solid #fff;
    }
    .dws__menu label.toggleMenu {
        display: block;
    }
    input.toggleMenu:checked + label.toggleMenu  {
        /* Permalink - use to edit and share this gradient: https://colorzilla.com/gradient-editor/#ffffff+0,f3f3f3+50,ededed+51,ffffff+100;White+Gloss+%232 */
background: #ffffff; /* Old browsers */
background: -moz-linear-gradient(top,  #ffffff 0%, #f3f3f3 50%, #ededed 51%, #ffffff 100%); /* FF3.6-15 */
background: -webkit-linear-gradient(top,  #ffffff 0%,#f3f3f3 50%,#ededed 51%,#ffffff 100%); /* Chrome10-25,Safari5.1-6 */
background: linear-gradient(to bottom,  #ffffff 0%,#f3f3f3 50%,#ededed 51%,#ffffff 100%); /* W3C, IE10+, FF16+, Chrome26+, Opera12+, Safari7+ */
filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#ffffff', endColorstr='#ffffff',GradientType=0 ); /* IE6-9 */

        color: #000;
    }
    input.toggleMenu:checked ~ ul {
        display: block;
    }
    .menu__item {
        margin: -1px;
    }
}

.about {
    padding-bottom: 100px;
}

.about__inner {
    display: grid;
    grid-template-columns: 448px 640px;
    grid-gap: 32px;
}

.about__title {
    text-align: left;
    margin-bottom: 25px;
}

.about__text {
    margin-bottom: 34px;
}

.about__link {
    font-size: 16px;
    line-height: 19px;
    color: #c4c4c4;
    text-decoration: underline;
}

.about__popup {
    background-image: url(../provios/popup.png);
    background-repeat: no-repeat;
    background-position: top center;
    background-size: cover;
    display: flex;
    justify-content: center;
    align-items: center;
}

.gallery {
    padding: 50px 0 105px;
    background-color: rgb(114, 112, 112);
    color: #fff;
}

.gallery__top {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-bottom: 40px;
    padding-right: 160px;
}

.gallery__link {
    font-size: 16px;
    line-height: 19px;
    text-decoration: underline;
}

.gallery__item-inner {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    grid-gap: 32px;
}

.slick-btn{
    cursor: pointer;
}

.booking {
    background-color: #eaeaea;
    padding: 75px 0;
}

.booking__title {
    margin-bottom: 43px;
}

.booking__form {
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-wrap: wrap;
    max-width: 830px;
    margin: 0 auto;
}

.booking__input {
    width: 256px;
    height: 44px;
    border: 1px solid #D9D9dE;
    background-color: transparent;
    padding: 11px 14px 12px;
    margin-bottom: 28px;
    font-size: 16px;
}

.booking__input::placeholder, 
.booking__area::placeholder{
    font-family: 'Roboto', sans-serif;
    font-size: 16px;
    color: #c4c4c4;
}

.booking__area {
    width: 100%;
    padding: 14px;
    height: 112px;
    border: 1px solid #D9D9dE;
    resize: none;
    margin-bottom: 67px;
}

.booking__btn {
    background-color: #f6290c;
    border-radius: 30px;
    border: none;
    font-size: 18px;
    line-height: 21px;
    color: #fff;
    padding: 19px 65px 20px;
    cursor: pointer;
}

.booking__label {
    font-size: 16px;
    line-height: 130%;
    text-decoration: underline;
    display: flex;
    align-items: center;
}

.booking__checkbox {
    position: absolute;
    width: 1px;
    height: 1px;
    overflow: hidden;
    clip: rect(0 0 0 0);
    padding-left: -45px;
}

.booking__checkbox-style {
    width: 26px;
    height: 26px;
    border: 1px solid #c4c4c4;
    border-radius: 2px;
    position: absolute;
    margin-left: -45px;
}

.booking__checkbox:checked + .booking__checkbox-style::before {
    content: '';
    position: absolute;
    width: 16px;
    height: 16px;
    background-color: #c4c4c4;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
}

.footer {
    background-color: #1f1e1e;
    padding: 80px 0;
}

.footer__logo {
    text-align: center;
    margin-bottom: 70px;
}

.footer__box {
    display: flex;
    justify-content: space-between;
    font-size: 14px;
    line-height: 130%;
    max-width: 830px;
    margin: 0 auto;
    color: rgba(255, 255, 255, .8);
}

.footer__info {
    width: 225px;
}
.footer__box-title {
    margin-bottom: 7px;
    font-weight: 500;
    color: #fff;
}
.footer__copy {
    margin-bottom: 3px;

}
.footer__link {
    text-decoration: underline;

}
.footer__address {
    width: 165px;
    
}
.footer__contacts {
    width: 210px;
}
.footer__mail {
    display: block;
}

@media (max-width: 1140px) {
    .direction__inner {
        grid-template-columns: repeat(3, 1fr);
        grid-gap: 20px;
    }
    .direction__img {
        width: 100%;
    }
    .about__inner {
        grid-gap: 20px;
        grid-template-columns: 1fr, 2fr;
    }
    .gallery__item-inner {
        grid-template-columns: repeat(2, 1fr);
        grid-gap: 32px;
    }
    .gallery__item-img {
        width: 100%;
    }
}

@media (max-width: 990px) {
    .popular__link {
        min-height: 200px;
    }
    .popular__items {
        grid-gap: 10px;
        
    }
    
}

@media (max-width: 800px) {
    .header__phone span {
        display: none;
    }
    .travel-info__items {
        grid-template-columns: repeat(2, 1fr);
        grid-gap: 5px;
    }
    .travel-info {
       width: 590px;
        height: 200vh;
        
    }
    .popular__link:nth-child(3),
    .popular__link:nth-child(6) {
        grid-column: auto;
        grid-row: auto;
    }
    .popular__items {
        grid-template-columns: repeat(2, 1fr);
    }
    .popular__items {
        min-height: 300px;
    }
    .popular {
        padding: 50px 0;
    }
    .about__inner {
        grid-gap: 20px;
        grid-template-columns: 1fr;
    }
    .about__popup {
        min-height: 440px;
    }
    .gallery {
        padding-left: -10px;
        min-width: 570px;
    }
    .gallery__item-img {
        width: 530px;
        height: 390px;
    }
    .booking {
        padding: 80px 0;
        min-width: 780px;
    }
    .booking__input {
        width: 100%;
    }
    .booking__label {
        margin-left: -193px;
        margin-left: 50px;
        width: 100%;
    }
    .footer {
        padding: 50px 0;
        min-width: 775px;
    }
    .footer__logo {
        margin-bottom: 40px;
    }
    .footer__box {
        display: block;
        text-align: center;
    }
    .footer__info,
    .footer__address {
        margin: 0 auto 25px;
    }
    .footer__contacts {
        margin: 0 auto;
    }
}

@media (max-width: 782px) {
    .travel-info {
        width: 780px;
        height: 110vh;
         
     }
     .direction__inner {
        grid-template-columns: repeat(2, 1fr);
        grid-gap: 10px;
    }
    .description__text {
        width: 256px;
    }
    .direction__img {
        width: 256px;
        height: 130px;
        display: block;

    }
    .popular__items {
        grid-template-columns: repeat(1, 1fr);
    }
    .gallery {
        padding-left: -10px;
        min-width: 780px;
        
    }
    .gallery__item-img {
        width: 300px;
        height: 160px;
    }
    .header {
        min-width: 780px;
    }
    .direction__img {
        transform: translate(20%, -10%);
    }
    .description__text {
        transform: translate(20%, -10%);
    }
    .popular__link {
        transform: translate(10%, -10%);
    }
    .popular__title {
        transform: translate(10%, -10%);
    }
    .map__title {
        margin-bottom: 46px;
        transform: translate(10%, -10%);
    }
    .map__iframe {
        height: 350px;
        transform: translate(10%, -10%);
    }
    .popular__items {
        border-bottom: none; 
    }
    .about__inner {
        grid-gap: 20px;
        grid-template-columns: 1fr;
        transform: translate(10%, -10%);
    }
    .about__popup {
        transform: translate(-5%, -10%);
    }
    .travel-info {
        height: 200vh;
    }
    .booking {
        padding: 80px 0;
        min-width: 780px;
    }
    .booking__input {
        width: 100%;
    }
    .booking__label {
        margin-top: -193px;
        margin-left: 50px;
        width: 100%;
    }
}

@media (max-width: 560px) {
    .header__title {
        font-size: 50px;
    }
    .logo {
        width: 100%;
        text-align: center;
        margin-bottom: 40px;
    }
    .header__phone-number {
        margin-left: 0;
    }
    .dws__menu {
        width: 100%;
        border-top: 0;
        border-bottom: transparent;
        margin-top: 15px;
        padding: 27px 0 24px;
    }
    .header__descr {
        margin: 0 auto;
    }
    .header__btn {
        margin: 0 auto;
    }
    .header__content {
        text-align: center;
    }
    .direction__inner {
        grid-template-columns: repeat(2, 1fr);
        grid-gap: 10px;
    }
    .direction {
        padding: 50px 0;
    }
    .title {
        font-size: 28px;
    }
    .travel-info__text {
        font-size: 14px;
    }
    .header {
        min-width: 780px;
    }
    .travel-info {
        height: 100vh;
         
    }
    .gallery__item-inner {
        grid-template-columns: repeat(1, 1fr);
    }
    .gallery__item-img {
        width: 500px;
        height: 300px;
        transform: translate(25%, 10%)
    }
    .gallery {
        min-width: 780px;
    }
    .direction__img {
        width: 256px;
        height: 130px;
        display: block;
        transform: translate(40%, -10%)
    }
    .description__text {
        transform: translate(40%, -10%);
    }
    .popular__link {
        transform: translate(20%, -10%);
    }
    .popular__title {
        transform: translate(20%, -10%);
    }
    .map__title {
        margin-bottom: 46px;
        transform: translate(20%, -10%);
    }
    .map__iframe {
        height: 350px;
        transform: translate(20%, -10%);
    }
    .about__inner {
        grid-gap: 20px;
        grid-template-columns: 1fr;
        transform: translate(20%, -10%);
    }
    .about__popup {
        transform: translate(-5%, -10%);
    }
    
}

@media (max-width: 460px) {
    .travel-info__items {
        grid-template-columns: repeat(2, 1fr);
    }
    .direction__inner {
        grid-template-columns: repeat(1, 1fr);
        
    }
    .direction__img {
        width: 256px;
        height: 130px;
        display: block;
        transform: translate(80%, -10%)
    }
    .travel-info {
        height: 110vh;
         
    }
    .description__text {
        width: 256px;
        transform: translate(80%, -10%)
    }
    .popular__link {
        transform: translate(30%, -10%);
    }
    .popular__title {
        transform: translate(30%, -10%);
    }
    .map__title {
        margin-bottom: 46px;
        transform: translate(30%, -10%);
    }
    .map__iframe {
        height: 350px;
        transform: translate(30%, -10%);
    }
    .popular__items {
        border-bottom: none; 
    }
    .about__inner {
        grid-gap: 20px;
        grid-template-columns: 1fr;
        transform: translate(30%, -10%);
    }
    .about__popup {
        transform: translate(-5%, -10%);
    }
}

@media (max-width: 386px) {
    .travel-info {
        height: 180vh;
         
    }
    .header {
        min-width: 775px;
    }
    .direction__img {
        width: 400px;
        height: 200px;
        transform: translate(40%, -10%);
    }
    .description__text {
        width: 400px;
        transform: translate(40%, -10%);
    }
    .popular__link {
        width: 400px;
        transform: translate(40%, -10%);
    }
    .popular__title {
        width: 400px;
        transform: translate(40%, -10%);
    }
    .map__title {
        width: 400px;
        margin-bottom: 46px;
        transform: translate(40%, -10%);
    }
    .map__iframe {
        width: 400px;
        height: 350px;
        transform: translate(40%, -10%);
    }
    .popular__items {
        border-bottom: none; 
    }
    .about__inner {
        grid-gap: 20px;
        grid-template-columns: 1fr;
        transform: translate(40%, -10%);
    }
    .about__popup {
        width: 400px;
        transform: translate(-5%, -10%);
    }
}

