<template>
<div class="page">
  <div class="container">
    <div class="page-divider mb-3">  
      <img class="page-divider__cube" src="../assets/SVG/cube.svg" alt="">
      <div class="page-divider__title">My V-Tell</div>
    </div> 
    <div class="myvtell">
        <div class="myvtell__title">Enter</div>
        <div class="myvtell__desc">Please authorize to access V-Tell subscriber's self care capabilities</div>
    </div>
    <div class="myvtell__form-container">
        <div class="myvtell__form-container--upper">
            <div class="myvtell__form-container--upper--flex">
                <label for="phone">Phone Number</label>
                <input type="text" name="phone" id="phone">
            </div>
            <div class="myvtell__form-container--upper--flex">
                <label for="pass">Password</label>
                <input type="passsword" name="pass" id="pass">
            </div>
            
                <button class="myvtell__btn">Enter</button>
            
            
                
            <!--<div class="myvtell__form-container--lower">
                
                <div class="myvtell__form-container--bottom">
                    <img src="../assets/myvtell/restore-badge.png" alt="">
                    <div>New Subsciber</div> 

                </div> 
            </div>-->
            
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

.flex-column {
    display: flex;
    flex-direction: column;
    align-items: flex-start;

    & label {
        color: $white;
        text-align: left;
        margin-bottom: .3rem;
    }
}

.myvtell {
    background: rgba(242, 242, 242, 0.05);
    padding: 3rem 2rem;
    text-align: left;

    &__title {
        font-size: 21px;
        margin-bottom: 1rem;
        color: $white;
    }

    &__desc {
        color:  $grey;
    }

    &__form-container {
        background: #383838;
        padding: 2rem 0;

        &--upper {
            border: 1px solid red;
            color: $white;
            margin-bottom: .3rem;
            display: flex;
            align-items: center;
            justify-content: center;

            &--flex {
                display: flex;
                flex-direction: column;
                align-items: flex-start;

            }
        }

    }
}



</style>
