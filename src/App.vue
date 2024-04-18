<template>
    <TheHeader />
    <MainFirstModule />
    <MainSecondModule />
    <MainThirdModule />
    <MainQuarterModule />
    <MainFifthModule />
    <MainSixthModule />
    <MainSeventhModule />
</template>

<script lang="js">
import TheHeader from "./components/TheHeader";
import MainFirstModule from "./components/MainFirstModule";
import MainSecondModule from "./components/MainSecondModule";
import MainThirdModule from "./components/MainThirdModule";
import MainQuarterModule from "./components/MainQuarterModule";
import MainFifthModule from "./components/MainFifthModule";
import MainSixthModule from "./components/MainSixthModule";
import MainSeventhModule from "./components/MainSeventhModule";

export default {
    name: 'App',
    components: {
        TheHeader,
        MainFirstModule,
        MainSecondModule,
        MainThirdModule,
        MainQuarterModule,
        MainFifthModule,
        MainSixthModule,
        MainSeventhModule
    },

    data() {
        return {

        }
    }
}
</script>

<style type="scss">
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    user-select: none;
    -moz-user-select: none;
    -webkit-user-select: none;
}
</style>