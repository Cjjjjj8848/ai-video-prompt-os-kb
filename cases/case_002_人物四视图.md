# Case 002：人物四视图人物转身表（Midjourney v6.1 奶油亚麻 lookbook）

## 来源
用户提供的 MJ v6.1 character turnaround 双场景提示词（有参考图 / 无参考图）+ 16:9 四竖栏参考图（奶油色亚麻衬衫 + 同色阔腿裤，亮白影棚柔和窗光）。

## 场景 A：有人物素材参考（--cref 锁脸，严格不改参考图）

**中文版**
```
脸部特写参考[你的脸部参考图URL]，全身参考[你的全身参考图URL]，model sheet，4-view character turnaround，均匀分为四个竖栏：第1栏脸部胸像特写，第2栏全身正面，第3栏全身侧面，第4栏全身背面。严格使用参考图中的同一女性——深棕头发盘成发髻、碎发垂颊、金色圆环耳环、双层细金项链、奶油色亚麻oversize衬衫塞进同色高腰百褶阔腿裤、尖头细跟浅口鞋。禁止改动参考图中任何面部特征、五官形状、肤色、痣、发型、配饰与服装颜色。亮白影棚，柔和窗光，地面有柔和窗影投影，高时尚lookbook，照片级写实，8k --cref [你的参考图URL] --cw 100 --ar 16:9 --v 6.1
```

**英文版**
```
Close-up face reference [your face reference image URL], full-body reference [your full-body reference image URL], model sheet, 4-view character turnaround, split into four vertical panels: 1st panel close-up portrait of the face, 2nd panel full-body front view, 3rd panel full-body side view, 4th panel full-body back view. Strictly the same woman from the reference images — brunette hair in a bun with loose face-framing strands, gold hoop earrings, layered thin gold necklaces, oversized cream linen button-down shirt tucked into matching high-waisted pleated wide-leg trousers, pointed stiletto heels. Do NOT alter any facial features, face shape, skin tone, beauty marks, hairstyle, accessories, or garment color from the reference. Bright white studio, soft window sunlight, soft window shadow cast on the floor, high fashion lookbook, photorealistic, 8k --cref [your reference image URL] --cw 100 --ar 16:9 --v 6.1
```

## 场景 B：没有人物素材参考（纯文字锁特征）

**中文版**
```
model sheet，4-view character turnaround，均匀分为四个竖栏：第1栏脸部胸像特写，第2栏全身正面，第3栏全身侧面，第4栏全身背面。四栏必须是同一个女性：25岁左右，橄榄肤色，深棕头发盘成低发髻、几缕碎发垂在脸颊，浓眉、深棕色大眼、立体高鼻梁、饱满裸色嘴唇，左眼下有一颗小痣；佩戴金色圆环耳环与双层细金项链。身穿奶油色亚麻oversize衬衫塞进同色高腰百褶阔腿裤，脚踩米白尖头细跟浅口鞋。所有四栏保持完全相同的发型、五官、配饰、服装颜色与身材比例。亮白影棚，柔和窗光从左侧打入，地面有柔和窗影投影，高时尚lookbook，照片级写实，8k，亚麻材质肌理，oversize垂坠廓形 --ar 16:9 --v 6.1
```

**英文版**
```
model sheet, 4-view character turnaround, split into four vertical panels: 1st panel close-up portrait of the face, 2nd panel full-body front view, 3rd panel full-body side view, 4th panel full-body back view. All four panels must show the SAME woman: around 25 years old, olive skin, dark brown hair in a low bun with a few loose strands framing the face, strong brows, deep brown large eyes, sculpted high nose bridge, full nude lips, a tiny beauty mark under the left eye; wearing gold hoop earrings and a layered thin gold necklace. Dressed in an oversized cream linen button-down shirt tucked into matching high-waisted pleated wide-leg trousers, off-white pointed stiletto pumps. Identical hairstyle, facial features, accessories, garment color and body proportions across all four panels. Bright white studio, soft window sunlight from the left, soft window shadow on the floor, high fashion lookbook, photorealistic, 8k, linen texture, oversize draped silhouette --ar 16:9 --v 6.1
```

## 蒸馏 DNA
- DNA-050（shot）四竖栏人物转身表分屏构图模板（1:3 脸部:全身分配）
- DNA-051（model_rules）Midjourney --cref/--cw 人物一致性锁定参数用法（100 锁脸 / 50-75 保脸换装 / 脸跑偏写死五官两遍）
- DNA-052（lighting）亮白影棚柔和窗光 lookbook 视觉规则（单色系/窗光/地面软投影/材质肌理）

## 评分
- 新颖性 2/2（图像生成端 character sheet 新领域）
- 复用性 2/2（任意人物+任意服装可套）
- 清晰度 1/1
- 总分 5/5（≥4 入库）

## 双场景差异
| 维度 | A・有参考图 | B・无参考图 |
|---|---|---|
| 锁脸手段 | --cref [图] --cw 100 | 文字死写五官+痣+配饰，强调 "same across all panels" |
| 提示词长度 | 短（外观交给参考图） | 长（必须自包含全部识别特征） |
| 风险 | --cw 太低会换脸 | 四栏易跑偏成四个人 |
| 替换位 | 只换 [你的参考图URL] | 换年龄/肤色/五官/服装整段描述 |

## 复用建议
- 影视/游戏角色设定、服装 lookbook、IP 形象建模参考
- 电商模特一致性（跨图保持同一模特脸）
- 后续生图/生视频前的外观锁定前置环节（四视图图 → 九宫格 → Seedance 视频）
