# namitaece.github2.io
<!DOCTYPE html>
<html lang="en">
<head>
 <!-- main banner -->

 

   
    <div class="navbar">
        <a class="active" href="#"><i class="fa fa-fw fa-home"></i>Home</a> 
        <a href="#"> <i class="fa fa-fw fa-user"></i> About</a>
        <a href="#"><i class="fa fa-fw fa-file"></i> Project</a> 
        <a href="#"><i class="fa fa-fw fa-phone"></i> Contact</a> 
        <a href="#"><i class="fa fa-fw fa-globe"></i> Experience</a>
      </div>
     
</section>





    <meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>
body {font-family: Arial, Helvetica, sans-serif;}
@import url('https://fonts.googleapis.com/css2?family=Josefin+Sans:wght@300&display=swap');
*{
    box-sizing:border-box;
    padding:0;
    margin:0;
}
.navbar {
  width: 100%;
  background-color: rgb(18, 17, 17);
  overflow: auto;
}

.navbar a {
  float: left;
  padding: 12px;
  color: rgb(152, 251, 168);
  text-decoration: none;
  font-size: 17px;
}

.navbar a:hover {
  background-color: rgba(130, 243, 110, 0.927);
}

.active {
  background-color: #3b2b3b;
}

@media screen and (max-width: 500px) {
  .navbar a {
    float: none;
    display: block;
  }
}

.navbar ul{
    display: flex;
  
}
.navbar a{
    color: rgba(15, 194, 239, 0.937);
    padding:10px;
    margin:0 5px;
}

.navbar a:hover{
    border-bottom:2px rgb(121, 111, 111) solid;
}
.navbar.flex{
    justify-content:space-between;
}





html {
  box-sizing: border-box;
}

*, *:before, *:after {
  box-sizing: inherit;
}

.column {
  float: left;
  width: 33.3%;
  margin-bottom: 16px;
  padding: 0 8px;
}

.card {
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.949);
  margin: 8px;
}

.about-section {
  padding: 50px;
  text-align: center;
  background-color: #4a4e4f;
  color: rgb(238, 114, 240);
}

.container {
  padding: 0 16px;
}

.container::after, .row::after {
  content: "";
  clear: both;
  display: table;
}

.title {
  color: rgb(18, 1, 1);
}

.button {
  border: none;
  outline: 0;
  display: inline-block;
  padding: 8px;
  color: white;
  background-color: #000;
  text-align: center;
  cursor: pointer;
  width: 100%;
}

.button:hover {
  background-color: rgb(7, 0, 0);
}
.showcase{
    height: 400px;
    background-color: rgba(4, 2, 28, 0.933);
color: rgb(28, 27, 27);
position:relative;
}

.showcase h1{
    font-size:40px;
}

.showcase p{
    margin:20px 0;
}

.showcase.grid{
    grid-template-columns:55% 45%;
    gap:30px;
}

.showcase-text{
    animation: slideInFromLeft 1s ease-in;
}
.showcase-form{
    position:relative;
    top:60px;
    height:350px;
    width:400px;
    padding:40px;
    z-index:100;
    animation: slideInFromRight 1s ease-in;
}

.showcase-form.form-control{
    margin:30px 0;
    }

    .showcase-form  input[type='text'],
    .showcase-form  input[type='email'] {
        border: 0;
        border-bottom:1px solid #e217ba;
        width:100%;
        padding:3px;
        font-size:16px;
    }
    .showcase-form input:focus{
        outline:none;
    }





.container
{max-width: 1100px;
margin:0 auto;
overflow: auto;
padding:0 40px;}

.card{
    background-color:rgba(207, 243, 87, 0.886);
    color: rgb(19, 18, 18);
    border-radius:10px;
    box-shadow:0 30px  10px rgba(0,0,0,0.2);
    padding:20px;
    margin:10px;
    
}
.btn{
    display: inline-block;
    padding:10px 30px;
    cursor:pointer;
    background: #04d5ec;
    color:rgb(28, 29, 29);
    border:none;
    border-radius: 5px;
}
.btn-outline{
    background-color: transparent;
    border:1px rgb(215, 228, 24) solid;


}

.flex{ 
    display:flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
    height:100%;
}

.grid{
    display:grid;
    grid-template-columns:repeat(2,1fr);
    gap:20px;
    justify-content:center;
    align-items:center;
    height:100%;
}
.footer.social a{
    margin:0 10px;
    
}
@media ( max-width:786px){

}
@media ( max-width:500px){
    .navbar{
        height:110px;
    }
}
.navbar.flex{
    flex-direction:column;
}
.navbar ul{
    padding:10px;
    background-color:rgba(12, 9, 9, 0.855);
}
.languages.flex{
    flex-wrap: wrap;
}
.languages .card{
    text-align: center;
    margin:18px 10px 40px;
transition: transform 0.2s ease-in;
}

.languages .card h4{
    font-size: 20px;
    margin-bottom: 10px;
}

