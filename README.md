# html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Event Registration</title>
    <link rel="stylesheet" href="pgm1.css">
</head>
<body>

    <div class="form-container">
        <h2>Welcome to my app</h2>
        <p>Event Registration Form</p>
        
        <form id="registrationForm">
            <div class="input-group">
                <label for="name">Name</label>
                <input type="text" id="name" required>
            </div>

            <div class="input-group">
                <label for="email">Email</label>
                <input type="email" id="email" required>
            </div>

            <div class="input-group">
                <label for="password">Password</label>
                <input type="password" id="password" required>
            </div>

            <div class="input-group">
                <label for="confirmPassword">Confirm Password</label>
                <input type="password" id="confirmPassword" required>
            </div>

            <div class="checkbox-group">
                <input type="checkbox" id="terms" required>
                <label for="terms">I accept the Terms and Conditions</label>
            </div>

            <button type="submit">Register</button>
        </form>
    </div>

    <!-- Linked directly to your pgm1.jss file -->
    <script src="pgm1.jss"></script>
</body>
</html>
