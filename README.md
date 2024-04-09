<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Our Team</title>
    <style>
        /* Your CSS styles here */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }

        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
        }

        .row {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
        }

        .box {
            width: calc(20% - 20px);
            margin-bottom: 20px;
            background-color: #f0f0f0;
            padding: 20px;
            box-sizing: border-box;
        }

        @media screen and (max-width: 768px) {
            .box {
                width: calc(40% - 20px);
            }
        }

        @media screen and (max-width: 480px) {
            .box {
                width: calc(100% - 20px);
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Our Team</h1>
        <div class="row">
            <div class="box">
                <h2>John Doe</h2>
                <p>Position: CEO</p>
                <p>Description: Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
            </div>
            <div class="box">
                <h2>Jane Smith</h2>
                <p>Position: CTO</p>
                <p>Description: Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
            </div>
            <div class="box">
                <h2>Michael Johnson</h2>
                <p>Position: COO</p>
                <p>Description: Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
            </div>
            <div class="box">
                <h2>Emily Davis</h2>
                <p>Position: CFO</p>
                <p>Description: Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.</p>
            </div>
            <div class="box">
                <h2>David Wilson</h2>
                <p>Position: CMO</p>
                <p>Description: Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
            </div>
        </div>
    </div>
</body>
</html>
