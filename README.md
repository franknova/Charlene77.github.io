# Charlene77.github.io
<html>
    <head>
        <title>TODO supply a title</title>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <link href="css/mycss.css" rel="stylesheet" type="text/css"/>
    </head>
    <body>
        <form action="">
            <table border="0" align="center" width="600">
                <tr> <td colspan="3" align="center" height="40" class="#ffff00"> 填写注册信息</td></tr>
                <tr> <td align="right">用户名:*</td>
                    <td><input type="text" name="userName"/></td>
                    <td class="#ffff00">用户名由字母开头，后跟字母、数字或下划线！</td>
                </tr>
                <tr> <td align="right" class="#ffff00">密码:*</td>
                    <td><input type="password" name="userPwd"/></td>
                    <td class="#ffff00">设置登录密码，至少6位！</td>
                </tr>
                <tr> <td align="right" class="#ffff00">确认密码:*</td>
                    <td><input type="password" name="userPwd1"/></td>
                    <td class="#ffff00">请再输入一次你的密码！</td>
                </tr>
                <tr> <td align="right">性别:*</td>
                    <td><input type="radio" name="userSex" value="男" checked/>男
                        <input type="radio" name="userSex" value="女"/>女</td>
                    <td>请选择你的性别！</td>
                </tr>
                <tr> <td align="right">邮箱地址:*</td>
                    <td><input type="text" name="userEmail" /></td>
                    <td>请填写您的常用邮箱，可以用此邮箱找回密码！</td>
                </tr>
                <tr> <td align="right" valign="top">基本情况:*</td>
                    <td colspan="2">
                        <textarea name="userBasicInfo" rows="5" cols="50"></textarea></td>
                </tr>
                <tr> <td colspan="3" align="center" height="40">
                        <input type="checkbox" name="accept" value="yes"/>
                        我已经仔细阅读并同意接受用户使用协议</td>
                </tr>
                <tr><td colspan="3" align="center" height="40">
                        <input type="submit" value="确认"/>&nbsp;
                        <input type="reset" value="取消"/>
                    </td>
                </tr>
            </table> 
        </form>
    </body>
</html>
