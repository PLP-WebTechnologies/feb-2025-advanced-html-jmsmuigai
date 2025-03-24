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

- SOLUTION
  <!DOCTYPE html>
<html lang="en">
<head>
    <!-- Metadata and page settings -->
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Advanced HTML5 Elements and Forms">
    <title>Advanced HTML5 Elements</title>
    
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
            padding: 20px;
        }
        table, th, td {
            border: 1px solid black;
            border-collapse: collapse;
            padding: 10px;
        }
    </style>
</head>
<body>
    <!-- Header Section -->
    <header>
        <h1>Welcome to Advanced HTML5 Elements</h1>
    </header>
    
    <!-- Ordered List with Roman Numerals -->
    <section>
        <h2>Ordered List with Roman Numerals</h2>
        <ol type="I">
            <li>Item One</li>
            <li>Item Two</li>
            <li>Item Three</li>
        </ol>
    </section>
    
    <!-- External Image -->
    <section>
        <h2>External Image from Pexels</h2>
        <img src="https://www.pexels.com/photo/example.jpg" alt="Example Image from Pexels" width="400">
    </section>
    
    <!-- Contact Table -->
    <section>
        <h2>Contacts Table</h2>
        <table>
            <tr>
                <th>Name</th>
                <th>Address</th>
                <th>Mobile</th>
                <th>Email</th>
            </tr>
            <tr>
                <td>John Doe</td>
                <td>123 Main St</td>
                <td>+123456789</td>
                <td>john@example.com</td>
            </tr>
            <tr>
                <td>Jane Smith</td>
                <td>456 Elm St</td>
                <td>+987654321</td>
                <td>jane@example.com</td>
            </tr>
            <tr>
                <td>Mike Johnson</td>
                <td>789 Oak St</td>
                <td>+112233445</td>
                <td>mike@example.com</td>
            </tr>
            <tr>
                <td>Emily Davis</td>
                <td>101 Pine St</td>
                <td>+554433221</td>
                <td>emily@example.com</td>
            </tr>
            <tr>
                <td>Chris Wilson</td>
                <td>202 Maple St</td>
                <td>+667788990</td>
                <td>chris@example.com</td>
            </tr>
        </table>
    </section>
    
    <!-- Registration Form -->
    <section>
        <h2>Registration Form</h2>
        <form>
            <!-- Name Field -->
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" placeholder="Enter your name" required>
            <br><br>
            
            <!-- Email Field -->
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" placeholder="Enter your email" required>
            <br><br>
            
            <!-- Password Field -->
            <label for="password">Password:</label>
            <input type="password" id="password" name="password" placeholder="Enter your password" required>
            <br><br>
            
            <!-- Date Field -->
            <label for="dob">Date of Birth:</label>
            <input type="date" id="dob" name="dob" required>
            <br><br>
            
            <!-- Dropdown Field -->
            <label for="country">Country:</label>
            <select id="country" name="country">
                <option value="usa">USA</option>
                <option value="uk">UK</option>
                <option value="canada">Canada</option>
            </select>
            <br><br>
            
            <!-- Radio Buttons -->
            <label>Gender:</label>
            <input type="radio" id="male" name="gender" value="male"> <label for="male">Male</label>
            <input type="radio" id="female" name="gender" value="female"> <label for="female">Female</label>
            <br><br>
            
            <!-- Checkboxes -->
            <label>Interests:</label>
            <input type="checkbox" id="sports" name="interests" value="sports"> <label for="sports">Sports</label>
            <input type="checkbox" id="music" name="interests" value="music"> <label for="music">Music</label>
            <input type="checkbox" id="reading" name="interests" value="reading"> <label for="reading">Reading</label>
            <br><br>
            
            <!-- Submit Button -->
            <button type="submit">Register</button>
        </form>
    </section>
</body>
</html>


Happy Coding! 💻✨

SOLUTION

<!DOCTYPE html>
<html lang="en">
<head>
    <!-- Page Metadata -->
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Advanced HTML5 Elements and Forms Example">
    <title>Advanced HTML5 Elements</title>

    <!-- Inline Styling for Table and Layout -->
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
        }
        table, th, td {
            border: 1px solid #000;
            border-collapse: collapse;
            padding: 8px;
        }
        section {
            margin-bottom: 30px;
        }
    </style>
