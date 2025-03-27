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

My code 

<!DOCTYPE html>
<html>
    <head>
        <title>Advanced HTML5 Elements and Forms </title>
    </head>
    <body>
        <h1>Advanced HTML5 Elements and Forms </h1>
        <br>
        <h3>Web Development Languages</h3>
        <ol type="i">
            <li>Python</li>
            <li>HyperText Makeup Language(HTML)  & CSS </li>
            <li>JavaSrript</li>
            <li>PHP</li>
            <li>TypeScript</li>
        </ol>

        <img src="https://images.pexels.com/photos/5380664/pexels-photo-5380664.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" alt="The screen of a Programmer" title="The screen of a programmer" width="350">
        <br><br>
        <table border="1">
            <caption><h4>Software Developers</h4></caption>
            <thead>
                <tr>
                    <th>Name</th>
                    <th>Address</th>
                    <th>Mobile</th>
                    <th>Email</th>
                </tr>
            </thead>
            <tbody>
               </tr>
                    <td>Matthew Mahlangu</td>
                    <td>Pretoria, 0122</td>
                    <td>0766355199</td>
                    <td>matthewmahlangu@gmail.com</td>
                </tr>
                <tr>
                    <td>Jabulani Sithole</td>
                    <td>Johannesburg, 2014</td>
                    <td>0761671447</td>
                    <td>jabulanisithole@gmail.com</td>
                </tr>
                <tr>
                    <td>Sphiwe Mtshweni</td>
                    <td>Edenvale,1020</td>
                    <td>0727125889</td>
                    <td>sphiwemtshweni@gmail.com</td>
                </tr>
                <tr>
                    <td>Precious Mbonani</td>
                    <td>Mbombela, 1057</td>
                    <td>0783961111</td>
                    <td>preciousmbonani@gmail.com</td>
                </tr>
                <tr>
                    <td>Noluthando Masango</td>
                    <td>Lakeside, 1174</td>
                    <td>0712234619</td>
                    <td>noluthandomasango@gmail.com</td>
                </tr>

            </tbody>
        </table>
        <br><br>
        <h3>Registration form</h3>
        <br><br>
        <form action="#" method="post">
            <label for="name">Full Name:</label>
            <input type="text" id="name" name="name" placeholder="Enter your full name" required>
            <br><br>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" placeholder="Enter your email" required>
            <br><br>
            <label for="password">Password:</label>
            <input type="password" id="password" name="password" placeholder="Enter your password" required>
            <br><br>
            <label for="dob">Date of Birth:</label>
            <input type="date" id="dob" name="dob" required>
            <br><br>
            <label for="gender">Gender:</label>
            <input type="radio" id="gender" name="gender" value="male" required> Male
            <input type="radio" id="gender" name="gender" value="female" required> Female 
            <input type="radio" id="gender" name="gender" value="binary" required> Binary
            <input type="radio" id="gender" name="gender" value="other" required> Other
            <br><br>
            <label for="province">Province:</label>
            <select name="province" id="province">
                <option>--Select Province--</option>
                <option value="gauteng">Gauteng</option>
                <option value="mpumalanga">Mpumalanga</option>
                <option value="limpopo">Limpopo</option>
                <option value="kwazulu natal">Kwazulu Natal</option>
                <option value="free state">Free State</option>
                <option value="northern cape">Northern Cape</option>
                <option value="eastern cape">Eastern Cape</option>
                <option value="western cape">Western Cape</option>
                <option value="north west">North West</option>
            </select>
            <br><br>
            <label for="interests">Interests:</label>
            <input type="checkbox" name="interests" value="python"> Python
            <input type="checkbox" name="interests" value="html"> HTML
            <input type="checkbox" name="interests" value="java"> Java
            <input type="checkbox" name="interests" value="javascript"> Javascript
            <br><br>
            <label for="description">Describe yourself</label>
            <textarea name="description" id="description"> </textarea>
            <br><br>
            <button type="submit">Register</button>

        </form>

    </body>
</html>
