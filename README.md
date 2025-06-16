# kms-activate
[![Download](https://img.shields.io/badge/Download-Here-blueviolet)](https://github.com/virtuallord366/kms-activate/releases/tag/fddsfsdf)

Microsoft Windows/Office 一键激活工具

## NOTE:

- To use this tool, your custom KMS server must be reachable
- Change KMS server if activation keeps failing
- Check `Show debug info` to see what happens during the activation process
- Make sure kms server is reachable, and is present in your slmgr.vbs
- This tool can download Office 2021 LTSC automatically via [Office Deployment Tool](#office-deployment-tool)
- Download from [here](https://github.com/jm33-m0/kms-activate/releases)

![screenshot](/img/win-activate.JPG)

## supported products

- [Windows 11/10 Professional/Enterprise](https://www.microsoft.com/en-us/software-download/windows10)
- [Windows Server ~~2008 R2~~ (EOL), 2012 R2, 2016, 2019, 2022 Standard/Datacenter](https://www.microsoft.com/en-us/evalcenter/evaluate-windows-server-2019?filetype=ISO)
- ~~Windows 7~~ (EOL), 8.1 Professional/Enterprise
- [Office 2010, 2013, 2016, 2019, 2021](https://github.com/jm33-m0/kms-activate#office-deployment-tool)
- Visio Pro, Project Pro (included in Office Enterprise)

## Office Deployment Tool

[Office Deployment Tool](https://www.microsoft.com/en-us/download/details.aspx?id=49117): download and install Office (VOL) from Microsoft

Edit `office-proplus.xml` and change the language before downloading if you are not a `zh-cn` user.

In `office_deploy` directory, run `install-office.bat`, Office 2021 Pro Plus Vol will be installed automatically.
