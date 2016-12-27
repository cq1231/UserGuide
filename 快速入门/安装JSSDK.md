### 申请试用   
####仅需3步，即可拥有自己的精益数据分析平台
1.进入www.shujike.com,点击右上方的免费试用  
2.请输入您的手机号码以及账号信息  
3.注册成功后登录您的账号即可开始使用
  
  
###安装JS采集API  
进入 应用后台->平台管理->添加应用,选择需要安装API的网站
![](http://www.shujike.com/images/buzhou.jpg)  
复制以下代码：  
    
    
        <script>
            var _dgt = _dgt || [];
                (function () {
                    _dgt.push(['setSiteId', '替换成您的网站ID']);
                    var d = document, g = d.createElement('script'), s = d.getElementsByTagName('script')[0];
                    g.type = 'text/javascript'; g.async = true; g.defer = true;
                    g.src = ('https:' == document.location.protocol ? 'https://' : 'http://') + 'shujike.cn/dgt.js';
                    s.parentNode.insertBefore(g, s);
                })();
        </script>    
1、将以上代码COPY到您网站的        <head>      与       </head>      之间即可  
2、为了采集全量数据,建议您将此代码放到类似于header.tpl,这种全站的页头模板当中  
  以上代码是异步加载,不会影响您的网站打开速度,您也可以放到网站的        </body>     之前  
    
