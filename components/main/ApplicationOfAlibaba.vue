<template>
    <div class="hs-application">
        <div class="columns">
            <div class="column is-offset-one-quarter">
                <figure class="iamge">
                    <img src="~assets/img/index70_2.png" />
                </figure>
            </div>
            <div class="column">
                <b-button @click="gotoRegister" size="is-large">가입문의</b-button>
            </div>
        </div>
        <div class="columns">
        </div>
    </div>
</template>

<script>
export default {
  methods:{
        gotoRegister(){
            window.open('https://forms.gle/uX1gfGShtdmv26kt8');
        }
  }
}
</script>