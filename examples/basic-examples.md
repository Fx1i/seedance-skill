# 使用示例

本文档提供各种场景的使用示例，帮助理解剧情到分镜稿生成的过程。

## 示例1：简单故事

### 输入
```
小明在公园散步，看到一只猫，他停下来观察，然后继续走
```

### 输出

```
片段1：
- 预估时长：4秒
- 场景：公园，晴天
- 主体：小明
- 动作：散步
- 机位：跟拍，中景
- 风格：明亮，自然光线
- 备注：展现悠闲散步状态
- AI提示词："Xiaoming walking in a park on a sunny day, medium tracking shot, natural lighting, peaceful atmosphere"

片段2：
- 预估时长：5秒
- 场景：公园草地
- 主体：小明，一只猫
- 动作：停下，观察猫
- 机位：中景转特写
- 风格：温馨，柔和光线
- 备注：停顿动作自然，观察姿态
- AI提示词："Xiaoming stops and observes a cat on the grass, medium shot transitioning to close-up, warm soft lighting, gentle moment"

片段3：
- 预估时长：4秒
- 场景：公园
- 主体：小明
- 动作：继续走
- 机位：跟拍，中景
- 风格：明亮，自然光线
- 备注：保持行走方向一致
- AI提示词："Xiaoming continues walking, medium tracking shot, consistent direction, natural lighting"

分割结果：
- 总片段数：3个
- 总预估时长：13秒
- 平均片段时长：4.3秒
```

---

## 示例2：场景转换

### 输入
```
她在图书馆看书，天黑后离开，走到外面遇到雨
```

### 输出

```
片段1：
- 预估时长：6秒
- 场景：图书馆内部，白天
- 主体：女孩
- 动作：安静看书
- 机位：中景，固定镜头
- 风格：温暖，室内灯光
- 备注：专注阅读状态
- AI提示词："A girl reading quietly in a library, medium shot fixed, warm indoor lighting, focused and peaceful"

片段2：
- 预估时长：4秒
- 场景：图书馆门口
- 主体：女孩
- 动作：收拾东西离开
- 机位：中景，跟拍
- 风格：室内过渡到室外光线
- 备注：准备离开的动作
- AI提示词："The girl gathers her belongings and leaves the library, medium tracking shot, transition from indoor to outdoor lighting"

片段3：
- 预估时长：2秒
- 场景：图书馆外
- 主体：夜空，路灯
- 动作：天色渐暗
- 机位：固定镜头，仰视
- 风格：黄昏光线，氛围变化
- 备注：时间过渡，光线变化
- AI提示词："The sky darkens outside the library, fixed shot looking up, dusk lighting transition, atmospheric change"

片段4：
- 预估时长：5秒
- 场景：街道，雨中
- 主体：女孩，雨滴
- 动作：遇到雨，躲避
- 机位：中景，动态镜头
- 风格：冷色调，雨中氛围
- 备注：光线变化到冷色调
- AI提示词："The girl steps outside and encounters rain, medium shot dynamic movement, cool color palette, rainy atmosphere"

分割结果：
- 总片段数：4个
- 总预估时长：17秒
- 平均片段时长：4.3秒
```

---

## 示例3：复杂动作序列

### 输入
```
角色在城市中追逐，跳过障碍，最后抓住目标
```

### 输出

```
片段1：
- 预估时长：5秒
- 场景：城市街道
- 主体：角色
- 动作：在城市中奔跑
- 机位：跟拍，动态运动
- 风格：紧张，快节奏
- 备注：展现追逐的紧张感
- AI提示词："Character running through city streets, dynamic tracking shot, fast-paced movement, tense atmosphere"

片段2：
- 预估时长：4秒
- 场景：城市障碍物前
- 主体：角色
- 动作：跳过障碍
- 机位：侧面拍摄，中景
- 风格：动态，动作感强
- 备注：跳跃动作的瞬间
- AI提示词："Character jumps over an obstacle, side view medium shot, dynamic action, athletic movement"

片段3：
- 预估时长：5秒
- 场景：城市街道，继续
- 主体：角色
- 动作：继续奔跑
- 机位：跟拍，平滑运动
- 风格：紧张，目标导向
- 备注：保持奔跑动作流畅
- AI提示词："Character continues running with determination, smooth tracking shot, focused movement, intense atmosphere"

片段4：
- 预估时长：3秒
- 场景：目标位置
- 主体：角色，目标
- 动作：抓住目标
- 机位：中景转特写
- 风格：高潮时刻，戏剧性
- 备注：动作的完成
- AI提示词："Character reaches and catches the target, medium shot transitioning to close-up, dramatic moment, climax scene"

分割结果：
- 总片段数：4个
- 总预估时长：17秒
- 平均片段时长：4.3秒
```

---

## 示例4：情感变化场景

### 输入
```
她收到礼物时很开心，打开后发现是旧的，表情变得失望
```

### 输出

