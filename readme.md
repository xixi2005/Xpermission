# Xpermission
基于laravel 5.4，vue.js 2.0的单网页权限管理系统！
## 使用
### 前端
adminLTE-spa(https://github.com/xixi2005/adminLTE-spa)
### 后端
laravel 5.4
## 状态码规范

状态码描述<br>
-1	    返回失败（默认）<br>
200	    返回成功（默认）<br>

400段：授权控制器 <br>
40001段：/login <br>
400011:登录失败：参数有误！ <br>
400012:登录失败：用户名或密码错误，请重试！<br>
400013:登录失败：认证失败! <br>
400014:登录失败:你登陆失败的次数太多，请在 60 秒后再次尝试登录<br>
400015:登录失败:xxxx <br>
