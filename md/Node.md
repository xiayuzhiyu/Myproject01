# 背景延伸
```
<style>
        * {
            padding: 0;
            margin: 0;
            box-sizing: border-box;
        }

        body {
            display: flex;
            justify-content: center;
            align-items: center;
        }

        .box {
            position: relative;
            display: flex;
            justify-content: space-between;
            width: 1208px;
            border: 1px solid #000;
        }

        .box-left,
        .box-right {
            width: 500px;
            height: 600px;
            border: 1px solid yellow;
        }

        .bg {
            position: absolute;
            left: 0;
            width: 100%;
            height: 100%;
            display: flex;
            justify-content: center;
            z-index: -1;
        }

        .bg>div {
            width: 100vw;
            height: 100%;
            background: linear-gradient(90deg, red, orange, yellow, green, blue, indigo, violet, red);
            flex-shrink: 0;
            opacity: .3;
        }
    </style>
</head>

<body>
    <div class="box">
        <div class="box-left"></div>
        <div class="box-right"></div>
        <div class="bg">
            <div></div>
        </div>
    </div>

</body>
```