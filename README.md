# 投标工具箱（bid-toolkit）

一套**打开就能用**的工程投标在线小工具：不注册、不上传、不开会员，把招标文件或投标文件里的关键项粘进去，当场给出判断。

🌐 在线使用：<https://bid-toolkit.app.workbuddy.host/>

---

## 为什么做这个

工程投标里最容易出事的，从来不是"不会写"，而是**漏项**：

- 招标文件里那条带★的废标红线，翻的时候看到了，做的时候忘了；
- 工程量清单的合计和单价乘不出来，复核时才发现；
- 投标保证金的退还条件写在第 17 页，谁也没翻到；
- 资格审查要求的人员证件，临开标才发现差一本。

这些事的共同点是：**它不需要专业知识，只需要有人逐条对照一遍**。而这个"逐条对照"恰恰是人在赶标时最不会做的事。

所以这套装成了纯前端工具 —— **你粘贴的内容不会离开你的浏览器**，不发请求、不落库、不留存。

## 工具

四个在线自查工具，打开即用，无需注册（链接指向在线版；仓库内有同名源码，可离线跑）：

| 工具 | 解决什么 | 在线使用 |
|---|---|---|
| 废标风险体检 | 45 项废标红线逐条勾选，分「红线 / 高危」两级提示，命中项直接告诉你该改哪一页 | <https://ldm2007-9576.github.io/bid-toolkit/bid-risk-check.html> |
| 资格审查自查 | 营业执照、资质、人员证件、业绩逐项对缺口，标出还差什么 | <https://ldm2007-9576.github.io/bid-toolkit/certcheck.html> |
| 常见废标项检查 | 形式性废标项：签章、份数、密封、有效期、大小写一致性 | <https://ldm2007-9576.github.io/bid-toolkit/failcheck.html> |
| 投标报价测算 | 报价构成与下浮率试算，先算清楚再报价，避免算错签错 | <https://ldm2007-9576.github.io/bid-toolkit/price-calc.html> |

## 指南文章

14 篇，都是能直接照着做的清单，不是概念文章。链接为在线版：

| 指南 | 解决什么 | 在线阅读 |
|---|---|---|
| [投标保证金怎么退](https://ldm2007-9576.github.io/bid-toolkit/guides/bid-deposit-refund.html) | 保证金从缴纳到退回的完整流程：谁退、什么时候退、要什么材料，以及最容易卡住的 6 个环节 | 在线阅读 |
| [投标保证金和保函怎么选](https://ldm2007-9576.github.io/bid-toolkit/guides/bid-bond-vs-deposit.html) | 保函与保证金的成本、资金占用与风险对比，选择看哪四点；保函条款必须核对的项目 | 在线阅读 |
| [开标前 48 小时终审清单](https://ldm2007-9576.github.io/bid-toolkit/guides/pre-bid-48h-checklist.html) | 23 项逐条核对：证照过期、少副本、大小写不一致、CA 锁没带等临门一脚废标项 | 在线阅读 |
| [工程量清单复核怎么做](https://ldm2007-9576.github.io/bid-toolkit/guides/boq-review.html) | 招标清单量与图纸量不一致时怎么核、偏差率怎么算、16 类最常见漏项 | 在线阅读 |
| [评标办法逐条响应表怎么填](https://ldm2007-9576.github.io/bid-toolkit/guides/evaluation-response-table.html) | 把评标办法逐条抄进表格逐条作答，附得分点与高频丢分陷阱 | 在线阅读 |
| [资格审查资料清单](https://ldm2007-9576.github.io/bid-toolkit/guides/qualification-docs.html) | 16 类资料逐条列明要准备什么、怎么盯有效期，另附 8 种常见不合格情形 | 在线阅读 |
| [施工组织设计怎么写](https://ldm2007-9576.github.io/bid-toolkit/guides/construction-organization-design.html) | 标准章节框架、每章该写什么，以及最容易被监理退回的 12 个原因 | 在线阅读 |
| [竣工归档资料怎么组卷](https://ldm2007-9576.github.io/bid-toolkit/guides/completion-archive.html) | 检验批、隐蔽验收、材料报验之间的逻辑关系与常见缺项 | 在线阅读 |
| [投标废标红线 45 项自查](https://ldm2007-9576.github.io/bid-toolkit/guides/bid-rejection-redlines.html) | 把散落在招标文件各处的废标条款整理成五类 45 项，封标前逐条排掉 | 在线阅读 |
| [工程签证与索赔](https://ldm2007-9576.github.io/bid-toolkit/guides/variation-and-claim.html) | 现场签证单该写什么、索赔证据怎么收集、时效怎么盯 | 在线阅读 |
| [投标报价与评标基准价](https://ldm2007-9576.github.io/bid-toolkit/guides/bid-pricing-baseline.html) | 基准价的四种算法、报价三层校验、不平衡报价能用到哪一步为止 | 在线阅读 |
| [工程投标岗位证书怎么配](https://ldm2007-9576.github.io/bid-toolkit/guides/cert-config.html) | 按发证机关分清四套证书体系，别把特种作业当特种设备 | 在线阅读 |
| [投标文件排版与装订](https://ldm2007-9576.github.io/bid-toolkit/guides/doc-format-binding.html) | 暗标怎么排、正副本怎么装、签字盖章最容易漏在哪 | 在线阅读 |
| [电子标上传故障排查](https://ldm2007-9576.github.io/bid-toolkit/guides/ebid-upload-troubleshoot.html) | CA 锁识别不到、签章报错、文件超限、解密超时的三层排查清单 | 在线阅读 |

全部指南目录：<https://ldm2007-9576.github.io/bid-toolkit/guides/>

## 在售清单

`store.html` 是本仓库对应的**在售电子资料清单**（分组 + 价格 + 一句说明）。
它由在架商品真源自动生成，不是手写页面 —— 商品下架或上新时同步重生成，
避免"页面还挂着已下架的商品"这类静默失效。

在线版：<https://ldm2007-9576.github.io/bid-toolkit/store.html>

## 本地运行

纯静态，无构建步骤：

```bash
git clone <本仓库>
cd bid-toolkit
python -m http.server 8000   # 然后打开 http://localhost:8000
```

## 许可证

工具页面与指南文字：MIT（见 [LICENSE](LICENSE)）。

⚠️ 仓库里**不包含**任何资料模板源文件 —— 那些是另售的可编辑成品（Word/Excel/PPT），不在本仓库的授权范围内。

## 说明

工具给出的是**自查提示**，不是法律意见，也不能替代你对招标文件原文的判断。真出争议时，以招标文件原文和评标委员会的认定为准。
