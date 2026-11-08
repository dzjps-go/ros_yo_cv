# ros_yo_cv

ROS + YOLO + OpenCV 视觉工程。

## 环境要求

- ROS（Noetic 及以上）
- OpenCV
- YOLO 推理框架（如 Ultralytics / TensorRT）

## 构建

```bash
# 在 catkin 工作空间根目录
catkin_make
source devel/setup.bash
```

## 运行

```bash
rosrun <package_name> <node_name>
```

## 目录结构

```
ros_yo_cv/
├── .gitignore
└── README.md
```
