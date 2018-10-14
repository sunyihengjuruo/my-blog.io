# my-blog.io
<script>
   function check(){
      var name=document.getElementById("name").value;
   var pass=document.getElementById("pass").value;
   if(name=="cdssxxx" && pass=="2372535103"){
   alert("登入成功");
   window.document.f.action="file:///C:/Users/Administrator/Desktop/BLOG.HTM";
   window.document.f.submit();
   }else{
   alert("用户名或密码错误");
   
   }
   
   }
</script>

<form name="f" action="">
<center>用户名:<INPUT TYPE="text" NAME="" id="name"><br></center>
<center>密码:<INPUT TYPE="password" NAME="" id="pass"><br></center>
<center><INPUT TYPE="button" value="登入" onclick="check()"><INPUT TYPE="reset" value="重置"></center>
</form> 
