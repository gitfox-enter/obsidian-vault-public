# 日志本 · 公开模板

> 一个基于 Obsidian + PARA + GitHub 的笔记仓库模板。
> 笔记体系参考 B站「爬爬虾」的 Obsidian 教学视频搭建。

---

## 📌 视频教程

[Obsidian邪修用法，免费云同步，AI，手机端，进阶技巧](https://www.bilibili.com/video/BV1fZCyBYEuT)

> UP主：爬爬虾 | 介绍 Obsidian 的笔记体系搭建、免费云同步方案、AI 辅助笔记、手机端适配、进阶技巧

---

## 🚀 快速上手（3 步）

### 第 1 步：克隆到本地

```bash
git clone https://github.com/gitfox-enter/obsidian-vault-public.git my-obsidian-vault
cd my-obsidian-vault
```

### 第 2 步：创建你自己的 GitHub 仓库

1. 登录 GitHub，新建空仓库
2. 仓库名随便（比如 `my-vault`），**不要** 勾选模板文件

### 第 3 步：关联并推送

```bash
git remote set-url origin https://github.com/你的用户名/你的仓库名.git
git add -A
git commit -m "init"
git push -u origin main
```

### 第 4 步：在 Obsidian 里打开

1. 打开 Obsidian → **打开已有仓库** → 选择 clone 的文件夹
2. 安装插件：**Obsidian Git** + **Custom Attachment Location**
3. 配置自动同步

---

## 📁 笔记体系（PARA）

| 目录 | 用途 |
|------|------|
| `0-收件箱/` | 碎片想法，先丢进来 |
| `1-项目/` | 正在做的事，有截止日期 |
| `2-领域/` | 长期关注的方向 |
| `3-资源/` | 知识卡片 + 工具收藏 |
| `4-归档/` | 做完的旧项目 |
| `5-模板/` | 新建笔记的模板 |

---

## ⚙️ 必须安装的插件

| 插件 | 配置要点 |
|------|----------|
| **Obsidian Git** | 设置 GitHub remote，开启自动同步 |
| **Custom Attachment Location** | 路径：`assets/${noteFileName}/${generatedAttachmentFileName}` |

---

## 🔗 相关链接

- 爬爬虾 Obsidian 教程：[BV1fZCyBYEuT](https://www.bilibili.com/video/BV1fZCyBYEuT)
- Obsidian 官网：[obsidian.md](https://obsidian.md)
- PARA 方法：[fortelabs.com/para](https://fortelabs.com/para)
