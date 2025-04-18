# Startups-at-IITK-website
This website enlists well known startups from IIT Kanpur and information about them
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Startups from IITK
    </title>
<link href=""  type="png">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet" />
    
    <style>

        * {
            box-sizing: border-box;
        }

        body {
            background-color: #fff5e6;
            font-family: 'Poppins', sans-serif;
            padding: 20px;
            margin: 0;
        }

        h1 {
            text-align: center;
            margin-bottom: 40px;
            color: #e65100;
        }

        h4 {
            text-align: center;
            margin-bottom: 40px;
            color: #c3139a;
        }

        .container {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: center;
        }
        

        .card {
            background-color: #ffffff;
            border-radius: 10px;
            width: 22%;
            min-width: 250px;
            padding: 15px;
            box-shadow: 0 4px 8px rgba(230, 81, 0, 0.15);
            display: flex;
            flex-direction: column;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .card:hover {
            transform: translateY(-10px);
            box-shadow: 0 8px 20px rgba(230, 81, 0, 0.3);
        }

        .img {
            overflow: hidden;
            border-radius: 7px;
        }

        .img img {
            width: 100%;
            border-radius: 7px;
            transition: transform 0.3s ease;
        }

        .card:hover .img img {
            transform: scale(1.05);
        }

        .capsules {
            margin-top: 10px;
            display: flex;
            gap: 10px;
            flex-wrap: wrap;
        }

        .capsules span {
            background-color: #ff9800;
            color: white;
            padding: 4px 10px;
            border-radius: 12px;
            font-size: 12px;
        }

        .content h2 {
            font-size: 18px;
            margin: 10px 0 5px;
            color: #e65100;
        }

        .content p {
            font-size: 14px;
            color: #555;
        }

        .button {
            align-self: center;
            margin-top: auto;
            padding: 10px 20px;
            border-radius: 20px;
            background-color: #ffe0b2;
            border: none;
            font-weight: bold;
            cursor: pointer;
            transition: 0.3s ease;
        }

        .button a {
            color: #e65100;
            text-decoration: none;
        }

        .button:hover {
            background-color: #ffcc80;
        }

        @media (max-width: 992px) {
            .card {
                width: 45%;
            }
        }

        @media (max-width: 576px) {
            .card {
                width: 90%;
            }
        }
    </style>
</head>

<body>
    <h1>Startups from IIT Kanpur</h1>
    <h4> WHERE INNOVATION MEETS AMBITION</h4>
    <h3></h3>

    <div class="container">

        <div class="card">
            <div class="img">
                <img src="Ixigo_logo.svg.png" alt="Startup Image">
            </div>
            <div class="capsules">
                <span>online travel agency</span>
                <span>AI-based travel platform</span>
            </div>
            <div class="content">
                <h2>IXIGO</h2>
                <h3>Know & Go</h3>
                <p>An Indian online travel agency (OTA) that helps users plan, book, and manage their trips across
                    various modes of transport like trains, flights, buses, and hotels</p>
            </div>
            <button class="button">
                <a target="_blank" href="https://www.ixigo.com/">Learn More</a>
            </button>
        </div>


        <div class="card">
            <div class="img">
                <img src="Pine_Labs_Logo.jpg" alt="Startup Image">
            </div>
            <div class="capsules">
                <span>Point of Sale (POS) Systems</span>
                <span>Digital Payments</span>
            </div>
            <div class="content">
                <h2>Pine Labs</h2>
                <h3>Our platform, your move</h3>
                <p>A leading Indian fintech company specializing in payment solutions for merchants and businesses</p>
            </div>
            <button class="button">
                <a target="_blank" href="https://www.pinelabs.com/">Learn More</a>
            </button>
        </div>

        <div class="card">
            <div class="img"><img src="Giva-logo.png" alt="Startup Image"></div>
            <div class="capsules"><span>silver jewelry </span><span>online jewelry store</span></div>
            <div class="content">
                <h2>GIVA</h2>
                <h3>Unlock Your True Colours with GIVA's Exquisite Stone Jewellery</h3>
               <p>A jewelry company that focuses on silver, gold, and lab-grown diamond jewelry</p>
            </div><button class="button"><a target="_blank"
                    href="https://www.giva.co/?gad_source=1&gclid=Cj0KCQjwzYLABhD4ARIsALySuCSvpp20eU3s_2evrLzlgKPSwRPLdGb0fd_CT-Vb-mkRJwhEceXTjkcaAhDLEALw_wcB">Learn
                    More</a></button>
        </div>
        <div class="card">
            <div class="img"><img src="cult-fit-logo-png_seeklogo-454845.png" alt="Startup Image"></div>
            <div class="capsules"><span>fitnessp</span><span>wellbeing</span></div>
            <div class="content">
                <h2>cult.fit</h2>
                <h3>Make health easy</h3>
                <p>A fitness platform offering both online and offline experiences, focusing on making fitness accessible and enjoyable</p>
            </div><button class="button"><a target="_blank" href="https://www.cult.fit/">Learn More</a></button>
        </div>
        <div class="card">
            <div class="img"><img src="nobroker-logo.jpg" alt="Startup Image"></div>
            <div class="capsules"><span>No Brokerage</span><span>Real Estate</span></div>
            <div class="content">
                <h2>NO BROKER</h2>
                <h3>Ab ki baar no broker ka raj</h3>
                <p>A real estate platform that connects property owners directly with potential tenants or buyers, eliminating the need for brokers and brokerage fees</p>
                
                
            </div><button class="button"><a target="_blank" href="https://www.nobroker.in/bangalore/rent">Learn More</a></button>
        </div>
        <div class="card">
            <div class="img"><img src="download.png" alt="Startup Image"></div>
            <div class="capsules"><span>logistics </span><span>transportation</span></div>
            <div class="content">
                <h2>PORTER</h2>
                <h3>Porter hai, ho jayega</h3>
                <p>A logistics service provider offering convenient and reliable delivery services within and between cities</p>
            </div><button class="button"><a target="_blank" href="https://porter.in/">Learn More</a></button>
        </div>
        <div class="card">
            <div class="img"><img src="sharechat-logo-vector.png" alt="Startup Image"></div>
            <div class="capsules"><span>local language social networking</span><span>Social Media</span></div>
            <div class="content">
                <h2>ShareChat</h2>
                <h3>Be Quick!</h3>
                <p>A social media app popular in India, allowing users to share content, connect with others, and express themselves in their native language</p>
            </div><button class="button"><a target="_blank" href="https://sharechat.com/">Learn More</a></button>
        </div>
        <div class="card">
            <div class="img"><img src="MPL-Logo-04-1.jpg" alt="Startup Image"></div>
            <div class="capsules"><span>eSports platform</span><span>mobile gaming</span></div>
            <div class="content">
                <h2>MPL</h2>
               <h3>Play Cash Games on MPL - Win Real Money </h3>
               <p>A mobile gaming platform where users can play a variety of games, including fantasy sports, and compete for real cash prizes</p>
            </div><button class="button"><a target="_blank" href="https://www.mpl.live/">Learn More</a></button>
        </div>
      
</body>

</html>
