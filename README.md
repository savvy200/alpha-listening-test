# 10 Hz Listening Test · 欢迎加入测试

欢迎体验两种不同风格的 **10 Hz 双耳节拍音乐**（A、B），分享主观放松感、舒适度及试听建议。

> **非医疗声明**：本项目为自愿试听与主观体验交流，不是临床试验、医疗器械或疾病治疗。现有研究不能证明本项目的两段音频可治疗或延缓 ALS（渐冻症）、脑卒中等疾病。请勿代替规范诊疗或康复。

## 网站

启用 GitHub Pages 之后访问：

**https://savvy200.github.io/alpha-listening-test/**

本仓库完全独立，不影响其他项目。

## 文件结构

- `docs/index.html` — 公开试听页面、临床证据对照表和文献
- `docs/audio/track-a.mp3` — A 音轨，5 分钟，立体声（需独立上传）
- `docs/audio/track-b.mp3` — B 音轨，5 分钟，立体声（需独立上传）
- `.github/ISSUE_TEMPLATE/audio-feedback.yml` — GitHub 试听反馈模板

### 启用 GitHub Pages

在仓库 **Settings → Pages → Build and deployment** 中设置：**Deploy from a branch**，`main`，`/docs`，保存。发布前应确认两个MP3文件均已上传。

音频必须使用立体声耳机才能分别向左右耳送入200 Hz和210 Hz。10 Hz指左右声道的**听觉频差**，不能由此推断脑电活动已经同步到10 Hz。

## 临床证据及限制

| 情境或疾病 | 研究发现 | 干预方式 | 适用于本项目的程度 |
|---|---|---|---|
| 围手术期焦虑及疼痛 | 61人随机试验发现部分焦虑和疼痛评分下降 [1] | 双耳节拍声音 | 存在相关研究，但场景不同 |
| 急性疼痛 | 16项试验的系统综述提示一些初步积极结果，证据质量低至很低 [2] | 不同频段的双耳节拍 | 仍属探索 |
| 慢性疼痛 | 结果不足以确认临床有效性 [2] | 双耳节拍 | 证据不足 |
| 脑卒中 Stroke | 27名完成试验者的研究显示，双耳节拍与康复训练相结合时部分生活活动及情绪评分改善 [3] | 双耳节拍＋康复 | 不能据此证明单独听本音频有康复疗效 |
| 渐冻症 ALS | 30人随机试验中，主动音乐治疗组整体生活质量评分有改善信号 [4] | **主动音乐治疗**，非双耳节拍 | 仅间接参考 |
| 睡眠问题、抑郁和PTSD | 方法、频率和结论不一致 | 声音、神经反馈、电刺激等 | 不能用来证明本音频治疗疾病 |
| 帕金森病、阿尔茨海默病、癫痫 | 部分研究使用其他节律或不同干预 | EEG反馈、tACS等 | 缺乏本音频直接证据 |

### 参考文献

1. Loong LJ, et al. (2022). *The Effect of Binaural Beat Audio on Operative Pain and Anxiety in Cataract Surgery under Topical Anaesthesia: A Randomized Controlled Trial.* [PubMed](https://pubmed.ncbi.nlm.nih.gov/36011825/).
2. Shamsi F, et al. (2024). *Does brain entrainment using binaural auditory beats affect pain perception in acute and chronic pain?: a systematic review.* [PubMed](https://pubmed.ncbi.nlm.nih.gov/38216943/).
3. Chen R, et al. (2025). *Effects of Auditory Frequency Stimulation on Balance and Rehabilitation Outcomes in Patients With Stroke: A Randomized Case-Control Study.* [PubMed](https://pubmed.ncbi.nlm.nih.gov/40621706/).
4. Raglio A, et al. (2016). *Active music therapy approach in amyotrophic lateral sclerosis: a randomized-controlled trial.* [PubMed](https://pubmed.ncbi.nlm.nih.gov/27437724/).
5. (2023). *Binaural beats to entrain the brain? A systematic review.* [PLOS ONE](https://doi.org/10.1371/journal.pone.0286023).

参考研究均**未验证本项目的A/B音轨**。

## 试听安全与隐私

请低音量起步，使用立体声耳机，感到头痛、耳鸣、眩晕或不适立即停止。对使用呼吸机、监护设备的人，不要遮挡设备警报或照护者声音；需要时请照护人员协助。

提交 GitHub Issues 需要 GitHub 账号，用户名与文字反馈会公开。**请勿提供病历、诊断、联系方式或其他健康敏感信息**。反馈不构成临床疗效证据。

本项目未声明开放源码或音乐再利用许可，请勿未经授权传播。
