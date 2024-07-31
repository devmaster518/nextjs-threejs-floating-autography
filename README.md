# nextjs-threejs-floating-autography

> floating autography simulation app using `next.js` + `three.js`

<video width="320" height="240" controls>
  <source src="./videoclip.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

## Requirements

### English

- `Next.js` environment setup
- `Three.js` settings
  - Full serifs
  - Button placement
- Draw on `Three.js` canvas with **mouse** or **Apple Pencil**
- Determine which mesh area the drawn characters belong to
- Transform characters according to the transformation of each mesh
- Apply physical laws (springs, gravity) to each mesh
- Select one character from the written characters
- Add external force to float meshes other than the selected character

### 日本語

開発項目

- Next.js の環境構築
- Three.js の設定
  - 全面にセリフを
  - ボタン配置
- Mouse もしくは Apple Pencil で Three.js の Canvas に描画
- 描画した文字がどこのメッシュ領域に属すのか判定
- 各メッシュの変形に合わせて文字を変形
- 各メッシュに物理法則（バネ、重力）を適応
- 書かれた文字の中から 1 文字を選択
- 選択した文字以外のメッシュを浮かせるよう外力を追加

```bash
$ yarn install
$ yarn dev
```

---

&copy; 2024 @codeguru827

All rights reserved.
