# 日志本 · 公开模板

> 一个基于 Obsidian + PARA + GitHub 的笔记仓库模板。
> 原始教程来自 **B站「爬爬虾」**，本仓库参照其笔记体系搭建。
> 
> **这不是用来 fork 的，是用来 clone 的。** 复制到你自己的 GitHub，然后改成你自己的笔记仓库。

---

## 📌 视频教程

| 来源 | 链接 |
|------|------|
| B站 UP主 | **爬爬虾** |
| Obsidian 邪修用法 | [B站搜索「爬爬虾 Obsidian」](https://search.bilibili.com/all?keyword=%E7%88%AC%E7%88%AC%E8%9B%BE%20Obsidian) |

本仓库的笔记体系（PARA 目录结构、Obsidian Git 同步方案、图片管理规范等）均参考自爬爬虾的教学视频。

---

## 🚀 快速上手（3 步）

### 第 1 步：克隆到本地

```bash
git clone https://github.com/gitfox-enter/obsidian-vault-public.git my-obsidian-vault
cd my-obsidian-vault
```

### 第 2 步：创建你自己的 GitHub 仓库

1. 登录你的 GitHub 账号
2. 新建一个仓库，仓库名随便（比如 `my-vault`），**不要** 勾选任何模板文件
3. 创建后，你会看到类似这样的地址：
   ```
   https://github.com/你的用户名/my-vault.git
   ```

### 第 3 步：关联到你自己的仓库并推送

```bash
# 把 remote 从我的改成你的
git remote set-url origin https://github.com/你的用户名/my-vault.git

# 推送过去
git add -A
git commit -m "init"
git push -u origin main
```

### 第 4 步：在 Obsidian 里打开

1. 打开 Obsidian
2. **打开已有仓库** → 选择你刚 clone 的 `my-obsidian-vault` 文件夹
3. 安装插件：**Obsidian Git**（核心）+ **Custom Attachment Location**（图片管理）
4. 在 Obsidian Git 设置里，填上你刚才创建的 GitHub 仓库地址，设置自动同步

> 现在这个仓库就是你的了，可以开始往里写笔记。

---

## 📁 笔记体系（PARA）

本仓库基于 Tiago Forte 的 PARA 方法，结构如下：

| 目录 | 用途 | 新建方法 |
|------|------|----------|
| `0-收件箱/` | 碎片想法，先丢进来 | 新建笔记，写完再归类 |
| `1-项目/` | 正在做的事，有截止日期 | 复制 `5-模板/项目卡片.md` |
| `2-领域/` | 长期关注的方向 | 每领域一篇笔记 |
| `3-资源/` | 知识卡片 + 工具收藏 | 复制 `5-模板/知识卡片.md` |
| `4-归档/` | 做完的旧项目 | 从 1-项目 移动过来 |
| `5-模板/` | 新建笔记时的模板 | 别动它，用来复制 |

**每天写日记**：
- 用 Obsidian 内置的「每日笔记」插件，自动生成 `每日笔记/2026-08-01.md`

---

## ⚙️ 技术栈

| 组件 | 工具 | 用途 |
|------|------|------|
| 笔记软件 | **Obsidian** | 核心编辑器，跨平台 |
| 同步方案 | **Obsidian Git** | 自动同步到 GitHub，免费、版本可回溯 |
| 图片管理 | **Custom Attachment Location** | 附件自动按笔记名分目录存放 |
| 微信同步 | **笔记同步助手** | 微信内容一键存进 Obsidian |

### 必须安装的插件

| 插件 | 安装方式 | 配置要点 |
|------|----------|----------|
| **Obsidian Git** | 社区插件搜索安装 | 设置 GitHub remote 地址，开启自动同步 |
| **Custom Attachment Location** | 社区插件搜索安装 | 路径格式：`assets/${noteFileName}/${generatedAttachmentFileName}` |

---

## 🛠️ 日常使用

### 新建一篇知识笔记
1. 打开 `5-模板/知识卡片.md`
2. 复制一份到 `3-资源/` 下对应文件夹
3. 改标题和内容

### 新建一个项目
1. 打开 `5-模板/项目卡片.md`
2. 复制一份到 `1-项目/`
3. 填写项目信息

### 记录碎片想法
1. 直接新建笔记到 `0-收件箱/`
2. 周末整理，归类到 1-项目 或 3-资源

### 同步到手机
1. 在手机端 Obsidian 里 clone 你 GitHub 上的仓库
2. 安装 Obsidian Git 插件，配置自动同步
3. 写完自动推 GitHub，电脑端也能看到

---

## 🔗 相关链接

- 爬爬虾 Obsidian 教程：[B站搜索](https://search.bilibili.com/all?keyword=%E7%88%AC%E7%88%AC%E8%9B%BE%20Obsidian)
- Obsidian 官网：[obsidian.md](https://obsidian.md)
- PARA 方法：[fortelabs.com/para](https://fortelabs.com/para)
- GitHub 免费仓库：[github.com](https://github.com)
- 笔记同步助手：[wechatobsidian.com](https://wechatobsidian.com/)

---

> 有问题？先看看爬爬虾的教程，大部分问题都能解决。
