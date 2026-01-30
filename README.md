# wintools
 windows system tool suite

 2024/05/21
 RAMMap.exe --  Physical Memory Analyzer and Cleaner V1.0 for x64 windows 10 or later

 2024/06/07
 WinObj.exe -- WinObj is a must-have tool if you are a system administrator concerned about security, a developer tracking down object-related problems, or just curious about the Object Manager namespace.

 2024/06/13
 PoolMon.exe -- PoolMon (poolmon.exe), the Memory Pool Monitor, displays data that the operating system collects about memory allocations from the system paged and nonpaged kernel pools, and the memory pools used for Terminal Services sessions. The data is grouped by pool allocation tag.

 2024/06/20
 MemoryCleaner.exe -- Memory Cleaner is considerably better because it uses functions built into Windows to judiciously free memory - with no performance impact whatsoever. You can now access Memory Cleaner functions from the tray icon without having to open up the main window. The cleaning prodecures are both silent and the only alert you will see is the amount of RAM recovered briefly displayed in the window. If you find your RAM usage exceeding 60% regularly, then MemoryCleaner is an absolute must have.

 2024/06/20
 MemoryCleaner.exe -- v1.1 fix bug:
 1. 以 “Runas”方式提升权限来支持随windows自启动(登录windows时自动启动)
 2. windows任务栏重建时重建Tray Icon (任务栏/桌面奔溃时重建工具托盘, 通过Kill explorer进程来让桌面重启进行测试)

 2024/07/16
 ProcMon.exe -- 进程/线程活动监视器；网课防摸鱼神器：通过阻塞应用运行来防止网课期间玩游戏、聊天等分心行为

 2024/07/30
 MemoryCleaner.exe -- v1.2 fix bug:
 1. 当工具以 /boot (登录windows时自动启动)方式运行时直接隐藏窗口
 2. 修复 TOPMOST(置顶)无效的Bug; 窗口上按 Enter键 自动关闭的Bug

 ProcMon.exe -- v1.2 fix bug:
 1. 窗口上按 Enter键 自动关闭的Bug

 CoreInfo.exe -- Coreinfo is a MFC utility that shows you the mapping between logical processors and the physical processor, NUMA node, and socket on which they reside, as well as the cache’s assigned to each logical processor. 

 2024/7/31
 MemoryCleaner.exe -- v1.3, 集成Sysinternals CacheSet功能, CacheSet is an applet that allows you to manipulate the working-set parameters of the system file cache。
 
 2024/08/07
 Handlexp.exe -- v1.0 Handlexp is a MFC utility that displays information about open handles for any process in the system. You can use it to see the programs that have a file open, or to see the object types and names of all the handles of a program.

  2024/09/10
 BreakTimer -- v1.0 一个中断计时器工具, 基于Windows桌面应用程序开发, 支持自定义行为, 包括多种背景模式、音频播放等

 2024/10/21
 PoolMon.exe -- v1.1 fix bug:
 1. 变量滞后初始化导致异常

 2024/10/23
 SnipIt.exe -- v1.0 Snipping tool, 屏幕截图工具, 仅支持x86-64, Windows11/10下进行了简单的兼容性测试 
 BreakTimer.exe -- v1.1 fix bug:
 1. re-build taskbar
 2. support background opacity

 2024/11/01
 DrawIt.exe -- v1.0 Screen draw tool, only support x86-64, simple compatibility test was carried out under Windows 11/10
 SnipIt/BreakTimer tools open Options dialog at first run or failed to register hotkey

 2025/01/02
 RecordIt.exe -- v1.0 Record video of desktop/window/crop-window, only support x86-64, test in window 10/11

  2025/01/14
 RecordIt.exe -- v1.1 support to capture audio

 2025/01/17
 PoolMon.exe -- v2.0 support Mapped-Driver
 WinObj.exe -- fix nullptr bug

2025/02/11
RecordIt.exe -- v1.2 support Encoding Quality（Bitrate）

2025/03/18
SearchStrings.exe -- v1.0 Search for ANSI and Unicode strings in binary images.
ZoomIt.exe -- v1.0 ZoomIt is a screen zoom tool for technical presentations and demos. 
DrawIt.exe -- v1.1 bug fixed: 
1. DC resource leak
2. not exit draw mode when kill focus

2025/03/21
LiveZoomIt.exe -- v1.0 LiveZoomIt is a screen live-zoom tool for technical presentations and demos. 

2025/06/11 
DiskCleaner.exe -- v1.0 存储感知清理工具，定期自动清理指定目录集下的过期文件，以释放存储空间

2025/06/30
SDelete.exe -- v1.0 文件粉碎器，通过对文件内容所在的存储空间进行覆写和擦除以使数据不可恢复，从而达到安全删除数据。

2025/08/04 
TCPView.exe -- v1.0  网络终结点查看器，显示系统上所有 TCP 和 UDP 终结点的详细列表，包括本地和远程地址以及 TCP 连接的状态。

2026/01/10
DsnMon.exe -- v1.0 Dns查询事件监视器，实时接收由Microsoft-Windows-DNS-Client事件提供器的Dns事件。Microsoft-Windows-DNS-Client从Windows 8.1开始才提供DNS Query Event.

2026/01/26
NetworkMon.exe -- v1.0 网络连接监视器，记录计算机上的 TCP/UDP 连接。 每个连接都通过 ProcessId字段链接到一个进程。 该事件还包含源和目标主机名、 IP 地址、端口号和 IPv6 状态

2026/01/30
DnsMon.exe -- v2.0 支持底部属性区；导出；规则配置；Whois