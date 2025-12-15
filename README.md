
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>KPR Login Page</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #e9eef3;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }

        .login-box {
            background-color: #ffffff;
            width: 330px;
            padding: 30px;
            text-align: center;
            border-radius: 10px;
            box-shadow: 0 0 12px rgba(0,0,0,0.2);
        }

        .login-box img {
            width: 130px;
            margin-bottom: 15px;
        }

        .login-box h2 {
            margin-bottom: 20px;
            color: #333;
        }

        input {
            width: 90%;
            padding: 10px;
            margin: 10px 0;
            border-radius: 5px;
            border: 1px solid #ccc;
            font-size: 14px;
        }

        button {
            width: 95%;
            padding: 10px;
            margin-top: 15px;
            background-color: #0056b3;
            color: white;
            border: none;
            border-radius: 5px;
            font-size: 16px;
            cursor: pointer;
        }

        button:hover {
            background-color: #003f87;
        }
    </style>
</head>
<body>

    <div class="login-box">

        <!-- KPR College Logo (Direct URL) -->
        <img src="https://kprcas.ac.in/file/wp-content/uploads/2022/01/Logo.png" alt="KPR College Logo">

        <h2>Student Login</h2>

        <input type="text" placeholder="Username">
        <input type="password" placeholder="Password">

        <button>Login</button>

    </div>

</body>
</html>

