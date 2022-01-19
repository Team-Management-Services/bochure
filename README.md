<html>

<head>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css"
        integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z" crossorigin="anonymous" />
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"
        integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj"
        crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"
        integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN"
        crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"
        integrity="sha384-B4gt1jrGC7Jh4AgTPSdUtOBvfO8shuf57BaghqFfPlYxofvL8/KUEfYiJOMMV+rV"
        crossorigin="anonymous"></script>
    <script src="https://kit.fontawesome.com/20c5629a29.js" crossorigin="anonymous"></script>

    <title>TMS Brochure</title>
    <style>
        .container {
            background-image: linear-gradient(-180deg, white, #00BFFF);
            background-repeat: no-repeat;
            background-size: 100%;
        }

        .mySlides {
            display: none;
            height: 500px;
        }

        .img {
            display: block;
            margin-left: auto;
            margin-right: auto;
            width: 80%;
            background-size: cover;
            padding: 0%;
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        .y {
            font-family: 'Roboto', sans-serif;
            background: lightskyblue url('https://i.pinimg.com/originals/3c/24/46/3c24462450c2a902bf7e18f3d9aada81.jpg');
            color: #fff;
            display: flex;
            flex-direction: column;
            justify-content: flex-end;
            height: auto;
            max-width: 100%;
            margin: 0 auto;
            overflow: auto;
        }

        header {
            flex: 1;
            height: 100%;
            display: flex;
            align-items: center;
            justify-content: center;
        }

        header h1 {
            font-size: 60px;
        }

        .counters {
            background: #659df1;
            color: #fff;
            padding: 20px
        }

        .counters .container1 {
            display: grid;
            grid-gap: 100px;
            text-align: center;
        }

        .counters .counter {
            font-size: 45px;
            margin: 10px 0;
        }

        @media (max-width: 700px) {
            .counters .container1 {
                grid-template-columns: repeat(2, 1fr);
            }

            .counters .container1>div:nth-of-type(1),
            .counters .container1>div:nth-of-type(2) {
                border-bottom: 1px lightskyblue solid;
                padding-bottom: 20px;
            }
        }

        .logo-img {
            height: 150px;
            width: 300px;
            padding-right: 20px;
        }

        .icon {
            color: #0a0c7e;
            font-size: 30px;
            margin-right: 20px;
            margin-bottom: 20px;
        }

        .vr-text {
            font-family: "Roboto";
            font-size: 16px;
            font-weight: 400;
            justify-content: left;
            padding: 10PX;
            margin-bottom: 5px;
            font-weight: bold;
        }

        .vr-heading {
            color: #2c2ab8;
            font-family: "Roboto";
            font-size: 24px;
            font-weight: 700;
            text-decoration: underline;
        }

        .vr-container {
            background-color: rgb(255, 255, 255);
            margin: 10px;
            width: 50px;
            height: 50px;
            border-radius: 40px;
            padding-top: 20px;
            padding-bottom: 40px;
            padding-right: 40px;
            padding-left: 20px;
            margin-right: 10px;
            margin-bottom: 10px;
        }

        .vr-list {
            list-style-type: none;
            padding-left: 5px;
        }

        .hr-line {
            background-color: #fffafa;
        }

        .vr-copyright {
            color: rgb(0, 128, 248);
            font-family: "Roboto";
            font-size: 16px;
            font-weight: 400;
            font-weight: bold;
        }

        .card-img {
            width: 100%;
            border-radius: 100px;
            padding: 20px;
        }

        .img-container {
            padding: 10px;
        }

        .add {
            color: rgb(0, 128, 248);
        }

        .text {
            text-align: center;
            color: #1F51FF;
            padding: 80px;
            text-decoration: blanchedalmond underline;
        }

        .container2 {
            background-color: lightskyblue;
        }

        .para {
            text-align: left;
            font-family: "roboto";
            font-size: 20px;
        }

        .head {
            font-family: "roboto";
            font-weight: bold;
            text-align: left;
        }

        .head1 {
            font-family: "roboto";
            font-weight: bold;
            text-align: left;
            font-size: 28px;
        }

        .head2 {
            font-family: "roboto";
            font-weight: bold;
            text-align: left;
            color: whitesmoke;
            text-shadow: 5px 5px 20px blue, 0 0 10px #051563;
            text-transform: uppercase;
        }

        .proenqcus {
            padding: 20px;
            border: 5px blue solid;
            background-color: white;
        }

        .para1 {
            text-align: left;
            font-family: "roboto";
            font-size: 18px;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Poppins', sans-serif;
        }

        body {
            height: 100%;
            width: 100%;
            text-align: center;
            background: #f2f2f2;
        }

        .wrapper {
            display: grid;
            margin: 40px 40px 30px 0px;
            grid-gap: 20px;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
        }

        @media (max-width: 700px) {
            .wrapper {
                margin: 50px auto;
            }
        }

        .wrapper .box {
            width: 350px;
            margin: 0 auto;
            position: relative;
            perspective: 1000px;
            padding-top: 0%;
        }

        .wrapper .box .front-face {
            background: #fff;
            height: 500px;
            width: 100%;
            display: flex;
            flex-direction: column;
            justify-content: center;
            box-shadow: 0px 5px 20px 0px rgba(0, 81, 250, 0.1);
            transition: all 0.5s ease;
            background: linear-gradient(-135deg, lightskyblue, #ffffff, #051563);
        }

        .box .front-face .icon {
            height: 80px;
        }

        .box .front-face .icon i {
            font-size: 65px;
        }

        .box .front-face span,
        .box .back-face span {
            font-size: 22px;
            font-weight: 600;
            text-transform: uppercase;
        }

        .box .front-face .icon i,
        .box .front-face span {
            background-clip: text;
        }

        .box .back-face {
            position: absolute;
            top: 0;
            left: 0;
            z-index: 1;
            height: 500px;
            width: 100%;
            padding: 30px;
            color: #fff;
            opacity: 0;
            transform-style: preserve-3d;
            backface-visibility: hidden;
            background: linear-gradient(-135deg, #c850c0, #4158d0);
            transform: translateY(110px) rotateX(-90deg);
            box-shadow: 0px 5px 20px 0px rgba(0, 81, 250, 0.1);
            transition: all 0.5s ease;
        }

        .box .back-face p {
            margin-top: 10px;
            text-align: justify;
        }

        .box:hover .back-face {
            opacity: 1;
            transform: rotateX(0deg);
        }

        .box:hover .front-face {
            opacity: 0;
            transform: translateY(-110px) rotateX(90deg);
        }
    </style>


</head>

<body>
    <div class="container">
        <div class="img">
            <img src="https://imagizer.imageshack.com/img922/8676/dUGIky.png" alt="duGIky" width="100%"
                height="300px" />
        </div>
        <div class="row images">
            <div class="col-12">
                <img class="mySlides w3-animate-top"
                    src="https://cutewallpaper.org/21/coding-background-wallpaper/79+-Web-Developer-Wallpapers-on-WallpaperPlay.jpg"
                    style="width:100%">
                <img class="mySlides w3-animate-bottom" src="https://wallpaperaccess.com/full/5568.jpg"
                    style="width:100%">
                <img class="mySlides w3-animate-top"
                    src="https://apicms.thestar.com.my/uploads/images/2020/08/24/831125.jpg" style="width:100%">
                <img class="mySlides w3-animate-bottom" src="https://wallpaperaccess.com/full/1385386.jpg"
                    style="width:100%">
            </div>
        </div>
        <div class="row">
            <h2 class="col-12 mt-5 mb-4 head">About Us</h2>
            <img src="https://www.pequotlibrary.org/wp-content/uploads/2019/08/technology1.jpg" width="100%"
                height="300px" class="col-sm-6" />
            <p class="col-sm-6 para">Team Management Services are not just Software Company, we work with you to create
                your company’s growth strategy. We provide wide range software solutions in the fields of Web
                Development, App Development, Brand promotions along with Digital
                marketing solutions for companies and education sector-“Edtech and Fintech” companies and all industry
                sectors.<br> Our Methodology brings excellence, design innovation and strategic engagement.
            </p>
        </div>
        <div class="row mt-5 mb-5">
            <p class="col-sm-6 para">TMS services was established in the year 2019 at Prakash Nagar, Hyderabad one of
                the metropolitan city. The company is headed by specialists and experts of their own respective domains
                thus nurturing the growth of the company in a diversified
                arena. The company sources employment in different fields such as Marketing / Sales, Digital Marketing,
                Web Development, Software Development, App Development, Graphic Designer and BPS sector.
            </p>
            <img src="https://image.freepik.com/free-photo/modern-office-building-low-angle-view-skyscrapers-city-singapore-modern-office-building-low-angle-view-skyscrapers-city-singapore_231208-1463.jpg"
                width="100%" height="300px" class="col-sm-6" />
        </div>
        <div class="row mt-5 mb-5">
            <img src="https://azulotech.com/wp-content/uploads/2021/10/azulotec-digital-marketing-agency.jpg"
                width="100%" height="300px" class="col-sm-6" />
            <p class="col-sm-6 para">TMS is a company for aspiring Digital Marketers, aspiring IT professionals and
                experienced candidates too. It’s a company that gives opportunity for interns, nurtures and trains and
                brings out the potential in them and makes them ready for
                the workforce. The company success rate is outstanding with efficient workforce and management.
            </p>
        </div>
        <div class="row mt-5">
            <p class="col-sm-6 para">TMS Business Services offers best in class call Centre services “Voice” to clients
                from different industries such as Banking and Financial and more to SME’s entire UK and US.We have
                started initially with a PHP based IT project for an Australian
                client. After that we moved onto a BPO project of Data Mining, SMM (Social media Marketing) for a US
                client. So far our success rate increased and continued our journey along with a UK project.
            </p>
            <img src="https://insights.datamark.net/wp-content/uploads/2019/10/iStock-1059548978-1024x726.jpg"
                width="100%" height="300px" class="col-sm-6" />
        </div>
        <div class="row mt-5">
            <h1 class="col-12 mt-4 mb-4 head2">Why Team Management Services ?</h1>
            <h2 class="col-sm-12 mt-4 mb-4 head">Know About our COMPANY</h2>
            <p class="col-sm-12 para">TMS is a company for aspiring Digital Marketers, aspiring IT professionals and
                experienced candidates too. It’s a company that gives opportunity for interns, nurtures and trains and
                brings out the potential in them and makes them Ready for
                the workforce. The company success rate is outstanding with efficient workforce and management.
            </p>
        </div>
        <div class="row mt-3">
            <h1 class="col-12 mt-3 mb-3 head">MOBILE APPLICATION</h1>
            <img src="https://www.techfunnel.com/wp-content/uploads/2019/09/Top-Low-Code-Mobile-Application-Development-Platforms-1.png"
                width="100%" height="300px" class="col-sm-6" />
            <p class="col-sm-6 para"> We provide IOS & Android mobile application development service so you can reach
                your customer on their favorite devices. We create mobile applications of any complexity for B2B and B2C
                uses cases. Our client’s come from multiple different
                industries. Over these years, we’ve built up specific knowledge and expertise in creating applications
                for the following niches.
            </p>
        </div>
        <div class="row mt-3">
            <h1 class="col-12 mt-4 mb-4 head">WEB DEVELOPING</h1>
            <p class="col-sm-6 para"> As a Web development, we are independent organization so we are happy to customize
                any product that you recommend and also we offer attractive web design services to work towards
                maximizing profit through an appealing front-end design. Our
                team works with sole aim of providing the best web page designs to coalition with specification provided
                by our clients. Take your business to the next level with our custom web design service we are
                specialized in undertaking all custom
                web designing projects based on clients requirement.</p>
            <img src="https://www.proitmelbourne.com.au/blog/wp-content/uploads/2020/12/Web-mobile-development-banner-06.jpg"
                width="100%" height="300px" class="col-sm-6" />
        </div>
        <div class="row mt-3">
            <h1 class="col-12 mt-4 mb-4 head">DIGITAL MARKETING</h1>
            <img src="https://img.freepik.com/free-photo/digital-marketing-new-startup-project-online-search-engine-optimisation_36325-2205.jpg?size=626&ext=jpg"
                width="100%" height="300px" class="col-sm-6" />
            <p class="col-sm-6 para">Digital marketing services provides business of all sizes with an opportunity to
                market your brand 24/7 at a low cost.from startup to medium sized enterprises to multiple location
                companies, a digital marketing company helps you expand your
                niche market reach's to offer goods and services to your target customer,irrespective of time
                differences and location. </p>
        </div>
        <div class="row mt-3">
            <h1 class="col-12 mt-4 mb-4 head">BRAND PROMOTION</h1>
            <p class="col-sm-6 para">We will promote your brand in off-line & online. We focus on deploying creative
                excellence in powerful visualization around your product.Our attractive videos create interesting
                animated videos are targeting towards educate the customer and
                to promote your business purpose. We explore the best possible media platforms that we can use to
                promote your brand and enhance its reach. Though we also value the digital marketing mix popular
                nowadays, we don't underestimate the traditional
                mode of advertising as well. With a little effort, our managers bring more prominence to your business.
            </p>
            <img src="https://media-exp1.licdn.com/dms/image/C4E1BAQGitBG0GaqElQ/company-background_10000/0/1612427395032?e=2159024400&v=beta&t=E2V89jSWPDAeiT6X1_19PzlSGzHfDpRyN6JZzqrWiZg"
                width="100%" height="300px" class="col-sm-6" />
        </div>
        <div class="row mt-3 mb-4">
            <h1 class="col-12 mt-4 mb-4 head">BUSINESS PROCESS SERVICES</h1>
            <img src="https://5.imimg.com/data5/UP/PK/BX/SELLER-5650899/bpo-services-500x500.png" width="100%"
                height="300px" class="col-sm-6" />
            <div class="col-sm-6 mt-4 mb-4 para">
                <p>TMS Business Services offers best in class call Centre services “Voice” to clients from different
                    industries such as Banking and Financial and more to SME’s entire UK and US.
                </p>
            </div>
        </div>
        <div class="row mt-3">
            <h1 class="col-12 mt-4 mb-4 head">CONSULTANT SERVICES</h1>
            <p class="col-sm-6 para">
                U. S. IT RECRUITMENT CONSULTANTS is a Premier HR Head Hunting Organization, catering to human resources
                needs of Corporate World.
                The Company was founded by Miss SameenaSabeer an ardent supporter for human resources planning.
                Established in the year 2019, we have Specialized Teams of Recruitment Consultants & Trainers catering
                across industry functions.
                Our team is better equipped to meet the needs of our clients and are trained to assess the candidates.
                They enjoy complete encouragement and guidance from highly seasoned seniors, who have experience in all
                areas of recruitment.
                Head Hunting Is Our Forte.
            </p>
            <img src="https://neuroscienceforbusiness.co.za/wp-content/uploads/2015/12/strategic-leadership-coaching.jpg"
                width="100%" height="300px" class="col-sm-6" />
        </div>
        <section class="counters y mt-5 mb-5 mt-5 col-sm-12">
            <div class="row">
                <div class="col-sm-3">
                    <h3>Projects</h3>
                    <div class="counter" data-target="18">18</div>
                </div>
                <div class="col-sm-3">
                    <h3>Service</h3>
                    <div class="counter" data-target="10">10</div>
                </div>
                <div class="col-sm-3">
                    <h3>Happy Clients</h3>
                    <div class="counter" data-target="15">15</div>
                </div>
                <div class="col-sm-3">
                    <h3>Rating</h3>
                    <div class="counter" data-target="4.8">4.8</div>
                </div>
            </div>
        </section>

        <div class="row proenqcus mt-5 mb-5 pt-5">
            <div class="col-sm-4">
                <h1 class="head1">Productivity</h1>
                <p class="para1">Less hassle, Less waste and projects have clear goals for each increment.</p>
            </div>
            <div class="col-sm-4">
                <h1 class="head1">Enquiry</h1>
                <p class="para1">+91 991 218 3661</p>
            </div>
            <div class="col-sm-4">
                <h1 class="head1">Customer Satisfaction</h1>
                <p class="para1">Produce fast results, delivery meet expectation and concrete results in each. </p>
            </div>
        </div>

        <h1 class="head">Our Services</h1>
        <p class="para">We run all kinds of services in the form of INFORMATION & TECHNOLOGY.</p>
        <div class="wrapper">
            <div class="box">
                <div class="front-face">
                    <div class="icon">
                        <i class="fas fa-mobile"></i>
                    </div>
                    <span>App Development</span>
                </div>
                <div class="back-face">
                    <span>App Development</span>
                    <p>
                        The first phase of the mobile app development process is defining the strategy for evolving your
                        idea into a successful App.
                    <ol>
                        <li>Analysis and planning</li>
                        <li>MVP</li>
                        <li>Front-End (Mobile App)</li>
                        <li>APP Development</li>
                        <li>Testing</li>
                        <li>UI/UX Design</li>
                        <li>Back-End / Server Technology</li>
                        <li>API</li>
                    </ol>
                    </p>
                </div>
            </div>
            <div class="box">
                <div class="front-face">
                    <div class="icon">
                        <i class="fas fa-code"></i>
                    </div>
                    <span>Web Development</span>
                </div>
                <div class="back-face">
                    <span>Web Development</span>
                    <p>
                        Dynamic sites can also access information from a database and such are known as database-driven
                        website.
                        <br> We Create amazing website designs to advertises your business online.
                    <ol>
                        <li>Simple web design gives good presence across the web. </li>
                        <li>Our simple websites are designed to bring you results and remain affordable.</li>
                        <li>Simple web design can grow as your business grows. </li>
                        <li>Custom Mobile-friendly websites. </li>
                    </ol>
                    </p>
                </div>
            </div>
            <div class="box">
                <div class="front-face">
                    <div class="icon">
                        <i class="fas fa-chart-line"></i>
                    </div>
                    <span>Digital Marketing</span>
                </div>
                <div class="back-face">
                    <span>Digital Marketing</span>
                    <p>
                        Use digital content to achieve your business objectives. To increase website traffic, strengthen
                        online presence, raise brand awareness, perform better in search results.
                    <ol>
                        <li>Pay Per Click (PPC) </li>
                        <li>Management Social Media Marketing </li>
                        <li> Search Engine Optimization (SEO) </li>
                        <li>Online Reputation Management (ORM)</li>
                        <li>Email Marketing</li>
                    </ol>
                    </p>
                </div>
            </div>
            <div class="box">
                <div class="front-face">
                    <div class="icon">
                        <i class="fa fa-bullhorn"></i>
                    </div>
                    <span>Brand Promotions</span>
                </div>
                <div class="back-face">
                    <span>Brand Promotions</span>
                    <p>
                        We Promote Your Brand it will beneficiary to to develop business houses and it will save the
                        time of the customer.<br> Benefits To The Business:
                    <ol>
                        <li>It helps the business to build a long term brand.</li>
                        <li>Sometimes help in building the overall market share in the short term as well</li>
                        <li>It reminds the loyal customers how well the brand has served them over the years and
                            persuades their purchasing decision towards their branded products.</li>
                    </ol>
                    </p>
                </div>
            </div>
            <div class="box">
                <div class="front-face">
                    <div class="icon">
                        <i class="fa fa-bar-chart"></i>
                    </div>
                    <span>Bussiness Process Services</span>
                </div>
                <div class="back-face">
                    <span>Bussiness Process Services</span>
                    <p>
                        Business Services offers best in class call Centre services “Voice” to clients from different
                        industries. <br> <br> BPS provides below services:
                    <ol>
                        <li>Call center Services</li>
                        <li>Outbound Sales</li>
                        <li>Voice & Email</li>
                        <li>Outbound Support</li>
                        <li>Email & Chat</li>
                    </ol>
                    </p>
                </div>
            </div>
            <div class="box">
                <div class="front-face">
                    <div class="icon">
                        <i class="fas fa-business-time"></i>
                    </div>
                    <span>Consultant service</span>
                </div>
                <div class="back-face">
                    <span>Consultant Service</span>
                    <p>
                        Over the years, U.S. IT RECRUITMENT CONSULTANTS has evolved as the Hyderabad most preferred
                        executive search partner for placing high caliber professionals at executive, middle and senior
                        level positions across industries.
                        <ol>
                            <li>To Prepare for the Interview Professionally.</li>
                            <li>To groom you with Basic Soft Skills and Corporate Etiquette.</li>
                            <li>Resume designing and Presenting.</li>
                            <li>To upskill for Effective Communication & Business English.</li>
                        </ol>
                    </p>
                </div>
            </div>
        </div>

        <div class="container2">
            <div class="row">
                <div class="col-12 col-md-6 mt-5 mb-5">
                    <div class="text-center text-md-left">
                        <img src="https://imagizer.imageshack.com/img922/8676/dUGIky.png" class="logo-img">
                        <div class="d-flex flex-row justify-content-center justify-content-md-start mt-3 mb-3">
                            <div class="d-flex flex-row justify-content-center justify-content-md-start mt-3 mb-3">
                                <div class="vr-container">
                                    <a href="www.tmsmgmtservices.com/"><i class="fab fa-google icon"></i></a>
                                </div>
                                <div class="vr-container">
                                    <a href="https://www.facebook.com/TMSTechnosoft/"><i
                                            class="fab fa-facebook icon"></i></a>
                                </div>
                                <div class="vr-container">
                                    <a href="https://www.instagram.com/p/CWY5kSahOFP/?utm_medium=copy_link"><i
                                            class="fab fa-instagram icon"></i></a>
                                </div>
                                <div class="vr-container">
                                    <a
                                        href="https://www.linkedin.com/in/team-management-services-working-together-growing-together-a40236228/"><i
                                            class="fa fa-linkedin-square icon"></i></a>
                                </div>
                            </div>
                        </div>
                        <p class="vr-text">
                            <i class="fa fa-home icon"></i>
                            <span class="add"> 1-8-853, 19/3RT,Lane number-2, Street No.5, Prakash Nagar,
                                Begumpet, Hyderabad, Telangana-500016.
                            </span>
                        </p>
                    </div>
                </div>
                <div class="col-12 col-md-6 mt-5">
                    <h1 class="vr-heading pb-2">Contact Us :- </h1>
                    <ul class="vr-list">
                        <li class="mb-3">
                            <i class="fa fa-envelope icon mr-2"></i>
                            <span class="vr-text"><a
                                    href="mailto:info@tmstechnosoft.com">info@tmstechnosoft.com</a></span>
                        </li>
                        <li class="mb-3">
                            <i class="fa fa-dot-circle-o icon mr-2"></i>
                            <span class="vr-text"><a href="mailto:hr@tmstechnosoft.com">hr@tmstechnosoft.com</a></span>
                        </li>
                        <li class="mb-3">
                            <i class="fa fa-phone-alt icon mr-2"></i>
                            <span class="vr-text"><a href="tel:9912183661">+91 9912183661</a></span>
                        </li>
                        <li class="mb-3">
                            <i class="fa fa-skype icon mr-2"></i>
                            <span class="vr-text"><a href="skype:live:.cid.e670d1faafa9b88b?CHAT">TMS
                                    TECHNOSOFT</a></span>
                        </li>
                        <li class="mb-3">
                            <i class="fa fa-map-marker icon mr-2"></i>
                            <span class="vr-text"><a href="https://maps.app.goo.gl/3tHXNT8HW1Yme9a99">TMS GOOGLE
                                    MAPS</a></span>
                        </li>
                    </ul>
                </div>
            </div>
            <hr class="hr-line" />
            <div class="text-center">
                <i class="fa fa-copyright icon" aria-hidden="true"></i>
                <span class="vr-copyright">Reserved by TMS, Created by Team Management Services.</span>
            </div>
        </div>
    </div>


    <script>
        var myIndex = 0;
        carousel();

        function carousel() {
            var i;
            var x = document.getElementsByClassName("mySlides");
            for (i = 0; i < x.length; i++) {
                x[i].style.display = "none";
            }
            myIndex++;
            if (myIndex > x.length) {
                myIndex = 1
            }
            x[myIndex - 1].style.display = "block";
            setTimeout(carousel, 2500);
        }

        const counters = document.querySelectorAll('.counter');
        const speed = 200; // The lower the slower

        counters.forEach(counter => {
            const updateCount = () => {
                const target = +counter.getAttribute('data-target');
                const count = +counter.innerText;
                // Lower inc to slow and higher to slow
                const inc = target / speed;
                // console.log(inc);
                // console.log(count);
                // Check if target is reached
                if (count < target) {
                    // Add inc to count and output in counter
                    counter.innerText = Math.ceil(count + inc);
                    // Call function every ms
                    setTimeout(updateCount, 1);
                } else {
                    counter.innerText = target;
                }
            };
            updateCount();
        });
    </script>

</body>

</html>
