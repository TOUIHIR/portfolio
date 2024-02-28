<!DOCTYPE html>
<!-- Coding By CodingNepal - codingnepalweb.com -->
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <!-- ===== CSS ===== -->
    <link rel="stylesheet" href="style.css">

    <!-- ===== Boxicons CSS ===== -->
    <link href='https://unpkg.com/boxicons@2.1.1/css/boxicons.min.css' rel='stylesheet'>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta2/css/all.min.css" />
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet" />
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.0.0/dist/css/bootstrap.min.css"
        integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@4.0.0/dist/js/bootstrap.min.js"
        integrity="sha384-JZR6Spejh4U02d8jOt6vLEHfe/JQGiRRSQQxSfFWpi1MquVdAyjUar5+76PVCmYl"
        crossorigin="anonymous"></script>

    <!-- sldiderr -->

    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/slick-carousel/1.8.1/slick.min.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/slick-carousel/1.8.1/slick-theme.min.css">

    <script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/slick-carousel/1.8.1/slick.min.js"></script>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.3/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-rbsA2VBKQhggwzxH7pPCaAqO46MgnOM80zW1RWuH61DGLwZJEdK2Kadq2F9CUG65" crossorigin="anonymous">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.3/dist/js/bootstrap.bundle.min.js"
        integrity="sha384-kenU1KFdBIe4zVF0s0G1M5b4hcpxyD9F7jL+jjXkk+Q2h455rYXK/7HAuoJl+0I4"
        crossorigin="anonymous"></script>




    <style>
        .animated-img {
            position: relative;
            opacity: 0;
            animation: fadeInUp 4s linear forwards;
        }

        .animated-skills {
            position: relative;
            opacity: 0;
            animation: moveleft 4s linear forwards;
        }

        .animatedcard {
            position: relative;
            opacity: 0;
            animation: fadeInUp 3s linear forwards;
        }

        @keyframes moveleft {
            0% {
                opacity: 0;
                transform: translateX(25px);
            }

            25% {
                opacity: 0.5;
                transform: translateX(50pxpx);
            }

            50% {
                opacity: 0.5;
                transform: translateX(75px);
            }

            75% {
                opacity: 0.75;
                transform: translateX(100px);
            }

            100% {
                opacity: 1;
                transform: translateX(150px);
            }

        }

        @keyframes fadeInUp {
            0% {
                opacity: 0;
                transform: translateY(100px);
            }

            50% {
                opacity: 0.5;
                transform: translateY(25px);
            }

            100% {
                opacity: 1;
                transform: translateY(0);
            }
        }
    </style>

    <title>AYMEN'S PORTFOLIO</title>
</head>

