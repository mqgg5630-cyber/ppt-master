<!-- ppt-master-schema: spec-lock/v1 -->
# Execution Lock

## canvas
- viewBox: 0 0 1280 720
- format: PPT 16:9

## communication
- primary_language: zh-Hans
- audience: 风味化学 / 食品科学 / 生物信息方向的学术受众
- objective: 讲清机器学习筛选鲜味肽的技术路线、模型进展与应用
- core_message: 机器学习把鲜味肽筛选从湿实验驱动转为「计算预测 + 实验验证」双轨，准确率超 90%
- consumption_mode: 学术汇报 + 在线下载可编辑 PPTX

## mode
- mode: free design flat

## visual_style
- visual_style: 浅色学术科技风（深海军蓝封面与收束带，白卡软投影，青绿/橙点缀）

## colors
- bg: #F4F6F7
- card: #FFFFFF
- card_shadow: #E3E9ED
- primary_navy: #0B2C47
- navy_block: #123A5A
- accent_teal: #0E8F86
- accent_teal_light: #2FB3A8
- accent_orange: #E8743B
- accent_orange_dark: #B5663A
- body_text: #273742
- weak_text: #6B7C8A
- faint_text: #A3B2BF
- tint_blue: #E8EFF5
- tint_teal: #DFF0EE
- tint_orange: #FBE9DD
- chart_blue: #4F86B2
- chart_lightblue: #8FB3CC
- chart_grey: #B7C3CD

## typography
- font_family: "Microsoft YaHei", "PingFang SC", "Noto Sans CJK SC", Arial, sans-serif
- title_family: "Microsoft YaHei", "PingFang SC", "Noto Sans CJK SC", Arial, sans-serif
- body_family: "Microsoft YaHei", "PingFang SC", "Noto Sans CJK SC", Arial, sans-serif
- hero: 68
- title: 40
- subtitle: 26
- body: 24
- annotation: 24
- data_big: 48
- section_label: 24
- card_heading: 26
- band_heading: 28
- kpi_medium: 32
- kpi_word: 33
- mono_seq: 28
- formula: 28

## icons
- library: tabler-outline
- inventory: flask, database, binary-tree, brain, chart-bar, atom-2, search, bulb, clock, coin, arrow-right, refresh, world, file-text, test-pipe, check, alert-triangle, network, filter, cpu, soup, link, route, award

## page_rhythm
- P01: 封面（深海军蓝 + 受体插画 + 三 KPI）
- P02: 什么是鲜味肽（定义卡 + 受体示意图 + 三特性卡）
- P03: 为什么需要新范式（湿实验流程 + 三痛点 + pain-compare bar + 收束带）
- P04: ML 路线总览（干/湿双泳道流水线 + 反馈回路 + 数学本质）
- P05: 数据构建（三数据源 + 虚拟酶解 + 四级过滤）
- P06: 基准数据集（dataset-table + 数据驱动/不平衡两卡）
- P07: 特征编码（序列→向量 + 手工特征 vs 深度表征）
- P08: 算法谱系（algo-genealogy 三代 + UMPred-FRL 集成带）
- P09: 评价指标（metric-donut 环图 + ACC/MCC/Sn 卡 + 验证协议）
- P10: 模型演进时间线（2020–2025 六节点 + 代际色带）
- P11: 工具与服务器（tools-table + 快速上手三步）
- P12: 准确率对比（acc-compare column + 90% 参考线 + KPI）
- P13: 分子对接（T1R1/T1R3 口袋示意 + 原理/相互作用/工具）
- P14: 腐乳案例（case-peptides 表 + 四步流程 + KPI + 机制）
- P15: 挑战与展望（outlook 插画 + 三挑战 + 展望 + 总结）

## pptx_structure
- mode: flat

## forbidden
- `mask`, `<style>`, `class`, external CSS, `<foreignObject>`, `textPath`, `@font-face`, `<animate*>`, `<set>`, `<script>` / event attributes, `<iframe>`
- HTML named entities in text; write typography as raw Unicode and escape XML reserved characters
- 任何文字字号不得小于 24 px（导出后 ≥18pt）；来源信息只写演讲者备注，不做小字脚注
