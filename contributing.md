# 贡献指南

感谢你对本项目的兴趣！你的贡献将帮助到成千上万的同学。

## 贡献流程

我们使用 GitHub 的 "Fork & Pull Request" 标准流程：
1.  **Fork** 本仓库到你自己的 GitHub 账户。
2.  **Clone** 你 fork 的仓库到本地。
3.  **创建新分支 (Branch)**：`git checkout -b feature/add-prof-xxx`
4.  **修改/添加内容**：
    * 找到 `data/` 目录下对应的地区和学校文件（如 `data/HK/HKUST.md`）。
    * 如果文件不存在，请创建它。
    * **重要**：在文件顶部，请先用二级标题 `##` 标明学院/学系（如 `## 计算机科学系 (CS)`），然后再创建表格。
5.  **Commit** 你的修改：`git commit -m "feat: Add Prof. XXX from HKUST"`
6.  **Push** 到你的远程分支：`git push origin feature/add-prof-xxx`
7.  **创建 Pull Request (PR)**：回到 GitHub 页面，向主仓库的 `main` 分支发起 PR。

## 数据格式标准
为保持数据一致性，请在对应的学校文件中，严格遵守以下 Markdown 表格格式：

| 老师 (Name) | 大方向 (General Area) | 职称 (Title) | 细化方向 (Specific Area) | 主页 (Homepage) | 备注 (Notes) |
| :--- | :--- | :--- | :--- | :--- | :--- |
| [中文名 (英文名)] | [CS / ECE / CMA] | [Professor] | [3-5个关键词, 或简短描述] | `[Homepage](URL)` | [选填: 招生/10043友好?] |

### 字段说明

* **老师 (Name)**：请尽量提供中文和英文名，如 `王志荣 (Raymond Wong)`。
* **大方向 (General Area)**：填写老师所属的系或大学科，如 `CS`, `ECE`, `MECH`, `CMA` 等。
* **职称 (Title)**：
    * 助理教授: `Assistant Professor`
    * 副教授: `Associate Professor`
    * 教授: `Professor`
    * 讲座教授: `Chair Professor`
    * （其他职称照实填写即可）
* **细化方向 (Specific Area)**：填写老师的具体研究兴趣，如 `数据库, 数据挖掘, 大数据`。
* **主页 (Homepage)**：必须使用 Markdown 链接格式 `[Homepage](URL)`。
* **备注 (Notes)**：**（选填，但非常重要）**。请添加如 `招PhD`, `华人`, `对10043友好`, `AAAI Fellow`, `刚入职缺学生` 等关键信息。

