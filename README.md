<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Website</title>
</head>

<body>

    <header>
        <h1>My Website</h1>
        <p>Welcome to my page</p>
    </header>

    <nav>
        <a href="#about">About</a> |
        <a href="#skills">Skills</a> |
        <a href="#contact">Contact</a>
    </nav>

    <main>

        <section id="about">
            <h2>About Me</h2>

            <p>
                I am a CSE student learning web development.
            </p>

            <figure>
                <img src="photo.jpg" alt="My photo" width="150">
                <figcaption>My Photo</figcaption>
            </figure>
        </section>

        <section id="skills">
            <h2>My Skills</h2>

            <ul>
                <li>HTML</li>
                <li>CSS</li>
                <li>JavaScript</li>
                <li>Python</li>
            </ul>
        </section>

        <article>
            <h2>My Goal</h2>

            <p>
                My goal is to become a Full Stack Developer.
            </p>
        </article>

        <section id="contact">
            <h2>Contact</h2>

            <form>
                <label>Name:</label>
                <input type="text">

                <br><br>

                <label>Message:</label>
                <textarea></textarea>

                <br><br>

                <button type="submit">Send</button>
            </form>
        </section>

    </main>

    <footer>
        <p>© 2026 My Website</p>
    </footer>

</body>

</html>
