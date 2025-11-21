tree -d -A -L 5
```plaintext
.
├── assets 示例图片资源
├── cfg 配置文件目录
│   ├── datasets 各种数据集配置文件
│   ├── models 模型架构配置文件
│   │   ├── 11
│   │   ├── 12
│   │   ├── rt-detr
│   │   ├── v10
│   │   ├── v3
│   │   ├── v5
│   │   ├── v6
│   │   ├── v8
│   │   └── v9
│   └── trackers 跟踪器配置文件
├── data 数据加载和处理模块
│   └── scripts
├── engine 核心引擎模块
├── hub
│   └── google
├── models 模型实现
│   ├── fastsam # Fast SAM 模型
│   ├── nas # 神经架构搜索
│   ├── rtdetr # RT-DETR 模型
│   ├── sam # Segment Anything 模型
│   │   └── modules
│   ├── utils
│   └── yolo  # YOLO 系列核心实现
│       ├── classify # 分类任务
│       ├── detect  # 检测任务
│       ├── obb # 旋转框检测
│       ├── pose # 姿态检测
│       ├── segment # 分割任务
│       ├── world
│       └── yoloe
├── nn 神经网络组件
│   └── modules
├── solutions 预置解决方案
│   └── templates
├── trackers 目标跟踪器
│   └── utils
└── utils 工具函数
    ├── callbacks
    └── export

```