.languages .card :hover{
    transform: translateY(-15%);
}
@keyframes slideInFromLeft{
    0% {
        transform: translateX(-100%);

    }
    100% {
        transform: translateX(0);
        
    }
}
@keyframes slideInFromRight{
    0% {
        transform: translateX(100%);

    }
    100% {
        transform: translateX(0);
        
    }
}
@keyframes slideInFromBottom{
    0% {
        transform: translateY(100%);

    }
    100% {
        transform: translateY(0);
        
    }
}
@keyframes slideInFromTop{
    0% {
        transform: translateY(-100%);

    }
    100% {
        transform: translateY(0);
        
    }
}
@media screen and (max-width: 650px) {
  .column {
    width: 100%;
    display: block;
  }
}
@import url('https://fonts.googleapis.com/css2?family=Josefin+Sans:wght@300&display=swap');
*{
    box-sizing:border-box;
    padding:0;
    margin:0;
}
body {
font-family: 'Josefin', sans-serif;
color:rgb(75, 74, 77);
line-height:1.6;
}
ul{list-style-type: none;}
a{text-decoration: none;
color:black;}
h1,h2{
    font-weight: 300;
    line-height:1.2 ;
    margin:10px,0 ;
}
p{margin: 10px,0;}
img{width:100%;}
</style>
</head>
<body>
<!-- about section-->


<section class="showcase">
  <div class="container grid">

      <div class="showcase-text">
          <h1>ABOUT ME</h1>
          <p>  
              Hello! I'm Namita S ,19 years old ,currently pursuing Btech in Electronics and Communications Engineering in Vellore Institute of Technology,Vellore.
               </p>
               <p>Learn More</p>

               </div>
               <div class="showcase-form card">
                  <h1>CONTACT INFO</h1>
                  <form>
                      <div class="form-control">
                          <input type="text" name="name" placeholder="Name"required>
                      </div>
                      <div class="form-control">
                          <input type="text" name="contact number" placeholder="Contact Number"required>
                      </div>
                      <div class="form-control">
                          <input type="text" name="email id" placeholder="Email Id"required>
                      </div>
                      <input type="submit" value="Send" class="btn btn-primary"> 
                  </form>
               </div>
      </div> 
     </div>
</section>

<section class="Hobbies">
  <h2 class="md text-center my-2">
             HOBBIES
  </h2>
  <div class="container flex">
      <div class="card">
          <h4>listening to music</h4>
      </div>
      <div class="card">
          <h4>Cycling</h4>
      </div>
      <div class="card">
          <h4>Reading Books</h4>
      </div>
      <div class="card">
          <h4>Painting</h4>
      </div>
      
  </div>
  <section class="Languages">
    <h2 class="md text-center my-2">
               LANGUAGES KNOWN
    </h2>
    <div class="container flex">
        <div class="card">
            <h4>Python</h4>
        </div>
        <div class="card">
            <h4>Java</h4>
        </div>
        <div class="card">
            <h4>C</h4>
        </div>
        <div class="card">
            <h4>Html</h4>
        </div>
        
    </div>
    
</section>


  


  <!-- Footer -->
 
  <!-- contact section-->
  

            <meta name="viewport" content="width=device-width, initial-scale=1">
<style>
body {font-family: Arial, Helvetica, sans-serif;}
* {box-sizing: border-box;}

input[type=text], select, textarea {
  width: 100%;
  padding: 12px;
  border: 1px solid #ccc;
  border-radius: 4px;
  box-sizing: border-box;
  margin-top: 6px;
  margin-bottom: 16px;
  resize: vertical;
}

input[type=submit] {
  background-color: #04AA6D;
  color: white;
  padding: 12px 20px;
  border: none;
  border-radius: 4px;
  cursor: pointer;
}

input[type=submit]:hover {
  background-color: #45a049;
}

.container {
  border-radius: 5px;
  background-color: #faf6f9;
  padding: 20px;
}
</style>
</head>
<body>


    <footer class="footer bg-dark py-5">
        <div class="container grid grid-2">
            <div>
               
                <p>Copyright &copy; 2022</p>
            </div>
<div class="body-part">
    <div class="icon-list">
        <a href="#instagram" class="instagram">
            <i class="fa fa-instagram"></i>
        </a>
         
        <a href="#facebook" class="facebook">
            <i class="fa fa-facebook"></i>
        </a>
         
        <a href="#twitter" class="twitter">
            <i class="fa fa-twitter"></i>
        </a>
         
        <a href="#linkedin" class="linkedin">
            <i class="fa fa-linkedin"></i>
        </a>
         
        <a href="#google" class="google">
            <i class="fa fa-google"></i>
        </a>
         
        <a href="#youtube" class="youtube">
            <i class="fa fa-youtube"></i>
        </a>
    </div>
</footer>

 

</body>
</html>

*,*::before, *::after{
   box-sizing: border-box; 
   font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
   font-weight: normal;
}
body{ 
    padding: 0;
    margin: 0;
    background: linear-gradient(to right, blue,pink);
}
.calculator-grid{
    display:grid;
    justify-content: center;
    align-content: center;
    min-height: 100vh;
    grid-template-columns: repeat(4,100px);
    grid-template-rows: minmax(120px,auto) repeat(5,100px);
}
.calculator-grid > button{
    cursor:pointer;
    font-size: 2rem;
    border: 1px solid whitesmoke;
    outline: none;
    background-color: rgba(255,255,255,0.75);
}
.calculator-grid > button:hover{
    background-color: rgba(255,255,255,0.9);   
}
.span-two{
    grid-column:span 2
}
.output {
    grid-column: 1/;
}
