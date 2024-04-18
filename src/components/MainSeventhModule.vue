<template>
    <div class="images">
        <img src="../assets/images/right-image.jpg" class="image__images">
        <img src="../assets/images/walk.jpg" class="image__images">
        <img src="../assets/images/girl-2.jpg" class="image__images" style="
        z-index: -10; object-position: top center !important; transform: scale(1.45);">
        <img src="../assets/images/man-from-tfr-slidebar.jpg" class="image__images">
        <img src="../assets/images/child-glasses.jpg" class="image__images">
    </div>
</template>

<style type="scss" scoped>
.images {
    display: grid;
    grid-template-columns: repeat(5, 288px);
    width: 100vw;
    height: 307px;
    overflow: hidden;

    .image__images {
        width: 100%;
        height: 307px;
        object-fit: cover !important;
        object-position: center center !important;
    }
}
</style>