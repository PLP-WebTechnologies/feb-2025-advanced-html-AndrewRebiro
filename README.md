# Advanced HTML5 Elements and Forms

## Objectives
Implement HTML5 images, lists, tables, forms and input types.
Use form validation attributes.
Apply multimedia elements such as audio and video.

## Instructions

- Create an index.html file.
- Add an ordered list with roman numerals
- Add an external image from pexels.com
- Add a table of 5 contacts with; name, address, mobile and emails
- Add a registration form

>[!NOTE]
>  The registration form should have:
>- Name, email, password, and date fields.
>- A dropdown, radio buttons, and checkboxes.
>- Proper labels and placeholders.
>- Required fields and validation attributes.
>- Ensure proper indentation and commenting.
 
# Tasks
- Create a well-structured HTML5 document.
- Ensure semantic correctness.

Happy Coding! 💻✨
MY CODE:
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML5 Form & Multimedia Example</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 20px;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 20px;
        }
        table, th, td {
            border: 1px solid #ddd;
        }
        th, td {
            padding: 8px;
            text-align: left;
        }
        img {
            max-width: 100%;
            height: auto;
            margin-top: 20px;
        }
        .form-section {
            margin-top: 30px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to the HTML5 Form & Multimedia Example</h1>
    </header>

    <!-- Ordered List with Roman Numerals -->
    <section>
        <h2>Ordered List with Roman Numerals</h2>
        <ol type="I">
            <li>Introduction to HTML5</li>
            <li>Understanding Forms</li>
            <li>Embedding Media</li>
            <li>Working with Tables</li>
            <li>Styling and Layout</li>
        </ol>
    </section>

    <!-- External Image from Pexels (Kenyan Flag) -->
    <section>
        <h2>External Image</h2>
        <img src="https://images.pexels.com/photos/16291766/pexels-photo-16291766.jpeg" alt="Kenyan Flag from Pexels" width="300">
    </section>

    <!-- Contact Table -->
    <section>
        <h2>Contacts Table</h2>
        <table>
            <thead>
                <tr>
                    <th>Name</th>
                    <th>Address</th>
                    <th>Mobile</th>
                    <th>Email</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>John Kgia</td>
                    <td>123 Main St</td>
                    <td>(123) 456-7890</td>
                    <td>john@example.com</td>
                </tr>
                <tr>
                    <td>Jane Smith</td>
                    <td>456 Oak Ave</td>
                    <td>(234) 567-8901</td>
                    <td>jane@example.com</td>
                </tr>
                <tr>
                    <td>Mark Omari</td>
                    <td>789 Pine Rd</td>
                    <td>(345) 678-9012</td>
                    <td>mark@example.com</td>
                </tr>
                <tr>
                    <td>Emily Nyakio</td>
                    <td>101 Birch Blvd</td>
                    <td>(456) 789-0123</td>
                    <td>emily@example.com</td>
                </tr>
                <tr>
                    <td>David Kamau</td>
                    <td>202 Cedar Ct</td>
                    <td>(567) 890-1234</td>
                    <td>david@example.com</td>
                </tr>
            </tbody>
        </table>
    </section>

    <!-- Registration Form -->
    <section class="form-section">
        <h2>Registration Form</h2>
        <form action="#" method="POST">
            <!-- Name -->
            <label for="name">Full Name:</label>
            <input type="text" id="name" name="name" placeholder="Enter your full name" required><br><br>

            <!-- Email -->
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" placeholder="Enter your email" required><br><br>

            <!-- Password -->
            <label for="password">Password:</label>
            <input type="password" id="password" name="password" placeholder="Enter a secure password" required minlength="8"><br><br>

            <!-- Date -->
            <label for="dob">Date of Birth:</label>
            <input type="date" id="dob" name="dob" required><br><br>

            <!-- Dropdown -->
            <label for="country">Country:</label>
            <select id="country" name="country" required>
                <option value="">Select your country</option>
                <option value="USA">United States</option>
                <option value="CAN">Canada</option>
                <option value="UK">United Kingdom</option>
            </select><br><br>

            <!-- Radio Buttons -->
            <label>Gender:</label><br>
            <input type="radio" id="male" name="gender" value="male">
            <label for="male">Male</label><br>
            <input type="radio" id="female" name="gender" value="female">
            <label for="female">Female</label><br><br>

            <!-- Checkboxes -->
            <label>Interests:</label><br>
            <input type="checkbox" id="coding" name="interests" value="coding">
            <label for="coding">Coding</label><br>
            <input type="checkbox" id="music" name="interests" value="music">
            <label for="music">Music</label><br><br>

            <!-- Submit Button -->
            <input type="submit" value="Register">
        </form>
    </section>

    <!-- Multimedia Elements: Audio and Video -->
    <section class="form-section">
        <h2>Multimedia Elements</h2>

        <!-- Audio -->
        <h3>Audio Example</h3>
        <audio controls>
            <source src="https://www.soundhelix.com/examples/mp3/SoundHelix-Song-1.mp3" type="audio/mp3">
            Your browser does not support the audio element.
        </audio>

        <!-- Video -->
        <h3>Video Example</h3>
        <video width="320" height="240" controls>
            <source src="https://www.w3schools.com/html/mov_bbb.mp4" type="video/mp4">
            Your browser does not support the video element.
        </video>
    </section>

</body>
</html>

