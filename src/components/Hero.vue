<template>
    <div class="hero">
        <div class="hero-info">
            <div class="hero-info-text">
                <h2 class="hero-info__title">
                Luxury homeware for people who love timeless design quality
                </h2>
                <span class="hero-info__description">
                    Shop the new Spring 2022 collection today
                </span>
            </div>
            <a href="#" class="hero-info__link">View collection</a>
        </div>
    </div>
</template>

<style lang="scss" scoped>
    .hero {
        background: url('/img/hero.jpg');
        height: 704px;
        background-size: cover;
        display: flex;
        align-items: center;
        justify-content: flex-end;
        padding-right: 80px;
        &-info {
            background-color: #fff;
            max-width: 630px;
            padding: 50px 55px;
            height: 444px;
            display: flex;
            flex-direction: column;
            justify-content: space-between;
            top: 130px;
            right: 80px;
            &__link {
                color: #2A254B;
                text-decoration: none;
                &:hover {
                    text-decoration: underline;
                }
            }
            &__title {
                font-family: 'Clash Display', sans-serif;
                font-weight: 400;
                font-size: 32px;
                margin: 0 0 20px 0;
                line-height: 1.5;
            }
            &__description {
                color: #5B5676;
                font-size: 18px;
            }
        }
    }
</style>



