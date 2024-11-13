<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Reset Your Password</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            display: flex;
            align-items: center;
            justify-content: center;
            height: 100vh;
            margin: 0;
            background-color: #f4f4f9;
        }
        .container {
            background-color: white;
            padding: 2em;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            width: 300px;
            text-align: center;
        }
        h1 {
            font-size: 1.5em;
            color: #333;
            margin-bottom: 1em;
        }
        .input-group {
            margin-bottom: 1.5em;
            text-align: left;
        }
        label {
            display: block;
            font-weight: bold;
            color: #555;
        }
        input[type="password"] {
            width: 100%;
            padding: 10px;
            margin-top: 0.5em;
            border-radius: 4px;
            border: 1px solid #ccc;
            font-size: 1em;
        }
        .submit-btn {
            background-color: #007bff;
            color: white;
            padding: 10px;
            border: none;
            border-radius: 4px;
            font-size: 1em;
            cursor: pointer;
            width: 100%;
        }
        .submit-btn:hover {
            background-color: #0056b3;
        }
        .message {
            margin-top: 1em;
            color: #28a745;
        }
        .error {
            color: #dc3545;
        }
    </style>
</head>
<body>

<div class="container">
    <h1>Reset Your Password</h1>
    <form id="resetForm">
        <div class="input-group">
            <label for="password">New Password</label>
            <input type="password" id="password" required>
        </div>
        <div class="input-group">
            <label for="verify">Verify Password</label>
            <input type="password" id="verify" required>
        </div>
        <button type="submit" class="submit-btn">Reset Password</button>
    </form>
    <div id="message" class="message"></div>
</div>

<script>
    document.getElementById("resetForm").addEventListener("submit", async function (e) {
        e.preventDefault();

        const params = new URLSearchParams(window.location.search);
        const token = params.get('token');
        const email = params.get('email');

        const password = document.getElementById("password").value;
        const verify = document.getElementById("verify").value;

        const messageElem = document.getElementById("message");
        messageElem.textContent = "";

        if (password !== verify) {
            messageElem.textContent = "Passwords do not match.";
            messageElem.classList.add("error");
            return;
        }

        // Perform the reset request
        try {
            const response = await fetch("https://your-backend-url.com/reset-password", {
                method: "POST",
                headers: {
                    "Content-Type": "application/json"
                },
                body: JSON.stringify({ email, token, password })
            });

            const data = await response.json();
            if (response.ok) {
                messageElem.textContent = "Password reset successful! You can now log in with your new password.";
                messageElem.classList.remove("error");
                messageElem.classList.add("message");
            } else {
                messageElem.textContent = data.message || "There was an issue resetting your password.";
                messageElem.classList.add("error");
            }
        } catch (error) {
            messageElem.textContent = "An unexpected error occurred.";
            messageElem.classList.add("error");
        }
    });
</script>

</body>
</html>
