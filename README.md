# Fb-Interface-1-with-HTML-CSS
FB Loading interface
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.2.1/css/all.min.css" integrity="sha512-MV7K8+y+gLIBoVD59lQIYicR65iaqukzvf/nwasF0nqhPay5w/9lJmVM2hMDcnK1OnMGCdVK+iQrJ7lzPJQd1w==" crossorigin="anonymous" referrerpolicy="no-referrer" />
<link rel="stylesheet" href="f.css">
    <title>Facebook</title>
</head>
<body>
    <div class="fb">
        <i class="fa-brands fa-facebook-f"></i>
        <div class="loading">
            <span></span>
            <span></span>
            <span></span>
            <span></span>
        </div> 
<div class="f">
    <h3>From</h3>
</div>
        <div class="i">
            <i class="fa-brands fa-meta"></i>
        </div>
        <div class="m">
            <h2>Meta</h2>
        </div>
    </div>
</body>
</html>

<!--CSS FILE-->
.fb{
    text-align: center;
}
.fb i{
    color: rgb(4, 154, 247);
    font-size: 50px;
    margin-top: 30px;
    border-radius: 50%;
    margin-left: -40px;
}
.loading span{
    width: 10px;
    height: 10px;
    margin: 0 15px;
    background-color: rgba(4, 154, 247);
    border-radius: 50%;
    display: inline-block;
    animation-name: dots;
    animation-duration: 2s;
    animation-iteration-count: infinite;
    animation-timing-function: step-end;
}
.loading span:nth-child(2){
    background-color: white;
    animation-delay: 0.4s;
}
.loading span:nth-child(3){
    background-color: rgba(4, 154, 247);
    animation-delay: 0.6s;
}
.loading span:nth-child(4){
    background-color: white;
    animation-delay: 0.8s;
}
@keyframes dots{
    50%{
        opacity: 0;
        transform: scale(0.7) translateY(10px);
    }
}
.f h3{
    color: rgb(125, 125, 125);
    margin-top: 600px;
    justify-content: center;
}
.i i{
    margin-top: -50px;
    font-size: 25px;
    margin-left: -70px;
}
.m h2{
    font-size: 25px;
    margin-left: 50px;
    margin-top: -30px;
    color: rgb(125, 125, 125);
}
