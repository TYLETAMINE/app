<template>
    <div class="info-title-image__third-module">
        <div class="left-info-block">
            <div class="images-layout"
            style="margin-left: 17px;">
                <img src="../assets/images/child-on-bike.jpg" class="img img-left-block">
            </div>

            <div class="title__left-block">
                <p class="title">Пуфер парка</p>
                <div class="sub-title__title">
                    <p class="sub-title">35.95 EUR</p>
                </div>
            </div>
        </div>

        <div class="right-info-block">
            <div class="images-layout">
                <img src="../assets/images/child-sit.jpg" class="img img-left-block">
            </div>

            <div class="title__right-block">
                <p class="title">Толстовка с логотипом с пийстами</p>
                <div class="sub-title__title">
                    <p class="sub-title">17.95 EUR</p>
                </div>
            </div>
        </div>
    </div>
</template>

<style type="scss" scoped>
.info-title-image__third-module {
    display: grid;
    height: 100vh;
    grid-gap: 140px;
    align-items: center;
    justify-content: center;
    grid-template-columns: repeat(2, 466px);

    .left-info-block,
    .right-info-block {

        .images-layout {
            margin: 77px 0 77px 0;
            width: 449px;
            height: 306px;
            display: grid;
            align-content: center;
            justify-content: center;
            align-items: center;
            background-size: cover !important;
            background-position: center center !important;
            background-repeat: no-repeat !important;
            background: url(../assets/images/child-on-bike.jpg);

            .img {
                object-fit: cover;
                width: 340px;
                height: 460px;
            }
        }

        .title__left-block,
        .title__right-block {
            padding-top: 30px;
            font-family: Georgia, 'Times New Roman', Times, serif;
            text-transform: uppercase;
            font-size: 2.25em;
            line-height: 1.1;

            .sub-title__title {

                .sub-title {
                    font-weight: 700;
                    word-wrap: break-word;
                    font-size: 1.25rem;
                    line-height: 1.2;
                    margin-top: 15px;
                    font-family: Roboto, sans-serif;
                }
            }
        }
    }

    .right-info-block {
        width: 515px;
        .images-layout {
            width: 449px;
            height: 302px;
            background: url(../assets/images/child-sit.jpg);

            .img {
                width: 302px;
                object-position: -50px center;
            }
        }
    }


}
</style>