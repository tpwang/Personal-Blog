#### 欢迎来到`王铁鹏`[的个人主页]()        ![图标](https://avatars3.githubusercontent.com/u/8352496?v=3&s=460 "图标")

###### [wangtiepeng@21cn.com](EMAIL). 
###### 
<html>
<tr>Lession One </tr>
<td> 这是我的第一篇文章，不知道写些什么，祝大家能够开心工作，每天都有新的收获。</td>

<body>
<p id="demo">点击这个按钮，获得您的坐标：</p>
<button onclick="getLocation()">试一下</button>
<script>
var x=document.getElementById("demo");
function getLocation()
  {
  if (navigator.geolocation)
    {
    navigator.geolocation.getCurrentPosition(showPosition);
    }
  else{x.innerHTML="Geolocation is not supported by this browser.";}
  }
function showPosition(position)
  {
  x.innerHTML="Latitude: " + position.coords.latitude + 
  "<br />Longitude: " + position.coords.longitude;	
  }
</script>
</body>






</html>
