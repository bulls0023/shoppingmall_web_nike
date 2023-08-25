# shoppingmall_web_nike
간단하게 만들어본 나이키 홈페이지 js 요소 추가할 게 많음

<!DOCTYPE html>
<html>
<head>
    <meta charset='utf-8'>
    <title>NIKE.UNOFFICIAL</title>
    <link href = "style.css" rel ="stylesheet">
</head>
<body>
    <div class = "navbar">
        <a class = "logo" href = "#">
            <p>JUST DO IT</p>
        </a>
        <ul>
            <li><a href = "#">Contract</a></li>
            <li><a href = "#">Shop</a></li>
            <li><a href = "#">Cart</a></li>
            <li><a href = "#">Login</a></li>
        </ul>
    </div>

    <img class = "hero_header" src = "logo_pic.png">
    <h1>Our new Products</h1>
    <hr>
    <div class = "products">
        <table>
        <tr>
            <td>
                 <a href = "#">
                <img src = "product01.png" alt = "나이키 덩크 로우 레트로">
                 <p>나이키 덩크 로우 레트로</p>
                 <p class = "price">59,000</p>
                </a>
            </td>
            <td>   
                 <a href = "#">
                 <img src = "product02.png">
                 <p>상품이름</p>
                 <p class = "price">59,000</p>
                 </a>
            </td> 
            <td>
                 <a href = "#">
                 <img src = "product03.png">
                 <p>상품이름</p>
                 <p class = "price">79,000</p>
                 </a>
            </td>  
        </tr>
        </table>
        <table>
        <tr>
            <td>
                <a href = "#">
                <img src = "product04.png">
                <p>상품이름</p>
                <p class = "price">69,000</p>
                </a>
            </td>
            <td>
                <a href = "#">
                <img src = "product05.png">
                <p>상품이름</p>
                <p class = "price">79,000</p>
                </a>
            </td>
            <td>    
                <a href = "#">
                <img src = "product06.png">
                <p>상품이름</p>
                <p class = "price">59,000</p>
                </a>
            </td>    
        </tr>
        </table>
        <table>
            <td>
                <a href = "#">
                <img src = "product07.png">
                <p>상품이름</p>
                <p class = "price">89,000</p>
                </a>
            </td>
            <td>
                <a href = "#">
                <img src = "product08.png">
                <p>상품이름</p>
                <p class = "price">89,000</p>
                </a>
            </td>
            <td>
                <a href = "#">
                <img src = "product09.png">
                <p>상품이름</p>
                <p class = "price">99,000</p>
                </a>
            </td>
            </tr>
        </table>    
        <div class = "clearfix"> </div>
    </div>
    
    <div class = "footer">
        <a href = "#"><img src = "로고"></a>
        <a href = "#"><img src = "로고"></a>
        <a href = "#"><img src = "로고"></a>
        <a href = "#"><img src = "로고"></a>
        <a href = "#"><img src = "로고"></a>
    </div>
</body>
</html>


body{
    margin: 0;
    min-width: 900px;
    
}
.navbar{
    height: 60px;
    padding-left: 30px;
}
.logo{
    
    line-height: 50px;
    float: left;
    font-size: 10px;
    font-style: oblique;
    font-weight: bolder;
}
.logo img{
    vertical-align: middle;
}
.navbar ul{
    float: right;
}
.navbar li{
    list-style-type: none;
    float: left;
    margin-right: 30px;
}
.navbar a{
    text-decoration: none;
    color : black;
    font-style : bold;
    font-size: 13px;
}
.hero_header{
    
    height: 500px;
    width: 100%;
    display: block;
    border: 3px solid black;
}
body h1{
    text-align: center;
    margin-top: 70px;
    margin-bottom: 24xp;
    font-size: 24px;
    font-style: bold;
    color :#131313;
   
}

.products{
    margin-left: auto;
    margin-right: auto;
    padding: 0;
    width: 740px;
    text-align: center;
}
.products img{
    width: 225px;
    height: 225px;
    margin-left: 20px;
    margin-right: 20px;
}
.price{
    margin-top: 4px;
    margin-bottom: 4px;
}
.clearfix{
    clear: both;
}
.footer{
    text-align: center;
}
.footer img{
    margin-top: 40px;
    height: 20px; 
    margin-bottom: 80px;
    margin-left: 10px;
    margin-right: 10px;
}
