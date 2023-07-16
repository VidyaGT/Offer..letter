# Offer..letter
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Project : Offer Letter Using HTML and CSS</title>
    <link rel="stylesheet" href="style.css">
</head>
  <style>
    *{
    margin: 5px;
    /* margin: 22px 10px 22px 10px; */
    padding: 0px;
}
html{
    height: 90vh;
    width:80vw;
}
body{
    background-color: azure;
    height: fit-content;
    width:fit-content;
    border: 2px solid blue;
}
header{
    margin: 25px;
    padding: 2px;
    height:150px;
    width: 1000px;
    max-height: 160px;
}
nav{
    height: 60px;
    width:700px;
    margin:20px;
    padding :5px;
    display:inline-block;
}
header nav h2{
    text-align: left;
    font-size: 35px;
    line-height: 0.4em;
    font-weight: bold;
    color: blue;
    height:20px;
    
}
header nav p{
    text-align: left;
   letter-spacing: 0.038em;
   color: rgb(35, 57, 57);
   
  
}
header img{
    height: 140px;
    width: 190px;
    /* margin: 20px 10px 20px 10px; */
    /* padding-left: 700px; */
    display: inline-block;
    text-align: right;
}
.heading{
    color: blue;
    margin: 50px;
    padding: 5px;
    font-size:50px;
    text-decoration: underlined solid blue;
    text-align: justify;
    font-family:Georgia, 'Times New Roman', Times, serif ;
   
}
.name{
    font-size: 18px;
    font-family: Georgia, 'Times New Roman', Times, serif;

}
.para{
    margin: 25px;
    padding: 5px;
    height:80vh;
    width:80vw;
    font-style: normal;
    font-family:Georgia, 'Times New Roman', Times, serif ;
}
.founder{
   text-align: left;
    color: blue;
    display:inline-block
}
.msm{
    
    height:20px;
    width: 20px;
    display:inline-block;

}
footer{
    text-align:center;
    color:black;
    text-decoration: double;
}
  </style>
  
<body>
    <header>
<nav>
    <h2>InternPe</b></h2>
    <p>Jaipur(Rajasthan)</p>
   </nav><img src="logo interpe.jpg" alt="InternPe logo">
    </header>
    <main>
<section>
    <div class="heading">
        
        <h6>DEMO OFFER LETTER</h6>
         </div>
    <div class = "name">
 <pre>
            
    
  <b>Dear Vidya Turkar</b></pre>
                </div>
    <div class="para">
     <p>



     We are delighted to welcome you for the Internship of<b> Web Development</b> Internship in our company.This internship is being observed by <b>INTERNPE</b>,as a learning opportunity for you.</p>


           
     <p> 
     Your internship starts on <b>03/07/2023</b> and ends on <b>30/07/2023</b>. It's <b>4  Weeks</b> program.It's also an Unpaid program all focus is on learning.</p>

     <p>
     We look Forward to a worthwhile and faithful association that will make you equipped for future projects.Wishing you the most enjoyable and truly meaningful internship program experince.
    </p>


     </p>
    </div>
    <div class="founder">
        <h1>Co-Founder</h1>
        <h1>InternPe</h1>
        
    </div><div class="msm">
        <img src="msmeLogo.jpeg" alt="<MSME logo">
    </div>
</section>
    </main>
    <footer>
<p>link to site: https://internpe.in/ </p>
    </footer>
</body>
</html>
