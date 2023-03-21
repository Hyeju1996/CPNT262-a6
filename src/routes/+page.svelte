<sevelte: head>
    <link href="https://fonts.googleapis.com/css2?family=Nunito:ital,wght@0,300;1,200;1,300&family=Open+Sans:ital,wght@0,300;0,600;1,400;1,800&family=Poppins:ital,wght@0,300;0,400;1,300;1,400;1,500&family=Roboto:ital,wght@0,100;0,300;0,400;1,100&family=Source+Sans+Pro:ital,wght@1,900&display=swap" rel="stylesheet"> 
    
   <div class="hero">
    <h1>Welcome to South Korea</h1>
   </div>


</sevelte:>

<slot></slot>

<style>
    .hero {
        font-family: 190px;
        display: flex;
        align-items: center;
        justify-content: center;
        min-height: 80vh;
        flex: auto;
        background-image: url('https://lp-cms-production.s3.amazonaws.com/public/2019-06/09a64fea2933f6da77ab07d671d1f678-south-korea.jpg?sharp=10&vib=20&w=1200');
        background-repeat: no-repeat;
        background-size: cover;
        background-position: center;    
        }
    .hero h1 {
        font-family: 'Source Sans Pro', sans-serif;
        font-size: clamp (300px, 15vw,150px);
        color:black;
        margin: 0;
    }
 
</style>