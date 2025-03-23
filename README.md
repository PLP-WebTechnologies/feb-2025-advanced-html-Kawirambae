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
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Webpage</title>
</head>
<body>

    <!-- Ordered List with Roman Numerals -->
    <h2>My Hobbies</h2>
    <ol type="I">
        <li>Swimming</li>
        <li>Dancing</li>
        <li>Writing</li>
        <li>Travelling</li>
        <li>Reading</li>
    </ol>

    <!-- External Image from Pexels -->
    <h2>Character Image</h2>
    <img src="https://images.pexels.com/photos/16231450/pexels-photo-16231450/free-photo-of-a-woman-with-red-hair-and-a-man-in-a-white-shirt.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=2" 
         alt="Elves" width="500">

    <!-- Table of Contacts -->
    <h2>Contact List</h2>
    <table border="1">
        <tr>
            <th>Name</th>
            <th>Address</th>
            <th>Mobile Number</th>
            <th>Email</th>
        </tr>
        <tr>
            <td>Alec</td>
            <td>Nairobi</td>
            <td>0712345678</td>
            <td>alec@gmail.com</td>
        </tr>
        <tr>
            <td>June</td>
            <td>Russia</td>
            <td>12345678</td>
            <td>june@gmail.com</td>
        </tr>
        <tr>
            <td>Joburg</td>
            <td>Malaysia</td>
            <td>98765432</td>
            <td>joburg@gmail.com</td>
        </tr>
        <tr>
            <td>Malia</td>
            <td>USA</td>
            <td>1234567890</td>
            <td>malia@gmail.com</td>
        </tr>
        <tr>
            <td>Baby</td>
            <td>Houston</td>
            <td>368992376</td>
            <td>baby@gmail.com</td>
        </tr>
    </table>

    <!-- Registration Form -->
    <h2>Registration Form</h2>
    <form action="submit-form.php" method="post">
        
        <!-- Name Field -->
        <label for="name">Full Name:</label>
        <input type="text" id="name" name="name" placeholder="Enter your full name" required>
        <br><br>

        <!-- Email Field -->
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" placeholder="Enter your email" required>
        <br><br>

        <!-- Password Field -->
        <label for="password">Password:</label>
        <input type="password" id="password" name="password" placeholder="Create a password" required>
        <br><br>

        <!-- Date of Birth Field -->
        <label for="dob">Date of Birth:</label>
        <input type="date" id="dob" name="dob" required>
        <br><br>

        <!-- Dropdown Field -->
        <label for="country">Select Your Country:</label>
        <select id="country" name="country" required>
            <option value="">--Choose--</option>
            <option value="USA">USA</option>
            <option value="UK">UK</option>
            <option value="Canada">Canada</option>
            <option value="Australia">Australia</option>
        </select>
        <br><br>

        <!-- Radio Buttons -->
        <label>Gender:</label><br>
        <input type="radio" id="male" name="gender" value="Male" required>
        <label for="male">Male</label>

        <input type="radio" id="female" name="gender" value="Female" required>
        <label for="female">Female</label>

        <input type="radio" id="other" name="gender" value="Other" required>
        <label for="other">Other</label>
        <br><br>

        <!-- Checkboxes -->
        <label>Interests:</label><br>
        <input type="checkbox" id="sports" name="interests" value="Sports">
        <label for="sports">Sports</label>

        <input type="checkbox" id="music" name="interests" value="Music">
        <label for="music">Music</label>

        <input type="checkbox" id="reading" name="interests" value="Reading">
        <label for="reading">Reading</label>
        <br><br>

        <!-- Submit Button -->
        <button type="submit">Register</button>
    </form>

</body>
</html>

