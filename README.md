# NoxPlayer

// 分卷压缩文件，每卷86M，压缩NoxPlayer文件夹内容，压缩文件名称NoxPlayer-win-6.2.7.1.7z.001, NoxPlayer-win-6.2.7.1.7z.002 ...
7za.exe a -t7z -r -m0=LZMA2 -mx9 -v86m NoxPlayer-win-6.2.7.1.7z NoxPlayer

// 解压分卷文件，解压到当前NoxPlayer目录
7za.exe x -y -oNoxPlayer NoxPlayer-win-6.2.7.1.7z.001
