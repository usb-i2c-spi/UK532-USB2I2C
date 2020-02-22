│  README.txt				//使用说明，文件目录
│  USB2XXX_Mamu使用说明.pdf	//USB2I2C_DEMO、USB2ISP_DEMO、USB2SPI_DEMO使用说明
|							//使用前请先阅读！
│  USBIOSALE.pdf			//电子订货单
├─USB2I2C_20090430			//USB2I2C开发包，更新日期：2009.04.30
│  │  USB2I2C_V3.1D_20090430.pdf	//USB2I2C数据手册
│  │  
│  ├─USB2I2C_DEMO					//USB2I2C上位机测试程序及源代码
│  │  │  TABCTL32.OCX
│  │  │  USB2I2C_DEMO_VBCN.exe		//USB2I2C上位机VB测试程序
│  │  │  USB2I2C_DEMO_VC.exe		//USB2I2C上位机VC测试程序
│  │  │  USB2I2C_DEMO使用说明.pdf	//USB2I2C_DEMO使用说明
│  │  │  USBIOX.DLL					//USB2I2C驱动动态链接库
│  │  │  
│  │  └─Resource					//USB2I2C上位机测试程序及源代码
│  │      ├─BCB_Projects			//USB2I2C上位机BCB源代码
│  │      │  │  Project1.bpr
│  │      │  │  Project1.cpp
│  │      │  │  Project1.exe
│  │      │  │  Project1.obj
│  │      │  │  Project1.res
│  │      │  │  Project1.tds
│  │      │  │  Unit1.cpp
│  │      │  │  Unit1.ddp
│  │      │  │  Unit1.dfm
│  │      │  │  Unit1.h
│  │      │  │  Unit1.obj
│  │      │  │  Unit2.obj
│  │      │  │  Unit3.obj
│  │      │  │  USBIOX.DEF
│  │      │  │  USBIOX.DLL
│  │      │  │  USBIOX.LIB
│  │      │  │  
│  │      │  ├─Bpl
│  │      │  └─Lib
│  │      ├─C_Project				//USB2I2C上位机C源代码
│  │      │  └─SPEED_I2C
│  │      │          MAKEFILE
│  │      │          SPEED_I2C.C
│  │      │          
│  │      ├─Labview_Project			//USB2I2C上位机Labview源代码
│  │      │  ├─LabviewUSB2I2C_StreamI2C
│  │      │  │      CloseDevice.vi
│  │      │  │      OPEND.vi
│  │      │  │      OpenDevice.vi
│  │      │  │      USBIOX.DLL
│  │      │  │      USBIOX.H
│  │      │  │      USBIO_StreamI2C.vi
│  │      │  │      
│  │      │  └─LabviewUSBI2CProject
│  │      │          BytesToValue.vi
│  │      │          CheckSensor.vi
│  │      │          CloseDevice.vi
│  │      │          DataWithoutSame.vi
│  │      │          DataWithSame.vi
│  │      │          DemoI2CStream.vi
│  │      │          EnablePorts.vi
│  │      │          EnablePorts2.vi
│  │      │          Find Devieces.vi
│  │      │          LVmeasure.vi
│  │      │          OneSensor.vi
│  │      │          OPEND.vi
│  │      │          OpenDevice.vi
│  │      │          ReadDataFromSensor.vi
│  │      │          ReadSensorStats.vi
│  │      │          USBI2C VI TREE.vi
│  │      │          USBIOX.DLL
│  │      │          USBIOX.H
│  │      │          USBIO_StreamI2C.vi
│  │      │          多条曲线.vi
│  │      │          多条曲线2.vi
│  │      │          或.vi
│  │      │          文档.txt
│  │      │          
│  │      ├─Linux_Pro					//USB2I2C上位机Linux源代码
│  │      │      usb2spi_test.c
│  │      │      USBIOX.c
│  │      │      USBIOX.h
│  │      │      
│  │      ├─VB_Project					//USB2I2C上位机VB源代码
│  │      │  ├─USB2I2C_DEMO_VBCN
│  │      │  │      CHIP4.ico
│  │      │  │      frmMain.frm
│  │      │  │      frmMain.frx
│  │      │  │      frmMain.log
│  │      │  │      Module1.bas
│  │      │  │      MSSCCPRJ.SCC
│  │      │  │      TABCTL32.OCX
│  │      │  │      USB2I2C.VBP
│  │      │  │      USB2I2C.vbw
│  │      │  │      USB2I2C_DEMO_VBCN.exe
│  │      │  │      USBIOX.DLL
│  │      │  │      USBIOX.INF
│  │      │  │      USBIOX.SYS
│  │      │  │      USBIOXDLL.bas
│  │      │  │      
│  │      │  └─USB2I2C_DEMO_VBEN
│  │      │          CHIP4.ico
│  │      │          frmMain.frm
│  │      │          frmMain.frx
│  │      │          frmMain.log
│  │      │          Module1.bas
│  │      │          MSSCCPRJ.SCC
│  │      │          TABCTL32.OCX
│  │      │          USB2I2C.VBP
│  │      │          USB2I2C.vbw
│  │      │          USB2I2C_DEMO_VBEN.exe
│  │      │          USBIOX.DLL
│  │      │          USBIOX.INF
│  │      │          USBIOX.SYS
│  │      │          USBIOXDLL.bas
│  │      │          
│  │      └─VC_Project						//USB2I2C上位机VC源代码
│  │          └─USB2I2C_DEMO_VC
│  │              │  CtrlSheet.cpp
│  │              │  CtrlSheet.h
│  │              │  EeprPage.cpp
│  │              │  EeprPage.h
│  │              │  EppPage.cpp
│  │              │  EppPage.h
│  │              │  I2CSPage.cpp
│  │              │  I2CSPage.h
│  │              │  LEDBTDisp.cpp
│  │              │  LEDBTDisp.h
│  │              │  MemPage.cpp
│  │              │  MemPage.h
│  │              │  OtherPage.cpp
│  │              │  OtherPage.h
│  │              │  resource.h
│  │              │  StdAfx.cpp
│  │              │  StdAfx.h
│  │              │  Total.h
│  │              │  USB2I2C.APS
│  │              │  USB2I2C.CPP
│  │              │  USB2I2C.dsp
│  │              │  USB2I2C.dsw
│  │              │  USB2I2C.H
│  │              │  USB2I2C.ncb
│  │              │  USB2I2C.opt
│  │              │  USB2I2C.plg
│  │              │  USB2I2C.rc
│  │              │  USB2I2CDlg.cpp
│  │              │  USB2I2CDlg.h
│  │              │  USB2I2C_DEMO.exe
│  │              │  USBIOX.DLL
│  │              │  USBIOX.H
│  │              │  USBIOX.LIB
│  │              │  
│  │              ├─Debug
│  │              ├─Release
│  │              └─RES
│  │                      USB2I2C.ico
│  │                      USB2I2C.RC2
│  │                      
│  ├─USB2I2C_DRIVER				//USB2I2C驱动文件
│  │  ├─DRIVER					//USB2I2C驱动文件
│  │  │      USBIOX.DLL
│  │  │      USBIOX.INF
│  │  │      USBIOX.SYS
│  │  │      
│  │  ├─LIB_BCB					//USB2I2C驱动BCB库文件
│  │  │      USBIOX.DEF
│  │  │      USBIOX.DLL
│  │  │      USBIOX.LIB
│  │  │      
│  │  ├─LIB_C					//USB2I2C驱动VC++库文件
│  │  │      USBIOX.H			//USB2I2C驱动文件所有API函数的详细说明！重要！
│  │  │      USBIOX.LIB
│  │  │      
│  │  └─USB2XXXLinuxDriver		//USB2I2C Linux驱动
│  │          usb2spi_test.c
│  │          USBIOX.c
│  │          USBIOX.h
│  │          
│  ├─USB2I2C_PUB				//USB2I2C测试程序及源代码
│  │  ├─SPEED_I2C				//USB2I2C测试通信速度程序及源代码
│  │  │      MAKEFILE
│  │  │      SPEED_I2C.C
│  │  │      
│  │  └─USB2I2C_EXAM			//USB2I2C非常规操作（非标准I2C总线通信协议）程序及源代码
│  │          I2C_EXAM.C
│  │          
│  └─USB2I2C_SCH_PCB			//USB2I2C原理图和PCB图（均经过测试验证！可放心使用）
								//（所有产品销售：http://www.usb-i2c-spi.com/cn/mail.htm）
