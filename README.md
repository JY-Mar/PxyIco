# PxyIco

icons of proxy tools

## 项目结构

```text
├── .github/workflows/
│   └── run-jobs.yml           # GitHub Actions工作流
├── resources/                 # 图标
│   ├── App/                   # App图标文件目录
│   ├── Color/                 # 彩色图标文件目录
│   │   ├── Circle/            # 彩色圆形图标
│   │   ├── Scat/              # 彩色作者头像
│   │   └── ...                # 彩色图标
│   └── Mono/                  # 单色图标文件目录
│       ├── Dark/              # 暗色图标
│       └── ...                # 亮色图标
|── scriptsForPython/          # Python脚本
├── docs/                      # GitHub Pages输出目录
│   ├── index.html             # 主页面
│   ├── App/                   # 拷贝到doc目录下的 App图标文件目录
│   ├── Color/                 # 拷贝到doc目录下的 彩色图标文件目录
│   │   ├── Circle/            # 拷贝到doc目录下的 彩色圆形图标
│   │   ├── Scat/              # 拷贝到doc目录下的 彩色作者头像
│   │   └── ...                # 拷贝到doc目录下的 彩色图标
│   ├── Mono/                  # 拷贝到doc目录下的 单色图标文件目录
│   │   ├── Dark/              # 拷贝到doc目录下的 暗色图标
│   │   └── ...                # 拷贝到doc目录下的 亮色图标
│   └── images.json            # 统计图标信息
└── README.md
```

# 远程图标配置参考

[https://github.com/luestr/ProxyResource/blob/main/Tool/Loon/Lcf/zh-CN/Loon_Sample_Configuration_By_iKeLee.lcf](https://github.com/luestr/ProxyResource/blob/main/Tool/Loon/Lcf/zh-CN/Loon_Sample_Configuration_By_iKeLee.lcf)

## PxyRes 集成的图标

> 来自
> 1. [Koolson/Qure](https://github.com/Koolson/Qure)
> 2. [Orz-3/mini](https://github.com/Orz-3/mini)

[点此预览图标](https://jy-mar.github.io/PxyIco/)

### 使用

- 方式一，`raw.githubusercontent.com` 引用

例：

```
https://raw.githubusercontent.com/JY-Mar/PxyIco/refs/heads/main/resources/Color/Back.png
```

- 方式二，`github.io` 直接引用

例：

```
https://jy-mar.github.io/PxyIco/Color/Back.png
```