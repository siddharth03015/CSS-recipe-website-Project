<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Recipie project Css
    </title>
    <link rel="stylesheet" href="style.css">

    
</head>
<body>
    <div class="container">
        <header>
            <div class="navcontainer">
            <nav>
                <ul id="navList">
                    <li>
                        <p id="navLogo">  Himalayan Restaurant</p>

                    </li>
                    <li>

                        <div id="navitems">
                            <a href="#"> Home Page</a>
                            <a href="#"> Contacts</a>
                            <a href="#"> About</a>
                        </div>

                    </li>
                </ul>
            </nav>
        </div>
        </header>
        <main>
            <div class="contentbox">
            <!-- item1 -->
             <section>
                <div class="item">
                    <div class="leftbox">
                        <h2>
                            Gulab Jamun
                        </h2>
                       <div>
                         <h2>ingredients</h2>
                        <ul class="ingbox">
                            <li>Sugar</li>
                            <li>Bread</li>
                            <li>Oil</li>
                        </ul>
                       </div>
                        <div>
                            <h2>Recipie</h2>
                        <ol class="recipebox">
                            <li>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Est, eos.</li>
                            <li>Lorem ipsum dolor sit.</li>
                            <li>Lorem ipsum dolor sit amet consectetur adipisicing.</li>
                            <li>Lorem ipsum dolor sit amet consectetur adipisicing elit. Sunt, quod ab non modi repudiandae itaque.</li>
                        </ol>
                        </div>

                    </div>
                    <div class="rightbox">
                        <img src="Gulab-Jamun-Recipe-Piping-Pot-Curry.jpg" alt="" width="400px" height="300px">
                        <div class="overlay">
                            <span>  Click Here to know more</span>

                        </div>

                    </div>
                    
                </div>
             </section>
              <section>
                <div class="item">
                    <div class="leftbox">
                        <h2>
                            Barfi
                        </h2>
                       <div>
                         <h2>ingredients</h2>
                        <ul>
                            <li>Sugar</li>
                            <li>Bread</li>
                            <li>Oil</li>
                        </ul>
                       </div>
                        <div>
                            <h2>Recipie</h2>
                        <ol>
                            <li>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Est, eos.</li>
                            <li>Lorem ipsum dolor sit.</li>
                            <li>Lorem ipsum dolor sit amet consectetur adipisicing.</li>
                            <li>Lorem ipsum dolor sit amet consectetur adipisicing elit. Sunt, quod ab non modi repudiandae itaque.</li>
                        </ol>
                        </div>

                    </div>
                    <div class="rightbox">
                        <img src="barfi.jpg" alt="" width="500px" height="auto">
                        <div class="overlay">
                            <span>  Click Here to know more</span>

                        </div>

                    </div>
                    
                </div>
             </section>

             </div>
        </main>
        <footer>
              <div class="footerbox">
                <p> copyright &copy; Himalayan Restaurant Ltd 2026 all rights are reserved</p>

            </div>

        </footer>
      
     </div>
    
</body>
</html>

CSS PART

*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
.container{
    height:100%;
    width: 100%;
    overflow-x: none ;
    background-color: #7f96ad;
    background-image: linear-gradient(
    150deg,
    hsl(240deg 100% 20%) 0%,
    hsl(45deg 20% 43%) 0%,
    hsl(52deg 46% 50%) 0%,
    hsl(54deg 77% 54%) 0%,
    hsl(53deg 98% 58%) 1%,
    hsl(47deg 89% 66%) 3%,
    hsl(36deg 77% 70%) 5%,
    hsl(17deg 62% 73%) 7%,
    hsl(6deg 43% 74%) 11%,
    hsl(31deg 23% 72%) 17%,
    hsl(105deg 19% 73%) 25%,
    hsl(143deg 41% 74%) 38%,
    hsl(173deg 34% 66%) 63%,
    hsl(205deg 45% 62%) 88%,
    hsl(221deg 60% 58%) 97%,
    hsl(230deg 74% 50%) 100%
  );

    
    
    

}
.navcontainer{
    width: 100vw;
    /* background-color: rgb(184, 184, 229); */
    background-color: #0093E9;
    background-image: linear-gradient(160deg,#0093E9 0%,#80D0C7 100%);

    min-height: 100px;
     display: flex;
    justify-content: center;

    align-items: center;
    position: relative;

}
nav{
    width: 100%;
    padding-right: 2rem ;
}
#navList{
    width: 100%;
    /* margin-left: 15px;
    margin-right: 15px; */
    padding: 15px;
    list-style-type: none;
    font-size: 2.5rem;
    display: flex;
    justify-content: space-around;

    align-items: center;




}
#navLogo{
    font-size: 2.5rem;
    color: white;

}
a{
    text-decoration: none;
    color: azure;
}
#navitems{
    display: flex;
    gap: 40px;
    


}
.footerbox{
    background-color: #0093E9;
    background-image: linear-gradient(160deg,#0093E9 0%,#80D0C7 100%);
    color: azure;
    width: 100%;
    text-align: center;
    min-height: 40px;   


}
.footerbox p{
    color: azure;
    font-size: 2rem;
}
.contentbox{
    width: 50%;
    margin: auto;
    border: 1px solid black;
    background-color: white;
    display: flex;
    flex-direction: column;
    gap: 100px;
    padding: 3rem;
    box-shadow: 3px 3px 30px black;



}
.item{
    display: flex;
    /* gap: 30px; */
    justify-content: space-around;
    align-items: center;
}
.rightbox img{
    border-radius: 10px;
}
.rightbox:hover{
    transform: scale(1.1);
    transition: all 0.6s linear 0s;
}
.leftbox{
    display: flex;
    gap: 20px;
    flex-direction: column;
}
.leftbox h2{
    font-size: 2rem;
}
.ingbox{
    font-size: 1.4rem;
}
.recipebox{

    font-size: 1.1rem;

}
.rightbox{
    position: relative;
    overflow: hidden;
}
.rightbox .overlay{
    position: absolute;
    top: 0;
    left: 0;
    height: 100%;
    width: 100%;

    background-color: rgba(75, 67, 67, 0.588);
    display: flex;
    align-items: center;
    justify-content: center;
    border-radius: 10px;
    opacity: 0;
    transition: all 0.3s linear 0s;
    box-shadow: 1px 1px 10px black;
    border-radius: 10px;
}
.rightbox:hover .overlay{
    opacity: 1;
}
.rightbox .overlay span{
    color: azure;
    font-size: 1.2rem;
}

