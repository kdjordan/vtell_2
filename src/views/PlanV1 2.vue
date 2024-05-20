<template>
<div class="page">
    <div class="container">
        <PageCrumbs path="plans / v1" />
        <PageDivider title="PLan V-1" />
        <div class="plan-page">
            <div class="plan-page__button-container">
                <button class="plan-page__btn active">More about tariff</button>
                <button class="plan-page__btn">Complementary services</button>
                <button class="plan-page__btn">List of countries</button>
                <button class="plan-page__btn">Calculator</button>
            </div>

        </div>
    </div>
</div>

</template>
<script>
import PageDivider from '@/components/PageDivider';
import PageCrumbs from '@/components/PageCrumbs';
export default {
    components: {PageDivider, PageCrumbs}
}
</script>

<style lang="scss">
@import '../scss/_variables.scss';
@import '../scss/_base.scss';
@import '../scss/_utilities.scss';
@import '../scss/_page.scss';

.plan-page {
    background-color: #404040;
    padding: 64px 35px 48px;
    display: inline-block;
    width: 100%;
    max-width: 895px;
    text-align: left;
    position: relative;
    font-size: 16px;

    &__button-container {
        display: flex;

        @media(max-width: 890px) {
            flex-direction: column;
        }

    }

    &__btn {
        display: block;
        padding: 20px 26px;
        background-color: #737370;
        border: 1px solid transparent;
        color: white;
        font-size: 20px;
        margin: 0 .1rem;

         @media(max-width: 890px) {
            margin: .1rem 0;
        }
    }
}

.active {
    background: $red;
    
}

</style>
