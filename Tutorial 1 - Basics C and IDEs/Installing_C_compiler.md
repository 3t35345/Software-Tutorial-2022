# Prerequisite: Installing the C/C++ Compiler
Original Author: Li Chi Kin (ckliam@connect.ust.hk)

## Table of Contents
Windows
MacOS
Ubuntu

## Windows
### Install MinGW w64
source: https://www.youtube.com/watch?v=FEeFG9OR-QU&ab_channel=GeekyScript

1. Go to this website  https://sourceforge.net/projects/mingw/to download the compiler
![image](https://github.com/3t35345/Software-Tutorial-2022/assets/21338940/e4098608-3456-4dcb-a817-6cd3aa108203)
2. Open the downloaded setup tool, press the Install and Continue button, and you will reach this interface.
  <img width="948" alt="image" src="https://github.com/3t35345/Software-Tutorial-2022/assets/21338940/5af504fa-77e5-43c7-b43a-447d55e8e41f">
Select all packages by clicking 'Mark for Installation', go to Installation (at the top left corner), and click 'Apply Changes'
  <img width="486" alt="image" src="https://github.com/3t35345/Software-Tutorial-2022/assets/21338940/717a3666-13dd-4f1b-a842-60007c55c5ae">
  <p></p>
3. Copy the path of your Mingw to the environment variable
<p></p>
  3.1. Search PATH in windows
  <p></p>
  3.2. Click on 'Edit the system environment variables', in Chinese,'編輯系統環境變數'.
<img width="489" alt="Screenshot 2023-08-30 112937" src="https://github.com/3t35345/Software-Tutorial-2022/assets/21338940/8248493b-369f-4096-8008-d648c2a8772c">
  <p></p>
  3.3. Add C:\MinGW\bin to PATH <p>
  <img width="409" alt="Screenshot 2023-08-30 115839" src="https://github.com/3t35345/Software-Tutorial-2022/assets/21338940/fa150969-81c3-4f64-a922-1732d3c09974">
    <p></p>
4. To test whether the installation is successful, you can type 
 `g++ --version` in the terminal to check.

## MacOS
source: https://www.youtube.com/watch?v=lGsyqgpMAYY&ab_channel=CodeWithArjun

Since I don't have a Mac :(, I cannot demonstrate how to install the compiler on MacOS. But no worries! The process is fairly simple and straightforward (At least simpler than that in Windows). 

## Ubuntu
The GCC compiler should be installed on Ubuntu by default. You can use the command `g++ -v` to check it.


