<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Form</title>
</head>
<body>
    <h1>Form</h1>
    <h2>Answer2</h2>
    <form action="/submit" method="post">
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" required>
        <br><br>

        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required>
        <br><br>

        <label for="password">Password:</label>
        <input type="password" id="password" name="password" required>
        <br><br>

        <label for="subscribe">Subscribe us:</label>
        <input type="checkbox" id="subscribe" name="subscribe">
        <br><br>

        <label>Gender:</label>
        <input type="radio" id="male" name="gender" value="male">
        <label for="male">Male</label>
        <input type="radio" id="female" name="gender" value="female">
        <label for="female">Female</label>
        <input type="radio" id="other" name="gender" value="other">
        <label for="other">Other</label>
        <br><br>

        <label for="file">Upload a file:</label>
        <input type="file" id="file" name="file">
        <br><br>

        <label for="country">Country:</label>
        <select id="country" name="country">
            <option value="us">United States</option>
            <option value="ca">Canada</option>
            <option value="uk">United Kingdom</option>
            <option value="au">Australia</option>
        </select>
        <br><br>
        
        <input type="submit" value="submit">

        <input type="reset" value="reset">

        <button type="button" onclick="alert">Click me</button>

    </form> 
    
</body>
</html>
