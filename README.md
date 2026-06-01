# pptx-normalizer

> WorkBuddy AI 助手技能：统一 PPT 格式

一键去除 PowerPoint 中所有动画、禁用自动播放、统一字体为微软雅黑。

## 功能

- ✅ 移除所有幻灯片切换动画
- ✅ 禁用自动播放——所有幻灯片改为点击手动切换
- ✅ 全文字体统一为**微软雅黑**（文本框、表格）
- ✅ 自动备份原文件为 `.bak`

## 安装

```bash
pip install python-pptx
```

## 使用

```bash
python3 scripts/normalize.py <input.pptx> [output.pptx]
```

不指定输出文件时，将覆盖原文件（自动备份为 `.pptx.bak`）。

## 作为 WorkBuddy Skill 使用

```bash
cp -r . ~/.workbuddy/skills/pptx-normalizer/
```

## 许可

MIT
