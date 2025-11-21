# tree -L 4 -A
.
├── assets 示例图片资源
│   ├── bus.jpg
│   └── zidane.jpg
├── cfg 配置文件目录
│   ├── datasets 各种数据集配置文件
│   │   ├── african-wildlife.yaml
│   │   ├── Argoverse.yaml
│   │   ├── brain-tumor.yaml
│   │   ├── carparts-seg.yaml
│   │   ├── coco128-seg.yaml
│   │   ├── coco128.yaml
│   │   ├── coco8-grayscale.yaml
│   │   ├── coco8-multispectral.yaml
│   │   ├── coco8-pose.yaml
│   │   ├── coco8-seg.yaml
│   │   ├── coco8.yaml
│   │   ├── coco-pose.yaml
│   │   ├── coco.yaml
│   │   ├── construction-ppe.yaml
│   │   ├── crack-seg.yaml
│   │   ├── dog-pose.yaml
│   │   ├── dota8-multispectral.yaml
│   │   ├── dota8.yaml
│   │   ├── DOTAv1.5.yaml
│   │   ├── DOTAv1.yaml
│   │   ├── GlobalWheat2020.yaml
│   │   ├── hand-keypoints.yaml
│   │   ├── HomeObjects-3K.yaml
│   │   ├── ImageNet.yaml
│   │   ├── kitti.yaml
│   │   ├── lvis.yaml
│   │   ├── medical-pills.yaml
│   │   ├── Objects365.yaml
│   │   ├── open-images-v7.yaml
│   │   ├── package-seg.yaml
│   │   ├── signature.yaml
│   │   ├── SKU-110K.yaml
│   │   ├── tiger-pose.yaml
│   │   ├── VisDrone.yaml
│   │   ├── VOC.yaml
│   │   └── xView.yaml
│   ├── default.yaml
│   ├── __init__.py
│   ├── models 模型架构配置文件
│   │   ├── 11
│   │   │   ├── yolo11-cls-resnet18.yaml
│   │   │   ├── yolo11-cls.yaml
│   │   │   ├── yolo11-obb.yaml
│   │   │   ├── yolo11-pose.yaml
│   │   │   ├── yolo11-seg.yaml
│   │   │   ├── yolo11.yaml
│   │   │   ├── yoloe-11-seg.yaml
│   │   │   └── yoloe-11.yaml
│   │   ├── 12
│   │   │   ├── yolo12-cls.yaml
│   │   │   ├── yolo12-obb.yaml
│   │   │   ├── yolo12-pose.yaml
│   │   │   ├── yolo12-seg.yaml
│   │   │   └── yolo12.yaml
│   │   ├── README.md
│   │   ├── rt-detr
│   │   │   ├── rtdetr-l.yaml
│   │   │   ├── rtdetr-resnet101.yaml
│   │   │   ├── rtdetr-resnet50.yaml
│   │   │   └── rtdetr-x.yaml
│   │   ├── v10
│   │   │   ├── yolov10b.yaml
│   │   │   ├── yolov10l.yaml
│   │   │   ├── yolov10m.yaml
│   │   │   ├── yolov10n.yaml
│   │   │   ├── yolov10s.yaml
│   │   │   └── yolov10x.yaml
│   │   ├── v3
│   │   │   ├── yolov3-spp.yaml
│   │   │   ├── yolov3-tiny.yaml
│   │   │   └── yolov3.yaml
│   │   ├── v5
│   │   │   ├── yolov5-p6.yaml
│   │   │   └── yolov5.yaml
│   │   ├── v6
│   │   │   └── yolov6.yaml
│   │   ├── v8
│   │   │   ├── yoloe-v8-seg.yaml
│   │   │   ├── yoloe-v8.yaml
│   │   │   ├── yolov8-cls-resnet101.yaml
│   │   │   ├── yolov8-cls-resnet50.yaml
│   │   │   ├── yolov8-cls.yaml
│   │   │   ├── yolov8-ghost-p2.yaml
│   │   │   ├── yolov8-ghost-p6.yaml
│   │   │   ├── yolov8-ghost.yaml
│   │   │   ├── yolov8-obb.yaml
│   │   │   ├── yolov8-p2.yaml
│   │   │   ├── yolov8-p6.yaml
│   │   │   ├── yolov8-pose-p6.yaml
│   │   │   ├── yolov8-pose.yaml
│   │   │   ├── yolov8-rtdetr.yaml
│   │   │   ├── yolov8-seg-p6.yaml
│   │   │   ├── yolov8-seg.yaml
│   │   │   ├── yolov8-worldv2.yaml
│   │   │   ├── yolov8-world.yaml
│   │   │   └── yolov8.yaml
│   │   └── v9
│   │       ├── yolov9c-seg.yaml
│   │       ├── yolov9c.yaml
│   │       ├── yolov9e-seg.yaml
│   │       ├── yolov9e.yaml
│   │       ├── yolov9m.yaml
│   │       ├── yolov9s.yaml
│   │       └── yolov9t.yaml
│   └── trackers 跟踪器配置文件
│       ├── botsort.yaml
│       └── bytetrack.yaml
├── data 数据加载和处理模块
│   ├── annotator.py
│   ├── augment.py
│   ├── base.py
│   ├── build.py
│   ├── converter.py
│   ├── dataset.py
│   ├── __init__.py
│   ├── loaders.py
│   ├── scripts
│   │   ├── download_weights.sh
│   │   ├── get_coco128.sh
│   │   ├── get_coco.sh
│   │   └── get_imagenet.sh
│   ├── split_dota.py
│   ├── split.py
│   └── utils.py
├── engine 核心引擎模块
│   ├── exporter.py
│   ├── __init__.py
│   ├── model.py
│   ├── predictor.py
│   ├── results.py
│   ├── trainer.py
│   ├── tuner.py
│   └── validator.py
├── hub
│   ├── auth.py
│   ├── google
│   │   └── __init__.py
│   ├── __init__.py
│   ├── session.py
│   └── utils.py
├── __init__.py
├── models 模型实现模块
│   ├── fastsam
│   │   ├── __init__.py
│   │   ├── model.py
│   │   ├── predict.py
│   │   ├── utils.py
│   │   └── val.py
│   ├── __init__.py
│   ├── nas
│   │   ├── __init__.py
│   │   ├── model.py
│   │   ├── predict.py
│   │   └── val.py
│   ├── rtdetr
│   │   ├── __init__.py
│   │   ├── model.py
│   │   ├── predict.py
│   │   ├── train.py
│   │   └── val.py
│   ├── sam
│   │   ├── amg.py
│   │   ├── build.py
│   │   ├── __init__.py
│   │   ├── model.py
│   │   ├── modules
│   │   │   ├── blocks.py
│   │   │   ├── decoders.py
│   │   │   ├── encoders.py
│   │   │   ├── __init__.py
│   │   │   ├── memory_attention.py
│   │   │   ├── sam.py
│   │   │   ├── tiny_encoder.py
│   │   │   ├── transformer.py
│   │   │   └── utils.py
│   │   └── predict.py
│   ├── utils
│   │   ├── __init__.py
│   │   ├── loss.py
│   │   └── ops.py
│   └── yolo
│       ├── classify
│       │   ├── __init__.py
│       │   ├── predict.py
│       │   ├── train.py
│       │   └── val.py
│       ├── detect
│       │   ├── __init__.py
│       │   ├── predict.py
│       │   ├── train.py
│       │   └── val.py
│       ├── __init__.py
│       ├── model.py
│       ├── obb
│       │   ├── __init__.py
│       │   ├── predict.py
│       │   ├── train.py
│       │   └── val.py
│       ├── pose
│       │   ├── __init__.py
│       │   ├── predict.py
│       │   ├── train.py
│       │   └── val.py
│       ├── segment
│       │   ├── __init__.py
│       │   ├── predict.py
│       │   ├── train.py
│       │   └── val.py
│       ├── world
│       │   ├── __init__.py
│       │   ├── train.py
│       │   └── train_world.py
│       └── yoloe
│           ├── __init__.py
│           ├── predict.py
│           ├── train.py
│           ├── train_seg.py
│           └── val.py
├── nn
│   ├── autobackend.py
│   ├── __init__.py
│   ├── modules
│   │   ├── activation.py
│   │   ├── block.py
│   │   ├── conv.py
│   │   ├── head.py
│   │   ├── __init__.py
│   │   ├── transformer.py
│   │   └── utils.py
│   ├── tasks.py
│   └── text_model.py
├── py.typed
├── solutions
│   ├── ai_gym.py
│   ├── analytics.py
│   ├── config.py
│   ├── distance_calculation.py
│   ├── heatmap.py
│   ├── __init__.py
│   ├── instance_segmentation.py
│   ├── object_blurrer.py
│   ├── object_counter.py
│   ├── object_cropper.py
│   ├── parking_management.py
│   ├── queue_management.py
│   ├── region_counter.py
│   ├── security_alarm.py
│   ├── similarity_search.py
│   ├── solutions.py
│   ├── speed_estimation.py
│   ├── streamlit_inference.py
│   ├── templates
│   │   └── similarity-search.html
│   ├── trackzone.py
│   └── vision_eye.py
├── trackers
│   ├── basetrack.py
│   ├── bot_sort.py
│   ├── byte_tracker.py
│   ├── __init__.py
│   ├── README.md
│   ├── track.py
│   └── utils
│       ├── gmc.py
│       ├── __init__.py
│       ├── kalman_filter.py
│       └── matching.py
└── utils
    ├── autobatch.py
    ├── autodevice.py
    ├── benchmarks.py
    ├── callbacks
    │   ├── base.py
    │   ├── clearml.py
    │   ├── comet.py
    │   ├── dvc.py
    │   ├── hub.py
    │   ├── __init__.py
    │   ├── mlflow.py
    │   ├── neptune.py
    │   ├── platform.py
    │   ├── raytune.py
    │   ├── tensorboard.py
    │   └── wb.py
    ├── checks.py
    ├── cpu.py
    ├── dist.py
    ├── downloads.py
    ├── errors.py
    ├── events.py
    ├── export
    │   ├── engine.py
    │   ├── imx.py
    │   ├── __init__.py
    │   └── tensorflow.py
    ├── files.py
    ├── git.py
    ├── __init__.py
    ├── instance.py
    ├── logger.py
    ├── loss.py
    ├── metrics.py
    ├── nms.py
    ├── ops.py
    ├── patches.py
    ├── plotting.py
    ├── tal.py
    ├── torch_utils.py
    ├── tqdm.py
    ├── triton.py
    └── tuner.py