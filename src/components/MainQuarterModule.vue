<template>
    <div class="man-block man-block__quater-module">
        <div class="left-block left-block__man-block">
            <div class="title__left-block">
                <p class="title">Измените свой образ с помощью новейшей мужской одежды, обуви и аксессуаров. Откройте
                    для себя сезонные модели самых разных стилей и фасонов, обновляемые еженедельно.</p>
            </div>

            <div class="images__left-block">
                <img src="../assets/images/man-onLeft-block.jpg" class="man-on-left">
            </div>
        </div>

        <div class="right-block right-block_man-block">
            <div class="images images__right-block">
                <img src="../assets/images/man-onRight-block.jpg" class="man-on-right">
            </div>

            <div class="title__right-block">
                <p class="title">Еженедельные тенденции моды для мужчин</p>
            </div>
        </div>
    </div>
</template>

<script>

</script>

<style type="scss">
.man-block {
    padding-top: 30px;
    height: 100vh;
    display: grid;
    grid-template-columns: repeat(2, 560px);
    justify-content: center;
    font-family: 'Open Sans';
    background-color: #eed490;

    .left-block {
        width: 560px;
        display: grid;
        justify-content: center;

        .title__left-block {
            width: 520px;
            padding-top: 20px;

            .title {
                font-style: italic;
                font-size: 1em;
                line-height: 1.6;
            }
        }

        .images__left-block {
            background: url(../assets/images/right-image.jpg);
            background-size: cover;
            height: 322px;
            width: 500px;
            margin-top: 35%;
            background-position: center center;
            background-repeat: no-repeat;
            display: grid;
            justify-self: center;
            align-content: flex-end;
            justify-content: center;

            .man-on-left {
                width: 392px;
                height: 517px;
                padding-bottom: 30px;
                object-fit: cover;
            }
        }
    }

    .right-block {
        display: grid;
        /* align-items: center; */
        /* justify-content: start; */

        .images {
            width: 100%;
            height: 334px;
            display: grid;
            align-items: center;
            justify-self: center;
            background: url(../assets/images/slidemd.jpg);
            background-repeat: no-repeat;
            background-size: cover;
            background-position: center center;

            .man-on-right {
                width: 339px;
                height: 479px;
                align-self: center;
                object-fit: cover;
                display: grid;
            }
        }

        .title__right-block {
            .title {
                font-weight: 700;
                text-transform: uppercase;
                line-height: 1.3;
                font-family: Georgia, 'Times New Roman', Times, serif;
                font-size: 2.25rem;
            }
        }
    }
}
</style>