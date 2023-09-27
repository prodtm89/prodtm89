- 👋 Hi, I’m @prodtm89
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
prodtm89/prodtm89 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>iPhone Screen</title>
    <style>
        /* iPhone frame */
        .iphone {
            width: 375px; /* Adjust the width as needed */
            height: 667px; /* Adjust the height as needed */
            background-color: #000;
            border: 5px solid #333;
            border-radius: 20px;
            margin: 50px auto;
            overflow: hidden;
            position: relative;
        }
        
        /* iPhone screen */
        .screen {
            width: 100%;
            height: 100%;
            background-color: #fff; /* You can change this color to represent your screen content */
        }
        
        /* Home button */
        .home-button {
            width: 40px;
            height: 40px;
            background-color: #333;
            border-radius: 50%;
            position: absolute;
            bottom: 20px;
            left: calc(50% - 20px);
        }
    </style>
</head>
<body>
    <div class="iphone">
        <div class="screen">
            <!-- Your screen content goes here -->
        </div>
        <div class="home-button"></div>
    </div>
</body>
</html>
