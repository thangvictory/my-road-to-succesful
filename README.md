
<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
        <title> Discovery VietNam</title >
        <style>
            body{
            font-family:cursive;
            background-color:lightskyblue ;
            margin-left:3em;
            color:black;
            animation-duration: initial;
            
            }
            h1{
                color:red;
                font-size:3em;

            }
            .title{
            
                color:blue;
                margin-left:4em;
                float:left;
                text-decoration:underline;
            }
            p{
                
                font-size:1.2em;
                margin-top:1.2em;
                color:white;
            
            }
            img{
                text-align:center;
                width:45em;
               }
            iframe{
                text-align:center;
                margin-top:2.5em;
            }

            title,img{
                margin-top:4.5em;
            }
            a:hover,a:active{
                
                color:white;
            }
            #introduce{
                font-size:1.5em;
                color:darkmagenta;
                float:left;
                position:relative;
                margin-top:4em;
                margin-left:3em;
        

                 }
            #viet{
                float:right;
                width:55em;
                margin-top:3em;
                margin-right:4.5em;
                position:relative;
            }
            h2{
                text-align:center;
                color:darkblue;
                font-size:1.2em;
            }
            h3{
                color:darkblue;
                font-style:italic;
                font-weight:bold;
                font-size:2em;
                position:relative;
            }
            #hanoi{
                position:relative;
                margin-top:22em;   
            }
            .ha{
                float:right;
                margin-top:8em;
                margin-right:3em;
            }
            .igiang{
                float:RIGHT;
                margin-top:1em;
                margin-right:5em;

            }
            .giang{
                float:left;
            }
            #bay{
                margin-top:1em;
            }
            .long{
                font-size:1.2em;
                margin-top:3em;
            }
            .back{
                font-size:1.3em;
                margin-right:2em;
                margin-top:2em;
                margin-left:50em;
            }
            #da{
                margin-top:3em;
                
            }
            #hoa{
                margin-left:3em;
                margin-top:3.5em;
            }
            #lao{
                margin-top:3.2em;
            }
            #hoi{
                margin-top:3.5em;
                margin-left:3em;
            }
            img{
                width:40em;
                height:25em;
            }
            #slideShow{
                float:left;
            }
        </style>
    </head>
    <body>
        <h1>Discovery VietNam ....</h1>
        <iframe width="1200" height="500"
                src="https://www.youtube.com/embed/eH2WNtL5ong">
        </iframe>
        <h2>location : South East Asia</h2>
        <h2>cuisine : famous for "pho", eel soup, "mi quang" and many delicious and fantastic traditional dishes </h2>
        <h2>scenery : the interesting and poetry scenery with the moutains, rivers, beaches, caves, waterfall, hills make anybody who come here surprise</h2>
        <h2>famous place : Ha Long Bay, Phu Quoc island, Nha Trang Beach, Hoi An, Ha Noi, Nghe An, ... </h2>
        <div id="introduce">
        <ol>
            <li><a href="#hanoi">Ha Noi Capital</li>
            <li><a href="#hagiang">Ha Giang</li>
            <li><a href="#quangninh"> Quang Ninh</li>
            <li><a href="#haiphong">Hai Phong</li>
            <li><a href="#laocai">Lao Cai </li>    
            <li><a href="#thanhhoa">Thanh Hoa</li>
            <li><a href="#nghean">Nghe An</li>
            <li><a href="#hue">Hue</li>
            <li><a href="#danang">Da Nang </li>
            <li><a href="#quangnam">Quang Nam</li>
            <li><a href="#taynguyen">Tay Nguyen</li>
            <li><a href="#dalat">Da Lat</li>
            <li><a href="kiengiang">Kien Giang</li>    
            <li><a href="mekong">The Mekong Delta</li>
        </ol>  
        </div>
    
        <img id="viet" src="C:\Users\Windows 10 TIMT\Desktop\picture\vietnam.jpg">;
    
        <h3 id="hanoi">Ha Noi Capital</h3>
        <div id="slideShow">
            <img src="C:\Users\Windows 10 TIMT\Desktop\picture\hanoi.jpg">
            <img src="C:\Users\Windows 10 TIMT\Desktop\picture\hanoi2.jpg">
            <img src="C:\Users\Windows 10 TIMT\Desktop\picture\hanoi3.jpg">
            <img src="C:\Users\Windows 10 TIMT\Desktop\picture\hanoi4.jpg">
            <img src="C:\Users\Windows 10 TIMT\Desktop\picture\hanoi5.jpg">
            <img src="C:\Users\Windows 10 TIMT\Desktop\picture\hanoi6.jpg">
        </div>
