# Android-monitor-shell-script
- 安卓系统监控shell 脚本, 包括cpu, memory, fps, sensor, 电量 等信息
- sh /data/local/tmp/monitor.sh {montior_folder} {montiorWindow} {monitorPackages} {monitor_interval} {meminfo_type} &

- busybox为了弥补android系统中shell 命令支持不足的情况, 需要将busybox与monitor 脚本放在一个位置, 由busybox来运行脚本
