# 验证测试输出

## 测试输入
> 唐太宗因魏征直谏被顶撞，赐尚方宝剑给李靖平定突厥，长孙无忌反对，皇帝朝堂驳斥，李靖接剑后在军营部署。

## 五段拆解
- ① 触发决定（0-2s）：皇帝被魏征顶撞后震怒，命赐尚方宝剑"平定突厥，先斩后奏"
- ② 反对发酵（2-5s）：长孙无忌殿外听闻，暗中联络御史
- ③ 正面交锋（5-9s）：御史弹劾违反三省制，皇帝怒斥群臣不思开疆
- ④ 转折真相（9-12s）：李靖接剑以为问责，实际是放权平突厥
- ⑤ 高潮决议（12-15s）：李靖部署军务，众将响应

## H3 T2VA 输出

```
integrated_multimodal_description: [Shot 1] AI-generated photorealistic digital-human period drama, cinematic lighting, high contrast, an extreme close-up fills the frame with the Tang emperor's angry eyes, golden crown glinting at the frame edge. The emperor (S1) says: <d>[Chinese] 魏征敢当庭顶撞朕，这朝堂还有没有规矩！</d> [Shot 2] At 00:01.500, the camera cuts to a medium shot of the eunuch kneeling in the candlelit study. The eunuch (S4) says: <d>[Chinese] 奴婢在。</d> The emperor (S1) says: <d>[Chinese] 取尚方宝剑，赐李靖，平定突厥，先斩后奏。</d> [Shot 3] At 00:03.000, the shot cuts to a low-angle medium shot outside the palace corridor, the grand councilor Zhangsun Wuji in dark purple robes stands in shadow, face half-lit. Zhangsun Wuji (S2) mutters: <d>[Chinese] 尚方宝剑？皇上这是要架空三省啊。</d> [Shot 4] At 00:04.500, a close-up of Zhangsun Wuji's hand gripping a jade belt pendant tightly. He says: <d>[Chinese] 让御史台准备上奏。</d> [Shot 5] At 00:06.000, the shot cuts to a wide shot of the Tang throne hall, red pillars and golden dragon screens, officials in two rows. The censor (S2) kneels forward: <d>[Chinese] 陛下！尚方宝剑赐武将，有违三省六部之制，臣不敢奉诏！</d> [Shot 6] At 00:07.500, the camera pushes in with small amplitude at slow speed toward the emperor's face as he stands. The emperor (S1) says: <d>[Chinese] 三省之制？突厥犯边十年，你们不思开疆拓土，只会拿制度压人！</d> [Shot 7] At 00:09.000, an extreme close-up of the emperor's resolute eyes. The emperor (S1) says: <d>[Chinese] 李靖能定北疆，他就是标准。有本事，你们也去边关！</d> [Shot 8] At 00:10.500, the shot cuts to a medium shot in the military tent, General Li Jing in iron armor before a map, expression grave. The messenger (S4) presents the sword: <d>[Chinese] 将军，陛下赐尚方宝剑。</d> Li Jing (S3) says: <d>[Chinese] 可是陛下要问责于我？</d> [Shot 9] At 00:12.000, a close-up of Li Jing's hands receiving the sword, the blade gleaming. His eyes widen. The messenger (S4) says: <d>[Chinese] 陛下口谕：平定突厥，先斩后奏，不必请旨。</d> [Shot 10] At 00:13.500, the camera cuts to a medium shot of Li Jing facing his generals, sword raised. Li Jing (S3) says: <d>[Chinese] 陛下如此信任，我李靖定踏平突厥！诸将听令，整军出发！</d> The generals (S5) shout: <d>[Chinese] 得令！</d>

overall_soundscape: Candle flames crackle in the quiet study while silk robes rustle. Outside, cold wind sweeps the palace corridor. In the throne hall, voices echo off the high ceiling and the emperor's fist strikes the armrest with a heavy thud. In the military tent, armor clinks, the sword blade rings as it is drawn, and fists pound the wooden table in unison.

non_diegetic_music: Low war drums at a slow, menacing tempo open, joined by soaring pipa strings that rise in tension during the court debate. At the emperor's outburst, a full orchestral hit with gong crashes peaks, then resolves into a heroic flute melody over marching drums as the general accepts the sword, building to a final triumphant chord.
```

## 验证清单
- [x] 五段结构完整
- [x] 人物 archetype：皇帝(S1)/权臣(S2)/忠将(S3)/内侍(S4)/部将(S5)
- [x] 眼部特写 ×2，面部特写 ×2，手部特写 ×1，全景 ×1，低角度 ×1，推镜头 ×1
- [x] 自称体系：朕/奴婢/臣/我李靖/得令
- [x] 反问句："可是陛下要问责于我？"
- [x] 时间码严格递增 0:01.5 → 0:03.0 → 0:04.5 → 0:06.0 → 0:07.5 → 0:09.0 → 0:10.5 → 0:12.0 → 0:13.5
- [x] H3 三字段齐全，格式正确
- [x] 英文正文 + 中文对白
- [x] overall_soundscape 不重复对白
