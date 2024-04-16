<template>
    <div class="info-title-image__first-module">
        <div class="left-info-block">
            <div class="image-layout">
                <div class="images-left-block">
                    <img src="../assets/images/center-title-image.jpg" class="first-img">
                    <img src="../assets/images/center-title-image.jpg" class="second-img">
                </div>
            </div>

            <div class="title__left-block">
                <p class="l-text">Пальто с капюшоном с высоким воротником и длинными рукавами с
                    эластичными манжетами. Передние прорезные карманы на кнопках,
                    накладные карманы, открывающиеся сбоку, боковые молнии по краю,
                    функциональная внутренняя кулиска. передняя часть на молнии,
                    скрытая планкой на кнопках.</p>
            </div>
        </div>

        <div class="right-info-block">
            <div class="main-title__right-block">
                <h2 class="r-custom">ПОСЛЕДНИЕ ТЕНДЕНЦИИ ИЗ НОВОЙ КОЛЛЕКЦИИ ZARA</h2>

                <div class="sub-title__right-block">
                    <p class="sub-title">Обновите свой гардероб в новом сезоне и делайте покупки в нашем еженедельном
                        редакторе новинок в
                        Интернете в Zara. От нашей модной женской коллекции до непринужденной линии TRF - есть модели на
                        любой вкус и на любой случай. Узнавайте о последних модных тенденциях здесь и сейчас вместе с
                        нами.</p>
                </div>
            </div>

            <div class="image-block__right-block">
                <div class="main-block__image-block">
                    <img src="../assets/images/right-image.jpg" class="first-img">
                    <img src="../assets/images/right-image.jpg" class="second-img">
                </div>
            </div>
        </div>
    </div>
</template>

<style type="scss" scoped>
@import url('https://fonts.googleapis.com/css2?family=Open+Sans:ital,wght@0,300..800;1,300..800&display=swap');

.info-title-image__first-module {
    display: grid;
    margin-top: 20px;
    justify-content: center;
    grid-template-columns: repeat(2, 580px);

    .left-info-block {
        display: grid;
        align-items: center;
        justify-content: center;

        .image-layout {
            margin: 0 72px 0 72px;

            .images-left-block {
                display: grid;
                align-items: center;
                justify-content: center;
                grid-template-columns: repeat(2, auto);

                .first-img {
                    width: 100px;
                    height: 334px;
                    object-fit: cover;
                    object-position: -140px;
                }

                .second-img {
                    width: 337px;
                    height: 479px;
                    object-fit: cover;
                    object-position: 100% center;
                }
            }
        }

        .title__left-block {
            width: 100%;
            width: 581px;
            display: grid;
            padding: 30px;
            align-items: self-start;

            .l-text {
                font-style: italic;
                font-size: 0.875rem;
                font-family: 'Open Sans';
            }
        }
    }

    .right-info-block {
        height: 700px;
        margin-top: 30px;

        .main-title__right-block {

            .r-custom {
                line-height: 1.3;
                font-weight: 700;
                font-size: 2.25rem;
                padding: 30px 0 30px 43px;
                font-family: Georgia, serif;
            }

            .sub-title__right-block {
                font-style: italic;
                font-size: 0.875rem;
                padding: 0 0 0 43px;
                font-family: 'Open Sans';
            }
        }

        .image-block__right-block {

            .main-block__image-block {
                display: grid;
                padding-top: 10px;
                justify-content: center;

                .first-img {
                    z-index: 2;
                    width: 480px;
                    height: 258px;
                    object-fit: cover;
                    border: 16px solid #eed490;
                }

                .second-img {
                    z-index: 1;
                    top: -165px;
                    left: 320px;
                    width: 193px;
                    height: 213px;
                    object-fit: cover;
                    position: relative;
                }
            }
        }
    }
}
</style>