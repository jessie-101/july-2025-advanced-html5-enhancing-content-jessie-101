# july-2025-advanced-html5-enhancing-content-jessie-101
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Enhanced HTML5 Form</title>
</head>
<body>

<header>
    <h1>Enhanced HTML5 Form with Lists, Tables, and Media</h1>
</header>

<main>
    <!-- Section 1: Lists -->
    <section>
        <h2>Types of Programming Languages</h2>
        <ul>
            <li>Python</li>
            <li>JavaScript</li>
            <li>Java</li>
            <li>C++</li>
        </ul>
    </section>

    <!-- Section 2: Tables -->
    <section>
        <h2>Programming Language Features</h2>
        <table>
            <thead>
                <tr>
                    <th>Language</th>
                    <th>Popularity</th>
                    <th>Difficulty</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Python</td>
                    <td>High</td>
                    <td>Easy</td>
                </tr>
                <tr>
                    <td>JavaScript</td>
                    <td>High</td>
                    <td>Medium</td>
                </tr>
                <tr>
                    <td>C++</td>
                    <td>Medium</td>
                    <td>Hard</td>
                </tr>
            </tbody>
        </table>
    </section>

    <!-- Section 3: Media -->
    <section>
        <h2>Programming Tutorials</h2>
        <p>Watch this tutorial on Python:</p>
        <video controls>
            <source src="python-tutorial.mp4" type="video/mp4">
        </video>
    </section>

    <!-- Section 4: HTML5 Form -->
    <section>
        <h2>Registration Form</h2>
        <form action="#" method="POST">

            <!-- Name Field -->
            <fieldset>
                <legend>Personal Information</legend>
                <label for="name">Full Name:</label>
                <input type="text" id="name" name="name" required placeholder="Enter your full name">

                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required placeholder="Enter your email address">
            </fieldset>

            <!-- Gender Field -->
            <fieldset>
                <legend>Gender</legend>
                <label for="male">Male</label>
                <input type="radio" id="male" name="gender" value="male">
                <label for="female">Female</label>
                <input type="radio" id="female" name="gender" value="female">
            </fieldset>

            <!-- Age Field -->
            <fieldset>
                <legend>Age</legend>
                <label for="age">Age (18-100):</label>
                <input type="number" id="age" name="age" min="18" max="100" required>
            </fieldset>

            <!-- Subscription Field -->
            <fieldset>
                <legend>Subscription</legend>
                <label for="subscribe">Subscribe to our newsletter:</label>
                <input type="checkbox" id="subscribe" name="subscribe">
            </fieldset>

            <!-- Submit Button -->
            <button type="submit">Submit</button>
        </form>
    </section>

</main>

<footer>
    <p>&copy; 2025 Your Name | All Rights Reserved</p>
</footer>

</body>
</html>
