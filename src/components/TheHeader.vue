<template>
    <header class="header">
        <div class="main-title__header">
            <div class="zara-title">
                <div class="cemter-title-img">
                    <img class="image__center-title-img"
                    src="../assets/images/center-title-image.jpg" 
                    alt="Zara Collection 2024" />
                </div>
            </div>
        </div>
    </header>
</template>

<script>
export default {

}
</script>

<style type="scss" scoped>
.header {
    background: url(../assets/images/headerImage.jpg);
    
    width: 100%;
    height: 107.8vh;
    background-size: cover;
    background-repeat: no-repeat;
    background-position: 50% 50%;

    .main-title__header {
        width: 100%;
        height: 100%;
        display: grid;
        align-items: center;
        justify-content: center;
        background-color: rgba(0, 0, 0, 0.2);

        .zara-title {
            background: url(../assets/images/zara-title.png);
            
            width: 998px;
            height: 100vh;
            display: grid;
            align-items: center;
            background-size: contain;
            background-repeat: no-repeat;
            background-position: center center;
        }

        .cemter-title-img {
            display: grid;
            align-items: center;
            justify-content: center;

            .image__center-title-img {
                width: 297px;
                height: 463px;
                object-fit: cover;
                object-position: 6.41%;
            }
        }
    }
}
</style>