```
片段1：
- 预估时长：5秒
- 场景：房间内
- 主体：女孩，礼物盒
- 动作：收到礼物，开心反应
- 机位：特写，聚焦表情
- 风格：温暖，欢快氛围
- 备注：展现开心表情
- AI提示词："Girl receiving a gift box with happy expression, close-up on face, warm lighting, joyful atmosphere"

片段2：
- 预估时长：4秒
- 场景：房间内
- 主体：女孩，礼物盒
- 动作：打开礼物盒
- 机位：中景，固定镜头
- 风格：明亮，期待氛围
- 备注：期待的表情
- AI提示词："Girl opening the gift box, medium shot fixed, bright lighting, expectant expression"

片段3：
- 预估时长：4秒
- 场景：房间内
- 主体：女孩，旧物品
- 动作：发现是旧的，表情变化
- 机位：特写，聚焦表情变化
- 风格：光线渐暗，情绪转折
- 备注：表情从期待到失望的变化
- AI提示词："Girl's expression changes as she sees the old item inside, close-up capturing emotional shift, lighting dims to reflect disappointment"

片段4：
- 预估时长：3秒
- 场景：房间内
- 主体：女孩
- 动作：失望反应
- 机位：特写，固定镜头
- 风格：冷色调，失望氛围
- 备注：保持失望表情
- AI提示词："Girl showing disappointed expression, close-up fixed shot, cool color palette, sad atmosphere"

分割结果：
- 总片段数：4个
- 总预估时长：16秒
- 平均片段时长：4秒
```

---

## 示例5：多角色互动

### 输入
```
小明和小红在餐厅吃晚餐，他们开心地聊天，然后一起离开
```

### 输出

```
片段1：
- 预估时长：6秒
- 场景：餐厅，晚上
- 主体：小明，小红
- 动作：用餐，聊天
- 机位：中景，固定镜头
- 风格：温馨，餐厅灯光
- 备注：展现用餐场景
- AI提示词："Xiaoming and Xiaohong having dinner together in a restaurant at night, medium shot fixed, warm restaurant lighting, pleasant conversation"

片段2：
- 预估时长：4秒
- 场景：餐厅
- 主体：小明，小红
- 动作：开心地聊天
- 机位：中景，轻微摇镜
- 风格：温馨，欢快氛围
- 备注：互动的欢快氛围
- AI提示词："Xiaoming and Xiaohong chatting happily together, medium shot with gentle panning, warm atmosphere, joyful interaction"

片段3：
- 预估时长：3秒
- 场景：餐厅门口
- 主体：小明，小红
- 动作：一起起身，离开
- 机位：跟拍，中景
- 风格：温馨，结束感
- 备注：一起离开的动作
- AI提示词："Xiaoming and Xiaohong stand up and leave together, medium tracking shot, warm ending atmosphere, together movement"

分割结果：
- 总片段数：3个
- 总预估时长：13秒
- 平均片段时长：4.3秒
```

---

## 示例6：时间跳跃

### 输入
```
他在办公室工作到深夜，第二天早上到达公司发现事情解决了
```

### 输出

```
片段1：
- 预估时长：5秒
- 场景：办公室，深夜
- 主体：他
- 动作：工作到深夜
- 机位：中景，固定镜头
- 风格：冷色调，工作氛围
- 备注：展现工作状态
- AI提示词："He is working late in the office at night, medium shot fixed, cool color palette, focused work atmosphere"

片段2：
- 预估时长：2秒
- 场景：办公室，时间过渡
- 主体：环境，时钟
- 动作：时间流逝，天色变化
- 机位：固定镜头，延时效果
- 风格：光线变化，时间感
- 备注：时间跳跃的视觉表现
- AI提示词："Time passing in the office, fixed shot with time-lapse effect, lighting changing from night to dawn, temporal transition"

片段3：
- 预估时长：4秒
- 场景：公司，早晨
- 主体：他
- 动作：到达公司，查看情况
- 机位：中景，跟拍
- 风格：明亮，早晨光线
- 备注：从夜晚到早晨的光线变化
- AI提示词："He arrives at the company in the morning, medium tracking shot, bright morning lighting, new day atmosphere"

片段4：
- 预估时长：4秒
- 场景：公司
- 主体：他
- 动作：发现事情解决了
- 机位：中景转特写
- 风格：轻松，释然氛围
- 备注：表情从严肃到释然
- AI提示词："He discovers the issue has been resolved, medium shot transitioning to close-up showing relief, relaxed atmosphere, positive change"

分割结果：
- 总片段数：4个
- 总预估时长：15秒
- 平均片段时长：3.8秒
```

---

## 使用技巧

### 1. 提供清晰的场景描述
```
✅ 好的输入："一个女孩在海边看日落"
❌ 不好的输入："一个女孩在看东西"
```

### 2. 包含情感信息
```
✅ 好的输入："她开心地看着照片"
❌ 不好的输入："她看着照片"
```

### 3. 描述动作的具体性
```
✅ 好的输入："她快速跑向门"
❌ 不好的输入："她去了门那边"
```

### 4. 明确时间信息
```
✅ 好的输入："早上，他去上班"
❌ 不好的输入："他去上班"
```

### 5. 复杂场景分段处理
```
长剧情可以分段输入：
第一段："她起床，洗漱"
第二段："吃早餐，出门"
第三段："到达公司，开始工作"
```

## 输出解读

### 片段数量
根据剧情复杂度和动作完整性自动确定，通常2-6个片段。

### 时长分布
- 简单动作：3-5秒
- 中等复杂：5-10秒
- 复杂场景：10-15秒
- 场景过渡：2-3秒

### 镜头类型选择
基于动作类型和情感需求自动选择合适的镜头。

### 连贯性要点
"备注"字段中的信息帮助确保片段间的一致性。

## 进阶示例

查看更多示例可以帮助你更好地理解如何描述剧情。建议：
1. 先从简单场景开始
2. 逐步增加复杂度
3. 观察系统如何处理不同类型的剧情
4. 根据输出优化你的输入描述

通过这些示例，你可以学习如何有效地描述剧情，以获得最佳的分镜稿和AI提示词。