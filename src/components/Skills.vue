<template>
    <div class="container">
        <transition
            appear
            enter-active-class="animated bounceInUp" 
        > 
            <div class="row text-center">
                <div class="col-md-3">
                    <h3>Web Development</h3>
                    <img class="icons" src="https://img.icons8.com/dusk/140/000000/web-design.png">
                    <WebDev />
                </div>
                <div class="col-md-3">
                    <h3>Data Science</h3>
                    <img class="icons" src="https://img.icons8.com/plasticine/150/000000/accept-database.png">
                    <DataSci />
                </div>
                <div class="col-md-3">
                    <h3>Programming Languages</h3>
                    <img class="icons" src="https://img.icons8.com/material-two-tone/120/000000/programming.png">
                    <ProgLang />
                </div>
                <div class="col-md-3">
                    <h3>Other Skills</h3>
                    <img class="icons" src="https://img.icons8.com/dusk/120/000000/programming-flag.png">
                    <Other />
                </div>
            </div>
        </transition>
    </div>
  
</template>

<script>
import WebDev from './Skills/WebDev'
import DataSci from './Skills/DataSci'
import ProgLang from './Skills/ProgLang'
import Other from './Skills/Other'
export default {
    data(){
        return{

        }
    },
    components: {
        WebDev,
        DataSci,
        ProgLang,
        Other
    }

}
</script>

<style>
h3{
    font-family: 'Long Cang', cursive;
}

.icons{
    margin-top: 20px;
    margin-bottom: 20px;
}

</style>