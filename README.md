

1. Fork此仓库  

2. 获取GLaDOS的cookie  
   
    有些浏览器可能显示的英文，但都大差不差，若图片未显示，则需要使用魔法或者解决DNS污染  
    
    ![获取cookie.png](./GLaDOS/images/获取cookie.png)  

3. 将cookie填入`Settings` -> `Secrets and variables` -> `Actions` -> `Repository secrets`中，命名一定要是`GLADOS_COOKIE`  
   
    ![配置cookie.png](./GLaDOS/images/配置cookie.png)  

## 4. 配置微信推送(非必须)

可以不配置，可以只配置其中一个，也可以都配置  

### 4.1 Server酱

和配置cookie一样的方式，将Server酱中的SendKey复制到`Repository secrets`命名为 `SENDKEY`  
[Server酱](https://sct.ftqq.com/)  
暂时只支持`方糖服务号`进行推送(因为懒)  
若此通道被弃用，那到时候再说吧  

### 4.2 pushPlus

和配置cookie一样的方式，将pushpuls微信公众号中的token复制到`Repository secrets`命名为 `TOKEN`  
[pushPlus](https://www.pushplus.plus/)  

## 其它  
如果需要更新代码，可以重新Fork此仓库  
或者在电脑中安装 [Git软件](https://git-scm.com/) ，然后运行脚本`Pull_From_Origin.bat`一键更新  

最后，求个小小的star  
QWQ  
