# Process Maps

本仓库用于归档 draw.io 流程图、架构图、课程实验图和研究过程图。

## 目录结构

| 目录 | 内容 |
| --- | --- |
| `ai-ml/` | AI、机器学习、模型结构及相关主题图。 |
| `ai-watermark/` | 大模型水印、语义水印、图像隐写、水印生成与检测图。 |
| `course-labs/` | 课程实验流程、账户/卡片业务流程和算法流程图。 |
| `didi-rl/` | Didi 派单、强化学习、候选格子和数据集处理图。 |
| `frontend/` | 前端页面、查询和交互流程图。 |
| `network-systems/` | 网络、HTTP/UDP、ROS、SSL 和系统架构图。 |
| `security/` | 软件安全、栈结构、注入、认证和检测相关图。 |
| `archive/` | 空白、占位、模板、测试、草稿或暂时无法确认用途的图。 |

## 命名规范

- 文件名统一使用英文小写 `kebab-case`。
- 保留 `.drawio` 作为源文件格式。
- 文件名应描述图的主题，避免使用 `Untitled Diagram`、`test`、纯数字或“副本”类名称。
- 空白、默认模板、用途不明确或暂不使用的文件放入 `archive/`。
- 避免仅大小写不同的文件名，例如 `ROS.drawio` 和 `ros.drawio`，尤其是在 Windows 环境下。

## 图表索引

### AI 与机器学习

| 文件 | 说明 |
| --- | --- |
| `ai-ml/5g-security-characteristics.drawio` | 5G 网络特点与安全挑战。 |
| `ai-ml/vision-transformer-architecture.drawio` | Vision Transformer 架构和注意力模块。 |

### AI 水印

| 文件 | 说明 |
| --- | --- |
| `ai-watermark/entropy-based-dynamic-bias.drawio` | 基于熵值的水印动态偏移控制流程。 |
| `ai-watermark/image-steganography-lsb-flow.drawio` | 基于像素最低有效位的图像隐写流程。 |
| `ai-watermark/llm-watermark-method-summary.drawio` | 大模型水印生成与检测方法概览。 |
| `ai-watermark/llm-watermark-research-overview.drawio` | 高效大模型水印技术研究总览。 |
| `ai-watermark/llm-watermark-research-overview-draft.drawio` | 大模型水印研究总览的草稿或副本。 |
| `ai-watermark/semantic-watermark-vocabulary-splitting.drawio` | 语义驱动的水印词表加密与划分流程。 |
| `ai-watermark/watermark-extraction-algorithm.drawio` | 水印提取与检测算法流程。 |
| `ai-watermark/watermark-injection-algorithm.drawio` | 水印注入算法及输入输出流程。 |

### 课程实验

| 文件 | 说明 |
| --- | --- |
| `course-labs/account-close-restore-flow.drawio` | 销户与恢复账户流程。 |
| `course-labs/account-open-flow.drawio` | 开户流程。 |
| `course-labs/account-recharge-flow.drawio` | 账户充值流程。 |
| `course-labs/card-issue-flow.drawio` | 发卡与补卡流程。 |
| `course-labs/card-loss-report-flow.drawio` | 挂失与解挂流程。 |
| `course-labs/fuzzy-match-flow.drawio` | 学号与姓名模糊匹配流程。 |
| `course-labs/media-security-dct-embedding-flow.drawio` | 媒体安全实验中的 DCT 数据嵌入流程。 |
| `course-labs/multiway-merge-sort-flow.drawio` | 多路归并排序流程。 |

### Didi 强化学习

| 文件 | 说明 |
| --- | --- |
| `didi-rl/didi-candidate-grid-selection.drawio` | 候选格子选择和特征比较。 |
| `didi-rl/didi-replay-buffer-datasets.drawio` | Didi 数据表与 Python Replay Buffer 构建流程。 |
| `didi-rl/didi-value-function-grid.drawio` | 价值函数与目的地格子示意图。 |

### 前端

| 文件 | 说明 |
| --- | --- |
| `frontend/airline-query-frontend-flow.drawio` | 航班查询前端流程，包括乘客人数、代理人、航段和总价。 |

### 网络与系统

| 文件 | 说明 |
| --- | --- |
| `network-systems/average-rate-calculation.drawio` | 平均速率计算流程。 |
| `network-systems/frame-format-diagram.drawio` | 包含长度、控制、数据和 CRC 字段的帧格式图。 |
| `network-systems/http-nginx-backend-routing.drawio` | HTTP 请求经 nginx 转发到后端服务的流程。 |
| `network-systems/instant-rate-calculation.drawio` | 瞬时速率计算流程。 |
| `network-systems/network-lab-threading-architecture.drawio` | 网络实验中的前端、输入输出和工作线程架构。 |
| `network-systems/ros-encryption-communication-model.drawio` | ROS 相关的加密通信模型。 |
| `network-systems/ros2-dds-layer-architecture.drawio` | ROS 2 架构与 DDS 层对比笔记。 |
| `network-systems/ssl-certificate-detection-system.drawio` | SSL 证书检测、自动化检测、实时预警和大模型检测系统。 |
| `network-systems/udp-client-request-flow.drawio` | UDP 客户端请求、超时、接收和速率输出流程。 |
| `network-systems/udp-server-message-flow.drawio` | UDP 服务端消息解析、统计、入队和前端输出流程。 |

### 安全

| 文件 | 说明 |
| --- | --- |
| `security/rsma-authentication-flow.drawio` | RSMA 认证和系统流程。 |
| `security/software-security-injection-architecture.drawio` | 软件安全注入架构，包含后端、前端、运行时和 UDP 数据传输。 |
| `security/stack-memory-layout.drawio` | 栈内存布局和控制流转移笔记。 |

### 归档

| 文件 | 说明 |
| --- | --- |
| `archive/default-lamp-template.drawio` | draw.io 默认灯泡故障排查模板。 |
| `archive/empty-analysis-data.drawio` | 空白或占位的数据分析图。 |
| `archive/empty-xmind.drawio` | 空白或占位的 XMind 相关图。 |
| `archive/hook-method-placeholder.drawio` | Hook 方法占位图或用途不明确的图。 |
| `archive/media-security-lab2-empty.drawio` | 空白或占位的媒体安全实验图。 |
| `archive/ros-current-placeholder.drawio` | 原 `ROS.drawio`，为避免大小写文件名冲突而单独保留。 |
| `archive/ros-empty-placeholder.drawio` | 原 `ros.drawio`，空白或占位的 ROS 图。 |
| `archive/test-diagram.drawio` | 测试图。 |

## 维护说明

- 移动或重命名图之前，先检查图中的可见标签或 draw.io XML 内容。
- 新增、移动、重命名或删除图后，需要同步更新本 README。
- 草稿、重复、用途不明确和空白文件先放入 `archive/`，确认后再删除或重新分类。
- 对已被 Git 跟踪的文件使用 `git mv` 移动，便于保留历史记录。
