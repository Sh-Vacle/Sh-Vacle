# Sh-Vacle · 软件开发作品集

中国矿业大学人工智能专业，2027届本科生。面向 Android 研发与通用软件开发岗位，正在学习 Java 后端开发。

项目实践：**Android / Kotlin / Python / 计算机视觉**。精选项目与源码入口如下；Java 后端仍为学习方向。

## 🧭 精选项目

### <img src="assets/autoledger.svg" width="34" alt="AutoLedgerCN项目图标"> 01 · [AutoLedgerCN](https://github.com/Sh-Vacle/AutoLedgerCN)

本地通知记账 Android 应用。Kotlin、Jetpack Compose、Room、DataStore：通知解析、金额过滤、交易指纹与跨来源去重、待确认流程、CSV及统计页面。

重点看：[业务源码](https://github.com/Sh-Vacle/AutoLedgerCN/tree/main/app/src/main/java/com/autoledgercn) · [架构](https://github.com/Sh-Vacle/AutoLedgerCN/blob/main/docs/ARCHITECTURE.md) · [运行与验收](https://github.com/Sh-Vacle/AutoLedgerCN/blob/main/docs/RUNNING.md)。当前源码版本尚未重新构建/实机验收，分类使用本地规则，未接入云AI。

### <img src="assets/video.svg" width="34" alt="campus-violence-recognition项目图标"> 02 · [校园暴力视频识别](https://github.com/Sh-Vacle/campus-violence-recognition)

TensorFlow、MobileNetV2、FFmpeg：视频抽帧、迁移学习、帧级评估、视频概率聚合及TFLite导出。保留共同贡献信息，历史帧级验证指标不作为视频级竞赛成绩。

重点看：[训练与推理源码](https://github.com/Sh-Vacle/campus-violence-recognition/tree/main/src) · [评估口径](https://github.com/Sh-Vacle/campus-violence-recognition/blob/main/docs/EVALUATION.md)。本轮未重新训练或验证设备部署。

### <img src="assets/experiment.svg" width="34" alt="pytorch-nn-compare项目图标"> 03 · [PyTorch 神经网络对比实验](https://github.com/Sh-Vacle/pytorch-nn-compare)

二维合成数据上的MLP组合配置对比，包含训练曲线、决策边界、混淆矩阵与结构化结果。补充算法实验组织与结果解释能力，不作为真实业务数据性能证明。

重点看：[实验入口](https://github.com/Sh-Vacle/pytorch-nn-compare/blob/main/train_compare.py) · [保存结果](https://github.com/Sh-Vacle/pytorch-nn-compare/tree/main/results) · [实验分析](https://github.com/Sh-Vacle/pytorch-nn-compare/blob/main/docs/EXPERIMENT_REPORT.md)。5项CPU数据/结构检查已有通过记录，历史准确率是单seed实验。

## 📬 学习方向与交流

继续学习 Java 后端开发；当前公开仓库尚未提供 Spring Boot、Redis或分布式系统的工程证明。

项目问题与技术交流可在对应仓库提交 Issue；[GitHub 账号](https://github.com/Sh-Vacle)是当前公开专业链接。不公开私人手机号或邮箱，不展示未获公开许可的团队竞赛源码。

## 📝 开发与验证说明

部分开发与整理使用 GPT、Codex 辅助；项目说明以真实源码、实验记录和验证边界为准，不将辅助工具当作技术成果。
