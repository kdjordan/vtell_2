<template>
<div class="page">
    <div class="container">
        <div class="crumbs">
            <img class="crumbs__img" src="../assets/back-button.png" alt="">
        <div class="crumbs__path">/&nbsp;<a href="/">HOME</a>&nbsp;/&nbsp;PARTNER PROGRAM</div>
        </div>
        <div class="page-divider mb-3">  
        <img class="page-divider__cube" src="../assets/SVG/cube.svg" alt="">
        <div class="page-divider__title">PARTNER PROGRAM</div>
        </div> 
        <img class="partnership__img mb-1"  src="../assets/pages/partnership.jpg" alt="">
        <div class="partnership__desc">
        <p>V-Tell is interested in collaboration with sales agents to promote our mobile services. The Partner’s target is to spread our mobile network services by attracting new Subscribers. V-Tell offers enticing compensation, which is 10% of a monthly subscription fee. The more customers you sign up, the more you earn.</p>
        <p class="red">Please use a partner compensation calculator to estimate your future earnings</p>
        <div class="calc__container">
            <div class="calc__header">
                <div>Subscriber Count</div>
                <div>Amount of additional phone Monthly Plan numbers sold (extra phone numbers purchased by a Subscriber)</div>
                <div>Monthly Plan</div>
                <!-- <div>&nbsp;</div> -->
            </div>
            <div class="calc__row">
                <div>
                    <input class="calc__row--input" type="text" name="" id="">
                </div>
                <div>
                    <input class="calc__row--input" type="text" name="" id="">
                </div>
                <div>
                    <input class="calc__row--input" type="text" name="" id="">
                </div>
                <svg width="50" height="50" xmlns="http://www.w3.org/2000/svg">
                    <circle cx="25" cy="25" r="23" stroke="#E7383B" stroke-width="3" fill="transparent"></circle>
                    <line x1="14" y1="25" x2="36" y2="25" stroke="#E7383B" stroke-width="3" stroke-linecap="round"></line>
                    <line x1="25" y1="14" x2="25" y2="36" stroke="#E7383B" stroke-width="3" stroke-linecap="round"></line>
                </svg>
            </div>
            <div class="calc__row calc__row--end">
                <div class="calc__row--end-curr">Currency</div>
            </div>
            <div class="calc__row calc__row--end">
                <div>
                    <input class="calc__row--input" type="text" name="" id="">
                </div>
            </div>
            
        </div>
        <button class="partnership__btn">Calculate</button>
        </div>
        <div class="partner-boxes">
            <div class="partner-boxes__box partner-boxes__box--1">
                <div class="partner-boxes__box--desc">V-Tell offers Unique Products</div>
            </div>
            <div class="partner-boxes__box partner-boxes__box--2">
                <div class="partner-boxes__box--desc">Attractive Partner’s compensation for successful Sales is guaranteed</div>
            </div>
            <div class="partner-boxes__box partner-boxes__box--3">
                <div class="partner-boxes__box--desc">Partners will always be informed about our latest news, promotions, and discounts.</div>
            </div>
            <div class="partner-boxes__box partner-boxes__box--4">
                <div class="partner-boxes__box--desc">My V-TELL Business (soon)</div>
            </div>
            <div class="partner-boxes__box partner-boxes__box--5">
                <div class="partner-boxes__box--desc">Attractive Partner’s compensation for successful Sales is guaranteed</div>
            </div>
            <div class="partner-boxes__box partner-boxes__box--6">
                <div class="partner-boxes__box--desc">Partners will always be informed about our latest news, promotions, and discounts.</div>
            </div>
            <div class="partner-boxes__box partner-boxes__box--7">
                <div class="partner-boxes__box--desc adjust">Learn more about our Terms and Conditions here</div>
            </div>

        </div>
    </div>
</div>

</template>
<script>

</script>

<style lang="scss">
@import '../scss/_variables.scss';
@import '../scss/_base.scss';
@import '../scss/_divider.scss';
@import '../scss/_utilities.scss';
@import '../scss/_page.scss';

