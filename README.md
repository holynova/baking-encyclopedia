# 烘焙百科 / Baking Encyclopedia

中文：先讲逻辑，再记名字。把 36 种经典烘焙品拆解成 6 个变量、7 种基底、5 种熟成方式，像查变量一样查烘焙：选基底、看膨松、比油量，名字再怪也不怕。内置变量查询台、品类筛选与四组易混淆对决，配 36 张实拍图。

English: Learn the logic before memorizing names. This encyclopedia breaks 36 classic baked goods into 6 variables, 7 bases, and 5 cooking methods, so you can look up any item the way a programmer checks a variable: pick the base, see the leavening, compare the fat. It includes a variable lookup station, category filters, four head-to-head comparisons of easily confused items, and 36 photos.

![烘焙百科截图](./assets/screenshot.png)

## 在线体验 / Live Demo

- [GitHub Pages 在线体验](https://holynova.github.io/baking-encyclopedia/)
- [GitHub Repo](https://github.com/holynova/baking-encyclopedia)

<img src="./assets/qr.png" width="180" alt="扫码访问 GitHub Pages 在线体验">

## 本地运行 / Run locally

```bash
python3 -m http.server
```

然后打开 http://localhost:8000/，或直接双击打开 `index.html`。

## 发布 / Deploy

```bash
~/workspace/custom-connectors/custom.legacy-github/bin/gh-push-dir holynova/baking-encyclopedia ~/workspace/publish/baking-encyclopedia main "Publish baking encyclopedia"
```

GitHub Pages · `https://holynova.github.io/baking-encyclopedia/`
