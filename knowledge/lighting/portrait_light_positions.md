# 人像九种光位决策表（Portrait Lighting Positions）

> 挂载 DNA-088。管"光的方向角度"，与 DNA-084（光的质感：阴天/硬窗/夜间暖光）叠加使用。
> 核心逻辑：光的角度 → 改变面部明暗分布 → 影响立体感、脸型修饰、氛围。换光如换人。

## 一、水平方向光位（光源相对相机的水平夹角）

| 光位 | 角度 | 面部效果 | 适用 | 英文关键词 |
|---|---|---|---|---|
| 顺光 | 正面 0° | 受光均匀、阴影少、淡化瑕疵、显年轻，立体感弱 | 清新、减龄、还原色彩 | front lighting, flat even illumination, minimal shadows, youthful look |
| 侧顺光(前侧光) | 前侧 ~45° | 增强立体感层次、显瘦，人像主力主光 | 形象照、肖像（最常用） | 45-degree key light, short lighting, dimensional modeling, slimming |
| 侧光 | 正侧 90° | "阴阳脸"强反差，轮廓立体 | 个性、情绪、硬朗 | split lighting, half-lit half-shadow, dramatic contrast |
| 侧逆光 | 侧后 ~135° | 一侧轮廓高光，人物与背景分离，头发有光泽 | 空间感、发丝光 | rim/kicker light from side-back, hair light, subject separation |
| 逆光 | 正后 180° | 全身高光/剪影，氛围感强 | 浪漫、文艺、梦幻 | backlight, silhouette, glowing edge, dreamy halo |

## 二、垂直方向光位

| 光位 | 角度 | 标志性特征 | 适用 | 英文关键词 |
|---|---|---|---|---|
| 蝴蝶光(美人光) | 正上方 ~45° | 鼻底蝴蝶形阴影，瘦脸、鼻下巴立体 | 女性形象、美妆 | butterfly/paramount lighting, shadow under nose, defined cheekbones |
| 顶光 | 头顶正上 | 头顶肩高光，面部阴影重需补光 | 主体分离，慎用单光 | overhead top light, heavy eye-socket shadows, needs fill |
| 底光(鬼光) | 下方由下往上 | 明暗夸张、反常 | 诡异、戏剧化，不日常单用 | under/horror lighting, uplight, eerie unnatural shadows |

## 三、经典变体

**伦勃朗光 (Rembrandt Lighting)**：侧顺光变体，光源前侧 ~45°、略高于眼，在**眼睛下方脸颊（远离光源一侧）形成小三角形光斑**，五官立体，影视/油画质感标配。
- 英文：Rembrandt lighting, triangular highlight on the cheek, painterly classic portrait.

## 四、按目的选光（商业调用）

| 目的 | 推荐光位 |
|---|---|
| 减龄 / 遮瑕疵 | 顺光 |
| 显瘦 / 立体 / 不出错 | 侧顺光、伦勃朗光 |
| 女性美妆 / 高级脸 | 蝴蝶光 |
| 情绪 / 个性 / 硬朗 | 侧光 |
| 梦幻浪漫 / 发丝光 | 逆光、侧逆光 |
| 悬疑 / 戏剧冲突 | 底光、顶光 |

## 五、与 DNA-084 三层叠加法

1. 底层：DNA-084 选定光的质感（柔光/硬光/暖光）；
2. 方向层：DNA-088 选定光的角度（本表）；
3. 表层：product_physics 品类材质（皮肤 SSS / 膏体反光等）。

例：M3 美妆开场压抑 → 平淡阴天顺光（暗淡无立体）；觉醒后 → 蝴蝶光 + 暖金高光（瘦脸立体、高级美人光）。
