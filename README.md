<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@100..900&display=swap" rel="stylesheet">
    <style>
        p {
            margin-bottom: 0px;
        }
        body {
            padding: 0;
            margin: 0;
            /* background-color: rgb(255, 255, 255); */
            background-color: hsl(0, 0%, 8%);
        }
        .cotainer {
            justify-content: center;
            display: flex;
            margin: 10% auto auto auto;
        }
        .j2 {
            width: 400px;
            height: 700px;
            display: flex;
            background-color: hsl(0, 0%, 12%);
            justify-content: center;
            vertical-align: text-bottom;
            border: none;
            border-radius: 20px;
            box-shadow: 10 10 10 10 white;                   
        }
        img {
            width: 100px;
            height: 100px;
            border-radius: 100px;
            margin-top: 18%;
        }
        .p_name {
            font-family: Inter;
            font-size: 30px;
            font-weight: 700;
            color: white;
            display: flex;
            justify-content: center;
        }
        .p_container {
            display: flex;
            flex-direction: column;
        }
        .btn {
            margin-bottom: 15px;
            padding: 15px 90px;
            border: none;
            border-radius: 9px;
            background-color: hsl(0, 0%, 20%);
            color: white;
            font-weight: 600;
            font-family: Inter;
            cursor: pointer;
        }
        .btn:hover {
            background-color: rgba(166, 223, 33, 0.95);
        }
        .btn:active {
            background-color: rgba(166, 223, 33, 0.95);
        }
    </style>
</head>
<body>
    <div class="cotainer">
    <div class="j2">
        <div class="p_container">
            <div style="justify-content:center;display:flex;"><img src="challenges_/avatar-jessica.jpeg"></div>
        <div style="display: flex; justify-content: center;">
            <div style="display: flex; justify-content: center; flex-direction: column;">
                <p class="p_name">Jessica Randall</p>
                <p class="Address"  style="color:  rgba(166, 223, 33, 0.95); vertical-align: middle; display: flex; justify-content: center; margin-bottom: 20px;font-family: Inter; font-weight: 600; font-size: 14px;">London, United Kingdom</p>
                <p style="color: white; vertical-align: middle; display: flex; justify-content: center; margin-bottom: 40px; font-size: 14px; font-weight: 400; font-family: Inter;">"Front-end developer and avid reader"</p>
                <div style="display: flex; flex-direction: column; justify-content: space-between;">
                    <button class="btn">GitHub</button>
                    <button class="btn">Frontend Mentor</button>
                    <button class="btn">Linkedin</button>
                    <button class="btn">Twitter</button>
                    <button class="btn">Instagram</button>
                </div>
            </div>
        </div>
        
    </div>
    </div>
</div>
</body>
</html>
