# ICML 2026 Camera-ready 提交流程清单

更新时间：2026-05-18

## 截止时间

- Camera-ready 截止：2026-05-28 23:59 AOE，换算到上海时间约为 2026-05-29 19:59:59。
- In-person Presentation Questionnaire 截止：2026-05-11 23:59 AOE。若尚未填，立即去 OpenReview Author Console / paper forum 检查是否还有补救入口。
- ICML 2026 会后还会开放一次小修窗口，用于根据会议反馈上传小修版本；具体信息会后再公布。

## 提交入口

- 登录 OpenReview。
- 进入 Author Console。
- 找到 ICML 2026 main track paper。
- 进入 paper 对应的 camera-ready form / Author Tasks。
- 上传 PDF、PMLR agreement，并填写 title、abstract、lay summary、paper checker code 等字段。

## 必做文件与表单

- Camera-ready PDF：
  - 必须用 ICML 2026 style file。
  - LaTeX 中使用 `\usepackage[accepted]{icml2026}`。
  - 必须是 US letter，不是 A4。
  - PDF 总大小不超过 20MB，包含 appendices。
  - 正文 main body 最多 9 页；后面接 acknowledgements、impact statement、references、appendices。
  - Main track 必须有 impact statement；position track 不要求。
  - Appendices 必须放在同一个 camera-ready PDF 中；没有 camera-ready supplementary material。

- PMLR Publication Agreement：
  - 每篇 paper 需要一份。
  - 由 corresponding author 填写并签署。
  - 作为 OpenReview camera-ready form 的一部分上传。
  - Agreement 文件最大 10MB。

- ICML consent forms：
  - 至少一名作者需要在 icml.cc 上数字签署 ICML 2026 Publishing Release form。
  - 如果是 oral presentation，做 oral 的作者还需要签 ICML 2026 Recording Release and License form。
  - 入口：https://icml.cc/ConsentForm

- Lay summary：
  - OpenReview form 中需要填写 plain language / lay summary。

- Registration 覆盖：
  - 线下展示 paper：至少一名作者必须注册，并在 Sessions 勾选 "Conference"；Virtual Pass 不够。
  - Proceedings-only paper：至少一名作者注册 "Conference" 或 "Virtual Pass" 即可。

## PDF 内容检查

- 去匿名化：camera-ready 是 non-anonymized 版本，应显示真实作者、机构、致谢等。
- 作者列表：
  - 可调整作者顺序。
  - 不允许新增或删除作者。
  - OpenReview author order、PDF author order 要一致。
  - OpenReview profiles 的 affiliation 要与 camera-ready PDF 中一致。
- Title / abstract：
  - 可小幅调整。
  - 大幅改 title 需要向 program chairs 申请许可。
  - OpenReview form 中的 title、abstract 要和 PDF 完全匹配。
  - Abstract 应为单段，建议 4-6 句。
  - OpenReview 的 title/abstract 可少量用 TeX math，但不要用自定义宏或其他 TeX 命令。
- 引用：
  - 尽量用 peer-reviewed 版本替代 arXiv citation。
  - 检查 OpenReview decision 中 Reference Correctness Check 提到的问题。
  - BibTeX 中专有名词大小写用花括号保护，如 `{Markov}`。
- Conflict of Interest Disclosure：
  - 如果存在可能影响工作的财务或实质性 COI，在 Introduction 末尾加一段，标题为 `Conflict of Interest Disclosure`。
  - 典型情况：论文评估/推广某公司开发的模型，而作者受雇于该公司。
  - 仅仅有作者受雇于企业本身不构成 COI；如果没有要披露的 COI，不要加这一段。
- 格式：
  - Title 和 section headings 用 Title Case，不要全大写。
  - 后续页面 running title 不能空，也不能保留示例标题。
  - citation font size 要和正文一致。
  - 不要用 MacOS Preview 或其他会改 margin 的工具处理 PDF。

## Paper checker

- 入口：https://papercheck.icml.cc/papercheck.html
- 上传 camera-ready PDF。
- 成功后会得到一个 5-letter submission code。
- 这个 code 只对该 paper id + 该 PDF 的精确组合有效；改 PDF 后要重新跑 checker。
- 将 5-letter code 填入 OpenReview camera-ready form。

## 推荐执行顺序

1. 确认 paper 是 in-person 还是 proceedings-only，并确认谁负责注册覆盖。
2. 用 ICML 2026 style file 重新编译 accepted 版本。
3. 加入作者信息、affiliation、acknowledgements、impact statement、appendices。
4. 检查 COI 是否需要披露。
5. 修正 references 和 title/abstract/capitalization。
6. 压缩 PDF 到 20MB 以内。
7. 跑 paper checker，拿到 5-letter code。
8. 对应作者签 PMLR Publication Agreement。
9. 在 icml.cc/ConsentForm 签 publishing release / recording release。
10. 在 OpenReview camera-ready form 上传 PDF 和 agreement，填写全部字段并提交。
11. 提交后下载/截图确认页面，留存提交时间和文件版本。

## 官方来源

- Author Instructions: https://icml.cc/Conferences/2026/AuthorInstructions
- Paper Checker: https://papercheck.icml.cc/papercheck.html
- PMLR Publication Agreement: https://proceedings.mlr.press/pmlr-license-agreement.html
- Consent Form: https://icml.cc/ConsentForm
