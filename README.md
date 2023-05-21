
<!doctype html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport"
          content="width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Document</title>

    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }

        #onepic {
            position: relative;
            max-width: 100%;
            max-height: 100%;
        }

        #onepic img {
            display: block;
            max-width: 100%;
            max-height: 100%;
            object-fit: contain;
        }

        #onepic .text-overlay {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            text-align: center;
        }

        svg {
            display: block;
            width: 100%;
            height: auto;
        }
    </style>
</head>
<body>

<div id="onepic">
    <img src="../pics/clouds.jpg">
    <div class="text-overlay">
        <svg viewBox="0 0 400 200">
            <defs>
                <path id="curve" d="M10 100 Q200 190 390 100"/>
            </defs>
            <text font-size="30" font-family="Marker Felt, fantasy" fill="white">
                <textPath href="#curve">
                    Hi, I'm Jim, welcome to my Github
                </textPath>
            </text>
        </svg>
    </div>
</div>


</body>
</html>

<img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>

<!--
**Jimolson-git/Jimolson-git** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
