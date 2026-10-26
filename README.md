# HandL20_FR 视频数据说明

本目录存放 HandL20_FR 项目使用的两个 MP4 视频数据文件。

## 文件清单

| 文件路径 | 说明 | 文件大小 |
|---|---|---:|
| `data/video1.mp4` | 视频样本 1 | 0.53 MiB |
| `data/video2.mp4` | 视频样本 2 | 0.49 MiB |

## 视频预览

### 视频 1

<video src="https://github.com/user-attachments/assets/49f3d0d5-fe2d-4c02-a9d9-c5db37852470" controls muted playsinline width="100%"></video>

本地文件：[data/video1.mp4](data/video1.mp4)

### 视频 2

<video src="https://github.com/user-attachments/assets/18dd064c-41f0-4cae-9b8a-b51aa0ff1d59" controls muted playsinline width="100%"></video>

本地文件：[data/video2.mp4](data/video2.mp4)

## 目录结构

```text
HandL20_FR/
├── data/
│   ├── video1.mp4
│   └── video2.mp4
└── README.md
```

## 使用说明

读取视频时，请使用对应的文件路径：

```python
import cv2

video_path = "data/video1.mp4"
capture = cv2.VideoCapture(video_path)
```

视频的编码、分辨率、帧率和时长等信息应以实际读取结果为准；如需训练或评测，请在项目配置中明确指定对应的视频文件，并自行维护生成的标注或处理结果。