│      ├─OLD					//USB2I2C前期的产品图片
│      │      USB2I2C_DEMO_BOT早期版本.jpg
│      │      USB2I2C_DEMO_TOP1早期版本.jpg
│      │      USB2I2C_DEMO_TOP2早期版本.jpg
│      │      
│      ├─USB2I2C-SIP8			//USB2I2C-SIP8适配器，适合模块设计
│      │      USB2I2C-SIP8.Bkp
│      │      USB2I2C-SIP8.ddb
│      │      USB2I2C-SIP8.pdf
│      │      
│      ├─USB2I2C_DEMO			//USB2I2C适配器，适合模块设计（5V）
│      │      USB2I2C_DEMO.Bkp
│      │      USB2I2C_DEMO.ddb
│      │      USB2I2C_DEMO_SCH_PCB.pdf
│      │      
│      ├─USB2I2C_DEMOS			//USB2I2C适配器，适合模块设计（3.3V和5V）
│      │      USB2I2C_DEMOS.ddb
│      │      USB2I2C_DEMOS_SCH_PCB.pdf
│      │      
│      └─USB2I2C_LIB			//USB2I2C原理图和PCB库文件
│              USB2I2C_LIB.Bkp
│              USB2I2C_LIB.ddb
│              
├─USB2ISP_20090430				//USB2ISP开发包，更新日期：2009.04.30
│  │  USB2ISP_V2D_20090430.pdf	//USB2ISP数据手册
│  │  
│  ├─USB2ISP_DEMO				//USB2ISP上位机测试程序及源代码
│  │  │  TABCTL32.OCX
│  │  │  USB2ISP-Demo使用说明.pdf	//USB2ISP_DEMO使用说明
│  │  │  USB2ISP_DEMO.exe			//USB2ISP上位机VC测试程序
│  │  │  USB2ISP_DEMO_VBCN.exe		//USB2ISP上位机VB测试程序
│  │  │  USBIOX.DLL					//USB2ISP驱动动态链接库
│  │  │  
│  │  └─Resource					//USB2ISP上位机测试程序及源代码
│  │      │  readme.txt				//USB2ISP上位机测试程序及源代码说明
│  │      │  
│  │      ├─VB_Project				//USB2ISP上位机VB源代码
│  │      │  │  CHIP4.ico
│  │      │  │  frmMain.frm
│  │      │  │  frmMain.frx
│  │      │  │  frmMain.log
│  │      │  │  Module1.bas
│  │      │  │  MSSCCPRJ.SCC
│  │      │  │  USB2ISP.csi
│  │      │  │  USB2ISP.VBP
│  │      │  │  USB2ISP.vbw
│  │      │  │  USB2ISP_DEMO_VBCN.exe
│  │      │  │  USBIOX.DLL
│  │      │  │  USBIOX.INF
│  │      │  │  USBIOX.SYS
│  │      │  │  USBIOXDLL.bas
│  │      │  │  
│  │      │  └─USB2ISP.NET
│  │      │      │  AssemblyInfo.vb
│  │      │      │  frmMain.Designer.vb
│  │      │      │  frmMain.resx
│  │      │      │  frmMain.vb
│  │      │      │  Module1.vb
│  │      │      │  USB2ISP.ico
│  │      │      │  USB2ISP.log
│  │      │      │  USB2ISP.suo
│  │      │      │  USB2ISP.vbproj
│  │      │      │  USB2ISP.vbproj.user
│  │      │      │  USBIOXDLL.vb
│  │      │      │  _UpgradeReport.htm
│  │      │      │  
│  │      │      ├─bin
│  │      │      │      USB2ISP.vshost.exe
│  │      │      │      
│  │      │      ├─My Project
│  │      │      ├─obj
│  │      │      │  │  USB2ISP.vbproj.FileList.txt
│  │      │      │  │  
│  │      │      │  └─Debug
│  │      │      │      │  USB2ISP.frmMain.resources
│  │      │      │      │  USB2ISP.vbproj.GenerateResource.Cache
│  │      │      │      │  USB2ISP.vbproj.ResolveComReference.cache
│  │      │      │      │  
│  │      │      │      └─TempPE
│  │      │      └─_UpgradeReport_Files
│  │      │              UpgradeReport.css
│  │      │              UpgradeReport_Minus.gif
│  │      │              UpgradeReport_Plus.gif
│  │      │              
│  │      ├─VB_ProjectEN				//USB2ISP上位机VB源代码
│  │      │      CHIP4.ico
│  │      │      frmMain.frm
│  │      │      frmMain.frx
│  │      │      frmMain.log
│  │      │      Module1.bas
│  │      │      MSSCCPRJ.SCC
│  │      │      USB2ISP.VBP
│  │      │      USB2ISP.vbw
│  │      │      USB2ISP_DEMO_VBEN.exe
│  │      │      USBIOX.DLL
│  │      │      USBIOX.INF
│  │      │      USBIOX.SYS
│  │      │      USBIOXDLL.bas
│  │      │      
│  │      └─VC_Project					//USB2ISP上位机VC源代码
│  │          │  CtrlSheet.cpp
│  │          │  CtrlSheet.h
│  │          │  EeprPage.cpp
│  │          │  EeprPage.h
│  │          │  EppPage.cpp
│  │          │  EppPage.h
│  │          │  I2CSPage.cpp
│  │          │  I2CSPage.h
│  │          │  LEDBTDisp.cpp
│  │          │  LEDBTDisp.h
│  │          │  MemPage.cpp
│  │          │  MemPage.h
│  │          │  OtherPage.cpp
│  │          │  OtherPage.h
│  │          │  resource.h
│  │          │  StdAfx.cpp
│  │          │  StdAfx.h
│  │          │  Total.h
│  │          │  USB2ISP.APS
│  │          │  USB2ISP.CPP
│  │          │  USB2ISP.dsp
│  │          │  USB2ISP.dsw
│  │          │  USB2ISP.H
│  │          │  USB2ISP.ncb
│  │          │  USB2ISP.opt
│  │          │  USB2ISP.plg
│  │          │  USB2ISP.rc
│  │          │  USB2ISPDLG.cpp
│  │          │  USB2ISPDLG.h
│  │          │  USBIOX.DLL
│  │          │  USBIOX.H
│  │          │  USBIOX.LIB
│  │          │  
│  │          ├─Debug
│  │          │      CtrlSheet.obj
│  │          │      EeprPage.obj
│  │          │      EppPage.obj
│  │          │      I2CSPage.obj
│  │          │      LEDBTDisp.obj
│  │          │      MemPage.obj
│  │          │      OtherPage.obj
│  │          │      StdAfx.obj
│  │          │      USB2ISP.exe
│  │          │      USB2ISP.ilk
│  │          │      USB2ISP.obj
│  │          │      USB2ISP.pch
│  │          │      USB2ISP.pdb
│  │          │      USB2ISP.res
│  │          │      USB2ISPDlg.obj
│  │          │      vc60.idb
│  │          │      vc60.pdb
│  │          │      
│  │          ├─hlp
│  │          ├─Release
│  │          │      CtrlSheet.obj
│  │          │      EeprPage.obj
│  │          │      EppPage.obj
│  │          │      I2CSPage.obj
│  │          │      LEDBTDisp.obj
│  │          │      MemPage.obj
│  │          │      OtherPage.obj
│  │          │      StdAfx.obj
│  │          │      USB2ISP.obj
│  │          │      USB2ISP.pch
│  │          │      USB2ISP.res
│  │          │      USB2ISPDlg.obj
│  │          │      USB2ISP_DEMO.exe
│  │          │      vc60.idb
│  │          │      
│  │          └─res
│  │                  USB2I2C.RC2
│  │                  USB2ISP.ico
│  │                  USB2ISP.RC2
│  │                  
│  ├─USB2ISP_DRIVER			//USB2ISP驱动文件
│  │  ├─DRIVER				//USB2ISP驱动文件
│  │  │      USBIOX.DLL		
│  │  │      USBIOX.INF
│  │  │      USBIOX.SYS
│  │  │      
│  │  ├─LIB_BCB				//USB2ISP驱动BCB库文件
│  │  │      USBIOX.DEF
│  │  │      USBIOX.DLL
│  │  │      USBIOX.LIB
│  │  │      
│  │  ├─LIB_C				//USB2ISP驱动VC++库文件
│  │  │      USBIOX.H		//USB2ISP驱动文件所有API函数的详细说明！重要！
│  │  │      USBIOX.LIB
│  │  │      
│  │  └─USB2XXXLinuxDriver	//USB2ISP Linux驱动
│  │          usb2spi_test.c
│  │          USBIOX.c
│  │          USBIOX.h
│  │          
│  ├─USB2ISP_PUB			//USB2ISP测试程序及源代码
│  │  │  README.txt			//USB2ISP测试程序及源代码
│  │  │  
│  │  ├─SPEED_I2C			//USB2ISP测试通信速度程序及源代码
│  │  │      MAKEFILE
│  │  │      SPEED_I2C.C
│  │  │      
│  │  └─USB2I2C_EXAM		//USB2ISP非常规操作（非标准I2C总线通信协议）程序及源代码
│  │          I2C_EXAM.C
│  │          
│  └─USB2ISP_SCH_PCB			//USB2ISP原理图和PCB图（均经过测试验证！可放心使用）
								//（所有产品销售：http://www.usb-i2c-spi.com/cn/mail.htm）
