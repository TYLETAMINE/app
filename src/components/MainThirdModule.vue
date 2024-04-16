<template>
    <div class="info-title-image__third-module">
        <div class="left-info-block">
            <div class="images-layout"
            style="margin-left: 17px;">
                <img src="../assets/images/girl.jpg" class="img img-left-block">
            </div>

            <div class="title__left-block">
                <p class="title">Пальто из исскуственного меха</p>
                <div class="sub-title__title">
                    <p class="sub-title">79.95 EUR</p>
                </div>
            </div>
        </div>

        <div class="right-info-block">
            <div class="images-layout">
                <img src="../assets/images/girl-2.jpg" class="img img-left-block">
            </div>

            <div class="title__right-block">
                <p class="title">Пуховик с воротником</p>
                <div class="sub-title__title">
                    <p class="sub-title">89.95 EUR</p>
                </div>
            </div>
        </div>
    </div>
</template>

<style type="scss">
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
            background: url(../assets/images/girl.jpg);

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
        .images-layout {
            width: 449px;
            height: 302px;
            background: url(../assets/images/look10.jpg);

            .img {
                width: 302px;
            }
        }
    }


}
</style>