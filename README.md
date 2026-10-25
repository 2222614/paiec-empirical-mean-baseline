# PAIEC 经验均值 Baseline

Predictive AI Evaluation Competition (PAIEC) 官方经验均值基线的本地复现。

- [比赛提交包](empirical_mean.zip)：内含 `model.py`、官方 README 和 MIT 许可证。
- [官方基线仓库](https://github.com/aims-foundations/paiec_baseline)

算法按 AI 系统完整属性与匿名 `benchmark_id` 筛选已揭晓标签，返回成功比例；没有匹配标签时返回 `0.5`。每次预测只使用当前调用提供的标签。

2026-10-25 本地重新打包检查通过，官方测试 4 项全部通过。合成演示不代表比赛成绩；本地记录显示尚未提交 Codabench，暂无官方分数。

来源版本：`cc88a959c1e5e7462f31a9215baba066ce6d6e2b`。
