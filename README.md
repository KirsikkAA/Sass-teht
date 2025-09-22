variables.scss on käytetty $primary-color, $secondary-color, $background-color, $color-text, $color-text-2, $color-light, $font-family ja $container-width

mixins.scss on @mixin container, @mixin button ja @mixin respond

layout.scss on esimerkiksi .site-header, jonka sisällä on .container, .logo, .main-nav
.main-link:iin kuuluu &:hover, jossa olen käyttänyt myös lighten() funktiota

Responsivuutta varten olen käyttänyt - grid-template-columns: 2fr 1fr;
ja pienelle näytölle grid-template-columns: 1fr;

Eri komponenteille on omat tyylit esim. .btn, .hero, .card, .sidebar

style.scss on 
@import 'variables';
@import 'mixins';
@import 'layout';
,joka kääntää tiedoston style.css
