writeCode

- Create a responsive layout according to the design shown below.

#### Large Screen view(Above 768px)

![Responsive Layout Assignment](https://raw.githubusercontent.com/suraj122/AC-STYLE-images/master/rwd/ex-1-desktop-view.png)

#### Small Screen view(Below 768px)

![Responsive Layout Assignment](https://raw.githubusercontent.com/suraj122/AC-STYLE-images/master/rwd/ex-1-mob-view.png)

- Using CSS resets is necessary.

- Use semantic tags and keep the nesting and indentation proper.

- Pay attention to the codes, your code quality matters a lot.

- Try to implement the layout as exactly as it has been provided in the design.

- Pay attention to minor things like spacing, alignment, size, etc.

- Use any font-family which suits better for the assignment.

- Once you are done with the assignment connect with the mentor and get the code reviewed.
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="assets/style.css">
    <script src="https://kit.fontawesome.com/ef43d9bbc3.js" crossorigin="anonymous"></script>
    <title>Responsive Website 1</title>
</head>
<body>
    <header>
        <div class="header container flex item-center">
            <img class="logo"src="assets/logo.png" alt="logo">
            <nav class="navigation">
                <ul class="flex item-center">
                    <li><a href="#">Home</a></li>
                    <li><a href="#">Blog</a></li>
                    <li><a href="#">About</a></li>
                </ul>
            </nav>
        </div>
    </header>
    <main>
        <section class="intro">
            <div class="container flex">
                <article class="flex-48">
                    <h1>What is Lorem Ipsum?</h1>
                    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Proin mollis convallis justo non bibendum. Fusce quis dictum justo. 
                        In venenatis metus sed erat ullamcorper, nec commodo est pretium. Suspendisse vitae lorem et mi sagittis laoreet. 
                        Quisque turpis orci, auctor ut suscipit quis, vestibulum id arcu. Praesent commodo justo et placerat porta. 
                        Donec sollicitudin tristique ex quis lacinia. Suspendisse sollicitudin lobortis est quis vestibulum. 
                        Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus.
                        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Proin mollis convallis justo non bibendum. Fusce quis dictum justo. 
                        In venenatis metus sed erat ullamcorper, nec commodo est pretium. Suspendisse vitae lorem et mi sagittis laoreet. 
                        Quisque turpis orci, auctor ut suscipit quis, vestibulum id arcu. Praesent commodo justo et placerat porta. 
                        Donec sollicitudin tristique ex quis lacinia. Suspendisse sollicitudin lobortis est quis vestibulum. 
                        Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus.
                    </p>
                    <button class="button">
                        Read More
                    </button>
                </article>
                <figure class="intro-img flex-48">
                    <img src="assets/01.png">
                </figure>
            </div>
        </section>
        <section class="blog container">
            <h2>Our Blog</h2>
            <div class=" flex flex-30">
                <article class="blog-art flex-30">
                    <img src="assets/02.png">
                    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Proin mollis convallis justo non bibendum. Fusce quis dictum justo. 
                        In venenatis metus sed erat ullamcorper, nec commodo est pretium. Suspendisse vitae lorem et mi sagittis laoreet. 
                        Quisque turpis orci, auctor ut suscipit quis, vestibulum id arcu. Praesent commodo justo et placerat porta. 
                        Donec sollicitudin tristique ex quis lacinia. Suspendisse sollicitudin lobortis est quis vestibulum.
                     </p>
                     <button class="button">
                        Read More
                    </button>
                </article>
                <article class="blog-art flex-30">
                    <img src="assets/03.png">
                    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Proin mollis convallis justo non bibendum. Fusce quis dictum justo. 
                        In venenatis metus sed erat ullamcorper, nec commodo est pretium. Suspendisse vitae lorem et mi sagittis laoreet. 
                        Quisque turpis orci, auctor ut suscipit quis, vestibulum id arcu. Praesent commodo justo et placerat porta. 
                        Donec sollicitudin tristique ex quis lacinia. Suspendisse sollicitudin lobortis est quis vestibulum.
                     </p>
                     <button class="button">
                        Read More
                    </button>
                </article>
                <article class="blog-art flex-30">
                    <img src="assets/04.png">
                    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Proin mollis convallis justo non bibendum. Fusce quis dictum justo. 
                        In venenatis metus sed erat ullamcorper, nec commodo est pretium. Suspendisse vitae lorem et mi sagittis laoreet. 
                        Quisque turpis orci, auctor ut suscipit quis, vestibulum id arcu. Praesent commodo justo et placerat porta. 
                        Donec sollicitudin tristique ex quis lacinia. Suspendisse sollicitudin lobortis est quis vestibulum.
                     </p>
                     <button class="button">
                        Read More
                    </button>
                </article>
            </div>
        </section>
    </main>
    <footer>
        <div class="footer container flex">
            <h3>&copy; Altcampus</h3>
            <figure class="icons flex">
                <i class="fab fa-facebook-square"></i>
                <i class="fab fa-twitter-square"></i>
            </figure>
        </div>

    </footer>
</body>
</html>
