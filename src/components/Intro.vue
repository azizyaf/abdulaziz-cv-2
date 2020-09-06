<template>
    <div>
        <div class="container-fluid px-0">
            <article class="main-image pull-down">
                <section>
                    <h1>Hello!</h1>
                    <h2><span>I'm</span> {{myName}}</h2>
                    <span>{{headline}}</span>
                    <!-- <p>Welcome to my website!</p> -->
                    <div class="social-media">
                        <a href="https://www.linkedin.com/in/azizyaf/" target="_blank">
                            <div class="fab fa-linkedin"></div>
                        </a>
                        <a href="https://www.instagram.com/azizyah95/" target="_blank">
                            <div class="fab fa-instagram"></div>
                        </a>
                        <a href="https://github.com/azizyaf" target="_blank">
                            <div class="fab fa-github"></div>
                        </a>
                    </div>
                </section>
            </article>
        </div>
        
    </div>
</template>

<script>
export default {
    data: function(){
        return{
            myName: 'Abdulaziz Yahya',
            headline: 'Full-Stack Web Developer'
        }
    }

}
</script>

<style scoped>
article{
    display: flex;
    justify-content: center;
    align-content: center;
    width: 100%;
    padding: 0 10px;
}
section{
    margin-top: 10%;
}

h1{
    font-family: 'Modak', cursive;
    font-size: 80px;
    margin-bottom: 20px;
}

h2{
    font-family: 'Fascinate Inline', cursive;
}

h2 span{
    font-family: 'Long Cang', cursive;
}

span{
    display: block;
    padding-bottom: 30ox;
    font-weight: bold;
}

.main-image{
    min-height: 100vh;
    background-size: cover;
    padding: 0 10px;
    text-align: center;
}

.main-image{
    background-image: url('https://rotarympls.org/wp-content/uploads/2017/05/main_background_yellow_city2.jpg');
}

.social-media{
    font-size: 40px;
    margin-top: 40px;
}

.social-media div{
    margin: 15px;
    color: black;
}

.social-media div:hover{
    color: white;
}
</style>