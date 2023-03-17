# University-Website
<!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width,initial-scale=1.0">
        <title>University Website Design- Easy Tutorials</title>
        <link rel="stylesheet" href="style.css">
        <link rel="preconnect" href="https://fonts.googleapis.com">
        <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
        <link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@200;400&display=swap" 
        rel="stylesheet">
        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">

    </head>
    <body>
        <section class="header">
            <nav>
              <a href="dev.html"> <img src="logo.png"></a>
              <div class="nav-links" id="navLinks" onclick="show()">
                <i class="fa fa-times" onclick="hidemenu()" ></i>
                <ul>   
                <li id="hoveree"   ><a href=""  >HOME</a></li>
                <li id="hoveree"><a href="">ABOUT</a></li>
                <li id="hoveree"><a href="">COURSE</a></li>
                <li id="hoveree"><a href="">BLOG</a></li>
                <li id="hoveree"><a href="">CONTACT</a></li>
               </ul>    
             </div>
             <i class="fa fa-bars" onclick="showmenu()"></i>
          </nav>
          <div class="textbox" >
            
                
            <h1>World's Biggest University</h1>
        <p>Making websites is now one of the easiest thing in the world.You just need to learn HTML,CSS<br>Javascript and you are good to go.</p>
        <a href="hero-btn">visit us to know more</a>
       </div>
       </section>
       

       <script>
           var navLinks=document.getElementById("navLinks");
           function showmenu(){
               navLinks.style.right = "0";

           }
           function hidemenu(){
               navLinks.style.right = "-200px";
           }
           
           
           const manish=document.getElementById('navLinks');
        //    manish.function show(){
               
        //    }
           manish.onclick=()=>{
               alert('work is in Under construction...');
           }


       </script>


    <!--course  ------->
    <section class="course">
       <div> <h1>COURSE   WE  OFFER</h1>
        <P>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Rerum provident expedita praesentium doloru
               </P>

       </div>
       <div class="row">
           <div class="column"><h2>INTERMEDIATE</h2><p>Lorem ipsum dolor sit amet, consectetur
                adipisicing elit. Ipsa iure, voluptates sint magni saepe
                 recusandae commodi ullam quasi! Laboriosam quas culpa officia.
                  Temporibus debitis, rem a asperiores ducimus architecto error.</p></div>
                 <div class="column"><h2>GRADUATION</h2><p>Lorem ipsum dolor sit amet, consectetur
                    adipisicing elit. Ipsa iure, voluptates sint magni saepe
                     recusandae commodi ullam quasi! Laboriosam quas culpa officia. 
                     Temporibus debitis, rem a asperiores ducimus architecto error.</p></div>
                
                     <div class="column"><h2>POST GRADUATION</h2><p>Lorem ipsum dolor sit amet, consectetur
                        adipisicing elit. Ipsa iure, voluptates sint magni saepe
                         recusandae commodi ullam quasi! Laboriosam quas culpa officia. Temporibus debitis,
                          rem a asperiores ducimus architecto error.</p></div>
                    </div>

    
    
    
    
    </section>
    <!------campus------------------------------------>
    <section class="campus">
        <h1>CAMPUS</h1>
        <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. </p>
        <div class="row">
            <div class="campus-col">
            
            <img src="london.png" >
            <div class="layer">
                <h3>LONDON</h3>
            </div>
            </div>
        <div class="campus-col">
            
                <img src="washington.png" >
                <div class="layer">
                    <h3>WASHINGTON</h3>
        </div>
        </div>
        <div class="campus-col">
            
                    <img src="newyork.png" >
                    <div class="layer">
                        <h3>NEWYORK</h3>
            </div>
            </div>

</div>

    </section>

    <!-------------------- Facilities---------------------------------------- -->
   <section class="facilities">
<div>
       <h1>FACILITIES</h1>
       <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. </p>
       <div class="fac-row">
        <div class="fac-col">
        
        <img src="library.png" >
        <h3> World class library</h3>
        <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit.</p>
        
        
        </div>
    <div class="fac-col">
        
            <img src="basketball.png" >
            <h3>Longest play ground</h3>
            <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit.</p>
            
    </div>
    <div class="fac-col">
        
                <img src="cafeteria.png" >
                <h3>Healthy and Tasty Food </h3>
                <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit.</p>
            
        </div>
        </div>
    </div>

   </section>
   <!-------------------Antimonials------------------------------------------------>

   <div class="antimonials">
       <h1><b>What our students says<b></h1>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
        
        <div class="row">
            <div class="ant-col">
                <img src="user1.jpg">
                

                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Consequuntur
                     veritatis dolorem ab dolores. Laudantium itaque beatae deserunt, 
                     delectus dolores, voluptatem corrupti quia tenetur nam pariatur
                      repellat necessitatibus illum quis? Laudantium!</p>
                      <br>
                      <b>S.Martina<b>
            </div>
            <div class="ant-col">
                <img src="user2.jpg">
                

                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Consequuntur
                     veritatis dolorem ab dolores. Laudantium itaque beatae deserunt, 
                     delectus dolores, voluptatem corrupti quia tenetur nam pariatur
                      repellat necessitatibus illum quis? Laudantium!</p>
                      <br>
                      <h3><b>Jackob Xender</b></h3>
            </div>
        </div>

   </div>


    
        
    
    
        
       
        
    </body>
</html>
