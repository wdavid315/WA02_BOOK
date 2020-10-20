環境工具安裝

[WA02] Build SDM850 WP BSP on Windows OS_for 5400.doc

其它更新與安裝

更新下載Snapdragon LLVM ARM toolchain 40120 & 40220 & 40320 & 40720
      download at https://createpoint.qti.qualcomm.com/tools

安裝路徑: C:\Apps\LLVM\4.0.1
                        C:\Apps\LLVM\4.0.2
                        C:\Apps\LLVM\4.0.3
                        C:\Apps\LLVM\4.0.7
                        C:\Apps\LLVM\4.0.11 (2019/10/28更新)


更新下載Hexagon 8.2.01 & 8.2.04 & 8.2.07
download at https://createpoint.qti.qualcomm.com/

      安裝路徑: C:\Qualcomm\HEXAGON_Tools\8.2.01
                        C:\Qualcomm\HEXAGON_Tools\8.2.04
                        C:\ Qualcomm\HEXAGON_Tools\8.2.07 (2019/10/28更新)


安裝GCC Linaro GNU 4.9 - 2014.07

安裝路徑: C:\Apps\gcc-linaro-aarch64-none-elf-4.9-2014.07_win32

安裝 Microsoft Visual Studio 14.0

因為我們只使用  nmake.exe,所以請從 FTP server以下的路徑下載
     /SW/WA03/SC8180X/Install_Tools/Microsoft Visual Studio 14.0
 並把它放置到 C:\Program Files (x86)目錄下.請將以下的參數加入到你的系統環境變數中的PATH
C:\Program Files (x86)\Microsoft Visual Studio 14.0\VC\bin


設置Windows環境變數，存在set_env.bat

echo "set non-HLOS enviroment..."

set ARMLMD_LICENSE_FILE=8224@10.101.225.226
