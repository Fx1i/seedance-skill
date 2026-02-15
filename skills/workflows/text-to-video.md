# 文本转视频工作流

## 概述

这是使用 Seedance 2.0 进行文本转视频（T2V）的完整工作流程，从初始设置到最终优化，帮助用户快速上手并获得理想结果。

## 工作流程步骤

### 第1步：选择模式

选择 **文本转视频（Text-to-Video）** 工作流（通常缩写为 **T2V**）。

**建议：**
- 初学者优先选择 T2V 模式，因为它是最直接的控制方式
- 如果不需要保证角色高度一致，不要从图片转视频开始
- 在专门的界面中进行测试可以获得最佳结果

### 第2步：设置格式

根据发布平台选择合适的参数：

#### 纵横比选择
- **9:16**：适合 TikTok / Reels / Shorts（竖屏社交内容）
- **16:9**：适合 YouTube 和影院式宽屏构图（横屏内容）
- **1:1**：适合方形信息流（Instagram 帖子）

#### 时长设置
- **5–10秒**：最理想的迭代长度，易于打磨和保持连贯
- 超过15秒的片段容易出现不一致问题
- 初期建议使用较短长度进行快速迭代

#### 分辨率设置
- 迭代阶段：使用标准画质（1080p）
- 最终输出：切换到高画质（4K）
- 注意：高画质生成时间更长

### 第3步：编写提示词

使用提示词配方构建你的提示：

#### 基础公式
**主体 + 场景 → 动作 → 机位 → 风格/光线 → 节奏/约束**

#### 示例构建过程

1. **主体 + 场景**："A young woman in red sportswear on a beach at sunset"
2. **添加动作**："running along the shoreline"
3. **添加机位**："with a smooth tracking shot following her movement"
4. **添加风格**："warm cinematic lighting, inspirational atmosphere"
5. **添加节奏**："single continuous shot, fluid motion"

**最终提示词**：
"A young woman in red sportswear running along the shoreline at sunset, smooth tracking shot following her movement, warm cinematic lighting, inspirational atmosphere, single continuous shot, fluid motion"

### 第4步：生成多个版本

**关键原则**：不要只看一条结果就下结论。

**最佳实践**：
- 一次生成 **2–4 个变体**进行对比
- 对比要点：
  - 哪个版本的主体最符合预期？
  - 哪个版本的机位运动最好？
  - 哪个版本的节奏最合适？
  - 哪个版本的风格最一致？

### 第5步：单变量迭代

**这是让结果变得稳定可靠的最关键习惯。**

**错误做法**：每次把所有东西都改掉
**正确做法**：每次只动**一个杠杆**：

#### 可调整的变量
- **机位运动**：增加或删除一种机位运动
- **动作简化**：减少或修改动作描述
- **风格调整**：替换风格/光线相关的词语
- **节奏控制**：添加"single continuous shot"或"jump cuts"
- **约束条件**：添加负面提示词

#### 示例迭代过程

**初始提示词**：
"A cat knocking over objects with exaggerated reactions, meme-style captions, and quick zooms"

**第一次迭代（只改节奏）**：
"A cat knocking over objects with exaggerated reactions, smooth pacing, and gentle camera movements"

**第二次迭代（只改风格）**：
"A cat knocking over objects with natural reactions, smooth pacing, and gentle camera movements"

**第三次迭代（只改动作）**：
"A cat gently pushing one object with natural reactions, smooth pacing, and gentle camera movements"

## 多模态参考工作流

如果你的界面支持 @AssetName 参考：

### 参考素材命名规范
- `@HeroFace`（角色身份）
- `@Outfit`（服装或盔甲）
- `@CityStreet`（环境）
- `@BrandPack`（品牌 Logo、配色或产品风格指南）
- `@MusicBeat`（节奏锚点）

### 使用场景
- 在多个场景中保持同一个角色
- 固定某张脸/一套服装
- 保持场景布局一致
- 固定某个产品镜头角度

## 常见问题快速修复

### 问题1：主体变化、跑偏
**解决方案**：
- 只保留 **一个主体 + 一个动作**
- 去掉场景切换
- 添加"keep outfit and face consistent"
- 使用参考素材工作流

### 问题2：运动抖动或混乱
**解决方案**：
- 把"dynamic"替换为"smooth"
- 添加"single continuous shot"
- 只指定一个机位运动（或完全不写机位运动）

### 问题3：节奏感觉不对
**解决方案**：
- 短视频：写上"jump cuts between scenes"
- 电影感：写"slow dolly-in, single shot, smooth panning"

### 问题4：竖屏构图不对
**解决方案**：
- 一开始就设置为 **9:16**
- 在提示中加上"centered composition, subject framed for vertical video"

## 练习建议

1. 从提示词库选一条模板
2. 生成 2–4 个变体
3. 只修正**一个问题**（机位、节奏、风格或跑偏）
4. 重复，直到片段稳定、连贯
5. 记录有效的修改组合，形成个人工作库

通过这样练习几轮之后，Seedance 风格的提示词写作就不再像赌运气，而更像一门可以打磨的手艺。