.partner-boxes {
    display: flex;
    margin-bottom: 6px;
    flex-wrap: wrap;
    // width: 100%;
    // align-items: center;
    justify-content: space-between;
    font-size: 12px;
    line-height: 20px;
    text-transform: uppercase;

    &__box {
        background: #52524f;
        color: white;
        flex: 0 0 24%;
        padding: 1rem 0;
        margin-bottom: 1rem;
        align-self: stretch;
        background-repeat: no-repeat;
        background-position-y: 20%;
        background-position-x: center;
        transform: scale(1);
        min-width: 180px;
        cursor: pointer;
        transition: all .4s;

        &--desc {
            display: inline-block;
            margin-top: 85%;
        }

        &--1 {
            background-image: url('../assets/pages/partner/partner_1.png');

            &:hover {
                background-image: url('../assets/pages/partner/partner_1-active.png');
                transform: scale(1.04);
            }   
        }

        &--2 {
            background-image: url('../assets/pages/partner/partner_2.png');

             &:hover {
                background-image: url('../assets/pages/partner/partner_2-active.png');
                transform: scale(1.04);
            }   
        }

        &--3 {
            background-image: url('../assets/pages/partner/partner_3.png');

             &:hover {
                background-image: url('../assets/pages/partner/partner_3-active.png');
                transform: scale(1.04);
            }   
        }

        &--4 {
            background-image: url('../assets/pages/partner/partner_4.png');

             &:hover {
                background-image: url('../assets/pages/partner/partner_4-active.png');
                transform: scale(1.04);
            }   

        }

        &--5 {
            background-image: url('../assets/pages/partner/partner_5.png');

            &:hover {
                background-image: url('../assets/pages/partner/partner_5-active.png');
                transform: scale(1.04);
            }   
        }

        &--6 {
            background-image: url('../assets/pages/partner/partner_6.png');

            &:hover {
                background-image: url('../assets/pages/partner/partner_6-active.png');
                transform: scale(1.04);
            }   
        }

        &--7 {
            background-image: url('../assets/pages/partner/partner_7.png');
            flex: 0 0 49%;
            max-height: 280px;

            &:hover {
                background-image: url('../assets/pages/partner/partner_7-active.png');
                transform: scale(1.04);
            }   

            & .adjust {
                display: inline-block;
                margin-top: 42.5%;
            }
        }
    }
}

.partnership {
  &__img {
    width: 100%;
    max-width: 960px;
  }
  
  &__desc {
      background: rgba(252, 252, 252, 0.25);
      padding: 56px;
      margin: 28px 0;
      box-shadow: 0 0 6em rgba(31, 31, 31, 0.25) inset;

      & p {
        font-size: 17px;
        line-height: 26px;
        margin-bottom: 1rem;

        &.red {
            color: $red;
        }
      }


    }

    &__btn {
        cursor: pointer;
        width: 100%;
        border: 1px solid transparent;
        color: $white;
        background: $red;
        padding: 20px 0;
        font-size: 20px;
        transition: all .4s;

        &:hover {
            background: $white;
            color: $red;
        }
    }
}

.calc {
    &__header {
        display: flex;
        justify-content: space-between;
        margin-right: 5rem;

        & > div {
            font-size: 16px;
            line-height: 20px;
            color: $white;
            text-align: left;
            flex: 0 0 30%;
        }

    }
    
    &__row {
        display: flex;
        width: 100%;
        justify-content: space-between;
        align-items: center;
        color: $white;
        margin-bottom: 2rem;

        & > div {
            flex: 0 0 26%;
        }

        &--input {
            margin: 0 1rem;
            border-radius: 0;
            border: 2px #ccc solid;
            background: transparent;
            padding: 10px;
            padding-left: 40px;
            color: white;
            margin: 0;

        }

        &--end {
            justify-content: flex-end;
            padding-right: 5.8rem;

            &-curr {
                padding-right: 8.4rem;
            }
        }
    }

    &__col {
        display: flex;
        flex-direction: column;

        & > div {
            align-items: center;
            max-width: 30%;
        }

        & input[type=text] {
            max-width: 178px;
            border-radius: 0;
            border: 2px #ccc solid;
            background: transparent;
            padding: 10px;
            padding-left: 40px;
            font-size: 24px;
            color: white;
            margin: 0;
        }
    }

}

</style>
