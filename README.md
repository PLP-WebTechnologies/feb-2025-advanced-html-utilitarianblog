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

# Solution
### index.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Advanced HTML5 Elements Assignment</title>
</head>
<body>

    <!-- Ordered List with Roman Numerals -->
    <h2>Ordered List (Roman Numerals)</h2>
    <ol type="I">
        <li>HTML5 Elements</li>
        <li>Forms and Input Types</li>
        <li>Form Validation</li>
        <li>Multimedia Elements</li>
        <li>Tables and Lists</li>
    </ol>

    <!-- External Image -->
    <h2>Sample Image</h2>
    <img src="https://images.pexels.com/photos/1108099/pexels-photo-1108099.jpeg" alt="Sample Image from Pexels" width="500">

    <!-- Contacts Table -->
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
            <td>123 Street, City</td>
            <td>+1234567890</td>
            <td>johndoe@example.com</td>
        </tr>
        <tr>
            <td>Jane Smith</td>
            <td>456 Avenue, City</td>
            <td>+0987654321</td>
            <td>janesmith@example.com</td>
        </tr>
        <tr>
            <td>Mike Johnson</td>
            <td>789 Road, City</td>
            <td>+1122334455</td>
            <td>mikej@example.com</td>
        </tr>
        <tr>
            <td>Sarah Brown</td>
            <td>101 Highway, City</td>
            <td>+6677889900</td>
            <td>sarahb@example.com</td>
        </tr>
        <tr>
            <td>David Wilson</td>
            <td>202 Lane, City</td>
            <td>+5566778899</td>
            <td>davidw@example.com</td>
        </tr>
    </table>

    <!-- Registration Form -->
    <h2>Registration Form</h2>
    <form action="#" method="post">
        <!-- Name Field -->
        <label for="name">Full Name:</label>
        <input type="text" id="name" name="name" placeholder="Enter your full name" required>

        <!-- Email Field -->
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" placeholder="Enter your email" required>

        <!-- Password Field -->
        <label for="password">Password:</label>
        <input type="password" id="password" name="password" placeholder="Enter a strong password" required>

        <!-- Date Field -->
        <label for="dob">Date of Birth:</label>
        <input type="date" id="dob" name="dob" required>

        <!-- Dropdown (Gender) -->
        <label for="gender">Gender:</label>
        <select id="gender" name="gender" required>
            <option value="" disabled selected>Select your gender</option>
            <option value="male">Male</option>
            <option value="female">Female</option>
            <option value="other">Other</option>
        </select>

        <!-- Radio Buttons (Subscription Plan) -->
        <fieldset>
            <legend>Choose a Subscription Plan:</legend>
            <label><input type="radio" name="plan" value="basic" required> Basic</label>
            <label><input type="radio" name="plan" value="standard"> Standard</label>
            <label><input type="radio" name="plan" value="premium"> Premium</label>
        </fieldset>

        <!-- Checkboxes (Preferences) -->
        <fieldset>
            <legend>Select Your Interests:</legend>
            <label><input type="checkbox" name="interests" value="technology"> Technology</label>
            <label><input type="checkbox" name="interests" value="sports"> Sports</label>
            <label><input type="checkbox" name="interests" value="music"> Music</label>
            <label><input type="checkbox" name="interests" value="movies"> Movies</label>
        </fieldset>

        <!-- Submit Button -->
        <button type="submit">Register</button>
    </form>

</body>
</html>
