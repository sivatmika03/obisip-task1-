<!DOCTYPE html>
<html lang="en">
  
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content=
        "width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="index.css">
    <title>Landing Page</title>
</head>
  
<body>
    <nav>
        <div class="heading">Landing Page</div>
        <span class="sideMenuButton" 
            onclick="openNavbar()">
            ☰
        </span>
  
        <div class="navbar">
            <ul>
                <li><a href="#Home">Home</a></li>
                <li><a href="#">About</a></li>
                <li><a href="#">Sign Up</a></li>
            </ul>
        </div>
    </nav>
  
    <!-- Side navigation bar for 
        responsive website -->
    <div class="sideNavigationBar" 
        id="sideNavigationBar">
        <a href="#" class="closeButton" 
            onclick="closeNavbar()">
            ❌
        </a>
        <a href="#">Home</a>
        <a href="#">About</a>
        <a href="#">Sign Up</a>
    </div>
  
    <!-- Content -->
    <div class="line" id="Home">
        <div class="side1">
            <h1>Starbucks</h1>
            <button>
                <a href=
"https://www.Starbucks.org/">
                    Explore More
                </a>
            </button>
        </div>
        <div class="side2">
            <img src=
"https://Starbucks.org/wp-content/cdn-uploads/20220401124017/HTML-Tutorial.png"
                width="500">
        </div>
    </div>
  
    <section class="about" id="My Projects">
        <div class="content">
            <div class="title">
                <span>OUR MENU</span>
            </div>
            <div class="boxes">
                <div class="box">
                    <div class="topic">
                        <a href="" target="_blank">
                            COFFEE
                        </a>
                    </div>
                    <p>
                        Starbucks would soon expand to Chicago and Vancouver, Canada and then on to California, Washington, D.C. and New York. By 1996, we would cross the Pacific to open our first store in Japan, followed by Europe in 1998 and China in 1999
                    </p>
                </div>
                <div class="box">
  
                    <div class="topic">
                        <a href="" target="_blank">
                            Americano
                        </a>
                    </div>
                    <p>
                       Caffè Americano is an Italian interpretation of “American coffee” that swaps out milk with hot water for a simple espresso drink that has become a staple at our cafés
                    </p>
                </div>
  
                <div class="box">
                    <div class="topic">
                        <a href="" target="_blank">
                            Frappuccino
                        </a>
                    </div>
                    <p>
                        Frappuccino is a line of blended iced coffee drinks sold by Starbucks. It may consist of coffee or crème base, blended with ice and ingredients such as flavored syrups and usually topped with whipped cream and or spices.
                    </p>
                </div>
            </div>
        </div>
    </section>
  
    <section class="contact" id="contact">
        <div class="content">
            <div class="title"><span>Order</span></div>
            <div class="contactMenu">
                <div class="input1">
                    <div class="label1">Your Name</div>
                    <div class="input2">
                        <input type="text" 
                            placeholder="Enter your Name here">
                    </div>
                    <div class="label1">
                        <label>Phone Number</label>
                    </div>
                    <div class="input2">
                        <input type="text" 
                            placeholder="Enter your Email here">
                    </div>
                    <div class="label1">
                        <label>Address</label>
                    </div>
                    <div class="input2">
                        <input type="text" 
                            placeholder="Enter your Password here">
                    </div>
                    <div class="button">
                        <button>ORDER</button>
                    </div>
                </div>
                <div class="input3">
                    <div class="rightside1">
                        <div class="title1">
                            <span>
                                Contact Us
                            </span>
                        </div>
                        <div class="content1">
                            A-143, 9th Floor, Sovereign 
                            Corporate Tower, Sector-136, 
                            Noida, Uttar Pradesh - 201305
                        </div>
                        <div class="title1">
                            <span>OUR PARTNERS</span>
                        </div>
                        <div class="content1">
                            Frappuccino is a line of blended iced coffee drinks sold by Starbucks. It may consist of coffee or crème base, blended with ice and ingredients such as flavored syrups and usually topped with whipped cream and or spices.
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- Footer section -->
    <footer>
        <div class="footer">
            <span>
                Created By
                <a href="https://www.starbucks.org/" 
                    target="_blank">
                    STARBUCKS
                </a>
            </span>
        </div>
    </footer>
    <script src="index.js"></script>
</body>
  
</html>
