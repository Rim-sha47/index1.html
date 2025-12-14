# index1.html<!DOCTYPE html>
<html>
<head>
    <title>HTML Form</title>
</head>
<body>

    <h2>Student Registration Form</h2>

    <form>
        <!-- Name -->
        <label>Full Name:</label><br>
        <input type="text" placeholder="Enter your name"><br><br>

        <!-- Email -->
        <label>Email:</label><br>
        <input type="email" placeholder="Enter your email"><br><br>

        <!-- Password -->
        <label>Password:</label><br>
        <input type="password" placeholder="Enter password"><br><br>

        <!-- Gender -->
        <label>Gender:</label><br>
        <input type="radio" name="gender"> Male
        <input type="radio" name="gender"> Female<br><br>

        <!-- Course -->
        <label>Course:</label><br>
        <select>
            <option>HTML</option>
            <option>CSS</option>
            <option>JavaScript</option>
            <option>React</option>
        </select><br><br>

        <!-- Message -->
        <label>Message:</label><br>
        <textarea rows="4" cols="30"></textarea><br><br>

        <!-- Submit -->
        <input type="submit" value="Submit">
        <input type="reset" value="Reset">

    </form>

</body>
</html>
