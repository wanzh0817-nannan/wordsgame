# 德语词汇 · 考前突击

浏览器里的德语词汇背诵小游戏。支持名词、动词、短语混合词表；动词四形态，词汇/短语一题过关。粘贴即可开练，支持错题 + 抽查多轮复习，词表保存在本机浏览器。

## 本地使用

双击或用浏览器打开 `index.html` 即可。

## 免费发布到 GitHub Pages（https 链接）

1. 在 GitHub 新建仓库（例如 `wordsgame`），设为 Public。
2. 将本项目推送到 `main` 分支（根目录包含 `index.html`）。
3. 打开仓库 **Settings → Pages**。
4. **Source** 选 **Deploy from a branch**，Branch 选 **main**，文件夹选 **/ (root)**。
5. 保存后等待 1～2 分钟，访问：

   `https://<你的用户名>.github.io/wordsgame/`

把该链接发给小朋友即可；词表与进度存在各自电脑的浏览器里，不会上传到你的仓库。

## 词表格式

每行一条，用 `|` 分隔。推荐带类型前缀：

```
类型|English|德语|3.Person|Präteritum|Perfekt|同义原形|同义3.Person|同义Prät.|同义Perf.
```

| 类型 | 说明 | 阶段数 |
|------|------|--------|
| `word` | 名词/形容词/副词等，德语须含冠词 | 1 |
| `phrase` | 动词短语，考整句 | 1 |
| `verb` | 动词，考四形态；后四列可填近义词变位 | 4 |

示例：

```
word|the coin|die Münze
phrase|to wipe the blackboard|die Tafel abwischen
verb|to run|rennen|rennt|rannte|ist gerannt
verb|to steal|stehlen|stiehlt|stahl|hat gestohlen|klauen|klaut|klaute|hat geklaut
```

旧格式（无类型，视为动词）仍支持：

```
to get, to receive|bekommen|bekommt|bekam|hat bekommen
```

## 练习规则

- **第 1 轮**：考整张词表。
- **之后每轮**：未掌握的词必考 + 从已掌握词中抽查约 30%（至少 1 个）。
- 抽查时若又答错（含跳过），该词会进入错题集。
- 动词须 **4 阶段都答对且未跳过**；词汇/短语须 **1 题答对且未跳过** 才算掌握。
- 动词可填近义词列（如 stehlen / klauen），任一写法算对。
- 错题集清空即 **全部掌握**。