</head>
<body>

    <!-- Header -->
    <header>
        <h1>Welcome to Advanced HTML5 Elements</h1>
    </header>

    <!-- Ordered List with Roman Numerals -->
    <section>
        <h2>Ordered List (Roman Numerals)</h2>
        <ol type="I">
            <li>HTML5 Basics</li>
            <li>Tables & Lists</li>
            <li>Forms & Validation</li>
        </ol>
    </section>

    <!-- External Image from Pexels -->
    <section>
        <h2>Image from Pexels</h2>
        <!-- Use a direct image link from Pexels (right-click > Copy Image Address) -->
        <img src="https://images.pexels.com/photos/1103970/pexels-photo-1103970.jpeg" 
             alt="Nature View from Pexels" 
             width="400">
    </section>

    <!-- Table of 5 Contacts -->
    <section>
        <h2>Contact List</h2>
        <table>
            <tr>
                <th>Name</th>
                <th>Address</th>
                <th>Mobile</th>
                <th>Email</th>
            </tr>
            <tr>
                <td>John Doe</td>
                <td>123 Main St</td>
                <td>+123456789</td>
                <td>john@example.com</td>
            </tr>
            <tr>
                <td>Jane Smith</td>
                <td>456 Elm St</td>
                <td>+987654321</td>
                <td>jane@example.com</td>
            </tr>
            <tr>
                <td>Mike Johnson</td>
                <td>789 Oak St</td>
                <td>+112233445</td>
                <td>mike@example.com</td>
            </tr>
            <tr>
                <td>Emily Davis</td>
                <td>101 Pine St</td>
                <td>+554433221</td>
                <td>emily@example.com</td>
            </tr>
            <tr>
                <td>Chris Wilson</td>
                <td>202 Maple St</td>
                <td>+667788990</td>
                <td>chris@example.com</td>
            </tr>
        </table>
    </section>

    <!-- Registration Form -->
    <section>
        <h2>Registration Form</h2>
        <form method="POST" action="#">
            <!-- Fieldset groups related fields together -->
            <fieldset>
                <legend>Personal Information</legend>

                <!-- Name Input -->
                <label for="name">Name:</label><br>
                <input type="text" id="name" name="name" placeholder="Enter your name" required>
                <br><br>

                <!-- Email Input -->
                <label for="email">Email:</label><br>
                <input type="email" id="email" name="email" placeholder="Enter your email" required>
                <br><br>

                <!-- Password Input -->
                <label for="password">Password:</label><br>
                <input type="password" id="password" name="password" placeholder="Enter your password" required>
                <br><br>

                <!-- Date of Birth Input -->
                <label for="dob">Date of Birth:</label><br>
                <input type="date" id="dob" name="dob" required>
                <br><br>
            </fieldset>

            <fieldset>
                <legend>Additional Details</legend>

                <!-- Country Dropdown -->
                <label for="country">Country:</label><br>
                <select id="country" name="country" required>
                    <option value="">--Select Country--</option>
                    <option value="usa">USA</option>
                    <option value="uk">UK</option>
                    <option value="canada">Canada</option>
                </select>
                <br><br>

                <!-- Gender Radio Buttons -->
                <label>Gender:</label><br>
                <input type="radio" id="male" name="gender" value="male" required>
                <label for="male">Male</label>

                <input type="radio" id="female" name="gender" value="female">
                <label for="female">Female</label>
                <br><br>

                <!-- Interests Checkboxes -->
                <label>Interests:</label><br>
                <input type="checkbox" id="sports" name="interests[]" value="sports">
                <label for="sports">Sports</label>

                <input type="checkbox" id="music" name="interests[]" value="music">
                <label for="music">Music</label>

                <input type="checkbox" id="reading" name="interests[]" value="reading">
                <label for="reading">Reading</label>
                <br><br>
            </fieldset>

            <!-- Submit Button -->
            <button type="submit">Register</button>
        </form>
    </section>

    <!-- Audio Element -->
    <section>
        <h2>Sample Audio</h2>
        <audio controls>
            <source src="https://www.soundhelix.com/examples/mp3/SoundHelix-Song-1.mp3" type="audio/mpeg">
            Your browser does not support the audio element.
        </audio>
    </section>

    <!-- Video Element -->
    <section>
        <h2>Sample Video</h2>
        <video width="400" controls>
            <source src="https://www.w3schools.com/html/mov_bbb.mp4" type="video/mp4">
            Your browser does not support the video tag.
        </video>
    </section>

</body>
</html>

