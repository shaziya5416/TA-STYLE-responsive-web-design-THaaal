writeCode

- Create a responsive layout according to the design shown below.

#### Large Screen view(Above 768px)

![Responsive Layout Assignment](https://raw.githubusercontent.com/suraj122/AC-STYLE-images/master/rwd/ex-2.png)

#### Small Screen view(Below 768px)

1. Figure what would be the best possible way to display the layout on small screens.

2. Create hmaburger icon to toggle menu on mobile view.

- Using CSS resets is necessary.
- Use semantic tags and keep the nesting and indentation proper.
- Pay attention to the codes, your code quality matters a lot.
- Try to implement the layout as exactly as it has been provided in the design.
- Pay attention to minor things like spacing, alignment, size, etc.
- Use "Nunito" font-family for the assignment.
- Figure out the best possible way to display the layout on small screens.
- Create hmaburger icon to toggle menu on small screen view.
- Once you are done with the assignment connect with the mentor and get the code reviewed.

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="assets/style.css">
    <script src="https://kit.fontawesome.com/ef43d9bbc3.js" crossorigin="anonymous"></script>
    <title>Responsive Website 2</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Nunito:wght@200;300;400;600;700;800;900&display=swap" rel="stylesheet">

</head>
<body>
    <header>
        <div class="header container flex item-center">
            <h2>Alt Events</h2>
            <nav class="navigation flex">
                <ul class="flex item-center">
                    <li><a href="#">Home</a></li>
                    <li><a href="#">About</a></li>
                    <li><a href="#">Services</a></li>
                    <li><a href="#">Contact</a></li>
                </ul>
                <button class="nav-bar">
                    Join Us
                </button>
            </nav>
        </div>
        <section class="hero container flex item-center">
            <article class="hero-article flex-48">
                <h1>Web Developer <br> Conference <strong>2020</strong> </h1>
                <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry.
                    Lorem Ipsum is simply dummy text of the printing and typesetting industry.
                </p>
                <button>
                    Register Now
                </button>
            </article>
            <img class="hero-img" src="assets/hero.png" alt="hero">
        </section>
    </header>
    <main>
        <section class="about container item-center flex">
            <img class="about-img" src="assets/about.png">
            <article class="about-article flex-48">
                <h1>ABOUT THE EVENT </h1>
                <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry.
                    Lorem Ipsum is simply dummy text of the printing and typesetting industry.
                </p>
                <button>
                    Register Now
                </button>
            </article>
        </section>
        <section class="join">
            <div class="join-1 container">
                <h1>Why you should join?</h1>
                <div class="flex">
                <article class="join-article flex-30">
                        <div class="number">
                            <h3><strong>1</strong></h3>
                        </div>
                        <div class="below-number">
                            <h3>Network</h3>
                            <p>
                                Lorem Ipsum is simply dummy text of the printing and typesetting industry.
                                Lorem Ipsum is simply dummy text of the
                            </p>
                        </div>
                </article>
                <article class="join-article flex-30">
                    <div class="number">
                        <h3><strong>2</strong></h3>
                    </div>
                    <div class="below-number">
                        <h3>Great Speakers</h3>
                        <p>
                            Lorem Ipsum is simply dummy text of the printing and typesetting industry.
                            Lorem Ipsum is simply dummy text of the
                        </p>
                    </div>
                </article>
                <article class="join-article flex-30">
                    <div class="number">
                        <h3><strong>3</strong></h3>
                    </div>
                    <div class="below-number">
                        <h3>Information</h3>
                        <p>
                            Lorem Ipsum is simply dummy text of the printing and typesetting industry.
                            Lorem Ipsum is simply dummy text of the
                        </p>
                    </div>
                </article>
                </div>
            </div>
        </section>
        <section class="schedule container">
            <h1>Schedule</h1>
            <div class="flex">
            <aside>
                <div class="aside">
                <figure class="date-red flex">
                    <h3>06 Sept</h3>
                </figure>
                <div class="vertical-line"></div>
                </div>
                <div class="aside">
                    <figure class="date-white flex">
                        <h3>07 Sept</h3>
                    </figure>
                    <div class="vertical-line"></div>
                    </div>
                    <div class="aside">
                        <figure class="date-white flex">
                            <h3>08 Sept</h3>
                        </figure>
                        <div class="vertical-line"></div>
                    </div>
                        <div class="aside">
                            <figure class="date-white flex">
                                <h3>09 Sept</h3>
                            </figure>
                    </div>
            </aside>
            <div> 
                <article class="schedule-article flex">
                    <img class="schedule-img" src="assets/schedule-01.jpg" >
                    <div class="date">6 September</div>
                    <article class="schedule-article2">
                        <h3>Digital world Transformation</h3>
                        <p>
                            Lorem Ipsum is simply dummy text of the printing and typesetting industry.
                            Lorem Ipsum is simply dummy text of the
                        </p>
                    </article>
                </article>
                <article class="schedule-article flex">
                        <img class="schedule-img" src="assets/schedule-02.jpg">
                        <div class="date">7 September</div>
                        <article class="schedule-article2">
                            <h3>Digital world Transformation</h3>
                            <p>
                                Lorem Ipsum is simply dummy text of the printing and typesetting industry.
                                Lorem Ipsum is simply dummy text of the
                            </p>
                        </article>
                </article>
                <article class="schedule-article flex">
                    <img class="schedule-img" src="assets/schedule-03.jpg">
                    <div class="date">8 September</div>
                    <article class="schedule-article2">
                        <h3>Digital world Transformation</h3>
                        <p>
                            Lorem Ipsum is simply dummy text of the printing and typesetting industry.
                            Lorem Ipsum is simply dummy text of the
                        </p>
                    </article>
                </article>
                <article class="schedule-article flex">
                    <img class="schedule-img" src="assets/schedule-04.jpg">
                    <div class="date">9 September</div>
                    <article class="schedule-article2">
                        <h3>Digital world Transformation</h3>
                        <p>
                            Lorem Ipsum is simply dummy text of the printing and typesetting industry.
                            Lorem Ipsum is simply dummy text of the
                        </p>
                    </article>
                </article>
            </div>
            </div>
            <button>
                Download Schedule
            </button>
        </section>
        <section class="icons">
            <div class="container flex">
                <figure class="icons-figure flex-25">
                    <img class="icons-img" src="assets/speaker.png">
                    <h3>10+</h3>
                    <p>Great Speaker</p>
                </figure>
                <figure class="icons-figure red flex-25">
                    <img class="icons-img" src="assets/idea.png">
                    <h3>10+</h3>
                    <p>Great Speaker</p>
                </figure>
                <figure class="icons-figure flex-25">
                    <img class="icons-img" src="assets/participants.png">
                    <h3>10+</h3>
                    <p>Great Speaker</p>
                </figure>
                <figure class="icons-figure flex-25">
                    <img class="icons-img" src="assets/sponsor.png">
                    <h3>10+</h3>
                    <p>Great Speaker</p>
                </figure>
            </div>
        </section>
        <section class="video container">
                <iframe width="100%" height="700" src="https://www.youtube.com/embed/0_H4UqCbfz4?controls=0" title="YouTube video player" 
                frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen>
                </iframe>
        </section>
        <section class="news">
            <h1>Our Latest News</h1>
            <div class="news1 container flex">
                <article class="news-article flex-30">
                    <img class="news-img" src="assets/news-01.png" alt="news">
                    <h5>How to build developer portfolio as a beginner developer</h5>
                    <p>
                        Lorem Ipsum is simply dummy text of the printing and typesetting industry.
                        Lorem Ipsum is simply dummy text of the printing and typesetting industry.
                    </p>
                    <a href="#">
                        Read More
                    </a>
                </article>
                <article class="news-article flex-30">
                    <img class="news-img" src="assets/news-02.png" alt="news">
                    <h5>How to build developer portfolio as a beginner developer</h5>
                    <p>
                        Lorem Ipsum is simply dummy text of the printing and typesetting industry.
                        Lorem Ipsum is simply dummy text of the printing and typesetting industry.
                    </p>
                    <a href="#">
                        <strong>Read More</strong>
                    </a>
                </article>
                <article class="news-article flex-30">
                    <img class="news-img" src="assets/news-03.png" alt="news">
                    <h5>How to build developer portfolio as a beginner developer</h5>
                    <p>
                        Lorem Ipsum is simply dummy text of the printing and typesetting industry.
                        Lorem Ipsum is simply dummy text of the printing and typesetting industry.
                    </p>
                    <a href="#">
                        Read More
                    </a>
                </article>
            </div>
        </section>  
    </main>
    <footer>
        <section class="footer1">
            <div class="container flex item-center">
            <img class="footer-logo flex-30 " src="assets/logo.svg">
            <div class="quick-link flex-30">
                <h5>Quick Links</h5>
                <ul class="flex">
                    <li><a href="#">Program</a></li>
                    <li><a href="#">About Us</a></li>
                    <li><a href="#">Contact Us</a></li>
                    <li><a href="#">Services</a></li>
                </ul>
            </div>
            <div class="social-media">
                <h5>Follow Us</h5>
                <figure class="social-icons">
                    <i class="fab fa-facebook-square"></i>
                    <i class="fab fa-twitter-square"></i>
                </figure>
            </div>
            </div>
        </section>
        <section class="footer2">
            <div class="container">
                <p> &copy; Altcampus Services Pvt. Limited 2018-Present </p>
            </div>

        </section>
        
    </footer>
</body>
</html>
