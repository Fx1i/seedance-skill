# 角色 & IP 一致性提示词模板

## 模板 1：超级英雄系列
```
Animate a superhero performing a signature move across different city rooftops while keeping costume, hairstyle, and facial features consistent.
```

### 中文描述
让一个超级英雄在不同城市屋顶表演招牌动作，同时保持服装、发型和面部特征的一致性。

### 优化建议
- 如果角色身份总是跑偏，减少场景多样性：每次生成只用一个环境
- 如果动作看起来僵硬，明确一个机位动作（"slow dolly-in"）+ 一个身体动作（"turns and raises a hand"）
- 使用参考素材：@HeroFace（脸部）、@Outfit（服装）保持一致性

---

## 模板 2：品牌吉祥物
```
Show a brand mascot interacting with multiple environments, such as a park, office, and home, without changing its color palette or expressions.
```

### 中文描述
展示品牌吉祥物在多个环境（如公园、办公室和家庭）中互动，而不改变其色调或表情。

### 优化建议
- 如果吉祥物表情变化过多，明确"consistent facial expression throughout"
- 如果颜色不匹配，添加"brand color palette strictly maintained"
- 使用参考素材：@Mascot（吉祥物设计）、@BrandPack（品牌配色指南）

---

## 模板 3：漫画英雄转型
```
Bring a comic book hero into a new storyline, fighting villains while maintaining outfit, posture, and animation style.
```

### 中文描述
将漫画英雄带入新故事线，与反派战斗，同时保持服装、姿势和动画风格的一致性。

### 优化建议
- 如果动作不一致，明确"maintaining characteristic poses and movements"
- 如果服装细节丢失，添加"detailed outfit texture and patterns preserved"
- 使用参考素材：@HeroCharacter（角色设计）、@CombatMoves（招牌动作）

---

## 模板 4：虚拟偶像
```
Create a virtual idol performing on stage with consistent facial features, hairstyle, and outfit design across multiple dance routines.
```

### 中文描述
创建一个虚拟偶像在舞台上表演，在多个舞蹈套路中保持面部特征、发型和服装设计的一致性。

### 优化建议
- 如果面部特征变化，使用"face locked reference"或"stable facial features"
- 如果舞蹈动作不连贯，添加"smooth transitions between dance moves"
- 使用参考素材：@IdolFace（脸部）、@StageOutfit（演出服装）、@DanceRoutine（舞蹈动作）

---

## 模板 5：动画主角
```
Animate an animated protagonist in different emotional scenes while maintaining body proportions, facial structure, and voice-sync accuracy.
```

### 中文描述
让一个动画主角在不同情感场景中表演，同时保持身体比例、面部结构和口型同步的准确性。

### 优化建议
- 如果口型不准确，添加"accurate lip-sync for dialogue"
- 如果身体比例变化，明确"consistent body proportions and anatomy"
- 使用参考素材：@CharacterDesign（角色设计）、@FaceReference（面部参考）

---

## 模板 6：产品拟人化
```
Create a personified product character interacting with users while maintaining brand colors, product features, and characteristic movements.
```

### 中文描述
创建一个拟人化的产品角色与用户互动，同时保持品牌色彩、产品特征和标志性动作的一致性。

### 优化建议
- 如果产品特征不明显，添加"distinctive product features clearly visible"
- 如果品牌色彩不一致，使用"brand color palette strictly applied"
- 使用参考素材：@ProductDesign（产品设计）、@BrandColors（品牌色彩）、@CharacterMoves（角色动作）