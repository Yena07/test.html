<html>
    <head>
        <style>
            body{
                margin: 0;
            }
            .top{
                z-index: 1000;
                top: 0;
                width: 100%;
                position: fixed;
                background-color: black;
                height: 10%;
            }
            .left{
                left: 0;
                height: 100%;
                position: fixed;
                background-color: orange;
                width: 20%;
                padding-top: 5%;
            }
            .right{
                right: 0;
                height: 100%;
                position: fixed;
                background-color: red;
                width: 20%;
                padding-top: 5%;
            }
            .middle{
                margin-left: 20%;
                margin-right: 20%;
                background-color: green;
                height: 100%;
            }
            ul {
                padding: 0;
            }
            ul > li {
                border-bottom: 5px solid red;
                color: white;
                padding: 10px;
            }
            li a{
                display: block;
                text-decoration: none;
                color : white;
            }
            .subList{
                list-style-type: circle;
                padding-left: 40px;
            }
            .subList > li{
                border-bottom: 0;

            }
        </style>
    </head>
    <body>
        <div class="top">
            <p>top</p>
        </div>
        <div class="left">
            <ul>
                <li>강좌
                    <ul class="subList">
                        <li><a href="">시간표</a></li>
                    </ul>
                </li>
                <li>포털
                    <ul class="subList">
                        <li><a href="#">출결조회</a></li>
                        <li><a href="#">봉사근로일지</a></li>
                    </ul>
                </li>
                <li>행긱
                    <ul class="subList">
                        <li><a href="">식단표</a></li>
                        <li><a href="#">외출외박신청</a></li>
                    </ul>
                </li>
                <li>그외
                    <ul class="subList">
                        <li><a href="#">컴퓨터공학부 사이트</a></li>
                        <li><a href="#">cando</a></li>
                    </ul>
                </li>
            </ul>
        </div>
        <div class="right">
            <p>right</p>
        </div>
        <div class="middle">
            <p>middle</p>
        </div>
    </body>
</html>
