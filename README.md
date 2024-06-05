
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mark up Sports Tools</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-image: url('bg.jpg');
            background-size: cover;
            background-position: center;
            color: white;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }
        .container {
            max-width: 400px;
            padding: 40px;
            border: 2px solid navy;
            border-radius: 10px;
            background-color: rgba(36, 35, 35, 0.8);
            text-align: top;
        }
        h1 {
            margin-top: 0;
        }
        input[type="submit"], button {
            background-color: dodgerblue;
            color: rgb(249, 249, 252);
            padding: 14px 20px;
            margin: 8px 0;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            width: 100%;
            font-size: 16px;
        }
        input[type="submit"]:hover, button:hover {
            background-color: royalblue;
        }
       
        .link {
            color: white;
            text-decoration: none;
            margin-top: 10px;
        }
        .link:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Markup Sports Tools</h1>
        <form id="catalogForm">
            <button type="button" onclick="location.href='index.html'">Register</button>
        </form>
        <p>Already have an account? <a href="login.html" class="link">Log in here</a></p>
    </div>
</body>
</html>
