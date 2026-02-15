# 自然语言转分镜稿工作流

## 功能描述

将用户的自然语言视频描述转换为结构化的分镜稿，并基于分镜稿生成优化的 Seedance 2.0 提示词。

## 工作流程

### 第一步：解析自然语言输入
分析用户描述中的关键元素：
- 主体（人物、动物、物体等）
- 场景（环境、地点、时间等）
- 动作（主要行为、互动等）
- 情感/氛围（整体感觉、情绪等）
- 技术要求（镜头、运动、风格等）

### 第二步：生成结构化分镜稿
按照标准格式输出分镜信息：
```
镜头序号：主体=XXX | 场景=XXX | 动作=XXX | 机位=XXX | 风格=XXX | 时长=XXX秒 | 备注=XXX
```

### 第三步：转换为 Seedance 2.0 提示词
基于分镜稿生成符合 Seedance 2.0 结构的英文提示词：
```
Subject + Setting → Action → Camera → Style/Lighting → Pacing/Constraints
```

## 使用示例

### 输入示例
"一个穿着红色运动服的女生在日落时的海边奔跑，镜头跟着她移动，展现她追逐梦想的感觉"

### 输出分镜稿
```
镜头1：主体=穿着红色运动服的女生 | 场景=海边日落 | 动作=奔跑 | 机位=跟拍 | 风格=暖色调电影感 | 时长=5秒 | 备注=展现追逐梦想的氛围
```

### 输出 Seedance 提示词
"A young woman in red sportswear running on the beach during sunset, smooth tracking shot following her movement, warm cinematic lighting, inspirational atmosphere, single continuous shot"

### 技术参数建议
- 纵横比：16:9（宽屏电影感）或 9:16（竖屏社交媒体）
- 分辨率：1080p（标准）或 4K（高质量）
- 时长：5-10秒（适合单镜头展示）

## 更多示例

### 示例1：产品展示
**输入**："展示新款智能手机，特写镜头展示外观，然后滑动展示屏幕界面"

**分镜稿**：
```
镜头1：主体=新款智能手机 | 场景=干净背景 | 动作=旋转展示外观 | 机位=特写旋转 | 风格=产品摄影风格 | 时长=3秒 | 备注=突出产品设计

镜头2：主体=智能手机屏幕 | 场景=产品展示环境 | 动作=滑动界面 | 机位=屏幕特写 | 风格=清晰明亮 | 时长=4秒 | 备注=展示UI流畅度
```

**Seedance 提示词**：
"Close-up shot of a new smartphone rotating to showcase design, product photography style, clean studio lighting, smooth rotation, then transition to screen interface with fluid swipe motion, bright and clear display"

### 示例2：品牌吉祥物
**输入**："我们的卡通熊吉祥物在办公室环境中工作，偶尔看向镜头微笑"

**分镜稿**：
```
镜头1：主体=卡通熊吉祥物 | 场景=现代办公室 | 动作=工作并看向镜头 | 机位=中景固定 | 风格=可爱动画风格 | 时长=6秒 | 备注=保持品牌一致性
```

**Seedance 提示词**：
"A cartoon bear mascot in a modern office environment, working at desk and occasionally looking at camera with smile, medium shot with fixed camera, cute animation style, brand colors consistent, character expression stable"

## 高级功能

### 多镜头组合
对于复杂场景，可以生成多个镜头的分镜稿，并提供镜头之间的转场建议。

### 情感关键词映射
将中文情感描述映射到对应的英文风格词：
- 温暖 → warm, soft lighting
- 梦幻 → dreamy, ethereal, mystical
- 紧张 → dramatic, intense, fast-paced
- 平静 → calm, serene, smooth motion

### 适配不同平台
根据发布平台自动调整建议：
- TikTok/Reels：9:16，快节奏，视觉冲击力强
- YouTube：16:9，电影感，更精细的细节
- Instagram：1:1，中心构图，适合静态展示

## 注意事项

1. 保持一个镜头一个主要动作的原则
2. 避免过于复杂的场景描述
3. 明确指定主体，避免歧义
4. 提供足够的上下文但不过度描述
5. 考虑最终使用平台的格式要求