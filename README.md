<html>
<head>
<style>
 #star-five {
      margin: 50px 0;
      position: relative;
      display: block;
      color: red;
      width: 0px;
      height: 0px;
      border-right: 100px solid transparent;
      border-bottom: 70px solid #DDCC11;
      border-left: 100px solid transparent;
      transform: rotate(35deg);
    }
    #star-five:before {
      border-bottom: 80px solid #DDCC11;
      border-left: 30px solid transparent;
      border-right: 30px solid transparent;
      position: absolute;
      height: 0;
      width: 0;
      top: -45px;
      left: -65px;
      display: block;
      content: '';
      transform: rotate(-35deg);
    }
    #star-five:after {
      position: absolute;
      display: block;
      color: red;
      top: 3px;
      left: -105px;
      width: 0px;
      height: 0px;
      border-right: 100px solid transparent;
      border-bottom: 70px solid #DDCC11;
      border-left: 100px solid transparent;
      transform: rotate(-70deg);
      content: '';
    }
#div0
{
position:relative;
left:200px;
}
#div1
{
background-color:blue;
width:250px;
height:150px;
position:absolute;
left:50px;
top:100px;
z-index:2
}
#div2
{
background-color:green;
width:250px;
height:150px;
margin:50px 0px 0px 50px;
z-index:1
}
#div3
{
position:absolute;
left:300px;
top:400px;
transform

}
</style>
</head>
<body>
<h1>Title</h1>
<div id=div0>
<div id=div1></div>
<div id=div2></div>
</div>
<div id=div3>
<div id=star-five></div>
</div>
