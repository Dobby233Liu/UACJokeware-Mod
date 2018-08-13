Original program by "Fifcom System Incorporated."
Edit by "Dobby233Liu"

1.文件说明

      uac.exe 改进后的启动程序
      FEC.exe 来自FIFCOM的AES加解密程序
      FIFCOM.ENCRYPT.FEC 即荒野行动稳定透视.exe.bak，不过这个是用 PowerOS 加密过的
      荒野行动稳定透视.exe.bak 请求权限的程序
      uac_src.bat 修改后的代码
      README.txt 自述文件，本文档
      demo.mp4 修改版示例

2.修改

    1.重写可执行程序，使文件不报毒（http://r.virscan.org/language/zh-cn/report/e7ce838f00a1b4890206cf413c287e0e（瑞星误报Malware.Undefined，即未知的恶意软件），https://habo.qq.com/file/showdetail?pk=AD0Gb11sB2YIPls6，而且个人不使用一键转换工具，而是用了VS2017写，但FEC.exe不变）
    2.修改bat，与exe配合
    3.EDIT:无自解压程序，因为自解压程序会弹弹窗
    4.在重写的时候保留了原来的版本信息
    5.找不到“再见，令人讨厌的%username%！.exe”的信息在我的电脑上无法显示，我也改了一下，让它出错

3.需求

     1..NET Framework 4.5 x86（从4.0更新），https://www.microsoft.com/en-us/download/details.aspx?id=30653（或4.0，https://www.microsoft.com/zh-cn/download/details.aspx?id=17718）
     2.非xp的windows系统

4.原版示例

       av25994047