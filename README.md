# v2rayN
A GUI client for Windows, support [Xray core](https://github.com/XTLS/Xray-core) and [v2fly core](https://github.com/v2fly/v2ray-core) and [others](https://github.com/2dust/v2rayN/wiki/List-of-supported-cores)


[![GitHub commit activity](https://img.shields.io/github/commit-activity/m/2dust/v2rayN)](https://github.com/2dust/v2rayN/commits/master)
[![CodeFactor](https://www.codefactor.io/repository/github/2dust/v2rayn/badge)](https://www.codefactor.io/repository/github/2dust/v2rayn)
[![GitHub Releases](https://img.shields.io/github/downloads/2dust/v2rayN/latest/total?logo=github)](https://github.com/2dust/v2rayN/releases)
[![Chat on Telegram](https://img.shields.io/badge/Chat%20on-Telegram-brightgreen.svg)](https://t.me/v2rayn)


## How to use
- If you are new to this, please download v2rayN-With-Core.zip from [releases](https://github.com/2dust/v2rayN/releases)
- Otherwise please download v2rayN.zip (you will also need to download cores in the bin directory). The msg looks like:在文件夹 (D:\studyspace\cpp\v2rayN\v2rayN\v2rayN\bin\Debug\net8.0-windows10.0.17763\bin\Xray) 下未找到Core文件 (文件名:xray, wxray)，请下载后放入文件夹，下载地址: https://github.com/XTLS/Xray-core/releases
- Run v2rayN.exe

## Requirements  
- (6.35 and above)[Microsoft .NET 8.0 Desktop Runtime ](https://dotnet.microsoft.com/en-us/download/dotnet/8.0)
- (6.33 and below)[Microsoft .NET 6.0 Desktop Runtime ](https://dotnet.microsoft.com/en-us/download/dotnet/6.0)
- [Supported cores](https://github.com/2dust/v2rayN/wiki/List-of-supported-cores)


## Telegram Channel
[github_2dust](https://t.me/github_2dust)

## How to set up the config
- Right click one server in Server List, set it as Active Server.
- Change the System proxy mode to Auto Config

## Tun Mode
- Default closed. But the software is not working even in the Global mode, we can try to set it open.

## System Proxy
- Clean System Proxy: Close the the proxy, recover and use the original network.
- Auto Config: Use proxy.
- No Change System Proxy: Do nothing, just keep other proxy setting.
- PAC Mode: Intelligent shunt mode, according to the rules to match the websites you visit, only accelerate foreign websites, domestic websites are not affected.

## Rout
- Global: All data goes out through the proxy
- BlackList: Except the websites in the blacklist, all websites access the Internet through the node server proxy.
- Except Mainland: Judging whether the target is cn from the geo file, if it is a direct connection outbound, other outbound agents (LAN has also been bypassed).

