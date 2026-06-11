# 德语动词 · 考前突击

浏览器里的德语动词背诵小游戏。粘贴词表即可开练，支持错题 + 抽查多轮复习，词表保存在本机浏览器。

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

每行一个词，用 `|` 分隔五列：

```
English释义|Infinitiv|3. Person|Präteritum|Perfekt
```

示例：

```
to get, to receive|bekommen|bekommt|bekam|hat bekommen
```

## 练习规则

- **第 1 轮**：考整张词表。
- **之后每轮**：未掌握的词必考 + 从已掌握词中抽查约 30%（至少 1 个）。
- 抽查时若又答错（含跳过），该词会进入错题集。
- 每个词须 **4 个阶段都答对且未跳过** 才算掌握。
- 错题集清空即 **全部掌握**。
