# 示例输出

## 用户输入（简略剧情）

> 万历皇帝因张居正改革受阻，赐密诏给戚继光整肃军务，文官集团反对，皇帝朝堂驳斥，戚继光接诏后在军营部署。

---

## 生成的 H3 T2VA 提示词（15秒）

```
integrated_multimodal_description: [Shot 1] AI-generated photorealistic digital-human period drama, cinematic lighting, high contrast, an extreme close-up fills the frame with the young emperor's furious eyes, golden imperial crown visible at the edge of frame. The camera holds static as the emperor (S1) says through gritted teeth: <d>[Chinese] 改革到了这一步，谁敢拦？</d> [Shot 2] At 00:01.500, the camera cuts to a medium shot of the eunuch kneeling in the dimly lit study, scrolls and candleholders on the desk. The eunuch (S4) says: <d>[Chinese] 奴婢在。</d> The emperor (S1) says off-screen: <d>[Chinese] 把这道密诏赐给戚继光，整肃军务，便宜行事。</d> [Shot 3] At 00:03.000, the shot cuts to a low-angle medium shot outside the palace steps, the elderly grand secretary in deep purple robes kneels in shadow, his face half-lit by cold sunlight. The grand secretary (S2) mutters: <d>[Chinese] 皇上这是要把文官都踩在脚下啊。</d> [Shot 4] At 00:04.500, the camera cuts to a close-up of the grand secretary's hand tightening around a memorial, veins visible. He says: <d>[Chinese] 传我的话，让都察院的人准备上奏。</d> [Shot 5] At 00:06.000, the shot cuts to a wide shot of the grand throne hall, red pillars and golden dragon carvings, officials lined in two rows. The censor (S2) steps forward and kneels: <d>[Chinese] 陛下！戚继光一介武将，手握便宜行事之权，有违祖制！</d> [Shot 6] At 00:07.500, the camera pushes in with small amplitude at slow speed toward the emperor's face as he rises from the dragon throne. The emperor (S1) says: <d>[Chinese] 祖制？我大明边患不断，你们不思强国，只知拿祖制压人！</d> [Shot 7] At 00:09.000, an extreme close-up of the emperor's eyes, sharp and resolute. The emperor (S1) says: <d>[Chinese] 戚继光能平倭患，他就是标准。有本事，你们也去！</d> [Shot 8] At 00:10.500, the shot cuts to a medium shot in the military tent, the seasoned general Qi Jiguang in iron armor stands before a sheepskin map, his expression heavy. The messenger (S4) hands over a sealed scroll: <d>[Chinese] 将军，陛下密诏。</d> Qi Jiguang (S3) says: <d>[Chinese] 可是又要催我撤军？</d> [Shot 9] At 00:12.000, a close-up of Qi Jiguang's hands opening the scroll, the characters "整肃军务，便宜行事" visible. His eyes widen. The messenger (S4) says: <d>[Chinese] 陛下说，以后军务不决，不必请旨。</d> [Shot 10] At 00:13.500, the camera cuts to a medium shot of Qi Jiguang facing his generals around the map, fist pounding the table. Qi Jiguang (S3) says: <d>[Chinese] 陛下如此信任，我戚家军定不负圣恩！整肃军务，从今日起！</d> The generals (S5) shout together: <d>[Chinese] 谨遵将令！</d>

overall_soundscape: Candle flames crackle in the quiet study while silk robes rustle with each movement. Outside, cold wind sweeps the stone steps. In the throne hall, voices echo off the high ceiling and the emperor's fist strikes the armrest with a heavy thud. In the military tent, armor clinks as the general steps forward and the scroll unfolds with a sharp paper sound, followed by fists pounding the wooden table in unison.

non_diegetic_music: Low taiko drums at a slow, menacing tempo open the piece, joined by sustained erhu strings that rise in tension during the court debate. At the emperor's outburst, a full orchestral hit with gong crashes peaks, then resolves into a determined bamboo flute melody over marching drums as the general accepts the edict, building to a final triumphant chord.
```

---

## 拆解说明

### 五段映射
| 阶段 | 时间 | 镜头 | 内容 |
|---|---|---|---|
| ① 触发决定 | 0-3s | Shot 1-2 | 皇帝震怒，命赐密诏戚继光 |
| ② 反对发酵 | 3-6s | Shot 3-4 | 首辅暗中联络言官 |
| ③ 正面交锋 | 6-10.5s | Shot 5-7 | 言官弹劾，皇帝怒斥群臣 |
| ④ 转折真相 | 10.5-13.5s | Shot 8-9 | 戚继光以为撤军，实际是放权 |
| ⑤ 高潮决议 | 13.5-15s | Shot 10 | 戚继光部署，众将响应 |

### 运镜分布
- 眼部大特写 ×2（Shot 1, Shot 7）
- 面部特写 ×2（Shot 6 推近, Shot 9）
- 中景 ×4（Shot 2, Shot 5, Shot 8, Shot 10）
- 低角度 ×1（Shot 3）
- 手部特写 ×1（Shot 4）
- 全景 ×1（Shot 5）
- 推镜头 ×1（Shot 6）

### 人物 archetype
- (S1) 皇帝 = 主角（明君）
- (S2) 首辅/言官 = 权臣/直臣（反对势力）
- (S3) 戚继光 = 忠将
- (S4) 太监/信使 = 内侍
- (S5) 部将 = 群像

### 对白特征
- 自称：朕/奴婢/臣/我戚家军/末将
- 反问："可是又要催我撤军？"
- 怒斥："你们不思强国，只知拿祖制压人！"
- 决断："整肃军务，从今日起！"
- 短句为主，一句一镜头
