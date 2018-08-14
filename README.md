# html-include-html
html静态页面导入公共静态模块

### 第一种：（弊端：引入的页面相关操作执行不了）
          1、页面引入include.js文件
          2、页面用include标签包含模板文件；例如：<include src="template.html"></include>
          
### 第二种
    <div id="page1"></div>
    <div id="page2"></div>
    <script>
          $("#page1").load("page/Page_1.html");
          $("#page2").load("page/Page_2.html");
    </script>