<body style="background-color: #2d2e32;">
    <nav>
        <div class="nav-bar">

           

            <div class="menu">
                <div class="logo-container">
                    <img src="logoA.png" alt="Logo" class="logo">
                </div>
            </div>
               

            <div class="contact-us-btn">
                <a href="contact.html" id="conbtn"> Contact Us</a>
                <i class='bx bx-menu sidebarOpen'></i>
            </div>

        </div>
    </nav>
    <!-- header start -->
    <div class="header-section">
        <div class="left-section">
            <!-- <img class="animated-img"                src="https://demo.phlox.pro/freelancer/wp-content/uploads/sites/272/2021/02/hero-img.png" alt="Header Image"> -->
            <img class="animated-img" src="Mypic.png" alt="Header Image">
        </div>
        <div class="right-section">
            <div class="intro animatedcard">
                <h2 style="color: #64f4ab;">--Introduction</h2>
            </div>
            <div class="main-text">
                <h1>

                    Hello<br>
                    I'm AYMEN <Br>
                    TOUIHIR
                </h1>
            </div>
            <div class="paragraph animatedcard">
                <p>
                    Software engineer and freelancer with a passion for creating innovative solutions,  <br>
                    delivering high-quality projects,<br>
                    and collaborating with talented individuals to create digital products.</p>
            </div>
            <div class="contact-button animatedcard">
                <a href="contact.html" style="border-radius: 1em;">
                    <p style="padding: 9px; "> Contact Us</p>
                </a>
            </div>
        </div>
    </div>

    <!-- cards and skills -->
    <!-- 
	<section class="header-section1">
        <div class="left-section1">
            <h2>My Skills</h2>
            <h3>Why Hire Me For the Next Project?</h3>
            <p>My skills include stress management, MIAGE (Methods of Computer Science Applied to Business Management), website and application development, and problem-solving. I excel at efficiently creating websites and applications, leveraging MIAGE principles to address business needs while managing stress effectively.</p>
            <div class="cv-button">
                <a href="#">Download CV</a>
            </div>
        </div>
        <div class="right-section1">
            <div class="card">
                <h3>Card 1</h3>
                <p>Card 1 content goes here</p>
            </div>
            <div class="card">
                <h3>Card 2</h3>
                <p>Card 2 content goes here</p>
            </div>
            <div class="card">
                <h3>Card 3</h3>
                <p>Card 3 content goes here</p>
            </div>
            <div class="card">
                <h3>Card 4</h3>
                <p>Card 4 content goes here</p>
            </div>
        </div>
    </section> -->


    <section class="skills">
        <div class="container">
            <div style="padding: 9% 5em;" class="content-section">
                <p style="color: #64f4ab;">--My Skills</p>
                <h1 style="padding:20px 1.5em; font-size: 36px;">Why Hire Me For the Next Project?</h1>
                <p style="padding: 25px ; font-size: larger  ;">
                    My skills include stress management,
                    MIAGE (Methods of Computer Science Applied to Business Management),
                    website and application development, and problem-solving. 
                     I excel at efficiently creating websites and applications,
                     leveraging MIAGE principles to address business needs while managing stress effectively.
                </p>


                <div class="cv-button" style="padding: 26px;">
                    <a href="CV_AYMENTOUIHIR.pdf.pdf">Download CV</a>
                </div>
            </div>
            <div class="cards-section">
                <div class="card  card1 anime" style="background-color: #2d2e32; border: none;">
                    <!-- Card 1 content goes here -->
                    <div style="width: 300px; background-color: #25262a; padding: 20px; border-radius: 44px;">
                        <div style="text-align: center; margin-left: 30%;">
                            <svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink"
                                width="100" height="100">
                                <circle cx="50" cy="50" r="40" fill="#2d2e32" stroke="#64f4ab" stroke-width="2" />
                                <g transform="translate(32, 32)">
                                    <svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink"
                                        width="37" height="38.134" viewBox="0 0 37 38.134">
                                        <defs>
                                            <linearGradient id="linear-gradient" x1="0.5" x2="0.5" y2="1"
                                                gradientUnits="objectBoundingBox">
                                                <stop offset="0" stop-color="#64f4ab" />
                                                <stop offset="1" stop-color="#327a56" />
                                            </linearGradient>
                                        </defs>
                                        <g id="product_design_icon" data-name="product design - icon"
                                            transform="translate(-27.328 -15.227)">
                                            <path id="Path_58" data-name="Path 58"
                                                d="M176.63,132.33a1.044,1.044,0,0,0-.63.967v11.652a1.059,1.059,0,0,0,.629.968l9.533,4.237a1.055,1.055,0,0,0,.861,0h0l9.533-4.237a1.059,1.059,0,0,0,.629-.968V133.3a1.044,1.044,0,0,0-.63-.967h0l-9.533-4.237a1.061,1.061,0,0,0-.861,0l-9.533,4.237Zm8.9,15.226-7.415-3.3v-9.333l7.415,3.3Zm9.533-3.3-7.415,3.3v-9.333l7.415-3.3Zm-8.474-14.041,6.925,3.078-6.925,3.078-6.925-3.078Z"
                                                transform="translate(-140.794 -105.358)" fill="url(#linear-gradient)" />
                                            <path id="Path_59" data-name="Path 59" d="M248,320h2.119v5.3H248Z"
                                                transform="translate(-203.261 -271.936)" fill="url(#linear-gradient)" />
                                            <path id="Path_60" data-name="Path 60" d="M248,72h2.119v5.3H248Z"
                                                transform="translate(-203.261 -56.773)" fill="url(#linear-gradient)" />
                                            <path id="Path_61" data-name="Path 61" d="M0,0H2.119V4.916H0Z"
                                                transform="translate(27.328 25.723) rotate(-64.46)"
                                                fill="url(#linear-gradient)" />
                                            <path id="Path_76" data-name="Path 76" d="M0,0H2.119V4.916H0Z"
                                                transform="translate(58.981 42.766) rotate(-64.46)"
                                                fill="url(#linear-gradient)" />
                                            <path id="Path_62" data-name="Path 62" d="M0,0H4.916V2.119H0Z"
                                                transform="translate(58.897 25.915) rotate(-25.54)"
                                                fill="url(#linear-gradient)" />
                                            <path id="Path_63" data-name="Path 63" d="M0,0H4.916V2.119H0Z"
                                                transform="translate(27.328 42.86) rotate(-25.54)"
                                                fill="url(#linear-gradient)" />
                                        </g>
                                    </svg>
                                </g>
                            </svg>
                        </div>
                        <h3 style="text-align: center; margin-top: 20px; color: #ffffff; font-family:monospace;">Web 
                            Design</h3>
                        <p style="text-align: center; color: #E8E8E8;font-family:monospace;">The technological
                            revolution is changing aspect</p>
                    </div>
                </div>
                <div class="card  card2 anime" style="background-color: #2d2e32; border: none;">
                    <!-- Card 2 content goes here -->
                    <div style="width: 300px; background-color: #25262a; padding: 20px; border-radius: 44px;">
                        <div style="text-align: center; margin-left: 30%;">
                            <svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink"
                                width="100" height="100">
                                <circle cx="50" cy="50" r="40" fill="#2d2e32" stroke="#64f4ab" stroke-width="2" />
                                <g transform="translate(32, 32)">
                                    <svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink"
                                        width="37" height="38.134" viewBox="0 0 37 38.134">
                                        <defs>
                                            <linearGradient id="linear-gradient" x1="0.5" x2="0.5" y2="1"
                                                gradientUnits="objectBoundingBox">
                                                <stop offset="0" stop-color="#64f4ab" />
                                                <stop offset="1" stop-color="#327a56" />
                                            </linearGradient>
                                        </defs>
                                        <g id="product_design_icon" data-name="product design - icon"
                                            transform="translate(-27.328 -15.227)">
                                            <path id="Path_58" data-name="Path 58"
                                                d="M176.63,132.33a1.044,1.044,0,0,0-.63.967v11.652a1.059,1.059,0,0,0,.629.968l9.533,4.237a1.055,1.055,0,0,0,.861,0h0l9.533-4.237a1.059,1.059,0,0,0,.629-.968V133.3a1.044,1.044,0,0,0-.63-.967h0l-9.533-4.237a1.061,1.061,0,0,0-.861,0l-9.533,4.237Zm8.9,15.226-7.415-3.3v-9.333l7.415,3.3Zm9.533-3.3-7.415,3.3v-9.333l7.415-3.3Zm-8.474-14.041,6.925,3.078-6.925,3.078-6.925-3.078Z"
                                                transform="translate(-140.794 -105.358)" fill="url(#linear-gradient)" />
                                            <path id="Path_59" data-name="Path 59" d="M248,320h2.119v5.3H248Z"
                                                transform="translate(-203.261 -271.936)" fill="url(#linear-gradient)" />
                                            <path id="Path_60" data-name="Path 60" d="M248,72h2.119v5.3H248Z"
                                                transform="translate(-203.261 -56.773)" fill="url(#linear-gradient)" />
                                            <path id="Path_61" data-name="Path 61" d="M0,0H2.119V4.916H0Z"
                                                transform="translate(27.328 25.723) rotate(-64.46)"
                                                fill="url(#linear-gradient)" />
                                            <path id="Path_76" data-name="Path 76" d="M0,0H2.119V4.916H0Z"
                                                transform="translate(58.981 42.766) rotate(-64.46)"
                                                fill="url(#linear-gradient)" />
                                            <path id="Path_62" data-name="Path 62" d="M0,0H4.916V2.119H0Z"
                                                transform="translate(58.897 25.915) rotate(-25.54)"
                                                fill="url(#linear-gradient)" />
                                            <path id="Path_63" data-name="Path 63" d="M0,0H4.916V2.119H0Z"
                                                transform="translate(27.328 42.86) rotate(-25.54)"
                                                fill="url(#linear-gradient)" />
                                        </g>
                                    </svg>
                                </g>
                            </svg>
                        </div>
                        <h3 style="text-align: center; margin-top: 20px; color: #ffffff; font-family:monospace;">Apps development</h3>
                        <p style="text-align: center; color: #E8E8E8;font-family:monospace;">The technological
                            revolution is changing aspect</p>
                    </div>


                </div>
                <div class="card  card3 anime" style="background-color: #2d2e32; border: none;">
                    <!-- Card 3 content goes here -->
                    <div style="width: 300px; background-color: #25262a; padding: 20px; border-radius: 44px;">
                        <div style="text-align: center; margin-left: 30%;">
                            <svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink"
                                width="100" height="100">
                                <circle cx="50" cy="50" r="40" fill="#2d2e32" stroke="#64f4ab" stroke-width="2" />
                                <g transform="translate(32, 32)">
                                    <svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink"
                                        width="37" height="38.134" viewBox="0 0 37 38.134">
                                        <defs>
                                            <linearGradient id="linear-gradient" x1="0.5" x2="0.5" y2="1"
                                                gradientUnits="objectBoundingBox">
                                                <stop offset="0" stop-color="#64f4ab" />
                                                <stop offset="1" stop-color="#327a56" />
                                            </linearGradient>
                                        </defs>
                                        <g id="product_design_icon" data-name="product design - icon"
                                            transform="translate(-27.328 -15.227)">
                                            <path id="Path_58" data-name="Path 58"
                                                d="M176.63,132.33a1.044,1.044,0,0,0-.63.967v11.652a1.059,1.059,0,0,0,.629.968l9.533,4.237a1.055,1.055,0,0,0,.861,0h0l9.533-4.237a1.059,1.059,0,0,0,.629-.968V133.3a1.044,1.044,0,0,0-.63-.967h0l-9.533-4.237a1.061,1.061,0,0,0-.861,0l-9.533,4.237Zm8.9,15.226-7.415-3.3v-9.333l7.415,3.3Zm9.533-3.3-7.415,3.3v-9.333l7.415-3.3Zm-8.474-14.041,6.925,3.078-6.925,3.078-6.925-3.078Z"
                                                transform="translate(-140.794 -105.358)" fill="url(#linear-gradient)" />
                                            <path id="Path_59" data-name="Path 59" d="M248,320h2.119v5.3H248Z"
                                                transform="translate(-203.261 -271.936)" fill="url(#linear-gradient)" />
                                            <path id="Path_60" data-name="Path 60" d="M248,72h2.119v5.3H248Z"
                                                transform="translate(-203.261 -56.773)" fill="url(#linear-gradient)" />
                                            <path id="Path_61" data-name="Path 61" d="M0,0H2.119V4.916H0Z"
                                                transform="translate(27.328 25.723) rotate(-64.46)"
                                                fill="url(#linear-gradient)" />
                                            <path id="Path_76" data-name="Path 76" d="M0,0H2.119V4.916H0Z"
                                                transform="translate(58.981 42.766) rotate(-64.46)"
                                                fill="url(#linear-gradient)" />
                                            <path id="Path_62" data-name="Path 62" d="M0,0H4.916V2.119H0Z"
                                                transform="translate(58.897 25.915) rotate(-25.54)"
                                                fill="url(#linear-gradient)" />
                                            <path id="Path_63" data-name="Path 63" d="M0,0H4.916V2.119H0Z"
                                                transform="translate(27.328 42.86) rotate(-25.54)"
                                                fill="url(#linear-gradient)" />
                                        </g>
                                    </svg>
                                </g>
                            </svg>
                        </div>
                        <h3 style="text-align: center; margin-top: 20px; color: #ffffff; font-family:monospace;">problem-solving</h3>
                        <p style="text-align: center; color: #E8E8E8;font-family:monospace;">The technological
                            revolution is changing aspect</p>
                    </div>


                </div>
                <div class="card  card4 anime" style="background-color: #2d2e32;border: none;">
                    <!-- Card 4 content goes here -->
                    <div style="width: 300px; background-color: #25262a; padding: 20px; border-radius: 44px;">
                        <div style="text-align: center; margin-left: 30%;">
                            <svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink"
                                width="100" height="100">
                                <circle cx="50" cy="50" r="40" fill="#2d2e32" stroke="#64f4ab" stroke-width="2" />
                                <g transform="translate(32, 32)">
                                    <svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink"
                                        width="37" height="38.134" viewBox="0 0 37 38.134">
                                        <defs>
                                            <linearGradient id="linear-gradient" x1="0.5" zx2="0.5" y2="1"
                                                gradientUnits="objectBoundingBox">
                                                <stop offset="0" stop-color="#64f4ab" />
                                                <stop offset="1" stop-color="#327a56" />
                                            </linearGradient>
                                        </defs>
                                        <g id="product_design_icon" data-name="product design - icon"
                                            transform="translate(-27.328 -15.227)">
                                            <path id="Path_58" data-name="Path 58"
                                                d="M176.63,132.33a1.044,1.044,0,0,0-.63.967v11.652a1.059,1.059,0,0,0,.629.968l9.533,4.237a1.055,1.055,0,0,0,.861,0h0l9.533-4.237a1.059,1.059,0,0,0,.629-.968V133.3a1.044,1.044,0,0,0-.63-.967h0l-9.533-4.237a1.061,1.061,0,0,0-.861,0l-9.533,4.237Zm8.9,15.226-7.415-3.3v-9.333l7.415,3.3Zm9.533-3.3-7.415,3.3v-9.333l7.415-3.3Zm-8.474-14.041,6.925,3.078-6.925,3.078-6.925-3.078Z"
                                                transform="translate(-140.794 -105.358)" fill="url(#linear-gradient)" />
                                            <path id="Path_59" data-name="Path 59" d="M248,320h2.119v5.3H248Z"
                                                transform="translate(-203.261 -271.936)" fill="url(#linear-gradient)" />
                                            <path id="Path_60" data-name="Path 60" d="M248,72h2.119v5.3H248Z"
                                                transform="translate(-203.261 -56.773)" fill="url(#linear-gradient)" />
                                            <path id="Path_61" data-name="Path 61" d="M0,0H2.119V4.916H0Z"
                                                transform="translate(27.328 25.723) rotate(-64.46)"
                                                fill="url(#linear-gradient)" />
                                            <path id="Path_76" data-name="Path 76" d="M0,0H2.119V4.916H0Z"
                                                transform="translate(58.981 42.766) rotate(-64.46)"
                                                fill="url(#linear-gradient)" />
                                            <path id="Path_62" data-name="Path 62" d="M0,0H4.916V2.119H0Z"
                                                transform="translate(58.897 25.915) rotate(-25.54)"
                                                fill="url(#linear-gradient)" />
                                            <path id="Path_63" data-name="Path 63" d="M0,0H4.916V2.119H0Z"
                                                transform="translate(27.328 42.86) rotate(-25.54)"
                                                fill="url(#linear-gradient)" />
                                        </g>
                                    </svg>
                                </g>
                            </svg>
                        </div>
                        <h3 style="text-align: center; margin-top: 20px; color: #ffffff; font-family:monospace;">Team Management</h3>
                        <p style="text-align: center; color: #E8E8E8;font-family:monospace;">The technological
                            revolution is changing aspect</p>
                    </div>


                </div>
            </div>
        </div>
    </section>

    <!-- skills details section  -->


    <div class="container skillsdelt mx-auto pt-16">
        <div class="flex flex-wrap">
            <div class="w-full lg:w-1/2" id="leftSection">
                <div class="flex flex-col h-full p-10 left_sec ">
                    <div class="mb-4 mt-4">
                        <h4 style="color: #64f4ab;" style=" font-family:monospace;" class="text-lg  font-bold">Project 1
                        </h4>
                    </div>
                    <div class="mb-4 mt-4">
                        <h2 class="text-5xl text-white font-bold " style=" font-family:monospace;">Automated email sender
                        </h2>
                    </div>
                    <div class="mb-4 mt-4">
                        <p class="text-white text-lg" style=" font-family:monospace;">This automated email sender can efficiently send over 50,000
                             emails in one hour,
                             making it ideal for updating business marketing strategies. <br>
                             It ensures timely delivery of messages, enabling businesses to reach a large audience effectively 
                             This service is essential for marketers and businesses to ensure
                             effective communication with their audience</p>
                    </div>
                    <div class="mb-4 mt-4">
                        <h2 class="text-5xl text-white font-bold " style=" font-family:monospace;">Checker SMTPS
                        </h2>
                    </div>
                    <div class="mb-4 mt-4">
                        <p class="text-white text-lg" style=" font-family:monospace;">SMTP checker verifies SMTP settings for email delivery.
                             It ensures emails are sent to the inbox,not spam. <br>
                             It checks server response, DNS configuration, and blacklist status, optimizing email deliverability.
                             This service is essential for marketers and businesses to ensure effective communication with their audience.
                            </p>
                    </div>
                    <div class="flex items-center">
                        <a href="#" class="flex items-center text-white text-yellow-500">
                            <span class=" mr-2">
                                <svg xmlns="http://www.w3.org/2000/svg" width="18" height="10.998"
                                    viewBox="0 0 18 10.998">
                                    <g id="right_arrow_-_icon" data-name="right arrow - icon"
                                        transform="translate(21 -6.501) rotate(90)">
                                        <path id="Path_98" data-name="Path 98"
                                            d="M6.59,11.858a.714.714,0,0,0,.627.38h4.066v8.028a.717.717,0,1,0,1.434,0V12.238h4.066a.713.713,0,0,0,.627-.38.748.748,0,0,0-.02-.745l-4.783-7.77a.709.709,0,0,0-1.214,0L6.61,11.113A.754.754,0,0,0,6.59,11.858Z"
                                            fill="#fecd1a" />
                                    </g>
                                </svg></span>
                        .</a>
                    </div>
                </div>
            </div>

            <div class="w-full lg:w-1/2 anime" id="rightSection">
                <div class="flex justify-center items-center h-full">
                    <div class="w-3/4">
                        <img style="border-radius: 37px;"
                            src="sender.png"
                            alt="Image" class="w-full h-auto rounded-lg">
                    </div>
                </div>
            </div>
            <div class="w-full lg:w-1/2 anime" id="rightSection">
                <div class="flex justify-center items-center h-full">
                    <div class="w-3/4">
                        <img style="border-radius: 37px;"
                            src="checker.png"
                            alt="Image" class="w-full h-auto rounded-lg">
                    </div>
                </div>
            </div>
        </div>
    </div>


    <div class="container skillsdelt mt-20 pt-16">
        <div class="flex flex-wrap">
            <div class="w-full lg:w-1/2 anime" id="rightSection1">
                <div class="flex justify-center items-center h-full">
                    <div class="w-3/4 ">
                        <img style="border-radius: 37px;"
                            src="school-manag.png"
                            alt="Image" class="w-full h-auto rounded-lg">
                    </div>
                </div>
            </div>
            <div class="w-full lg:w-1/2" id="leftSection1">
                <div class="flex flex-col h-full p-10 left_sec ">
                    <div class="mb-4 mt-4">
                        <h4 style="color: #64f4ab;" style=" font-family:monospace;" class="text-lg  font-bold">Project 2
                        </h4>
                    </div>
                    <div class="mb-4 mt-4">
                        <h2 class="text-5xl text-white font-bold " style=" font-family:monospace;"> School management app.</h2>

                        
                    </div>
                    <div class="mb-4 mt-4">
                        <p class="text-white text-lg" style=" font-family:monospace;">This comprehensive school management application 
                            handles all aspects of school administration, 
                            including student, teacher, security, and parent management, as well as accounting and payment tracking.                            we learn. Factual knowledge is less prized when everything you ever need to know can be
                            It is built using Spring Boot for the backend and Angular for the frontend,  
                            ensuring a robust and user-friendly system for efficient school operations. </p>
                    </div>
                    <div class="flex items-center">
                        <a href="#" class="flex items-center text-white text-yellow-500">
                            <span class=" mr-2">
                                <svg xmlns="http://www.w3.org/2000/svg" width="18" height="10.998"
                                    viewBox="0 0 18 10.998">
                                    <g id="right_arrow_-_icon" data-name="right arrow - icon"
                                        transform="translate(21 -6.501) rotate(90)">
                                        <path id="Path_98" data-name="Path 98"
                                            d="M6.59,11.858a.714.714,0,0,0,.627.38h4.066v8.028a.717.717,0,1,0,1.434,0V12.238h4.066a.713.713,0,0,0,.627-.38.748.748,0,0,0-.02-.745l-4.783-7.77a.709.709,0,0,0-1.214,0L6.61,11.113A.754.754,0,0,0,6.59,11.858Z"
                                            fill="#fecd1a" />
                                    </g>
                                </svg></span>
                            Read more
                        </a>
                    </div>
                </div>
            </div>

        </div>
    </div>
    <!-- line no 3 -->


    <div class="container skillsdelt mt-20 pt-16">
        <div class="flex flex-wrap">
            <div class="w-full lg:w-1/2" id="leftSection2">
                <div class="flex flex-col h-full p-10 left_sec ">
                    <div class="mb-4 mt-4">
                        <h4 style="color: #64f4ab;" style=" font-family:monospace;" class="text-lg  font-bold">Project 3
                        </h4>
                    </div>
                    <div class="mb-4 mt-4">
                        <h2 class="text-5xl text-white font-bold " style=" font-family:monospace;">Guide website</h2>
                
                    </div>
                    <div class="mb-4 mt-4">
                        <p class="text-white text-lg" style=" font-family:monospace;">A travel guide website for Marrakech, Morocco, offering detailed 
                            information on attractions, accommodations, dining, and activities.
                             It provides insights into local culture and traditions, as well as practical
                              travel tips. The site aims to help travelers plan their trips
                               to Marrakech and make the most of their visit.</p>
                    </div>
                    <div class="flex items-center">
                        <a href="#" class="flex items-center text-white text-yellow-500">
                            <span class=" mr-2">
                                <svg xmlns="http://www.w3.org/2000/svg" width="18" height="10.998"
                                    viewBox="0 0 18 10.998">
                                    <g id="right_arrow_-_icon" data-name="right arrow - icon"
                                        transform="translate(21 -6.501) rotate(90)">
                                        <path id="Path_98" data-name="Path 98"
                                            d="M6.59,11.858a.714.714,0,0,0,.627.38h4.066v8.028a.717.717,0,1,0,1.434,0V12.238h4.066a.713.713,0,0,0,.627-.38.748.748,0,0,0-.02-.745l-4.783-7.77a.709.709,0,0,0-1.214,0L6.61,11.113A.754.754,0,0,0,6.59,11.858Z"
                                            fill="#fecd1a" />
                                    </g>
                                </svg></span>
                            Read more
                        </a>
                    </div>
                </div>
            </div>

            <div class="w-full lg:w-1/2  anime" id="rightSection2">
                <div class="flex justify-center items-center h-full">
                    <div class="w-3/4">
                        <img style="border-radius: 37px;"
                            src="guide.png"
                            alt="Image" class="w-full h-auto rounded-lg">
                    </div>
                </div>
            </div>
        </div>
    </div>





    <div class="center-button">
        <button style="background-color: #ffaf29;">View All
            <div class="star-1">
                <svg xmlns:xlink="http://www.w3.org/1999/xlink" viewBox="0 0 784.11 815.53"
                    style="shape-rendering:geometricPrecision; text-rendering:geometricPrecision; image-rendering:optimizeQuality; fill-rule:evenodd; clip-rule:evenodd"
                    version="1.1" xml:space="preserve" xmlns="http://www.w3.org/2000/svg">
                    <defs></defs>
                    <g id="Layer_x0020_1">
                        <metadata id="CorelCorpID_0Corel-Layer"></metadata>
                        <path
                            d="M392.05 0c-20.9,210.08 -184.06,378.41 -392.05,407.78 207.96,29.37 371.12,197.68 392.05,407.74 20.93,-210.06 184.09,-378.37 392.05,-407.74 -207.98,-29.38 -371.16,-197.69 -392.06,-407.78z"
                            class="fil0"></path>
                    </g>
                </svg>
            </div>
            <div class="star-2">
                <svg xmlns:xlink="http://www.w3.org/1999/xlink" viewBox="0 0 784.11 815.53"
                    style="shape-rendering:geometricPrecision; text-rendering:geometricPrecision; image-rendering:optimizeQuality; fill-rule:evenodd; clip-rule:evenodd"
                    version="1.1" xml:space="preserve" xmlns="http://www.w3.org/2000/svg">
                    <defs></defs>
                    <g id="Layer_x0020_1">
                        <metadata id="CorelCorpID_0Corel-Layer"></metadata>
                        <path
                            d="M392.05 0c-20.9,210.08 -184.06,378.41 -392.05,407.78 207.96,29.37 371.12,197.68 392.05,407.74 20.93,-210.06 184.09,-378.37 392.05,-407.74 -207.98,-29.38 -371.16,-197.69 -392.06,-407.78z"
                            class="fil0"></path>
                    </g>
                </svg>
            </div>
            <div class="star-3">
                <svg xmlns:xlink="http://www.w3.org/1999/xlink" viewBox="0 0 784.11 815.53"
                    style="shape-rendering:geometricPrecision; text-rendering:geometricPrecision; image-rendering:optimizeQuality; fill-rule:evenodd; clip-rule:evenodd"
                    version="1.1" xml:space="preserve" xmlns="http://www.w3.org/2000/svg">
                    <defs></defs>
                    <g id="Layer_x0020_1">
                        <metadata id="CorelCorpID_0Corel-Layer"></metadata>
                        <path
                            d="M392.05 0c-20.9,210.08 -184.06,378.41 -392.05,407.78 207.96,29.37 371.12,197.68 392.05,407.74 20.93,-210.06 184.09,-378.37 392.05,-407.74 -207.98,-29.38 -371.16,-197.69 -392.06,-407.78z"
                            class="fil0"></path>
                    </g>
                </svg>
            </div>
            <div class="star-4">
                <svg xmlns:xlink="http://www.w3.org/1999/xlink" viewBox="0 0 784.11 815.53"
                    style="shape-rendering:geometricPrecision; text-rendering:geometricPrecision; image-rendering:optimizeQuality; fill-rule:evenodd; clip-rule:evenodd"
                    version="1.1" xml:space="preserve" xmlns="http://www.w3.org/2000/svg">
                    <defs></defs>
                    <g id="Layer_x0020_1">
                        <metadata id="CorelCorpID_0Corel-Layer"></metadata>
                        <path
                            d="M392.05 0c-20.9,210.08 -184.06,378.41 -392.05,407.78 207.96,29.37 371.12,197.68 392.05,407.74 20.93,-210.06 184.09,-378.37 392.05,-407.74 -207.98,-29.38 -371.16,-197.69 -392.06,-407.78z"
                            class="fil0"></path>
                    </g>
                </svg>
            </div>
            <div class="star-5">
                <svg xmlns:xlink="http://www.w3.org/1999/xlink" viewBox="0 0 784.11 815.53"
                    style="shape-rendering:geometricPrecision; text-rendering:geometricPrecision; image-rendering:optimizeQuality; fill-rule:evenodd; clip-rule:evenodd"
                    version="1.1" xml:space="preserve" xmlns="http://www.w3.org/2000/svg">
                    <defs></defs>
                    <g id="Layer_x0020_1">
                        <metadata id="CorelCorpID_0Corel-Layer"></metadata>
                        <path
                            d="M392.05 0c-20.9,210.08 -184.06,378.41 -392.05,407.78 207.96,29.37 371.12,197.68 392.05,407.74 20.93,-210.06 184.09,-378.37 392.05,-407.74 -207.98,-29.38 -371.16,-197.69 -392.06,-407.78z"
                            class="fil0"></path>
                    </g>
                </svg>
            </div>
            <div class="star-6">
                <svg xmlns:xlink="http://www.w3.org/1999/xlink" viewBox="0 0 784.11 815.53"
                    style="shape-rendering:geometricPrecision; text-rendering:geometricPrecision; image-rendering:optimizeQuality; fill-rule:evenodd; clip-rule:evenodd"
                    version="1.1" xml:space="preserve" xmlns="http://www.w3.org/2000/svg">
                    <defs></defs>
                    <g id="Layer_x0020_1">
                        <metadata id="CorelCorpID_0Corel-Layer"></metadata>
                        <path
                            d="M392.05 0c-20.9,210.08 -184.06,378.41 -392.05,407.78 207.96,29.37 371.12,197.68 392.05,407.74 20.93,-210.06 184.09,-378.37 392.05,-407.74 -207.98,-29.38 -371.16,-197.69 -392.06,-407.78z"
                            class="fil0"></path>
                    </g>
                </svg>
            </div>
        </button>
    </div>

    <div class="wrapperx">
        <div class="containerx num1">

            <span class="num " data-val="17">0</span>
            <span class="text">Happy Clients</span>
        </div>

        <div class="containerx">

            <span class="num" data-val="7">0</span>
            <span class="text">Projects Done</span>
        </div>

        <div class="containerx num2">

            <span class="num " data-val="2">0</span>
            <span class="text">Years Experience</span>
        </div>
    </div>







    <!-- slider  section  -->






    <div class="container" style="width: 100%; margin-top: 13%;">
        <div class="slider " style="width: 100% ;">
            <div class="slide " style="width: 100%;">
                <div class="row">


                   
                </div>
            </div>
        </div>
    </div>
    </div>
    <script>
        $(document).ready(function () {
            $('.slider').slick({
                arrows: false,
                dots: true,
                infinite: true,
                speed: 300,
                slidesToShow: 1,
                slidesToScroll: 1
            });
        });
    </script>


    <!-- footer section  -->


    <div class="footer1">

        <div class="logo_sec">
            <span class="logo navLogo">
                <!-- <img src="https://demo.phlox.pro/freelancer/wp-content/uploads/sites/272/2021/02/logo-header.svg"> -->
                
                    <path fill-opacity="0" stroke="#fff" stroke-width="3"
                        d="M 146.7050018310547 52.247501373291016 A 78.35250091552734 78.35250091552734 0 1 0 146.7050018310547 104.45750045776367">
                    </path>
                    <g transform="translate(10,52.247501373291016)">
                        <g>
                            <rect data-gra="graph-name-bg" stroke-width="2" class="i-icon-bg" x="0" y="0"
                                width="273.4100036621094" height="52.209999084472656" fill-opacity="0"></rect>
                            <!----> <!---->
                        </g>
                        <g transform="translate(10,3)">
                            <g data-gra="path-name" fill-rule="" class="tp-name">
                                <g transform="scale(1)">
                                    <g>
                                        <path
                                       d="M55.17 0L51.14 0 51.14-21.46 11.47-21.46 11.47 0 7.44 0 7.44-44.28 11.47-44.28 11.47-25.2 51.14-25.2 51.14-44.28 55.17-44.28 55.17 0ZM116.18 0L112.18 0 112.18-4.9Q109.86-3.64 106.91-2.58 103.96-1.51 100.69-0.74 97.42 0.03 93.97 0.45 90.53 0.87 87.21 0.87L87.21 0.87Q82.89 0.87 79.46 0.1 76.02-0.68 73.64-2.21 71.25-3.74 69.97-6.01 68.68-8.28 68.68-11.28L68.68-11.28Q68.68-14.24 70.18-16.52 71.67-18.79 74.45-20.48 77.22-22.17 81.13-23.35 85.05-24.52 89.88-25.35 94.72-26.17 100.34-26.7 105.96-27.23 112.18-27.59L112.18-27.59 112.18-30.97Q112.18-33.03 111.41-34.61 110.64-36.19 109.25-37.37 107.86-38.54 106-39.33 104.13-40.12 101.95-40.61 99.78-41.09 97.37-41.3 94.97-41.51 92.56-41.51L92.56-41.51Q89.3-41.51 86.63-41.19 83.95-40.86 81.63-40.3 79.31-39.74 77.18-38.99 75.06-38.25 72.9-37.42L72.9-37.42 72.9-42.12Q77.38-43.31 82.45-44.2 87.53-45.08 93.23-45.08L93.23-45.08Q98.07-45.08 102.26-44.26 106.45-43.44 109.54-41.64 112.63-39.83 114.41-36.98 116.18-34.13 116.18-30.04L116.18-30.04 116.18 0ZM112.18-9.12L112.18-24.01Q101.64-23.43 94.18-22.37 86.72-21.3 81.99-19.75 77.25-18.21 75.04-16.15 72.83-14.08 72.83-11.47L72.83-11.47Q72.83-9.35 73.91-7.7 74.99-6.06 77.02-4.95 79.05-3.83 81.95-3.27 84.85-2.71 88.46-2.71L88.46-2.71Q90.59-2.71 92.86-2.95 95.13-3.19 97.39-3.63 99.65-4.06 101.84-4.66 104.03-5.25 105.96-5.96 107.9-6.67 109.49-7.48 111.09-8.28 112.18-9.12L112.18-9.12ZM132.71-44.28L136.74-44.28 136.74-37.48Q138.16-38.7 139.9-40.09 141.64-41.48 143.73-42.64 145.83-43.8 148.28-44.57 150.73-45.34 153.53-45.34L153.53-45.34Q158.01-45.34 161.46-43.33 164.91-41.31 167.03-37.09L167.03-37.09Q169.1-38.99 171.29-40.52 173.48-42.06 175.78-43.12 178.09-44.18 180.54-44.76 182.99-45.34 185.6-45.34L185.6-45.34Q188.92-45.34 191.64-44.21 194.36-43.09 196.26-41.12 198.17-39.16 199.21-36.5 200.26-33.84 200.26-30.81L200.26-30.81 200.26 0 196.23 0 196.23-29.78Q196.23-32.55 195.57-34.72 194.91-36.9 193.51-38.41 192.11-39.93 189.93-40.72 187.76-41.51 184.73-41.51L184.73-41.51Q182.31-41.51 179.94-40.81 177.57-40.12 175.41-38.98 173.25-37.83 171.38-36.38 169.52-34.93 168.1-33.39L168.1-33.39Q168.26-32.48 168.27-31.84 168.29-31.2 168.29-30.29L168.29-30.29 168.29 0 164.26 0 164.26-29.78Q164.26-33.06 163.39-35.3 162.52-37.54 160.98-38.93 159.43-40.32 157.32-40.91 155.21-41.51 152.73-41.51L152.73-41.51Q150.37-41.51 148.07-40.7 145.76-39.9 143.67-38.61 141.58-37.32 139.8-35.72 138.03-34.13 136.74-32.55L136.74-32.55 136.74 0 132.71 0 132.71-44.28ZM255.79 0L236.65-20.01 217.57 0 212.48 0 234.13-22.72 213.54-44.28 218.63-44.28 236.65-25.33 254.72-44.28 259.82-44.28 239.22-22.72 260.85 0 255.79 0Z"
                                          transform="translate(-7.440000057220459, 45.34000015258789)"></path>

                                    </g> <!----> <!----> <!----> <!----> <!----> <!----> <!---->
                                </g>
                            </g> <!---->
                        </g>
                    </g>
                </g>
                <defs v-gra="od"></defs>
            </svg>
            </span>

        </div>
        <div class="infoo">
            <h3 style="color: white;">© 2024 Freelancer - Crafted with passion and creativity by AYMEN.</h3>
        </div>
        <div class="otheracc">

            <div class="elementor-grid-item">
                <a class="elementor-icon elementor-social-icon elementor-social-icon-auxicon-twich elementor-repeater-item-395a9c5"
                    href="#" target="_blank">

                    <i class="auxicon auxicon-twich"></i> </a>
            </div>>
            <div class="elementor-grid-item">
                <a class="elementor-icon elementor-social-icon elementor-social-icon-linkedin-in elementor-repeater-item-638ce13"
                    href="https://www.linkedin.com/in/aymen-touihir-00b964197/" target="_blank">

                    <i class="fab fa-linkedin-in"></i> </a>
            </div>
            
           
        </div>
    </div>
    <!-- Script -->
    <script src="script.js"></script>
    <script>



        const intersectionCallback = (entries) => {
            for (const entry of entries) { // Loop over all elements that either enter or exit the view.
                if (entry.isIntersecting) { // This is true when the element is in view.
                    entry.target.classList.add('animatedcard'); // Add a class.
                }
            }
        }

        /**
         * Create a observer and use the instersectionCallback as 
         * the instructions for what to do when an element enters
         * or leaves the view
         */
        const observer = new IntersectionObserver(intersectionCallback);

        /**
         * Get all .item elements and loop over them.
         * Observe each individual item.
         */
        const items = document.querySelectorAll('.anime');
        for (const item of items) {
            observer.observe(item);
            console.log("observ");
        }

    </script>

    <script>
        $(window).on('scroll', function () {
            var st = $(this).scrollTop(),
                vh = $(this).height(),
                $counter = $('.wrapperx'),
                ct = $counter.offset().top;
            if ((st + vh) > ct) {
                // #counter is in the viewport

                let valueDisplays = document.querySelectorAll(".num");
                let interval = 100;

                valueDisplays.forEach((valueDisplay) => {
                    let startValue = 0;
                    let endValue = parseInt(valueDisplay.getAttribute("data-val"));
                    let duration = Math.floor(interval / endValue);
                    let counter = setInterval(function () {
                        startValue += 1;
                        valueDisplay.textContent = startValue;
                        if (startValue == endValue) {
                            clearInterval(counter);
                        }
                    }, duration);
                });
            }
        })</script>

</body>
</body>

</html>