<script>
var slideShow = function(container) {
this.images = [];
this.curImage = 0;
for (i = 0; i < container.childElementCount; i++) {
    this.images.push(container.children[i]);
    this.images[i].style.display = "none";
}

// Handle going to to the next slide
var nextSlide = function() {
    for (var i = 0; i < this.images.length; i++) {
        this.images[i].style.display = "none";
    }
    this.images[this.curImage].style.display = "block";
    this.curImage++;
    if (this.curImage >= this.images.length) {
        this.curImage = 0;
    }
    window.setTimeout(nextSlide.bind(this), 3000);
};

nextSlide.call(this);
};
slideShow(document.getElementById("slideShow"));
</script>
      
        <div class="ha">
          <p>location : the capital of VietNam,<br>
             Northeastern of VietNam</p>
          <p>famous for centuries-old architecture<br> and rich culture with the 
              <br>influence of Southeast Asia, China and France.<br> The city center is the bustling AQ,
              <br> where narrow streets are called "goods."<br> There are many small temples, including 
              <br>Bach Ma, honor a legendary horse, along with<br> Dong Xuan Market, home appliances and street food.</p>
        </div>
        <iframe width="1200" height="500"
                src="https://www.youtube.com/embed/SxhASgbUESc">
        </iframe>
        <li class="back"><a href="#introduce">Come back to list</li> 
        <h3 id="hagiang">Ha Giang</h3>
        <div class="giang">
         <p>location : in North Pole of VietNam</p>   
        <p>Ha Giang has many majestic mountains, <br>
            including Tay Con Linh (2419 m)<br>
             and Kieu Lieu Ti (2402m) is the highest. 
             <br>In terms of vegetation, Ha Giang has many
             <br> pristine forests, precious woods,
             <br> and up to 1000 medicinal plants. 
             <br>Animals include tigers, pheasants, pangolins ,
             <br> and many other animals. In addition,
             <br> it is also famous for its beautiful terraces.</p>
           
        </div>
        <img class="igiang" src="C:\Users\Windows 10 TIMT\Desktop\picture\ha giang.jpg">
        <iframe width="1200" height="500"
                src="https://www.youtube.com/embed/BU5kFRM9Sa8">
        </iframe>
        <li class="back"><a href="#introduce">Come back to list</li> 
        <h3 id="quangninh">Quang Ninh</h3>
        <img height=344 src="C:\Users\Windows 10 TIMT\Desktop\picture\ha long.jpg">
        
        <div class="ha" id="bay">
            <p>location : along the northeastern<br>
                 coast of Vietnam. <br>
                The province is home to Hạ Long Bay,<br>
                 a World Heritage Site.</p>
            <p>The geological history of the limestone<br>
                 karst of the Gulf has been<br>
                  around 500 million years <br>
                 with very different geologic circumstances;<br>
                  and the full evolution of karst<br>
                   over 20 million years <br>
                  with a combination of thick limestone,<br>
                   hot and humid climates,<br>
                   and a slow progression of tectonic overgrowth. </p>
                   </div>
        <p class="long">           
                   The combination of environment,
                    climate, geology and geomorphology
                    has made Ha Long Bay a convergence of biodiversity
                     including tropical evergreen
                      tropical rain forest ecosystems
                      and marine and coastal ecosystems.
                       with many ecosystems.
                       Fourteen endemic plant species
                        and about 60 endemic species
                        have been discovered among thousands of flora
                         and fauna populations in the Gulf.</p>    
        
        <iframe width="1200" height="500"
         src="https://www.youtube.com/embed/O_Sm9HfBsb8">
         </iframe> 
         <li class="back"><a href="#introduce">Come back to list</li>
         <h3 id="haiphong">Hai Phong</h3>
         <div class="giang">
             <p> location : northeatern of VietNam</p>
             <p>Hai Phong is also known as<br>
                The city of Red Phoenix flower .<br>
                    Not only an industrial port city,<br>
                       Haiphong now has many architectural attractions,<br>
                        including traditional architecture<br>
                         with pagodas, communal houses, <br>
                         ancient temples and French neoclassical<br>
                          architecture located on the old streets.<br>
                             At the same time, Haiphong now owns <br>
                            a UNESCO World Biosphere Reserve<br>
                             located in the Cat Ba Islands.<br>
                              The city also has cultural features,<br>
                               especially culinary and traditional festivals.</p>
          </div>
         <img class="igiang" src="C:\Users\Windows 10 TIMT\Desktop\picture\hai phong.jpg">
         <iframe width="1200" height="500"
         src="https://www.youtube.com/embed/Oxk4xmBZ8A0">
         </iframe> 
         <li class="back"><a href="#introduce">Come back to list</li> 
            
           <h3 id="laocai">Lao Cai</h3>
           <img src="C:\Users\Windows 10 TIMT\Desktop\picture\sapa.jpg">
           <div class="ha" id="lao">
               <p>location : a province of the mountainous<br>
                 Northwest region of Vietnam </p>
               <p>Located across the Muong Hoa Valley<br>
                 from Vietnam's highest mountain, Fansipan,<br>
                  the province is sometimes<br>
                   referred to as the "queen of mountains"</p>
                <p>Sa Pa is the most beatiful district<br>
                     in Lao Cai and have many tourists<br>
                      around the world.<br>
                   The geographical location of the area<br>
                    makes it a truly unique place for<br>
                     many interesting plants and animals,<br>
                      allowing it to support many inhabitants.<br>
                       Many very rare or even endemic species<br>
                        have been recorded in the region.
               </p>
           </div> 
           <iframe width="1200" height="500"
         src="https://www.youtube.com/embed/yCLV25jw-QE">
         </iframe> 
         <li class="back"><a href="#introduce">Come back to list</li> 
          <h3 id ="thanhhoa">Thanh Hoa</h3> 
          <div class="giang" id="hoa">
              <p>location : middle North coastal</p>
              <p>Thanh Hoa is famous for Sam Son beach<br>
                 and fabulous cuisine<br>
                  with so many delicious food like<br>
                  "nem chua", Phu Quang tea,<br>
                   mountain rock, chicken horn<br>
                    (Vinh Loc district),<br>
                     Tu Truong girdle cake<br>
                      (Tho Xuan district) </p>
          </div>
          <img class="igiang" src="C:\Users\Windows 10 TIMT\Desktop\picture\sam son.jpg ">
          <iframe width="1200" height="500"
         src="https://www.youtube.com/embed/etL_Ovurr5I">
         </iframe> 
         <li class="back"><a href="#introduce">Come back to list</li> 
          <h3 id="nghean">Nghe An</h3>
          <img src="C:\Users\Windows 10 TIMT\Desktop\picture\nghe an.jpg">
          <div class="ha">
              <p>location :  middle North coastal</p>
              <p>Nghe An is a province that<br>
                 have fantastic scenery, multicultural<br>
                  and it is the hometown<br>
                   of many famous people like<br>
                    president Ho Chi Minh,<br>
                     Phan Boi Chau, Ngo Bao Chau...  </p>
                <p>Vinh is the central city<br>
                     and Cua Lo is famous beach <br>
                     in this Province</p>     
          </div>  
          <iframe width="1200" height="500"
          src="https://www.youtube.com/embed/IRxqMV9PH-E">
          </iframe> 
          <li class="back"><a href="#introduce">Come back to list</li>
            <h3 id="hue">Hue</h3>
            <div class="giang">
                <p>location : middle North coastal </p>
                <p>Hue was the capital of Vietnam feudal<br>
                     period under the Nguyen Dynasty<br>
                     (1802 - 1945). Today, the city is<br>
                      centered on many aspects<br>
                       of the Central such as culture,<br>
                        politics, health, education, <br>
                        tourism, science ... The prominent<br>
                         sites are the Perfume River and its legacy.<br>
                          The feudal dynasty, the city has five<br>
                           UNESCO titles in Vietnam:<br>
                            Hue Imperial Relics Complex (1993), <br>
                            Hue royal court music (2003),<br>
                             Nguyen Dynasty Woods (2009), <br>
                             Nguyen Dynasty (2014) ) and<br>
                              the Poetry System on Hue Royal Architecture (2016).</p>
            </div> 
            <img class="igiang" src="C:\Users\Windows 10 TIMT\Desktop\picture\hue.jpg">;
          <iframe width="1200" height="500"
            
            src="https://www.youtube.com/embed/adlK8azckAs">
          </iframe> 
          <li class="back"><a href="#introduce">Come back to list</li>
            <h3 id="danang">Da Nang</h3>
            <img src="C:\Users\Windows 10 TIMT\Desktop\picture\danang.jpg">
            <div class="ha" id="da">
                <p>location : middle South coastal</p>
                <p>Da Nang is known as the name<br>
                     "city of travel" with Hai Van Pass<br>
                      in the North, Ba Na resort in the West,<br>
                       Son Tra Peninsula in the North East,<br>
                        Ngu Hanh Son in the South East. <br>
                        In addition, The city also has a system of<br>
                         temples, pagodas, temples <br>
                         according to Oriental architecture,<br>
                          Western architectural churches<br>
                           like Con Ga Church, ... <br>
                           the most typical museums<br>
                            are Nghe Museum Cham sculpture.</p>    
                        </div>
                        <iframe width="1200" height="500"
            
            src="https://www.youtube.com/embed/VP8bDYBxuUw">
          </iframe> 
          <li class="back"><a href="#introduce">Come back to list</li>
            <h3 id="quangnam">Quang Nam</h3>
            <div id="hoi" class="giang">
                <p>location : middle South coastal</p>
                <p>Quang Nam is a land rich<br>
                     in cultural traditions<br>
                      with two world cultural heritages:<br>
                       Hoi An Ancient Town and My Son Holy Land,<br>
                        where Vietnamese, Chinese<br>
                         and French cultures converge.</p>
            </div> 
            <img class="igiang"  src="C:\Users\Windows 10 TIMT\Desktop\picture\hoi.jpg">
            <iframe width="1200" height="500"
            
            src="https://www.youtube.com/embed/fNOfkNc9AJE">
          </iframe> 
          <li class="back"><a href="#introduce">Come back to list</li>
            <h3 id="taynguyen">Tay Nguyen</h3>
            <img src="C:\Users\Windows 10 TIMT\Desktop\picture\taynguyen.jpg">
            <div class="ha">
                <p>location : Central of VietNam</p>
                <p>Tay Nguyen is home to many<br>
                     ethnic minorities in Vietnam,<br>
                      including Tay, Nung, Ede,<br>
                       Bana, Muong, Thai, Dao.<br>
                        Not only that,<br>
                       it also focuses on the unique<br>
                        primary forest ecology and <br>
                        rare plants and animals.<br>
                         In particular, it is famous for<br>
                          its unique elephant travel.</p>
            </div>
            <iframe width="1200" height="500"
            
            src="https://www.youtube.com/embed/haD3iYlblis">
          </iframe> 
          <li class="back"><a href="#introduce">Come back to list</li>
        <h3 id="dalat">Da Lat</h3>
        <div class="giang">
            <p>location : Lam Dong, southern of VietNam</p>
            <p>Dalat enjoys mild and mild<br>
                 mountain climate all year round.<br>
             The history of more than a century<br>
              also leaves the city<br>
               a valuable architectural heritage,<br>
                considered to be a museum<br>
                 of 20th century European architecture.<br>
                  Natural resources and rich humanities<br>
                   help Dalat become<br>
                    a famous tourist destination of Vietnam.</p>
        </div>
        <img class="igiang" src="C:\Users\Windows 10 TIMT\Desktop\picture\dalat.jpg">
        <iframe width="1200" height="500"
            
            src="https://www.youtube.com/embed/ad2a0_PZTmk">
          </iframe> 
          <li class="back"><a href="#introduce">Come back to list</li>
     </body>
     </html>
