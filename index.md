
<html>
<head>
<title>Page Title</title>
<style>
body {
  background-color: pink;
  text-align: center;
  color: white;
  font-family: Arial, Helvetica, sans-serif;
}

</style>
</head>
<body onload="time()">


<p id="showbox" ></p>
<script>
  function time(){
  var NowDate=new Date();
  var y = NowDate.getFullYear();
  var months ="01,02,03,04,05,06,07,08,09,10,11,12".split(",");
  var mm = months[NowDate.getMonth()];
  var d = NowDate.getDate();
  var h=NowDate.getHours() ;
  var m=NowDate.getMinutes();
  var s=NowDate.getSeconds();
  document.getElementById ('showbox') .innerHTML = y+"/"+mm+"/"+d+" "+h+":"+m+":"+s;
  setTimeout('time()',1);
  console.log(mm);
  }
  </script>
<h1 style=" color: white;
text-shadow: 2px 2px 4px #000000;"> This is  Ni Hsuan's homepage !</h1>
<!This is a paragraph.</!>
<p>National Tsing Hua University, Education</p>
<! src="avatar.png" alt="Avatar" style="width:200px">
<img class="_11kf img" alt="蔡妮軒的大頭貼照" src="https://scontent-hkg3-1.xx.fbcdn.net/v/t1.0-1/p320x320/78393574_1929601043853114_2695290676312014848_o.jpg?_nc_cat=106&amp;_nc_ohc=kDBoDvdzSUgAQn2PBaJzfRZyMd0zoZnz1ZJvCwLO_F3N_GoLy_GxCYbsg&amp;_nc_ht=scontent-hkg3-1.xx&amp;_nc_tp=1&amp;oh=570cdee421c9ec4bd011ddb0eaba1548&amp;oe=5E980F24">

<div class="subheading mb-3">
        <ul class="fa-ul">
          <li><i class="fa-li fas fa-user"></i>Hi, I'm Ni Hsuan Tsai, a girl from New Taipei City.<br>
          Aside from my study, in my freetime, I love dancing and drawing.<br> </li>
          
          <li><i class="fa-li fas fa-laptop"></i>If you have more questions about me, please contact me.
          </li>
          <li><i class="fa-li fas fa-envelope"></i> <a href="ya10007170550@gmail.com" title="click here for my e-mail"> click here for my e-mail</a></li>
        </ul>
      </div>
      
      
<p style="color:slateblue;"> Maybe these links can make you know more about me ~ </p>


<div class="subheading mb-3">
        <ol class="fa-ul">
          <li><i class="fa-li fas fa-user"></i><a href="https://hackmd.io/@nihhhsuan">https://hackmd.io/@nihhhsuan</a></li>
          <li><i class="fa-li fas fa-laptop"></i><a href="https://github.com/ni-hsuan">https://github.com/ni-hsuan</a>
          </li>
          
        </ol>
      </div>



</body>
</html>
