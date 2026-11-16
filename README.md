# 西北师范大学化学博士论文格式技能

用于创建论文排版模板、给已有稿件套用格式，以及检查 Word、PDF、LaTeX 论文的格式。技能名：`nwnu-doctor-thesis-format`。

## 功能

- 以西北师大校级规范作为页面、字体、段落和题注的排版基线。
- 用现行学位论文国标补充缺项，区分明确要求、推荐做法与示例。
- 对校规与国标的差异保留出处和待确认项，避免静默覆盖。
- 检查化学式上下标、单位、谱图、图表、文内引用和参考文献。
- 修改时保留原稿，另存副本；只要求审查时不改动文件。

这是社区整理的辅助技能，非西北师范大学官方发布或认证的论文模板。实际提交应核对当届研究生院及学院要求。

## 安装

下载仓库，将整个目录命名为 `nwnu-doctor-thesis-format`，放入 Codex 的用户技能目录：

- Windows：`%USERPROFILE%\.codex\skills\nwnu-doctor-thesis-format`
- macOS / Linux：`~/.codex/skills/nwnu-doctor-thesis-format`
- 自定义了 `CODEX_HOME` 时：`$CODEX_HOME/skills/nwnu-doctor-thesis-format`

安装后检查该目录下直接存在 `SKILL.md`，不要额外嵌套一层仓库目录。已有同名技能时，先保留备份再更新。

## 使用

附上待处理论文后，可直接输入：

```text
用 $nwnu-doctor-thesis-format 检查这份化学博士论文，只列格式问题。
```

```text
用 $nwnu-doctor-thesis-format 给这份Word套格式，保留原稿，另存副本。
```

```text
用 $nwnu-doctor-thesis-format 做一个化学博士论文Word空白模板。
```

若已确定，请同时说明提交阶段（盲审、答辩或归档），并提供学院最新通知或模板。未确定时仍可完成通用排版，但不会自动删除身份信息或生成签名。

技能提供规则和工作流程；实际编辑、渲染与排版验证需要运行环境具备相应文档工具。PDF外观检查不能替代Word源文件样式检查。

## 文件

```text
SKILL.md                  适用范围和执行流程
agents/openai.yaml        技能名称和调用提示
references/rules.md       排版参数、来源及差异处理
references/chemistry.md   化学论文专项检查
```

## 依据和版本

规则核验日期为 **2026-11-12**：

1. [西北师范大学研究生学位论文撰写格式及印制规格的规定](https://glxy.nwnu.edu.cn/_upload/article/files/ac/56/2990397b4cc0b6088382649052ad/2de72e0e-fe20-4af8-9c8f-ffc6ee839595.pdf)，2020年3月修订版。
2. [GB/T 7713.1—2025 信息与文献 编写规则 第1部分：学位论文](https://openstd.samr.gov.cn/bzgk/std/newGbInfo?hcno=36C05B5738C54D42B4B262525320B52F)，2026年2月1日实施。
3. [GB/T 7714—2025 信息与文献 参考文献著录规则](https://openstd.samr.gov.cn/bzgk/std/newGbInfo?hcno=C6CE52E55AC09B9C79A20AEA77CEDD14)，2026年7月1日实施。

未核实存在更新的化学化工学院专用模板。GB/T 7714—2025的现行状态已核实，技能未逐条内置其全部著录规则；执行文献转换时需查阅正文与学院采用口径。

仓库保留来源链接，不分发国标全文、学校徽标或字体素材。仓库也不包含论文原稿、科研数据、个人审查记录或真实签名。