│          USB2ISP_DEV.DDB		//USB2ISP_DEV开发板的原理图和PCB图
│          USB2ISP_DEV_SCH_PCB.pdf	//USB2ISP_DEV开发板的原理图和PCB图（PDF版本）
│          USB2ISP_LIB.Bkp		//USB2ISP原理图和PCB图库文件
│          USB2ISP_LIB.ddb
│          USB2XXX-DIP.Bkp
│          USB2XXX-DIP.ddb		//USB2XXX-DIP开发板的原理图和PCB图
│          USB2XXX-DIP_SCH_PCB.pdf	//USB2ISP_DEV开发板的原理图和PCB图（PDF版本）
│          
├─USB2SPI_20090430					//USB2SPI开发包，更新日期：2009.04.30
│  │  USB2SPI_V3.1D_20090430.pdf	//USB2SPI数据手册
│  │  
│  ├─USB2SPI_DEMO					//USB2SPI上位机测试程序及源代码
│  │  │  USB2SPI_DEMO_VBCN.exe		//USB2SPI上位机VB测试程序
│  │  │  USBIOX.DLL					//USB2SPI驱动动态链接库
│  │  │  
│  │  └─Resource					//USB2SPI上位机测试程序及源代码
│  │      │  readme.txt				//USB2SPI上位机测试程序及源代码
│  │      │  
│  │      ├─USB2SPI_C_DEMO			//USB2SPI上位机C源代码
│  │      │      USBIOX.DLL
│  │      │      USBIOX.H
│  │      │      USBIOX.LIB
│  │      │      usb_spi.c
│  │      │      usb_spi.dsp
│  │      │      usb_spi.dsw
│  │      │      usb_spi.exe
│  │      │      usb_spi.ncb
│  │      │      usb_spi.opt
│  │      │      usb_spi.plg
│  │      │      
│  │      ├─USB2SPI_DAQ				//USB2SPI数据采集DAQ
│  │      │      Form1.frm
│  │      │      Module1.bas
│  │      │      Module2.bas
│  │      │      MSSCCPRJ.SCC
│  │      │      Project1.vbp
│  │      │      Project1.vbw
│  │      │      USB2SPI_DAQ.exe
│  │      │      USBIOX.DLL
│  │      │      USBIOX.INF
│  │      │      USBIOX.SYS
│  │      │      USBIOXDLL.bas
│  │      │      
│  │      ├─USB2SPI_DEMO_VBCN		//USB2SPI上位机VB源代码
│  │      │      CHIP4.ico
│  │      │      frmMain.frm
│  │      │      frmMain.frx
│  │      │      frmMain.log
│  │      │      Module1.bas
│  │      │      MSSCCPRJ.SCC
│  │      │      USB2SPI.VBP
│  │      │      USB2SPI.vbw
│  │      │      USB2SPI_DEMO_VBCN.exe
│  │      │      USBIOX.DLL
│  │      │      USBIOX.INF
│  │      │      USBIOX.SYS
│  │      │      USBIOXDLL.bas
│  │      │      
│  │      ├─USB2SPI_DEMO_VBEN		//USB2SPI上位机VB源代码
│  │      │      CHIP4.ico
│  │      │      frmMain.frm
│  │      │      frmMain.frx
│  │      │      frmMain.log
│  │      │      Module1.bas
│  │      │      MSSCCPRJ.SCC
│  │      │      USB2ISP.VBP
│  │      │      USB2ISP.vbw
│  │      │      USB2ISP_DEMO_VBEN.exe
│  │      │      USBIOX.DLL
│  │      │      USBIOX.INF
│  │      │      USBIOX.SYS
│  │      │      USBIOXDLL.bas
│  │      │      
│  │      └─USB2SPI_TEST		//USB2SPI上位机BCB源代码
│  │              EXAM.C
│  │              TEST.C
│  │              
│  ├─USB2SPI_DRIVER				//USB2SPI驱动文件
│  │  ├─DRIVER					//USB2SPI驱动文件
│  │  │      USBIOX.DLL
│  │  │      USBIOX.INF
│  │  │      USBIOX.SYS
│  │  │      
│  │  └─LIB_C					//USB2SPI驱动VC++库文件
│  │          USBIOX.H			//USB2SPI驱动文件所有API函数的详细说明！重要！
│  │          USBIOX.LIB
│  │          
│  ├─USB2SPI_PCH_SCH			//USB2SPI原理图和PCB图（均经过测试验证！可放心使用）
								//（所有产品销售：http://www.usb-i2c-spi.com/cn/mail.htm）
