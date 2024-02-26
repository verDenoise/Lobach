<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Home</title>
    <link rel="stylesheet" href="css/style.css">

    <link rel="stylesheet" href="css/media.css">
    <link rel="icon" type="image/x-icon" href="img/icon.png">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.3/dist/css/bootstrap.min.css" rel="stylesheet"
          integrity="sha384-rbsA2VBKQhggwzxH7pPCaAqO46MgnOM80zW1RWuH61DGLwZJEdK2Kadq2F9CUG65" crossorigin="anonymous">
    <link rel="stylesheet" href="css/hamburger.css">
</head>

<body>
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.3/dist/js/bootstrap.bundle.min.js"
        integrity="sha384-kenU1KFdBIe4zVF0s0G1M5b4hcpxyD9F7jL+jjXkk+Q2h455rYXK/7HAuoJl+0I4"
        crossorigin="anonymous"></script>

<header>

    <section class="top-nav">

        <div class="logo"></div>
        <input id="menu__toggle" type="checkbox"/>
        <label class="menu__btn" for="menu__toggle">
            <span></span>
        </label>

        <ul class="menu__box">
            <li><a class="menu__item" href="index.html">HOME</a></li>
            <li><a class="menu__item" href="portfolio.html">PORTFOLIO</a></li>
            <li><a class="menu__item" href="blog.html">BLOG</a></li>
            <li><a class="menu__item" href="about.html">ABOUT</a></li>
        </ul>

    </section>

    <div class="header_logo">
        <a href="index.html">Design flat</a>
    </div>

    <nav class="header_nav" id="header_nav">
        <a href="index.html">HOME</a>
        <a href="portfolio.html">PORTFOLIO</a>
        <a href="blog.html">BLOG</a>
        <a href="about.html">ABOUT</a>
    </nav>

</header>

<main>

    <div class="my_main">


        <div class="main_welcome">
            <h1>РЕМОНТЫ ЛЮБОЙ СЛОЖНОСТИ</h1>

            <!-- Кнопка-триггер модального окна -->
            <button type="button" class="btn btn-success" data-bs-toggle="modal" data-bs-target="#exampleModal">
                Заказать обратный звонок
            </button>

            <!-- Модальное окно -->
            <div class="modal fade" id="exampleModal" tabindex="-1" aria-labelledby="exampleModalLabel"
                 aria-hidden="true">
                <div class="modal-dialog">
                    <div class="modal-content">
                        <div class="modal-header">
                            <h5 class="modal-title" id="exampleModalLabel">Заказ обратного звонка</h5>
                            <button type="button" class="btn-close" data-bs-dismiss="modal"
                                    aria-label="Закрыть"></button>
                        </div>
                        <div class="modal-body">
                            <form class="ml-2">
                                <div class="form-group">
                                    <label for="exampleInputNumber">Номер</label>
                                    <input type="tel" class="form-control" id="exampleInputNumber"
                                           aria-describedby="numberHelp" placeholder="Введите номер">
                                    <small id="numberHelp" class="form-text text-muted">Мы не предоставляем ваши данные
                                        третьим
                                        лицам</small>
                                </div>
                                <div class="form-group">
                                    <label for="exampleInputFIO">Фамилия и имя</label>
                                    <input type="text" class="form-control" id="exampleInputFIO"
                                           placeholder="ФИО">
                                </div>
                            </form>

                        </div>
                        <div class="modal-footer">
                            <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Закрыть</button>
                            <button type="button" class="btn btn-success" data-bs-dismiss="modal">Принять</button>
                        </div>
                    </div>
                </div>
            </div>

        </div>

        <div class="cards">
            <div class="welcome-box">
                <h2>Черновая отделка</h2>
                <h2>от 2399₽ за м²</h2>
            </div>
            <div class="welcome-box">
                <h2>Чистовая отделка</h2>
                <h2>от 3499₽ за м²</h2>
            </div>
            <div class="welcome-box">
                <h2>Евроремонт</h2>
                <h2>от 6999₽ за м²</h2>
            </div>
            <div class="welcome-box">
                <h2>Долларремонт</h2>
                <h2>от 9999₽ за м²</h2>
            </div>
        </div>

    </div>

    <div class="my_main_next">
        <div id="carouselExampleAutoplaying" class="carousel slide carousel-fade" data-bs-ride="carousel">
            <div class="carousel-inner">
                <div class="carousel-item active">
                    <img src="img/main2.jpg" class="d-block w-100">
                </div>
                <div class="carousel-item">
                    <img src="img/main3.jpg" class="d-block w-100">
                </div>
                <div class="carousel-item">
                    <img src="img/main1.jpg" class="d-block w-100">
                </div>
                <div class="carousel-item">
                    <img src="img/main4.jpg" class="d-block w-100">
                </div>
            </div>
            <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleAutoplaying"
                    data-bs-slide="prev">
                <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            </button>
            <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleAutoplaying"
                    data-bs-slide="next">
                <span class="carousel-control-next-icon" aria-hidden="true"></span>
            </button>
        </div>
    </div>

    <div class="main_text">
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore
            magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea
            commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat
            nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit
            anim id est laborum
        </p>
    </div>

