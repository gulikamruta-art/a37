<!DOCTYPE html>
<html>
<head>
    <title>Box Shadow Example</title>
    <style>
        .box {
            width: 300px;
            height: 150px;
            background-color: lightblue;
            position: relative;
            box-shadow: 5px 5px 15px gray;
            animation: moveBox 3s infinite alternate;
        }

@keyframes moveBox {
            from {
                left: 0px;
            }
            to {
                left: 300px;
            }
        }
    </style>
</head>

<body>
    <div class="box">
        This box has shadow
    </div>
</body>
</html>
