<template>
    <transition
        appear
        enter-active-class="animated bounceInUp" 
    >
        <div class="container text-center">
            <div>
                <div class="card">
                    <div class="card-body">
                        <span>Double Degree</span>
                        <p>Bachelor of Information Technology with Specialization in  SOFTWARE ENGINEERING</p>
                        <p>2015 - 2019</p>
                        <h3>FROM:</h3>
                    </div>
                </div>
                <div class="card-group">
                    <div class="card">
                        <img class="card-img-top img-thumbnail" src="../assets/segi.jpg" alt="Card image cap">
                        <div class="card-body">
                            <h5 class="card-title">
                                <a href="https://www.segi.edu.my/" target="_blank">
                                    <div>{{ segi }}</div>
                                </a>
                            </h5>
                            <p class="card-text">Petalin Jaya, Selangor 
                                MALAYSIA
                            </p>
                        </div>
                    </div>
                    <div class="card">
                        <img class="card-img-top img-thumbnail" src="https://media.glassdoor.com/l/ee/67/40/55/abertay-main-campus.jpg" alt="Card image cap">
                        <div class="card-body">
                            <h5 class="card-title">
                                <a href="https://www.abertay.ac.uk/" target="_blank">
                                    <div>{{ abertay }}</div>
                                </a>
                            </h5>
                            <p class="card-text">Dundee, Scotland
                                UK
                            </p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </transition>
    
    
    
</template>

<script>
export default {
    data: function(){
        return{
            segi: 'SEGi University',
            abertay: 'Abertay University'
        }
    }
   

}
</script>

<style scoped>

span{
    font-family: 'Long Cang', cursive;
    font-size: 30px;
}

/* .card-img-top{
    height: 180px;
    width: 240px;
} */


</style>