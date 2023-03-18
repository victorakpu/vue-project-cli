
<template>
    <div class="main-contact">
        <div >

            <h1 class="contact">Contact Us</h1>
            <p class="info-contact">
                want to give us feedback?
                Please do send us a <a class="a-link" href="mailto:akpuvic@gmail.com">mail</a>
            </p>

            <div class="socials">

                <h2 class="follow">Follow our socials</h2>
                    <a href="https://wa.me/message/FIDKYGB2FUMVL1">
                    <img src="wh.png" width="35px" height="35px" alt="Whatsapp:+2347045629607"/></a>

                    <a href="https://www.facebook.com/profile.php?id=100089193985240">
                        <img src="fb.png" width="35px" height="35px" alt="Facebook: King Victor"/>
                    </a>

                     <a href="https://www.instagram.com/kingvhikk/">
                        <img src ="ig.png" width="35px" height="35px" alt="Instagram: Kingvhikk"/>
                     </a>

                     <a href="https://twitter.com/imdisturbing9ja?t=vpGPfMx2TSzwTVBfgaFCbA&s=09">
                        <img src="twt.jpg" width="35px" height="35px" alt="Twitter: imdisturbing9ja"/></a>

                    <a href="t.me/@technixan">
                        <img src="tel.png" width="35px" height="35px" alt="Telegram: @technixan"/></a>
                
                    <a href="https://github.com/victorakpu">
                        <img src="github.png" width="35px" height="35px" alt="Github: victorakpu"/>
                    </a>


                    
                </div>
            </div>

        

    </div>

</template>

<script>
export default {
  name: 'ContactUs',
  
}
</script>

<style>

 
.main-contact{
  float: center;
    margin-top: 100px;
}
.contact{
    color:rgba(198,123,17,1);
}
.info-contact{
    font-size: 20px;
    color:#660da2;
    margin-top: 50px;
}
.socials{
    margin-top: 30px;
    margin-left: 30px; 

 }
img{
    background-color: #660da2;
    margin: 0 10px;
    border-radius: 5px ;
    border: 10px;
    margin: bottom 10px;
    margin-top: 8px ;
    
}
img:hover{
    background-color: lightgreen;
   color: #066000;
}
.follow{
    color:rgba(198,123,17,1);
    margin-top: 10px;
    margin-left: 10px;
}
.a-link{
    text-decoration: solid;
    color: rgba(198,123,17,1);
}
</style>