
# Mandala Topic Method Skill

一个用于中文内容选题发散的 Codex Skill。

它基于“曼陀罗选题法 / 九宫格选题法”，可以先围绕一个核心词生成结构化发散表，再根据「人群 + 场景 + 任意词」生成可直接使用的内容选题。

## 适合做什么

- 短视频选题
- 小红书笔记选题
- 公众号文章选题
- 私域内容选题
- 品牌内容策划
- 门店/行业内容矩阵
- 产品卖点发散

## 使用方式

你可以这样对 Codex 说：

```text
用曼陀罗选题法，帮我根据“宝妈 + 周末亲子用餐 + 安全”生成选题
```

也可以只给一个关键词：

```text
健身房
```

Codex 会先生成曼陀罗表格，再继续扩展选题方向和标题。

## 输出内容

默认输出包括：

1. 曼陀罗九宫格
2. 一级词与二级词发散表
3. 选题方向
4. 可直接使用的标题
5. 推荐优先做的选题

## 示例

输入：

```text
人群：宝妈
场景：周末亲子用餐
任意词：安全
```

输出示例：

```text
宝妈周末带娃吃饭，怎么判断一家餐厅真的安全？
亲子餐厅别只看儿童区，宝妈更该看这 5 个安全细节
从食材溯源到餐具消毒，宝妈选餐厅的避坑清单
```

## 安装方式

把本仓库克隆到你的 Codex skills 目录：

```bash
cd ~/.codex/skills
git clone https://github.com/melodylawrence/mandala-topic-method.git
```

Windows 用户通常可以放在：

```text
C:\Users\你的用户名\.codex\skills\mandala-topic-method\SKILL.md
```

安装后重启 Codex。

## 文件结构

```text
mandala-topic-method/
  SKILL.md
  README.md
```

## 触发词

- 曼陀罗选题法
- 曼陀罗九宫格
- 选题九宫格
- 帮我发散选题
- 根据人群、场景、关键词生成选题
```
