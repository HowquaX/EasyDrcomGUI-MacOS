# EasyDrcomGUI For GDUFE MacOS
## 关于EasyDrcomGUI For GDUFE：
EasyDrcomGUI For GDUFE 源于 Shindo 编写的为哈尔滨工业大学（威海）量身定制的第三方Dr.COM客户端，可在教学区、家属区、学生区使用，包括Windows, Mac OS X, Linux（包括OpenWrt）版本。
后经广财13级 XeonForce 修改为可在广财校园网内使用的版本。HowquaX在二者的基础上，进行了重新封装、打包使安装使用更简单。

Shindo的Github项目地址：https://github.com/coverxit/EasyDrcomGUI

XeonForce的项目地址(win32版本)：http://wp.xeonforce.com/easydrcom-for-gdufe/

HowquaX的项目地址：http://howqua.top/easydrcom-for-gdufe/

# EasyDrcomGUI
GUI Wrapper for **[EasyDrcom](https://github.com/coverxit/EasyDrcom)**, which is a 3rd Party Dr.COM Client for HITwh.

## Description
**本项目用于存放 MacOS 版 EasyDrcomGUI 的源代码。若您需要获取发行版，请移步至 [广财招协网站](http://epa.gdufe.edu.cn/easydrcom)。**

**若您需要获取其他平台源代码，请根据所需平台移步至对应分支：**

* Windows：[Win32分支](https://github.com/HowquaX/EasyDrcomGUI-For-GDUFE)

## Introduction
Mac OS 版需要10.9以上的系统环境， EasyDrcomGUI（以下简称**本项目**）使用 XCode 7 开发，语言为 C++（包括C++ 11的部分特性）和 Objective-C。

本项目依赖于 **libpcap**（已内建于Mac OS X），此外使用了第三方库 [STPrivilegedTask](https://github.com/sveinbjornt/STPrivilegedTask)。



## Change Log
**部分修改记录可在上述两个项目地址查看。**

**请移步至 [项目网站](http://howqua.top/easydrcom-for-gdufe/) 查看修改日志。**

修改的位置同win版的修改位置，如需更多帮助可联系作者。

## License
EasyDrcomGUI License:

	Copyright (C) 2014, 2015 Shindo 
	
	Licensed under the Apache License, Version 2.0 (the "License");
	you may not use this file except in compliance with the License.
	You may obtain a copy of the License at
	
		http://www.apache.org/licenses/LICENSE-2.0
	
	Unless required by applicable law or agreed to in writing, software
	distributed under the License is distributed on an "AS IS" BASIS,
	WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
	See the License for the specific language governing permissionss and
	limitations under the License.

WinPcap License:

	Copyright (c) 1999 - 2005 NetGroup, Politecnico di Torino (Italy).
	Copyright (c) 2005 - 2010 CACE Technologies, Davis (California).
	All rights reserved.
	
	Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:
	
	1. Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer. 
	2. Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution. 
	3. Neither the name of the Politecnico di Torino, CACE Technologies nor the names of its contributors may be used to endorse or promote products derived from this software without specific prior written permission. 
	
	THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT OWNER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

WTL License:

	Copyright © 2014 Microsoft Corporation, WTL Team. All rights reserved.
	 
	This file is a part of the Windows Template Library.
	The use and distribution terms for this software are covered by the
	Common Public License 1.0 (http://opensource.org/licenses/cpl1.0.php).
	By using this software in any fashion, you are agreeing to be bound by
	the terms of this license. You must not remove this notice, or
	any other, from this software.