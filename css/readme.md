    /*media query cc3*/
@media screen and (min-width:768px) and (max-width:1024px){
   div#anunciotablet {
    display:block; /*exibe o anúncio em telas de tablet*/
    }
}
@media screen and (max-width:569px){
    nav#menu {
        margin: 0 15px;
    }
}

@media screen and (max-width: 380px){
    nav#menu {
        height: auto;
    }
}
    nav#menu a {
        display: block;
         height: auto;
         margin: 5px 0;
         border-bottom:1px solid #fff;
    }
nav#menu a:last-child {
    border-bottom: none;
}

div#principal{
    display: none;
}