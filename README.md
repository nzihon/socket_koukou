aqq这是一个聊天的软件


jiyu:



positional arguments:
  {r,s,g,nc,break,continue}
                        -e 参数的详细说明
    r                   reboot 重启
    s                   shutdown 关机
    g                   独立选项，获取当前的ip地址以及学生端监听的端口
    nc                  独立选项，反弹shell的机器需出网，退出可使用命令exit
    break               独立选项，脱离屏幕控制，需要管理员权限
    continue            独立选项，恢复屏幕控制

optional arguments: 
  -h, --help            show this help message and exit
  -ip IP                ip 指定目标IP地址
  -p P                  port 指定监听端口，默认端口为4705
  -msg MSG              send_message发送消息 eg: -msg "HelloWord!"
  -c C                  command命令 eg: -c "cmd.exe /c ipconfig"
  -l L                  循环次数，默认为1
  -t T                  循环时间间隔，默认是22秒
  -e {r,s,g,nc,break,continue}
                        Extra Options加载额外的选项 eg：-e r
