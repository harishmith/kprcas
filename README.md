<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>KPRCAS Login</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <style>
        body {
            margin: 0;
            padding: 0;
            font-family: Arial, sans-serif;
            background: #f2f6ff;
            height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
        }

        .login-box {
            background: #ffffff;
            width: 360px;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 8px 20px rgba(0, 0, 0, 0.15);
            text-align: center;
        }

        .login-box img {
            width: 140px;
            margin-bottom: 15px;
        }

        .login-box h2 {
            margin-bottom: 20px;
            color: #1f3c88;
        }

        .login-box input {
            width: 100%;
            padding: 12px;
            margin: 10px 0;
            border-radius: 5px;
            border: 1px solid #ccc;
            font-size: 14px;
        }

        .login-box button {
            width: 100%;
            padding: 12px;
            margin-top: 10px;
            background-color: #1f3c88;
            color: white;
            border: none;
            border-radius: 5px;
            font-size: 16px;
            cursor: pointer;
        }

        .login-box button:hover {
            background-color: #142b63;
        }

        .footer {
            margin-top: 15px;
            font-size: 12px;
            color: #777;
        }
    </style>
</head>

<body>

    <div class="login-box">
        <!-- KPRCAS Logo -->
        <img src="download.jpg" alt="KPRCAS Logo">

        <h2>Login</h2>

        <form>
            <input type="text" placeholder="Username" required>
            <input type="password" placeholder="Password" required>
            <button type="submit">Login</button>
        </form>

        <div class="footer">
            © 2025 KPRCAS | Learn Beyond
        </div>
    </div>

</body>
</html>
