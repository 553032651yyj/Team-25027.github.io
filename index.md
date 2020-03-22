<!DOCTYPE html> 
<html xmlns="http://www.w3.org/1999/xhtml"> 
<head> 
<meta http-equiv="Content-Type" content="text/html; charset=utf-8" /> 
<title>点击删除按钮后 弹窗确认删除对话框 在线演示 www.divcss5.com </title> 
</head> 
 
<body> 
<p> 
  <script language="javascript"> 
    function delcfm() { 
        if (!confirm("确认要删除？")) { 
            window.event.returnValue = false; 
        } 
    } 
</script><form action="del.html" target="_blank" method="get"> 
<input name="" type="submit" value="删除" onClick="delcfm()" /></form> 
</p> 
</body> 
</html> 
