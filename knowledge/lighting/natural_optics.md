# 三态环境光源库（Natural Optics Library）

> 挂载DNA-084，阶段2分镜卡片按品类母题自动勾选。

## 光源A：平淡阴天光（杀3D/去油光最强）

**Prompt核心**：
Flat, completely non-directional overcast natural daylight, zero specular highlights, zero shiny reflections, light fully absorbed by matte surfaces.

**适用品类**：
- 服饰面料展示（亚麻/棉/针织）
- 日常真实生活切片
- 极简生活用品
- 任何需要消灭塑料高光的场景

**效果**：彻底去除CG感，光线完全被材质吸收，无油光无镜面反射。

---

## 光源B：单侧硬窗光（凸显毛孔与质感深度）

**Prompt核心**：
Hard directional natural side-lighting (un-diffused window light effect), high-contrast half-lit and half-shadow, revealing micro-shadows inside pores and wrinkles.

**适用品类**：
- 美妆个护对比（上妆前后）
- 3C机械金属倒角高光
- 强痛点面部表情特写
- 手部微距操作

**效果**：半明半暗，毛孔微阴影可见，立体感强。

---

## 光源C：夜间暖环境光（节日氛围与高级低调）

**Prompt核心**：
Warm low-light ambient environment (2700K-3200K tungsten glow), soft optical lens flares around point lights, realistic deep shadows with natural ISO luminance noise.

**适用品类**：
- 圣诞投影灯/节日氛围
- 香氛/烛光场景
- 夜间汽车座舱
- 家居温馨TVC
- 酒吧/夜店/派对场景

**效果**：暖色钨丝灯调，点光源柔焦光晕，暗部带自然噪点。

---

## 光学母版代码（阶段3强制注入）

```
Shot on iPhone primary camera (26mm f/1.8), raw unedited candid mobile photo aesthetic, natural native ISO sensor noise and organic grain, authentic dynamic range, mild optical lens distortion, zero 8k hyper-sharpening, zero 3D CGI gloss, zero beauty airbrushing.
```

---

## 光源选择决策表（商业母题×光学场景联动）

| 母题 | 开场光 | 转折光 | 终点光 | 原因 |
|---|---|---|---|---|
| M1 痛点消解 | 光源B硬窗光（凸显狼狈） | 光源B硬窗光 | 光源A阴天光（干净秩序） | 痛点需要硬光放大惨状，解决后回归柔和 |
| M2 感官ASMR | 光源A阴天光（去油光显材质） | 光源A阴天光 | 光源A阴天光 | 材质展示不需要戏剧性光影，要纯净 |
| M3 状态跃迁 | 光源A阴天光（脸色暗淡死白） | 光源B/C高光漫射（觉醒） | 光源C暖光（从容掌控） | 哑光死白→高光折射，反差最大 |
| M4 空间重构 | 光源C暗调现实 | 光源C爆发光 | 光源C暖光（家庭温馨） | 暗→亮裂变，全程暖调 |

---

## 模型光学字典映射（Compiler Dict）

| 目标模型 | 禁用词 | 替换词 |
|---|---|---|
| Seedance/Runway | 8k, masterpiece, hyper-detailed, octane render | Shot on iPhone, natural ISO noise, organic grain, zero CGI gloss |
| libTV/Kling | 8k hyper-sharpening | Shot on iPhone 11 (26mm f/1.8), raw unedited candid, authentic dynamic range |

---

## 三层堆叠法（美妆品类叠加规则）

美妆/护肤品类阶段3输出时，三层必须叠加，不可二选一：

1. **底层（DNA-084传感器）**：iPhone真实噪点+镜头轻微色散+光学母版代码
2. **中层（光源库）**：单侧硬窗光（凸显毛孔微阴影与面部真实结构）
3. **表层（product_physics/beauty_skincare.md）**：次表面散射SSS+膏体切面湿润微反光+水光折射带
