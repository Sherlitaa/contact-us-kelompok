<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us</title>
    <style>
        body {
            background-color: #f0fff0;
            font-family: sans-serif;
        }
        .container {
            width: 400px;
            margin: 100px auto;
            padding: 20px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        h2 {
            text-align: center;
            margin-bottom: 20px;
        }
        label {
            display: block;
            margin-bottom: 5px;
        }
        input[type="text"],
        input[type="email"],
        textarea {
            width: 100%;
            padding: 10px;
            margin-bottom: 15px;
            border: 1px solid #ccc;
            border-radius: 3px;
            box-sizing: border-box;
        }
        input[type="radio"] {
            margin-right: 5px;
        }
        input[type="checkbox"] {
            margin-right: 5px;
        }
        button {
            background-color: #008000;
            color: white;
            padding: 12px 20px;
            border: none;
            border-radius: 3px;
            cursor: pointer;
            width: 100%;
        }
        button:hover {
            background-color: #006400;
        }
    </style>
</head>
<body>
    <div class="container">
        <h2>Contact Us</h2>
        <form>
            <label for="firstName">First Name *</label>
            <input type="text" id="firstName" name="firstName" required>

            <label for="lastName">Last Name *</label>
            <input type="text" id="lastName" name="lastName" required>

            <label for="email">Email *</label>
            <input type="email" id="email" name="email" required>

            <label for="phone">Phone</label>
            <input type="text" id="phone" name="phone">

            <label for="message">Message *</label>
            <textarea id="message" name="message" required></textarea>

            <label>How did you hear about us? *</label>
            <input type="radio" id="google" name="hearAboutUs" value="google" required>
            <label for="google">Google</label>
            <input type="radio" id="facebook" name="hearAboutUs" value="facebook" required>
            <label for="facebook">Facebook</label>
            <input type="radio" id="friend" name="hearAboutUs" value="friend" required>
            <label for="friend">Friend</label>

            <label>Would you like to receive our newsletter?</label>
            <input type="checkbox" id="newsletter" name="newsletter">

            <button>Send</button>
        </form>
    </div>
</body>
</html>