│  │      USB2SPI_DEMOS.ddb		//USB2SPI适配器，适合模块设计（3.3V和5V）
│  │      USB2SPI_LIB.Bkp
│  │      USB2SPI_LIB.ddb		//USB2SPI原理图和PCB图库文件
│  │      USB2SPI_PCH_SCH.pdf	//USB2SPI适配器，适合模块设计（3.3V和5V）PDF版本
│  │      
│  └─USB2SPI_PUB				//USB2SPI测试程序及源代码
│      ├─SPEED_I2C				//USB2SPI测试通信速度程序及源代码
│      │      MAKEFILE
│      │      SPEED_I2C.C
│      │      
│      └─USB2I2C_EXAM			//USB2SPI非常规操作（非标准I2C总线通信协议）程序及源代码
│              I2C_EXAM.C
│              
└─USBxI2C_SMbus_SPI_EPP			//USB、SPI、I2C、SMbus、SPI、EPP并口等通信协议及规范
        EPP_v1.7.PDF			//EPP_v1.7并口通信协议及规范
        I2C_SPECIFICATION_V2.10.pdf	//I2C（英文）通信协议及规范
        I2C总线规范.pdf				//I2C（中文）通信协议及规范
        SMbus Protocol_V110.pdf		//SMbus通信协议及规范
        SPI Protocol.pdf			//SPI通信协议及规范
        SPI总线原理附图解.pdf		//SPI通信协议及规范
        
