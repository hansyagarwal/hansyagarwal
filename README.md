Hello :rooster:

<head>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/normalize/5.0.0/normalize.min.css">
   <link rel='stylesheet' href='https://maxcdn.bootstrapcdn.com/bootstrap/3.3.5/css/bootstrap.min.css'>
   <link rel='stylesheet' href='https://maxcdn.bootstrapcdn.com/font-awesome/4.4.0/css/font-awesome.min.css'>
    <style>
    .card{
}

.card img{
    margin: 0 auto;
    max-width: 100%;
    width: 100px;
    height: auto;
}

.cards{
    display: grid;
    margin: 0 auto;
    grid-gap: 1rem;
}

@media (min-width: 600px) {
  .cards { grid-template-columns: repeat(2, 1fr); }
}

@media (min-width: 900px) {
  .cards { grid-template-columns: repeat(6, 1fr); }
}

* {
  box-sizing: border-box;
}</style>
</head>

<div class="container">
  <div class="cards">
     <div class="card">
        <center>
            <img class="img" src="imgs/java.png">
        </center> 
     </div>
     <div class="card">
         <center>
             <img class="img" src="imgs/python.png">    
         </center>
     </div>
     <div class="card">
         <center>
             <img class="img" src="imgs/html.png">
         </center>
     </div>
     <div class="card">
        <center>
             <img class="img" src="imgs/css.png">   
        </center>
     </div>
     <div class="card">
        <center>
             <img class="img" src="imgs/boot.png">   
        </center>
     </div>
     <div class="card">
        <center>
             <img class="img" src="imgs/js.png">   
        </center>
     </div>
  </div>
  <br>
  <br>
  <div class="cards">
    <div class="card">
       <center>
           <img src="imgs/nodejs.png">
       </center>
    </div>
    <div class="card">
       <center>
           <img src="imgs/php.png">
       </center>
    </div>
    <div class="card">
       <center>
            <img src="imgs/postgre.png">   
       </center>
    </div>
    <div class="card">
       <center>
           <img src="imgs/mongodb.png">
       </center>
    </div>
    <div class="card">
       <center>
            <img src="imgs/git.png">   
       </center>
    </div>
    <div class="card">
       <center>
            <img src="imgs/graphql.png">   
       </center>
    </div>
  </div>
  </div>
