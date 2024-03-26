# Get Wash
Одностраничник адаптируемый на разные разрешения экрана был преимущественно использован boostrap с модулем scss.
## Технологии
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![Bootstrap](https://img.shields.io/badge/bootstrap-%238511FA.svg?style=for-the-badge&logo=bootstrap&logoColor=white)
![SASS](https://img.shields.io/badge/SASS-hotpink.svg?style=for-the-badge&logo=SASS&logoColor=white)
## Bootstrap
В headere был использован bootstrap, при уменьшении разрешения до 992px на экране выходит кнопка с навигацией. 
``` html
    <header class="header">
        <div class="container">
            <nav class="navbar navbar-expand-lg mt-4">
                <div class="container-fluid">
                    <a class="navbar-brand" href="#"><img src="img/GetWash.svg" alt="logo"></a>
                    <button class="navbar-toggler" type="button" data-bs-toggle="collapse"
                        data-bs-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false"
                        aria-label="Toggle navigation">
                        <span class="navbar-toggler-icon"></span>
                    </button>
                    <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
                        <div class="navbar-nav text-md-center text-sm-center">
                            <a class="nav-link ms-lg-3 me-lg-2 text-nowrap" aria-current="page" href="#">Как
                                использовать</a>
                            <a class="nav-link ms-lg-3" href="#">Партнерам</a>
                            <a class="nav-link ms-lg-5 me-lg-1" href="#">Скачать</a>
                            <a class="nav-link ms-lg-4 me-lg-5" href="#">Отзывы</a>
                            <button type="button" class="haeder__btn  text-nowrap">Получить доступ</button>
                        </div>
                    </div>
                </div>
            </nav>
        </div>
    </header>


```
![logo](img/header-pic-md.PNG)


[Figma](https://www.figma.com/file/jQ4cfanZXfDBmsXOyDh6ol/Realco-project?type=design&node-id=8-62&mode=design&t=5bN43qYv8CAcgQSP-0)
