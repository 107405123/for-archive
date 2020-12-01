# for-archive
for archive 
/*粉色圓形變藍色正方形*/

<html>

<head>
    <style>
        .circle {
            width: 800px;
            height: 800px;
            background-color: pink;
            border-radius: 800px;
            margin-top: 500px;
            margin-left: 1000px;
            animation-name: circle-change;
            animation-duration: 5s;
            animation-iteration-count: infinite;
            animation-direction: alternate;
        }



        @keyframes circle-change {
            from {
                background-color: pink;
                margin-top: 500px;
                margin-left: 1000px;
            }

            to {
                background-color: lightblue;
                border-radius: 0px;
                margin-top: 150px;
                margin-left: 150px;
                width: 150px;
                height: 150px;
            }
        }
    </style>
</head>

<body>
    <div class="circle"></div>

</body>

</html>
