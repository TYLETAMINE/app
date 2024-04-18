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
    height: 107.8vh;
    background-size: cover;
    background-repeat: no-repeat;
    background-position: 50% 50%;

    .header__title {
        width: 100%;
        height: 100%;
        display: grid;
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
</style>