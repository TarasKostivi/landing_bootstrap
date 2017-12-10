## Опис проекту

1. Шрифти які я використовував були взяті із "Google fonts".
Це шрифти які використані в проекті:
{"https://fonts.googleapis.com/css?family=Open+Sans:300" and "https://fonts.googleapis.com/css?family=Dosis:300,400" } 
2. Шрифти для іконок я брав "Fontawesome icons" і підключав за допомогою:
{css/font-awesome.min.css} 
3. Фреймверк який використовувався це:
"bootstrap.min.js"
4. Класи і компоненти які Я використовував:
header-nav, default-section, title, small-section, default-text, nav-tabs, standart-form, container, tabpanel, row,
portfolio-text.
5. Я задавав @media (max-width: 1199px а в Google превіряв на 992px; пк, ноутбуки,):
Я поміняв блокам (About studio, Services, Why choose us, Letest news) замість col-lg-4 на col-md-4 для того щоб помістилося в 4 колонки.
6. @media (max-width: 991px а в Google превіряв на 768px; планшети 10"):
Я поміняв (our-team) col-sm-12 щоб картинки вирівнялися по всіх 12 колонків і на (services) задав іконкам:
.services-tab .nav-tabs > li {
    width: 33.333%;
    margin-bottom: 30px;
тоді блокам задав col-xs-12 
(Why choose us): 
col-xs-12;
На карусель задав .riviews .carousel p{
    padding: 0 50px;
}
Для того щоб текст відступив від прaвої і від лівой сторони.
Для (Contact) задав  col-xs-12;
7. @media (max-width: 767px а в Google превіряв на 600px; планшети 7"):
На шапку зробив гврмошку з допомогою bootstrap щоб навігація з ліва стала одна під одною щоб на телефонах було зручніше.
На карусель задав для кнопок і для тексту:
.riviews .carousel p {
    padding: 0 50px;

.riviews .carousel-control {
    margin-left: -58px;

.riviews .carousel-control.right {
    margin-right: -58px;

(Contact) задав відступи між ними .contact-us .contact-item{
padding-bottom: 20px;
}   
(Form) зробив щоб вона було в стовпчик і на textarea{
 margin-top: 10px;   
} 
8. @media (max-width: 599px а в Google превіряв на 480px; телефони 4" - 4.7"):
в блоці stay informed{
    задав падінги щоб кнопка відступила з верху.
}
На сам inner задав{
    height: inherit;
    padding: 150px 0;
}
(max-width: 479px а в Google превіряв на 320px; телефони 3>" - 4.7"):
поставив іконки в services  одна під одною: 
.services-tab .nav-tabs > li {
    width: 100%;
}
і текст вирівняв по центру; 
поміняв шрифт в каруселях .riviews .carousel p {
    font-size: 12px;
}