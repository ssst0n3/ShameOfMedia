# 媒体耻辱柱

近期常读到一些新闻，作者为了得出他们的结论，通过提供不可信信息、使用春秋笔法或滥用统计学技巧曲解消息，侮辱读者智商。

于是我希望为这些作者和媒体建立一个可信度指标，为出现上述行为的作者和媒体扣分。扣满一定分值，则拉黑进入耻辱柱。

| 类型 | 问题 | 分值 | 说明 |
| --- | --- | --- | --- |
| 事实错误 | | -1 | 非主观意愿或因对领域知识不了解 |
| 夸大事实 | 标题党 | -1 | 为了传播效果夸大事实 |
| 歪曲事实 | 春秋笔法 | -2 | 已知事实，主观故意曲解，情节恶劣 |
| | 滥用统计学技术 | -2 |
| 观点之争 | - | 0 | 观点不同是常有之事，只要论据无事实问题，不在本项目考虑范围内 |

当前仅收集数据，下一步再开发web可视化应用。

## template

数据使用yaml在git仓库中存储：

```yaml
title: x
link: 
- x
source: x 
author:
- x
organization: x
tag:
- x
reason: |
  x
reporter:
- x
```
