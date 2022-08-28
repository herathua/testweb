<!DOCTYPE html>
<html lang="en">

<head>
    <title></title>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <style>
        * {
            box-sizing: border-box;
        }
        
        body {
            font-family: Arial, Helvetica, sans-serif;
        }
        /* Style the header */
        
        .column {
            float: left;
            width: 50%;
            padding: 10px;
            text-align: center;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            /* Should be removed. Only for demonstration */
        }
        
        .column2 {
            float: left;
            width: 100%;
            padding: 10px;
            height: 50px;
            text-align: center;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            font-size: 200%;
            color: #0BCEAF;
            /* Should be removed. Only for demonstration */
        }
        /* Clear floats after the columns */
        
        .row:after {
            content: "";
            display: table;
            clear: both;
        }
        /* Style the footer */
        
        .footer {
            background-color: #0BCEAF;
            padding: 10px;
            text-align: center;
        }
        
        body {
            margin: 0;
            font-family: Arial, Helvetica, sans-serif;
        }
        
        .topnav {
            overflow: hidden;
            background-color: #ffffff;
        }
        
        .topnav a {
            float: left;
            color: #000000;
            text-align: center;
            padding: 14px 16px;
            text-decoration: none;
            font-size: 17px;
            margin-left: auto;
            margin-right: auto;
        }
        
        .topnav a:hover {
            background-color: #0BCEAF;
            color: black;
        }
        
        .intro {
            display: grid;
            grid-template-columns: auto auto auto;
            background-color: #2196F3;
            padding: 10px;
        }
        
        .intro-item {
            background-color: rgba(255, 255, 255, 0.8);
            border: 1px solid rgba(0, 0, 0, 0.8);
            padding: 20px;
            font-size: 30px;
            text-align: center;
        }
        
        input[type=text],
        select {
            width: 100%;
            padding: 12px 20px;
            margin: 8px 0;
            display: inline-block;
            border: 1px solid #ccc;
            border-radius: 4px;
            box-sizing: border-box;
        }
        
        input[type=submit] {
            width: 100%;
            background-color: #0BCEAF;
            color: white;
            padding: 14px 20px;
            margin: 8px 0;
            border: none;
            border-radius: 4px;
            cursor: pointer;
        }
        
        input[type=submit]:hover {
            background-color: #05937b;
        }
        
        div {
            border-radius: 5px;
            background-color: #ffffff;
            padding: 20px;
        }
    </style>
</head>

<body>
    <div class="topnav" id="home">
        <a href="#home">Home</a>
        <a href="#About">About</a>
        <a href="#Qulity">Qulity</a>
        <a href="#Contact">Contact</a>
    </div>


    <div class="row" id="About">
        <div class="column" style="background-color:#0BCEAF ;height : 400px" ;><img src="about.png" alt="about" width="350" height="100%"></div>
        <div class="column" style="background-color:#0BCEAF;color:white; padding-top :7%;height : 400px ;font-size:400%" ;>I'm<br>AVISHKA
            <br> HERATH</div>

    </div>

    <div class="row " id="Qulity">
        <div class="column2 " style="background-color:white; ">Graphic Designer & Web Developer</div>


    </div>
    <div class="row ">
        <div class="column " style="background-color:rgb(255, 254, 254); ">


            <div class="downleft" style="font-size: 18px;color: #000;">
                Name: Uvindu Herath<br><br> Degree: B.Sc (Hons.) IT & M (Undergraduat)<br><br> Phone: +94 715145063<br><br>Address: 53/1,Bandawa,Polgahawela
            </div>
        </div>


        <div class="column " style="background-color:rgb(255, 255, 255); ">


            <div class="downleft" style="font-size: 18px;color: #000;">
                Birthday: 23 November 1999<br><br>Experience: 1 Years<br><br>Email: uvherath@gmail.com<br><br>Freelance: Available
            </div>
        </div>

    </div>

    <div class="row ">
        <div class="column2 " style="background-color:white; ">EDUCATION & EXPERICENCE</div>


    </div>
    <div class="row " id="Contact">
        <div class="column " style="background-color:rgb(255, 254, 254); ">
            <div class="TOPICLEFT" style="font-size: 30px;color: #000;">
                My Education<br><br><br>
            </div>

            <div class="downleft" style="font-size: 18px;color: #000;">
                Information Technology & Managemenet University of Moratuwa <br>| 2022 - 2026<br><br> Advertising and graphic Design National Institute of Business Management <br>| 2021 - 2022<br><br> Advanced Level Maliyadewa college <br>| 2018 - 2020<br><br>
            </div>
        </div>


        <div class="column " style="background-color:rgb(255, 255, 255); ">
            <div class="TOPICLEFT" style="font-size: 30px;color: #000;">
                My Expericence<br><br><br>
            </div>

            <div class="downleft" style="font-size: 18px;color: #000;">
                Member of Creative design Pillar Moraspirit <br>| 2022 - presen<br><br> Freelancer freelancer.com <br>| 2021 - present<br><br> Web Designer expro.lk <br>| 2020 - 2021<br><br>
            </div>
        </div>

    </div>
    <div class="row ">
        <div class="column2 " style="background-color:rgb(255, 255, 255); ">
            <div>
                <form action="/action_page.php">
                    <label for="fname"></label>
                    <input type="text" id="fname" name="firstname" placeholder="Your name..">

                    <label for="lname"></label>
                    <input type="text" id="lname" name="Email" placeholder="Email..">

                    <label for="lname"></label>
                    <input type="text" id="massage" name="massage" placeholder="massage..">



                    </select>

                    <input type="submit" value="Submit">
                </form>
            </div>
        </div>

        <div class="footer ">
            <p></p>
        </div>

</body>

</html>
