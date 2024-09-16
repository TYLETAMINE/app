<template>
    <header class="header">
        <div class="header__title">
            <div class="title__zara">
                <div class="zara__image">
                    <img class="image__image--center" src="../assets/images/center-title-image.jpg"
                        alt="Zara Collection 2024" />
                </div>
            </div>
        </div>
    </header>
</template>

<style type="scss" scoped>
.header {
    background: url(../assets/images/headerImage.jpg);

    width: 100%;
    height: 100vh;
    background-size: cover;
    background-repeat: no-repeat;
    background-position: 50% 40%;

    .header__title {
        width: 100%;
        height: 100%;
        display: grid;
        position: relative;
        align-items: center;
        justify-content: center;
        background-color: rgba(0, 0, 0, 0.2);

        .title__zara {
            background: url(../assets/images/zara-title.png);

            width: 998px;
            height: 100vh;
            display: grid;
            align-items: center;
            background-size: contain;
            background-repeat: no-repeat;
            background-position: center center;
        }


        .zara__image {
            display: grid;
            align-items: center;
            justify-content: center;

            .image__image--center {
                width: 297px;
                height: 463px;
                object-fit: cover;
                object-position: 6.41%;
                transition: cubic-bezier(0.075, 0.82, 0.165, 1) .4s;

                &:hover {
                    transform: scale(1.08);
                }
            }
        }
    }
}

@media only screen and (-webkit-min-device-pixel-ratio: 2),
only screen and (min--moz-device-pixel-ratio: 2),
only screen and (-o-min-device-pixel-ratio: 2/1),
only screen and (min-device-pixel-ratio: 2),
only screen and (min-resolution: 192dpi),
only screen and (min-resolution: 2dppx) {

    .header {
        width: 100vw;
        height: 25vh;

        .header__title {
            height: 100%;

            .title__zara {
                width: 90vw;
                height: 100%;

                .zara__image {
                    display: none;
                }
            }
        }
    }
}
</style>