</main>

<footer>

    <div class="wrapper">

        <h1>Ответы на самые частые вопросы</h1>

        <div class="line">

            <div style="padding: 2.5rem;">
                <div class="team_accordion">

                    <div style="--bs-accordion-active-color: #e1e141; --bs-accordion-active-bg: #5a5a5a"
                         class="accordion" id="accordionExample">
                        <div class="accordion-item">
                            <h2 class="accordion-header" id="headingOne">
                                <button style="font-size: 1.2rem" class="accordion-button" type="button"
                                        data-bs-toggle="collapse"
                                        data-bs-target="#collapseOne" aria-expanded="false" aria-controls="collapseOne">
                                    <strong>Как происходит оплата?</strong>
                                </button>
                            </h2>
                            <div id="collapseOne" class="accordion-collapse collapse show" aria-labelledby="headingOne"
                                 data-bs-parent="#accordionExample">
                                <div class="accordion-body">
                                    <p class="answer"><strong>Оплата происходит поэтапно.</strong>
                                        <li>Вы оплачиваете каждый этап после того, как проверили качество выполненной
                                            работы
                                            и
                                            подписали
                                            акт.
                                        </li>
                                    </p>

                                </div>
                            </div>
                        </div>

                        <div class="accordion-item">
                            <h2 class="accordion-header" id="headingTwo">
                                <button style="font-size: 1.2rem" class="accordion-button collapsed" type="button"
                                        data-bs-toggle="collapse"
                                        data-bs-target="#collapseTwo" aria-expanded="false" aria-controls="collapseTwo">
                                    <strong>В каком формате производится оплата?</strong>
                                </button>
                            </h2>
                            <div id="collapseTwo" class="accordion-collapse collapse" aria-labelledby="headingTwo"
                                 data-bs-parent="#accordionExample">
                                <div class="accordion-body">
                                    <p class="answer"><strong>Оплата производится любым удобным для вас
                                        способом:</strong>
                                        <li>наличный расчёт;</li>
                                        <li>на р/с;</li>
                                        <li>оплата банковской картой.</li>
                                    </p>
                                </div>
                            </div>
                        </div>

                        <div class="accordion-item">
                            <h2 class="accordion-header" id="headingThree">
                                <button style="font-size: 1.2rem" class="accordion-button collapsed" type="button"
                                        data-bs-toggle="collapse"
                                        data-bs-target="#collapseThree" aria-expanded="false"
                                        aria-controls="collapseThree">
                                    <strong>Стоимость в смете окончательная?</strong>
                                </button>
                            </h2>
                            <div id="collapseThree" class="accordion-collapse collapse" aria-labelledby="headingThree"
                                 data-bs-parent="#accordionExample">
                                <div class="accordion-body">
                                    <p class="answer"><strong>Смета и цены фиксируются за Вами после подписания и в
                                        процессе
                                        ремонта не
                                        меняются.</strong>
                                        <li>Изменения возможны в случае вашего желания произвести дополнительные работы
                                            путём
                                            подписания
                                            двустороннего дополнительного соглашения
                                        </li>
                                    </p>
                                </div>
                            </div>
                        </div>

                        <div class="accordion-item">
                            <h2 class="accordion-header" id="headingFour">
                                <button style="font-size: 1.2rem" class="accordion-button collapsed" type="button"
                                        data-bs-toggle="collapse"
                                        data-bs-target="#collapseFour" aria-expanded="false"
                                        aria-controls="collapseFour">
                                    <strong>В какие сроки будет сделан ремонт?</strong>
                                </button>
                            </h2>
                            <div id="collapseFour" class="accordion-collapse collapse" aria-labelledby="headingFour"
                                 data-bs-parent="#accordionExample">
                                <div class="accordion-body">
                                    <p class="answer"><strong>Сроки и стоимость фиксируются договором и не меняются на
                                        протяжении всего ремонта.</strong>
                                        <li>99% наших выполненных ремонтов были сделаны в срок, а какие-то сданы раньше.
                                        </li>
                                    </p>
                                </div>
                            </div>
                        </div>

                        <div class="accordion-item">
                            <h2 class="accordion-header" id="headingFive">
                                <button style="font-size: 1.2rem" class="accordion-button collapsed" type="button"
                                        data-bs-toggle="collapse"
                                        data-bs-target="#collapseFive" aria-expanded="false"
                                        aria-controls="collapseFive">
                                    <strong>Как узнать стоимость ремонта?</strong>
                                </button>
                            </h2>
                            <div id="collapseFive" class="accordion-collapse collapse" aria-labelledby="headingFive"
                                 data-bs-parent="#accordionExample">
                                <div class="accordion-body">
                                    <p class="answer"><strong>Предварительную стоимость можно узнать у нашего менеджера
                                        или
                                        посчитать
                                        самостоятельно, исходя из цен указанных на сайте.</strong>
                                        <li>Точную стоимость определит только специалист после замеров и согласования
                                            всех
                                            работ.
                                        </li>
                                    </p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</footer>

</body>
</html>
